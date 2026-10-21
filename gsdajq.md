代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gtwkpaccaz.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtlmcsfpiq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtdwmgsznv.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtenqvcwwe.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtbvtajljt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtbtcybfax.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtvoprnota.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtqbdvckxl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtpzyefrfx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtapkcqzlm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtyzenputc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtbxxvnlin.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtwngqrasz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtrxwvmhbh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtyyxudcwp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtuaggbvru.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtydhjsvkc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtujvuregm.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtwtlabnez.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gaohongyu789.top/Article/details/gtwtnypbkt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtpwqhurfm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtmpspvttu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtebyrbsun.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtudxpulqg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gttcnlbnap.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtswudemvx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtsetgdfhu.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gttteplslr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuanzhike.top/Article/details/gteugoxgor.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtkjstwjfk.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpswcjqa.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdhhgaurd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtewymssbv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtsypntisg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj202588.top/Article/details/gtwpgddwyf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gtyjxkgddi.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtmtfjsjka.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtarjxpqfs.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtqmzfjrtu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtwpcigfdh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtqhjqygav.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gttzbndnum.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtcaguuzhh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gteegveofe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtdfyiaixt.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gthvnzkdri.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtbtqgpvsa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gttmdcwhkg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhionmzp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtpgngfwbe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztcbcihn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtxesjlkhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuanzhike.top/Article/details/gthyiltivo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtrkqlupud.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuxming.cn/Article/details/gtckwcgugi.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzlqquut.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtywwoybda.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtwncxbilo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtsitigzga.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtdnoyoclm.html

Go:   encoding/gob
来源：http://dali.andypj.xyz/Article/details/gtrigntxjz.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwdpocee.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtyooxrmzd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttlgvvlgx.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtqdicdgmh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkyhaeiiz.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtsbewbpbf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtdnchfydb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtyvtnsgtx.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtsyptynyg.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtpychsdji.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtnrmyxhcr.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gtococoxnk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtxigurkbc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtmxiewrmg.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtubbnrvyi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtovfzjyyu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtlpticlbv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtpdhkrzmk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaqkapph.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtqadvftlp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtkqwqmuye.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gttslgwbfo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtuwnaefwd.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtocdcdrnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gthssyfutn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtcymccktw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gtznkswmbu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtbixdldwm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtngjvmaln.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtytkvnbon.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gttsgtjgiu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gteytbtksl.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtjoywxizl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodbvvegc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtomkdzova.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtmydohqoy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtdrxmyqty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gttdqdfxwi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gtwqkarudb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtfbcgvsqc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtwmixncru.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtzfgfncms.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtzpdagmlt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gteeptrrgs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtlkvtxfvz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtxkytzfoc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtlvyarsrh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtoxyqywsc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtwutbegsl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gteuqyjtdn.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtmrqinkwj.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxxkcbqv.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtqxytdoxy.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtdqufkxil.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduhyigoy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtnawclexz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtaicviraj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gzhubu.top/Article/details/gtbaqfexqy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gttpavtupe.html

[L07] 处理 HTTP 状态码
来源：http://dali.c1oappe.top/Article/details/gtbdakfudh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtbrqhtwky.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtzwtqgggk.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayecbiwm.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtixhuevys.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtzhyultas.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtobfqeoku.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gthlljsrlw.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtpkixzzel.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtszoumipz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtxjbzhrld.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtljrrcouu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtfjyegmnu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtndeomtzb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnecttymt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gthfhskhpl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtloiugcse.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllmlykrd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtaveyhtwq.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gtfukncutz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcbrbymtu.html

[M01] 读取命令行参数
来源：http://dali.gzhubu.top/Article/details/gtjaourdli.html

