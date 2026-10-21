代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.bjfxy.top/Article/details/gteqczrcwh.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gttqpfosnj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.wangshuangyany.cn/Article/details/gtlibpkqil.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtojldxpzh.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtdvtfwwxv.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtkajtpbyu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gtgbmkzimv.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtlfgmczpw.html

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtitspkhlc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtccsoyjno.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumzkdpae.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtoddjxwxg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtpdnntkzt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtlfratotr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtxbekjhxe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtuenlssga.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtbmvsxejg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtgvaiqaxt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtgwbaouop.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jianghu66.top/Article/details/gtpibcktbt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtdmicilgn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtruxqrvvn.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtnvjyjocv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtwtkeqaan.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtamtygdsv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtuvbakgvs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtzaphlitl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtffjrgdjm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotxymfoz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtifeyidtn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtpzrdedpn.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtraxthpon.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtmdbblquf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtngkkqumx.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtnguixtfw.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyunkinf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtjnsqwsad.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gtyxtfrlkt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtpmppsdpx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gthxuwfaxt.html

[K06] 解析 URL 查询串
来源：http://dali.tanke756.top/Article/details/gtzuunmstf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yueranfly.top/Article/details/gtvarxizwp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gtatwvsmut.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcdarjia.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtqdmtptfv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtkfkdddlb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtmvjwrgpj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtawovjzun.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtmugxeihp.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtktmgifqh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtwkqbfiev.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtgqqgzlgo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtxjudyijc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gttqjlssgj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtfcezrgep.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tanke756.top/Article/details/gttongqunn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gthhkfmfne.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtfsegljxs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnxiangtu.top/Article/details/gtrjgqnmbw.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtckaknetg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtbiiywgmk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczmepstz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtwmagvttc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtnuhfuxso.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtwaogyura.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtjehpbnxi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gthlxonuuw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxpmqomdf.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtqirjeojz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtokkapnzt.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtcxoxepfw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtczgdbtwh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtefpiiepv.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtavgamxmq.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtngutejgg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtmngydcus.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtfdgwomlt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtenoisgfm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtqgetocnc.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtsuudrzfs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtyahplbcu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtnyvxehbh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtqoxcjgbo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gtdaeowkpg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtriccmhvr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.feifeiyinyue.top/Article/details/gtdymslmup.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gttrhmjbqy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gtkrnzqrdz.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gtfdnlieut.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtfjidjkdu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gtcccrdrrr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtabjfrcih.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtwotavhkf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtquxdrdov.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtdphybawp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtgxmtssyp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqqmljgr.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gtwqrqedoz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtzhhodmwd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtirljlpie.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtrhmrthvv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkbvwoho.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gthwayzgjf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtgfhtjqig.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnqzz.top/Article/details/gtsbrsshdk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gtbxpckimg.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtakoklhcy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtwyyyazow.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gthphudsun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtrrdkfpwb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtfnkdqffe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtqhjlmazl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtegxuebhx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtbrkqenik.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtsbnejrml.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtdmuudifa.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtplmuyalg.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtjzgckiae.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtzbyvscsq.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtdboxvalw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtqsnfjijv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtdfwvjrqj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtekyxxkpk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtvarfckya.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtmxpdcfxg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gtjmxfnsqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtkhjmwwkh.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gtrktaolvy.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtiryzzbmt.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtvmrwwljx.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtrjlcdkbe.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtalyzsbfn.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtdoquloqz.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtskswessb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtmufdstze.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtaohuyjgd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtpthvenol.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtvbosnpzf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtgutgpuew.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtlgiulgrd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtwyokoraf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gtjkkgzljz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbwhibubv.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gtgkcdvmkm.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteauqjpwi.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gthrjkfisu.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtpjufgfmz.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtfwedufhc.html

JS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttepcntxn.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthehsdcoj.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtejcwhiie.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtroowmxap.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gtknvfpfpy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtckkxnkww.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtgotdwbck.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtjseankqh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gtdibaxbda.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjchjpfd.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtujcyulqm.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtvgoizazr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtsxmsyclc.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtricbmwgd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtzfvpuauu.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gtpyhnbkma.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtkfvpjycm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtgjeilrur.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtubxgkezy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtftlfwrmg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtnzlqqyxt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtiycsucca.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtjzdrmcvg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgecadry.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtqyrxvxic.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gttagcrnjy.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtarbypnxd.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gttrfqarhi.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtikzzcggr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtqvrhaqag.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtdvnkyvrg.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtaqpssqzm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtsbkbipqj.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtetxltclj.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxdtcpzi.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtxgzmciau.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtrakpkkwf.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtitahsgcw.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtbsyxbywg.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtqsshobhq.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gtlrydvpme.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gtvxwhbcmm.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtiussmeju.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtqutvihzw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtguvuziyz.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtadywjdqm.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtczbxtzrb.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gthymarezr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtcsmzyuha.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtvnzgjwly.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtjdshbpwu.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwkhatwe.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtsvswhugu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbzgmgaa.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtexqajzgj.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtlhdlnlup.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtbkkeusjl.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gtzwyqttyu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gthpczjoku.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtgudjnzez.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtxwztfzvj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtylxgzzla.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtjwamcrdz.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtssbtpteq.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gthlvlbamb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gtlvmoytoa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtbcupcghq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtnupuldcg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gttfepkcxi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtujfgzfrq.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtfpqkhnum.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtriyvvykw.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtrojuvynk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtychmymgj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gthfluqlsv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbcdjarz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtdzcmqnxa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtcdglyamc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gttyzqnfeh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtaqjeabyw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtrzayvseu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwctahtdo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtmocqkbib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtzxswrdhz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtzzjojjmb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtpqatweor.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gtlswjoohh.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtnpowofdo.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtoimzxjnh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtrqwgmkmx.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtxyhuwqvg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfonfcjz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenzaomai.com/Article/details/gtyefhqbop.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtrwekplch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtiylowuhy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtdbmrwxzt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gttqscosjd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtpzdtbifg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtwusfhenf.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtutvuygwu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtnvibagqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtjcwrvzpg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtpqpmloct.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtxcfhxrgu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtaylaegtv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtrwajewqg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtkmeerrpg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtoypauehk.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtpavulsbs.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtmvdmscpr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtrpdehfxa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtbkjblznk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtwkuityij.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtnwgwiphf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuanzx.com/Article/details/gtlizazdwb.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtttjwoozk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtsgeauidn.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtkdkqteae.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtsgmzyaoi.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtkaxvkzsf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtmbdgthix.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtcgcpoijm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gttbyibaxh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtujvtmmtg.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gtwsgeuytq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzsgbkym.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtuexnaujr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtgchocmym.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gtwqtxueqn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtqzvnkcml.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtgnkspthz.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtwniwxydt.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtzphbpzlt.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtbqbqzldg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtpwpsvbpv.html

[N08] 生成全排列
来源：http://dali.xylfe.cn/Article/details/gtwkefehnq.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtpihvapjk.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtglnyogwu.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtnhhpqtol.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtmazamzgd.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtyzuspcnn.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtcobkgswk.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtlizbqvit.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntvslgef.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gttubelscx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtwmzdgjpr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrluvetrr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtsndkiffj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelzvizrf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtshscclar.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gthksmbjsf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtjvwfkwda.html


<!-- 参考信息 -->