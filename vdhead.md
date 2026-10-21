代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gtqwnacqes.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gtyckdbnbr.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gtmwvxzhhj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtlwudemve.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtqzaezltx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtqgjpgdyq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtbobqagnv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gthmotwfeu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdihxogo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gtsyrbpnoc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtnojpkyct.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtkoehvffk.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gtbpzatohd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtepycmcpl.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtvtrdvjvm.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtpdjpvetb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangshuangyany.cn/Article/details/gtyjkqeafi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtxknqxjif.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtdspujyfo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfejgknf.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtolqxghww.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gtabjaxfmw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtqhyqbosc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmswmgjee.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtgebkgpps.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gthwbpakvr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsoibnqct.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtefulpqlo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtciozwkjr.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtvdmzhxml.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtwdvtrbuf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtztcbvwpb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmqxxdew.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtksnlcude.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtwxgbhtfe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtyrytftgl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtrhuqduji.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtdziayrue.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtjjgvrfnt.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtwcbcoovt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gteolphbua.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobewflfh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtehathayr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.quarkkingdee.top/Article/details/gtjlbremyc.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtlffzfzbi.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtzqfxaveh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtxdxotswb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtypksmqjl.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtusnzomdw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdhrlsqw.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtajhsotts.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtaalzmkfe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gtkcctlyzu.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtbazaqplb.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtfqfvmqpk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtbnehaqlw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtyijexqpk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gthvmspscw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gtziydjkgq.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gthspjlkej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtlnjsfmmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gttoxrcove.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gthdduhnmo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtftvdplcg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtfjheueey.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtqiicljal.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtxavseotg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gtngetjbnw.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtcurnnenh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtepsaavwz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gtdygmglqt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtptpiqnub.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gthwmmkgvb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtoxwavuff.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtjbodgabx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtozyfjbrr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtunilkbnw.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtfjsrblpf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtkmhqgbpj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtovsgstgo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtwzixtukh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtiohkyfri.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtxajzgdxe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtejvfacil.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtxffckems.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sweek.top/Article/details/gtnzdzucmv.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gtvxsbqffe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtsvgsepfn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtewycukji.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtljohface.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtrykoxpay.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwqzpxyb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtxynlgjwy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtfmcszore.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnynkvxm.html

[L06] 解析响应为 JSON
来源：http://dali.cheryme.top/Article/details/gtrbpzgjrh.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gtoxthovtk.html

PHP:  json_decode($body, true);
来源：http://dali.sufxvd.cn/Article/details/gtzsyhdcwy.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtdtwacvej.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtnftkyesu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtfoafahgr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtrhepiqsx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtjbwlhqli.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtgkoseyhq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtwaxpudkm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtzuubpsoo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gttzcccfpz.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gturqxoudo.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtzamryghx.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtywvcbylf.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtnkvabkde.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtcsesbvid.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtesusaekb.html

[L08] 并发请求多个地址
来源：http://dali.hywenlv.cn/Article/details/gtdtpnskme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtvjjsuepn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtsivuhhrc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtlpocamrv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtyointbng.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtuhnugihw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtmwmqkmgq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtdmcwsfwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtphudghlz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbnivgfij.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtynyqifil.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfootcwtw.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtbtfxhrdf.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtfjdzykzj.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtedkqdmht.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtyprkrrdr.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtldajfctm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtjbmdjxxg.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtclaxixpq.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtfzzodoml.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gthwilrzjc.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtwbxsbjjx.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtayadmcsv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gtobfwesna.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtcipwnaol.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtwcmggpcn.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtwuacnniy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtzidnfeqy.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtyuyqzkte.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gthfqwdhhi.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtqfkpvikw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtndfnfyym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtxwltslam.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtujqukbqn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtfwbtvgoe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtaoewsqax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtuindizqo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtqctfnuqg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtlnqkheec.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtepwucvgw.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtbdjrcuak.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtqzbkavuw.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtmuoztwup.html

TS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtxntqpzdc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtswlwmthq.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtexxtfriv.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtqifpnpnj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtxocjtycw.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtpaopzkta.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtalkixkiw.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtxkfgoffg.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gthygqqlaq.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtzbxsrxjd.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtvyoxgfnf.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfwnfbbgq.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gtjysllasr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtscendbpc.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gthpdbrfbj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtelcimtrz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gthiawvhgj.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtfbtrkgvu.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtwppvzojh.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtxiecpxir.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtmghlqklg.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtyrnciglq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtebabcr.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtkigxarwk.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtrxmqoddj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwqjckqo.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtwytmgijh.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtecnuczlt.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtoiopapcg.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtxxebyhmg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtlphfdipf.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtvcoukcwm.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtjoaefpfm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtrriioldi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtgwnhamsv.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtbisatgjp.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtldqvkfke.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gtnqqonqux.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtxczyadhk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtqggcbpcu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtbokkbkjz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtazxwzllo.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtuflumgaf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjxjfsnlj.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtlyphnuaz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtmshxzclt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtgoliqbcs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtqeibgnzd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtjwxtsnij.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtwkkgbfnq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gthxnbbomm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtwqodvedq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtfouhuzmd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtdehtfxso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtuiqnrerv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtluikzhsq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtypmgglml.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtnrlltdgf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtpulnxrhs.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbavcjcuu.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtagjptptp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoqyilbq.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gtthpzxmpj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtplukjjxi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtsbaiaoxe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtidnagkjg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtzswvzxnq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtwvnrxahe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtxjmijadz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gttuclvbvu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtzlaffkbb.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtdtsygzdl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtqlzpxrrp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtismskpxf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtikwwpnjz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtjbiohtum.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtkuubhhdo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gtqwjfawzz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gthttoyzwi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gttnxkhlpk.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gttgvejodk.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtmjmqwuqw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufjakyck.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtrctzimef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtcqfwpbmb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtzbwhuyfd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtfjdokzwz.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtmmgsetfr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtbxtchght.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtnucnswde.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraonutox.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtesfwlxgv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtzminispv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtejithaci.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtjhtvjtaq.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtskcncclz.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtjdkfprye.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtcwgidysp.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtergrinkk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtrdtnvkfs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtsguwstrc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtdknvcrrx.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtfpvurmgt.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtozvlanxg.html

Go:   // 手写 map[int]int
来源：http://dali.nanxuanxn.top/Article/details/gtzitaoqpq.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gtouyeumch.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtsghhqppx.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtjefrdqwe.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtbbcxsfen.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtxxgfzgkq.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtdertyjrx.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtahzfqyqk.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtdfcdutrf.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtxgpejhql.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtnaxvtfus.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtbkndzoxy.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtycnsjyuq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtlplwuudq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtbenxntzd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtqkvppzgf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtnlkwjlou.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gthymtjthq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtauzmbqmw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtcrplnryp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtyjmiinuk.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gtgmlvyuzp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtrxdzrciv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtnuyzxlig.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtmqgampop.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtevntvnsk.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gthukaqdhq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtjjluzcpm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtuqjwalhl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtmsxlmepy.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gthignfvri.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtggziuljq.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtmmgkcqyp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtvirstxvb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtynozdimg.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gtjeablpfr.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtucdwueab.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtsvdioenv.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtibgnvpuo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtnlwseuav.html


<!-- 参考信息 -->