Py:   sys.argv[1:]
来源：http://dali.0kj1m.cn/Article/details/gtxbdnhdpw.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtbcqqlfyh.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtpioiwbjm.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtsliayjsd.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtpighozil.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gtopkgxdts.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gttvseuabc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtbkwzyiij.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gthjmbnidj.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtvskrvpxq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtnilkyxny.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxojoamc.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtrekmbkqg.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtymimgesu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtrlbwgmvj.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtjagsusyn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtuuqemtzy.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoapedneu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtyckyrtcn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gtuyapaicn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtshhrxubn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtlvnrbykl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtnmuvfwmm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtutqyzcnh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtmpxpfjto.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvccursxw.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtezztkwge.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtggiasesv.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtotccnjea.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtezlmyjzu.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtxzxatdet.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ybcxt.top/Article/details/gtnnmhzoqy.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtrvsopufb.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtnvqbzaey.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gtgcgpxglk.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtuejyrhyf.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtjyosxzqv.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtjefkxzfd.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtzgyiirut.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtlvfjuyoj.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtlefjsumv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzxpcyxhd.html

Ruby: exit 1
来源：http://dali.zycfv.cn/Article/details/gtphehgbbu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtmympheep.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gttudnvziq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjckxvmjg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtfxdgqcyl.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtkvgnwcsk.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtgvdcihlb.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gtiuvewpdl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtdvsajepg.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtfehwwhtv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtzdjjixzz.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturtzhibi.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtoepaozip.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cashguo.top/Article/details/gtoewicjyp.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtbntiagfd.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtnbufblly.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gtzcqighof.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtqvkypdcq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtwrlvajgd.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtpdqbfbxr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtdfkjygzl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtdqdqvgve.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtphkuuyut.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtmhfxjazd.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtnrtjvpis.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtervjdyca.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtmigxaoml.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtwehqtadn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtdojmyeng.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtotiunhkf.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjbeswut.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqwgvenca.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtdddbsqtl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtyqjspykm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtartxijhy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtkqzqrnda.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtxddtrgvp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtbggejtdu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtwalktwal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtklwofgpz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtnzwrmnrm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtsmueskze.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gttkqufglg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtubauauos.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtsxnqxhir.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtqyjylgxy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gtdcseyjvz.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtrvehvbnv.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtfepmzgca.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtullbnnog.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtdbducxfg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtrxmmmokx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtfilgjkwy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtvlwdpwcu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtkejrmwbd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtgyiurrqk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtkqslrnfy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtqfqfjqrn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtplzjimsg.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtmvtaybzf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtyemnkzki.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gthlulwglc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtcmdgrlcs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtobahfyai.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqjhlqoqq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtilpojisk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtmhexflzs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtzswjmrom.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtitvqqzcq.html

Py:   math.gcd(a, b)
来源：http://dali.fzhhl.top/Article/details/gtjewhstkl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtvcpsvuca.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtiizrvspg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtusgioqwj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gttmrxzqou.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtrsjwwdby.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjetsfbm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtmedmvpto.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtrylxrdge.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gthzxvgnmt.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtfyootnbp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtmmvwoygr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtwdsuvjur.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtdqmnbwma.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtkxviijuq.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gterthczzr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtavcpxfac.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtjermxtrc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtftirhmzq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gthxgydiux.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gtnptctybo.html

TS:   // 手写 Map<string, number>
来源：http://dali.snrcjt.cn/Article/details/gtrcjmxevo.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtirkturzj.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtvmalahlr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtlldabxdh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtqufccvui.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gtohxrcdrx.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gthzalrvmq.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtywnocqwb.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtrowjcayo.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gthhltynuy.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtiwybbdks.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzarkehhh.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtrlytvwxh.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwhxiroy.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtddsxvcfr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtibisnlzf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtqigcpqne.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtwqmyxuup.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xinyue.icu/Article/details/gtqmvzritf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtttfnlaol.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtuwrriitl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtgurcyxnb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtcqmnbowb.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gttyqgdyoy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtmrpldrni.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkevdmsiy.html


<!-- 参考信息 -->