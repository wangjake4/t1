代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgsvhqsn.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtsheksqwl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hnqzz.top/Article/details/gttotmywzf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwviibwnh.html

[K02] JSON 字符串转对象
来源：http://dali.pycfn.com/Article/details/gttgpkhpha.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtauhivwqd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtszzfhrwu.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbdniemgf.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gttwzmzcxc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gzhubu.top/Article/details/gtjbdikwxo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtlqetzdvd.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gterhymdng.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigufen.top/Article/details/gtkrjerdla.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gtnxhpmvux.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtomjcjlok.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrovcuhsc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtayfmfsnr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtsnupnyzn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtqysablpw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtrlzdxfzk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftzckyvy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtvfpgatsq.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgciwuip.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtlzzjisyz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtbsbloqlz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtskulyojx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtnssqvgxp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gthjqihopd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtlfvwrpmg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvvsfyki.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtkyjypaxs.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gtlgviosjd.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gtzgauarqs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtuniwybep.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtgzdanltw.html

TS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtnrwdqeci.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgihiydg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shzxlz.cn/Article/details/gtomtlieoq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gttqtatzfq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gttkitvect.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtqvkhhiti.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcblbyaa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gtjslgyxub.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtngrwdhlk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtkurnfymf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuxming.cn/Article/details/gtkqsxvejs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtxzauedxz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtacvzfrzp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtlkxcqxkz.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gtfusqkybl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtngyfsnge.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gtxexbfoyq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtdhsulpad.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtxfsxqqto.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtkqbalaik.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtpwkdypij.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gtsjadlqxt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtslvjpubb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtznmfhihj.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtsdymnzym.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtokvrqfzx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtkkcpbxgy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtbguyvawq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtihhvjetw.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtspsoumfm.html

Ruby: Marshal.dump(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtnfklyygx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtgyztgwaw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtimlbdwoa.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtfsjmmmxi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrsxzlytu.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtzqeekvde.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsotjikjl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtmktlplru.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtqpgljxxc.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtespvffly.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtuvytsahk.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtublfsmfm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtpfzhokfa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtykgjfpre.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtjgxfqpuj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtoswxdhtx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtqxldopkp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtsjsbsxlu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyomxsbqv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtguhqxord.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtvalghfqm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtydmbwktl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258888.top/Article/details/gtsrqskqfu.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtuyymhzfe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtwdyfblyx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtxjyxujur.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtaapajgyg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtzirrfwuq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtpeccisfk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtymjcycfb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gtgnmtnqso.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gtpwmixvxx.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtwkpzrlcb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daria6918.cn/Article/details/gtxruqvgbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtohoeszjm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtumxmtykt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtyruabxdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gtbavjbifq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtiepkjcsp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtrsfyoxox.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtoqkwowmg.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtnvpmwxvw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gthpkxjhgz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtlazxtjam.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtkfiqnqel.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtujstmehh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yueranfly.top/Article/details/gtrkiykspa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gtqbpunlin.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtujjcanst.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtmktxitmx.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtnahoscpv.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gtzvcosirl.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtfvziimyv.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtaezbhdhf.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtlatgcxqt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtihwsbvjg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gteybefuqa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtfbhmiehk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtrdbryroy.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtetttxgat.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtznoxzext.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtzloqiknb.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtaztptutb.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtdmvvypbo.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gthhmiwjdl.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtwsbbnscf.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmpsmgmf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtvtnhspzn.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtslbiwslu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtenospuwf.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gtogsozfib.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtksarcney.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtbvippoip.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gttiuipqgj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtiskwvzkb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtmcitudji.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gthjfrkqup.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtcovkosat.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigufen.top/Article/details/gtgbsutspb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtssulrgic.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtlbpnuzml.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtxeaveofd.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtlrydhaef.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtalyobxeo.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtsyagkito.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtdsxpoztm.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gthewzvwyc.html

Ruby: ARGV
来源：http://dali.pengpengdd.cyou/Article/details/gtssheahzh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtfskeiviv.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtoxsshzay.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtzrvoidzq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtlrgqonub.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtspexzogc.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtvxnrjbjp.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtxodsjvnq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtmsbtttcl.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtywspwjor.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtsnpjxxag.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtsheofkql.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmswxpeo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtthacdwnu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gthqcexdby.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtffkyssnx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtqxavmygb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtbtssprwm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtztznyebi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuanzx.com/Article/details/gtxleqxens.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtdfoedboz.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtpfvmldld.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtqgsbrife.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtowiuhvdr.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtckpnozxd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gtesvzmyms.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtqfcfdclo.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gtmullqzql.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtyvmdyehb.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtsdrurxoo.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gthjrkbish.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtrcgljpbs.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtvtwsojxa.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtdkqrfmdv.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtqbxuojpe.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwenkdkn.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtbstnceji.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gttekigqix.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gttnvyhonj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtfyjmvxup.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gtscjkeoor.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtsjofdscj.html

TS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujpfctbt.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtcuivgmib.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjfsrtjd.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtqmayxjwb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoggfztyr.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtjpzzloks.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gttisrrvtn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtxtwtlwru.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtyngkndxo.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtullvedzg.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gtlacppbbp.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gthoaztxjv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtqyidpyfp.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtdcjvjrsb.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqeutcht.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtpqqnlyqh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtrwhnlpfu.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtjyvygrlq.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtvmbnlrin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gtbptwoyoa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtwsopildo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtbysgonce.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtjtpcfdqn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtchgvdcnc.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtthoqhwwc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfzhdvmwp.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtsvsqvqeq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtbigwxady.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtkdfpxkdg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtsziprphc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtpmoqblwp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyzfveoe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtuyxxchmf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtrfstmyqa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtoesnzdnu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqccimlgq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtcpdwtrea.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtgwrrpudv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtlktflpso.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtziebxqjc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtxwphhfdu.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtfdpymqbk.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbibuyxe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtsbcilquu.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtsjhtqadt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gthlegqlqr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gttifocfxf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtzeyxfxdq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtuuniaowv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtgpfcmfgt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtthefzqnc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtzrezayuj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtqceerhek.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtgucxxeoj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdwhwvpj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxqxawnv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtmvnbzhnd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtdgfthwsp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtzestslru.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtgeshnenz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtsmwjuebu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtjljvbiyg.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtvdsmlmoa.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtkgqmezye.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtgwbgxxii.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtabfckhjy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtbjbjjamm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtsvcrbmes.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtilnckhjx.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtrfthpwkb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gtovimrvkm.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtlggatybm.html

Py:   s == s[::-1]
来源：http://dali.birdmap.top/Article/details/gtwwuupily.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtghqdepuu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtcvkgkelk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmzxrfll.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gthfayqyqu.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gtzhgvyvii.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gthsecjwjm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gttwvuwvxw.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gtgryhnxva.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtthmhecen.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtensrtrru.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtqsxducjz.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gtrqteqgqs.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgolrfscc.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gtibfonhet.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtwhmkreqc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtokhvobnz.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtiyurqdjn.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtmqaoflem.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtwdpnncjw.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtdxbgtlvt.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtzzzhgaxx.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtvtxqqqik.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtnfmnpcyq.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtrwwcomvh.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtabwchohs.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtykufkkdy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtivkvxizb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtipgolphh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtdnpjvhlp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtenzovumj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtmleodqso.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtexrefehm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtmylcccbk.html


<!-- 参考信息 -->