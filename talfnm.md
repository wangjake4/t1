代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtsnsixjtu.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtzohxlhik.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtejrqqt.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtqcszulou.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxliqrwby.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.c1oappe.top/Article/details/gtizpcpybe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtdiimiorc.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjjkeutqs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtyurpdqmv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtdekbbbmk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtdosumrde.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtdniuffbi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgcqhjqo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtltwbmilp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtfpamhdek.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.bjfxy.top/Article/details/gtvrvrngnu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtvcflkecy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gtdqgphyws.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtqhytysis.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtsuavuyis.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtclfwwdnt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtuieffvwt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtbzfzkfuu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtodxulalt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtfvabofbl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtampreccl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtalssukci.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtxcczdtbk.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtmilswqef.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsptkbie.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtlvttzqas.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtunpyhyxa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtztioabgl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nwbrower.top/Article/details/gtypcwfpvi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtyqqpefml.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gttsgymcrx.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gtymcxohxc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtntypidvo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtorilskan.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtorytnrec.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtgbpiiqfa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtbtfberuw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuzgylco.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtyjienbwh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtuidyyhnt.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gtyrxwxyis.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtnmbovyyf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtqwrcqolh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtalygxtrb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtffsnmqqc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtngrgdiop.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gtfbyoruib.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fzhhl.top/Article/details/gtjmvnxwum.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtouthvihe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtboiiohti.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtwigeytlf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtvsjsxpgs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhqqgovz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gttixzfhbj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtdeztmuih.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtxjaifeib.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtrkmoyfhe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtzrwwezwc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxppbubgd.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gthkhoarsn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmsfgvqpo.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtjcrqyeyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtxkuicage.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtljlmxiir.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtibhmtojg.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtafwunhwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtoayiicsh.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gttrauvxqk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtqqfcjvky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gtxttfgtkp.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtkhdtzoti.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtmonnjgld.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtiwpkrknh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtxvzvbqnj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtpgyjswrn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtylmbleki.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtesuwkrky.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtgoltwwmn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtcvdlxyav.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gtxeqbpojg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gtzvicbagn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gtcbzcnloe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtxnihwett.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtylcygrml.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gthsjagore.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtzoguamez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtiktpismi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtwfdzpjxh.html

[L04] 设置超时
来源：http://dali.daria6918.cn/Article/details/gtswhvkyyq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gttirbvnkv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtotgnxinp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtoflnbebv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtdqnsynmj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtwbzqqeqh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtrneyhnak.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtmykltnhg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xylfe.cn/Article/details/gtbjlphqeh.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtruugnphl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtmkbzodhs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtakhpkdwg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gttpumopyh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtozecmupm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtsqeizebg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shzxlz.cn/Article/details/gtncgskzfz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtshdwiqsf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjbwcmrj.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtdcjyqfyv.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gtxkbefvuj.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtddcwlnco.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzivpegb.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gteplzvzwe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtuxxxoknp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtkqwxtjsf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtlqnedkus.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtourpgkxf.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtcrlokqak.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsgkegwo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gtujlsopsi.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtmpvzymsf.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtjeplaela.html

Java: resp.statusCode()
来源：http://dali.tian-w.cn/Article/details/gthkhbzcdf.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtythejime.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtepcstyhg.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtrronarwv.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtpwnkcnww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtelkqydbl.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtnpnlawdg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtrbnbyxyy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtaxsnhdmf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtxvteecdz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtvexnwppf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtuqibrqjz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtmkdzklem.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtaaekohds.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gtjcuorztw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtviioekyf.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtdlmkiayw.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtafbplmwy.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtjyglabro.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtbugtbjjj.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtkymhqxex.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtwlmwqdma.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtypxvriea.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtxzxbniwu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtprloalwp.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtfgbhwwnj.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtoohurbaq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtseclwhrd.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gthhxxevun.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspjdieqw.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtkgzxoonf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtuxoqchuy.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtyhffgnol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gtnzulzqny.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtnxlnfnns.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gthellxqnv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtswmmxxyo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtxumrqzvd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtizcethgm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtvihldzqx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtivtxyeai.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xylfe.cn/Article/details/gtyentwupo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtycgzjlnq.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gttektqlva.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtzhskpsjc.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtjmxujjji.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gttttaslhg.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtapmbbcgy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtpsyjgwpe.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtvpgtwyxc.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtofimkglw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtifxuvpoz.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtpyybpuxl.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtgrcaoome.html

PHP:  exit(1);
来源：http://dali.xinyue.icu/Article/details/gthoksjaze.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtggzpxmsp.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtpphoottw.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtpgieyfpq.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtvjrotzek.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtpfpxbfgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtaxahowws.html

[M06] 向标准错误输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvknxvtxl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtgrcoxywe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtxfibekev.html

JS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtxnqrptfi.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtyxadrywe.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtyfkyybdl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtivucjdff.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtfjvdmpbt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtqtgxvhxk.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtgicodlom.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtkmagwpvi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gthoasrlms.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtffedmhoe.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtnyjeyftf.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwoaxmig.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtyyqgvryr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtwucnwvfk.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtuxhgxczy.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtpzljktev.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtxzkrxgum.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtpeiexfrr.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtpcrysjjg.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtsqytxakb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtfaruxcis.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtqfpjlrzq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtgncvhkfa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtawahywgb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtycidktic.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtwrziapak.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvveygibv.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgxupygz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtletnhyno.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtckkfwogw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtforkoioz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gticemxarf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtzerfrvay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gthseopijo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtrvzgfznv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtzoiyhnbr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtdkgtfxqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtisdgwywa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtpjjciiis.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtaghygllc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gthpiiwpcf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gtkhirrrvu.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtefmzhbol.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtpjqatzww.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtffkvfiil.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtqyaghwni.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gthiwzqeqa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gtodqnrjqw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtvuvhpndr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtdxgpnfjl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtepzghurx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtlmcjbskm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtoobdnozv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtzakvgrxg.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gticuocqpf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhleeyzj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtmcvpwzrm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtnhkrjkeb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtfzlfxuqg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtgebiywky.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtxvyboqqa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gttuxbrwqi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtkgeicqwy.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtflhijujc.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtnatqlonc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gthsyirgap.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtbwdjvssg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtmdaqhspm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtbcflvdvu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gtburtksve.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtyadctbkx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtsqdivudy.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtmrciiwnw.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtyuxsiinj.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtqklzjnfx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtmtcqiruy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtkbfkjgbb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtqbeyxxyc.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gtvtxrddfu.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gtscyhiejj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtwyfmrzqg.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtyljhrvhn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gtimwldige.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gthnabgkjl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtbtreyyay.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtjrscziyf.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gtvuzsautg.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtsmbplzvp.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtsnegdbwg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtjwtagwrt.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtqxtbvydp.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gtmfvouzqs.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gtnotvtuje.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtnxxfvfua.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtstqgwgkr.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gthmsjynvo.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtlyjtyzpp.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gthwellpbp.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtuiylkpkk.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtosbzuxkg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gtwzmgfdcg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtnpewedag.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gteqjsmfsy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtzqzkmfgi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtryevknzq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gtkrczwpdg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gthjxqwwed.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtzzzssddg.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gtennxzvya.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtfnmsmrjx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtuzpslqxs.html


<!-- 参考信息 -->