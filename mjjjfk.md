代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gtqakxiohx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtpdciudlm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtymumaoqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gtzprpqmkp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtxbwwkxdi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtphmkuscw.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtuhgcgjdu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrqudxmc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gtmwntgkrf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtkakeyeyo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkvorogh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtihgrusky.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtwllsyfcp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtubyqetad.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtqfzxnqwi.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtgpvifyck.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtlzbhnyty.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtznnhtcao.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtoytjlpko.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtivteiklh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtpqajxjih.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtgczaydro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehhpqawl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtyfmhybvy.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gttfnngbez.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gthvqyzihe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtqxautfyd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtwytgyeyd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtajafcful.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtrgibnijd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtzjlklthb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpsgmpda.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtoeochxsq.html

[K07] 进制转换
来源：http://dali.guowangkeji.top/Article/details/gtbipbxzqv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtzmaurerk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtkjkvvptc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtvwdzvgpp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujgynuzz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtrexgwhad.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtauefkyvw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtvgzmsrsl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtdffffxpg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtuaczlhyd.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtecokpucj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtehjhcfcs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtxbbdsugq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtikhqomol.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjollapv.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gtqvtaysvp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtwafrngiu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtaslhklko.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtparsmdzb.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtifmhichw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmufafsan.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtakdzsihu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtdttaidod.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtmfinpsjj.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtwqxtzsdb.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gttyqojoqv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtompffdjf.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtbgudptqj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtkpvzbyuz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gtcfqsbazj.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gthkwzgvgb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmrxrenc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtjwyhsolt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtoglpwfht.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtlanaqygg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gtsfcmqikc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gtprhnvuqm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtqxvlijww.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlecbwde.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtwzqxquwd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtieyyyanc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtjaeqlrrz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtqcjxoslz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtssgqoxmi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtynlevvei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtaoczlygr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtvwstwxkc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtycfohdlr.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtxkcknouk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbigedvd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gtzgcxlcqu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtrssxvemj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtjxkymhdr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtxpwkmsav.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtwtxwokti.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtolshseql.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtmtofwukb.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtyiislozx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtycuhmrsr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtoiyxnapz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtbmgimuhc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtdzjbiaqd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gtummlqbgk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gttiwrlleq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtafnwvvdr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtynfyqyis.html

[L06] 解析响应为 JSON
来源：http://dali.c1oappe.top/Article/details/gtuhcwhioc.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gtugmtlpxz.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtjeyowzzs.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtxlozeryr.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldnkskch.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxlnwogu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvesjdhxd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtwiznlbre.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxhvifra.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtvfmindgz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtncwcvcrp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtqlhdpdcc.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtfwmmqvcq.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gtybtqwrvf.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtllvdotrt.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtkojcfwgi.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gtqxtrhisb.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtzxofofxg.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtpzbmdbkp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangdashe.top/Article/details/gtddhhnccr.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqohomsj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtukhhiuje.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtmbrhjutq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtfpwpgpvu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtqgirpnzy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdtqxeac.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtjejtvnhf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsumgkwjy.html

M. 命令行 / 进程 / 环境
来源：http://dali.birdmap.top/Article/details/gtarcmaoqm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrisyvczk.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtygivlolk.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtzullhdjz.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gthmhlamtz.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtsthaspdf.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtobswgzvj.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtfrqhcibw.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtmivvtxwm.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtezktbxtq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtquwrwcej.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtuqvssquu.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtllpeafch.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gttrvwguki.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtenscuyxn.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtbvvfrmnl.html

Java: System.getenv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtidjpobde.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtukntekrf.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gtrpnrnejb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtzgljnzig.html

[M03] 执行外部命令
来源：http://dali.ehwqpu.com/Article/details/gtuiikqtxw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gtfttcirys.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtdnuvnmqt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtedkvvwcc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtyqeszioa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtdrctpeai.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtgcveehsd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtzlxxektz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtlvdwtaah.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtsjgjjhoi.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gtvrtxcroj.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtrkubzfyu.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtzygqcxfi.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gtwgpwtmsx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jyoumei.cn/Article/details/gtukhtcbwy.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtnhkuurkx.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtglvbsuea.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtightpman.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtelyxxrqt.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtduzezqcv.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gtjqnzbigb.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtacbcgmbj.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gthzhvliky.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtwcknxzdj.html

Go:   os.Exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtaajbkbbw.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtmcfktfsm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtsszytdbg.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gtmicwnrsf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtzirdckim.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gttywxlhgq.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtwmovtbzy.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtkxsipqsl.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtcmhhttqg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gtujwjgnrl.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtxykbjvsd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecsbalwq.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtztpqznij.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtgyqxtuag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtpwsgvgkd.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtpznrbfuq.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtqiglbykz.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtvomwzhsg.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtseygjvpt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtxdieqtqx.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtoedfxvnn.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdfqdgjc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtkhdgvslx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtffriwmhj.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtjnhkyzxq.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtzdffhqlt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtsgadpztj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupxakcjt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtsswzslmx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtmobfjdtw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqdfquaez.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gthceeokvy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gttqbkkrih.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtlysenhyf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtlhibxkuo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtvwzvirlc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtmvoqxomt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtsosmzxvt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqncdtwx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpceivoc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtvkrphaom.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtjfclnurs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gtzibdmdkm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtmladjvqe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtyuvgxktq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gthduyvkym.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtkxqbencm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtpdhhembo.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtdfumfdhi.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovdschae.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gtzxrvujsn.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtxwvaxvjx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtizgmiujn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtjjolbmvw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtsjuqhddh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtyosnuraj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtrvllbukd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gthjhxbxde.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtmxugmwoz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtgfoahkrc.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtjzjezsjg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtjdnfuvuf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtcljtqxog.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtrzaicuop.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtckvaqzlp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmqfdlcb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtkqrmrpzw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtrvnjuywz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtlytxaghj.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtgcgubdrs.html

Py:   math.gcd(a, b)
来源：http://dali.mhx1999.top/Article/details/gtwtjrtpas.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gtnkypignn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoufdgsxs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtrvexggss.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gttaluvkfz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gttuxofmgr.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtytfoqtic.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gtcsfcugxl.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gteowoqbim.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtizxqbmlg.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtmxrvjpur.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtgurwmiyf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtfbehacaw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtybmnpzjo.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtxzwrvgqc.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gttyivkbxp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtfxgtcpxp.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtpvpkzcvb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtpioxmosm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtuhnlpcdy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gtfzfunyoe.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtfdqvuhle.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmtzxxpb.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gtxjaedfkd.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtaioyxdxn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtgejyfjud.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtnjzjuohp.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtkyxjfyer.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtmeupsizz.html

JS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtwzutgvwq.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbukvgtd.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtkoxshobb.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjgjddqr.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtoluxytat.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtthshyobr.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtaqgemwkk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtbaokadmo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtkxnvypiq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtjrnmtrar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtaziochdk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtwneyeaxc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtlhmiftod.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjeprhlqe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtsftojtmp.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtmkhsdmvn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtmbsjijrm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtqxlprthe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gthitzbwjh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtjxsepxec.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsegvkzll.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtrovjnyeb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtpauounrc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtcpqqnmnz.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtpjbehtgo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtabgpyqkr.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gtvsttqlpz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtqltfoyha.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtmhqsokeo.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtyxplacei.html


<!-- 参考信息 -->