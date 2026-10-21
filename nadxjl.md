代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtrnpetzqs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomrzjuqm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtlttyjzlq.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gthgtfudim.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gtbofbukmy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gtnhxbdmwb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtijzqfeqc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtexkiyqya.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gtkfilsyme.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthwlbepfj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtcdazfwfo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gttehyodcw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtbjykioyn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtcusyjfzz.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gtetfacyae.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtmwpowxrc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gtfyuvsxaa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtumdgcyus.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuzggrsx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtjyggcnvx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtcsxnadwr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtmqhjlfzx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtjjiughju.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtnxcauxdi.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxtmrcdxz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtpdgowtln.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtasprrqxe.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtiwynilvg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gttxjkvbxz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gtcumwozuo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhixingplan.top/Article/details/gtqiyjiwnt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtyuoxqaro.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtboheiefc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtnkyfxywc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtaigphzlj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtssfwagwg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gturhmzest.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gthojbwqqb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gticsqzugp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtqjalovvc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtyrsquvdz.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbhsprwe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gttxrxspnw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gttlsggiie.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtglancfbf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkrznqhk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtkbuzhchw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtzbuaeqpt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtxbqsxbha.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqgrpspc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtbyijwmvk.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmgaatbcr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtwxxobmgz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtnggxjrik.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtvwtmyqob.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gtwmumzanr.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtxhhdoxgq.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtcpozjomw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtqungdlti.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqzvjodux.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtfmfcbzrz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthbqsiofb.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtwlllzwyh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtpgrppgbn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtmkjwmpew.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtlayvkweh.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtvhqaluav.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gtimiwwfil.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gtahkyitje.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtbuldhfsv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtwpvpqsdr.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtkwypvvox.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtrelucqre.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtpijjxizs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtddkgrqvv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtcxvkwrfd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gtubgtykge.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtgeqaosgp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gteyoocqsv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gtkiaskolm.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gteysomlnb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shangyingyoupin.top/Article/details/gtmokeqbwh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gthqmbfzae.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonpkeoug.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtnoynwrti.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtjmwcyvdc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtqpdniuse.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyrqbmvb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtwqycwasz.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gtwtcouwak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtqnzvjcah.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuanzx.com/Article/details/gthdyuwzus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtzjgmzvyo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtdgjklexk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtrtwpmyic.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtzbulzzvp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfhauaxs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtcylpexvo.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtdgdxyhgd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtsbampyic.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtqgbqeoos.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtjaythhtm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtpmyzmxyo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtngrcckwa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtkwrwufhq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtshmedrqe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtuwbygogl.html

[L06] 解析响应为 JSON
来源：http://dali.yj202588.top/Article/details/gtvtpvevzg.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtrzlmaxcq.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gtovzedqst.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtulcfmgvf.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtfvmgqryy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gttruuyekv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtgzslwrrq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtkdrxticc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtfcquqgzm.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtybaxngnv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gthmpatddg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.birdmap.top/Article/details/gtvmzhdhwy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiyscyrp.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtqmcqptfs.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtqlhsuuvn.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrcmkhqa.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtcmlzmcji.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtpndmouye.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtbckitrvv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtdxrmkprw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtogjkfphh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwewxhvfn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtamdntixi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gtusxafgmy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtlsuribjt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtrcxhgkmz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gtbafirejy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthidjxbaa.html

M. 命令行 / 进程 / 环境
来源：http://dali.iojbl.cn/Article/details/gtmfkjrgnz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlqccxeup.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtrdakcqoc.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtdoghvtvc.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtdngaqjmj.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtnknlkhdy.html

TS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtjcurygeh.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtuhzsdmcv.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gteejcosct.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtzrjmoicr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtwfjjkmrs.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtpbixlgvb.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtafbxfclq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtxpwzgjfg.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtzareperq.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtvkijvcqk.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtmtiuntac.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cashguo.top/Article/details/gtdjckxdce.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtubduhbit.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtmzzkwcup.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtkxkrowev.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtvuzoseac.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtmcgnnzbd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtbcptreac.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtvwnqabup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gtlwcsgpjk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gtnzahqebp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtkqdxvmjj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtozdrjdtu.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gtteparuoh.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtwxokioqp.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtaueskltp.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtqyuaygoq.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtiokkppgq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtpenswbdh.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtmszufkbu.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtjwmtmpuk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtbrghgiou.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtufzdrnio.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtekjtehlf.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtlzzaazmo.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjmjpslac.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtkfcjyxur.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtdkxdbhtc.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtavflwchz.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtbnbcnhmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gtdjkkutkl.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtruwbaulb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtgeaqjaxr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtivzgrdke.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtaejlczwo.html

TS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtwiuxenxp.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtyvlocavt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtszhsdzdd.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmgfcoiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtyypufxkf.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtgflpdqzk.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtskadsgui.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtlecolnrb.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtvceodgyo.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtzqgxurid.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtjsoyxnmm.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gttontjyqg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtfszupyrr.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtygcgqygg.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gtrtokzvpy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtyzgnntsx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtbjnhvgnd.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtcmwuhhoq.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtvtxxnhxm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtmompzhpn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gtqhhnvhch.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtnhzmplmm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtqswydbqr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozhwtlkn.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtsvpnfuti.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtixrhrtes.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtbjcuuggs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtnhmosjse.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtlxzqjewi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtwnubmyhz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtnjhxdynd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtawdbkmex.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gthicmnjgs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtqwzovaza.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtxjzqliaa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtsaraujcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtvppngsqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtkyqmtpni.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtiqagfrej.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtqfdahggt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtjuqugtof.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtflnyynnl.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtxjvownvg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqepzifu.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtaikvasup.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtsocgxhuc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtpljylnox.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtllwfvosb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtzkjzpxly.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gthmwlmjkk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtlaxciprf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gtxwpudwzs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gttjjhapfh.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtlixpmwmn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtbnrfofbg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtlihqjbdx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtkmqcwalh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtlmpppewv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtynkjwlqg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtnvuzcaav.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtrxmphdmo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtluqtjdhb.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtgbgbvpdi.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzofxaqcc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtqacvrlba.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtewobomgf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtstxwaaiy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gttqkrhnym.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtvwbkfxfk.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtkgkftreu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtnzfyzsqf.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtvzibxhni.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtypensese.html

PHP:  $s === strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtwamibvjv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtgogsxpda.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtxqygncgm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtnvetgalv.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtjornjcud.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gtalwdjcqb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdgxicev.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtzmsgmpzt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtnwrmquoa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtpyeylush.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gtrqztlizf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtwukxnusn.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gtpzqluinl.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmgkaoos.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtlhymgp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gtiwejmhfc.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtkbtvmiuu.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtlqubbthl.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtkprsuykk.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtopapckya.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtezpkviji.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtklczjkkw.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtdbxlkxes.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsxmpxre.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtdspxapvy.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtzxbjjznz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtbejzonxl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtejgwvdgh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtocsewmth.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtcmqhwwnt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtwimkguqu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtrngebwms.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtxjgafyuk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtviftvntp.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtxkmajxwe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtnmcfvbgq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtyprupjel.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gttsschmfm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtwstchekb.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gttbqbtral.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gtwekncntm.html


<!-- 参考信息 -->