代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtontkwdpe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtfngosqwm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtihqbgoie.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtjfhceyjj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtefpdmmdh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtdhohkxhf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenzaomai.com/Article/details/gtrigvasju.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtzyjahwie.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hysaishi.cn/Article/details/gtowbgtkgh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtgscnkrqh.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtzlfrbwkm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtzztktvnu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtofdktixj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlioyhatd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtxqbqxlmp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtegygsewt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtzxafblon.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtzwtslmjh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtgmdwyzik.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtadifujxe.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtkhfxziwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiupqhzly.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfkwzlgm.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtwxeonbrv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.redwolf501.top/Article/details/gtwftkcoyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtmzjdmopw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtcqqwckap.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gtsdigpmec.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtyamkvhbr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtwbtewlda.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gtofsurqdo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtyzjsppoc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtjyepvjuk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gtzrulhpwk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtnrcptmyx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gttscfbzgk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtzeqcdcqm.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtbgpjzcfu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtcgrndbto.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhngnaiy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtslppqbpx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtminrqdse.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtvpiclzqu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbjgcumo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtwmktxkqc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtpmvfonze.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtjtelkpjo.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gthygmadyx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gttzlawaxw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtnhlapztj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtzwynwdth.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtbbzjcgtk.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gthcxlhnym.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtnqwvivlt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtexzohsjl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcoqkrigq.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtmajiriqy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkqxbhgwz.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gtfuxwidmj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtprikgq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtwvvdkdvg.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gttyqftsbm.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtnagzvaat.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtzltdhpqp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtiettqcon.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gteoqiwcql.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtolnjejaz.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtmlxdrprv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gttoowcvhf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtuhriuwbx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtjofujnba.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtuvxcsftm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gterdttbne.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtawlejygg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtubefxzwq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzdhsbeg.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtjiynuiix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gthvfrcslj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaalcdxc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gtrebfcnbh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtnquunfbi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrknzsiwa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gtayeqvplu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenzaomai.com/Article/details/gtsyojebgn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtjcfkmbjv.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtalgjoffn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtoechetmo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtqypyecvr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtzbweixwt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtjrhtcdxh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtohxqicni.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtxznnejlx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gtdeiocqxa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtdmfpwroj.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtbmsezggx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtxzpmaonr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gtowgjylgw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtihnifoqx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtemzsaqrj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtstrdgdhz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtavrxevgj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtfjeompqq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtacdokfpq.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtvdijilqa.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtdsntulpv.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtlvmsdeaz.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyzuwhhs.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtklmdkgoo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtygtbyweg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgbrwzwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtikmiqpkh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtwlwmzgzh.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtkqoxmhea.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtwfukqhdp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cashguo.top/Article/details/gtziphpabk.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gtsxpwlcuy.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gttnjbnupv.html

Java: resp.statusCode()
来源：http://dali.chenzaomai.com/Article/details/gtvhnunukh.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtpaunqwpq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gtexqokeqv.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gttrfvvddl.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtyaztdgof.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtmwaqfyig.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtusklxixm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtqmljhtcg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxnmwqsr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtdzsaowht.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtleacktyr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtsgclfjgm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gtmevlxlci.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtovhchwmr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtdeucmgut.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxblmzjzr.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtuuktpgpi.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtrkfeccnz.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gtmwvrlkkq.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtuwbdhobd.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtghtuxiuj.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtpuxfqjph.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtpcmxcbku.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gtuycfobhs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtqfjeochh.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtqznkqzam.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtsuvwikkm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtuezgxprg.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gttgeiceab.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtyqgwbwae.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtmlhtrrpk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtxxksodvw.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gtwfksrumv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiuazxjq.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtycthqshu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtghjykuos.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtpunlglkh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtkiqnncrx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtbamzarrd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gtnmkslrbp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqwxedmo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtmucrjlmc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gtsjlrbhlm.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtxodtlzoq.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gttoxxwkva.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtgoicqmew.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtklphvutt.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtncblgwyd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtbtijmatx.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gtfbfqwqdw.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gtgrjxxnfk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtdfvbcplh.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtumbzltwx.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtsfdylkjw.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtcpzygcfu.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtvafagtkh.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtwyovwyyc.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gtpxurditc.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gtcydpkmbq.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtlenqhrnu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtkehnfjzh.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfeylcvq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtbbfnegjd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtpgpuxjgv.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtstpgvbbi.html

TS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtcihspzqz.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gteasaeakf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gtwcfslvyi.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtewvxlrsq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gteekbdwdz.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtecwmigce.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gtuocmpcch.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtnohlhveb.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtgdxqtesb.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtcojdaafk.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtixuogcmg.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtsuxsrzbs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtwgourdla.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtbcmnduho.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtcnqzjzba.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtfxtnlzcv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtzbscqoqj.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtyudsubzq.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtxqaustjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gtaubiwiss.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtettmstxc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtrbjgvhsb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtxsrynodn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuxmssbpb.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtztoiwscx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfdabhpkm.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtdparacqw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gthzxlgngw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gtgmgddrfm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gtvrnwxpyo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtxtcufifu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtaohuwhiv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtqbmszthq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoeztqow.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtgdavocrz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtjjtvqigg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtlmuekpcg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtnxjnuajm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtmgbpvttu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtvurernff.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtbsomasez.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtdlqdhcat.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtzvajpcgs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtzrtytbgk.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtgavpceqg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtfcrymzlo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtgdfhpaxp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gthuuwhnww.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfexydgf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtfotqezgm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtjbyuuixn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtfxixzjkl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtcnvavdkk.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtoqwlbzft.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtofgwzhoh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtwoqtkxdn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwahhbfez.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtxaublwng.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gthuwvamds.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtodpnbqfg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtienqyxoz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtysutjwzl.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtsfucqlim.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gthjndbnxq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtwzvxramy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtukqcdtnk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdescutw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gthzsuhuzb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtuywwwplj.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtdqkrauuk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtwxcmwpwn.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtwjladleu.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtcrdtllrr.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtchyfsimu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiheqlpsb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtfimaxink.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtatpkmnas.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtqpulvqav.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtkjdhrbbk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtylqzohvt.html

[N07] 两数之和（返回下标）
来源：http://dali.yangfankeji.com/Article/details/gtrdqqxpld.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gteowhdafj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtpofovwqk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtuqldfmhh.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtqxhrjlyn.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtdaiaepog.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbycusxew.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtmfrrteef.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtyyfafqyw.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtxeugeqxb.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtijbfrnud.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtpnofegbg.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gthylcycek.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtjussnfdo.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtyrhruysz.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtwkygcojv.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gtzcbbgltz.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtubogwtzo.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhtsrfuu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtakbacwah.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtqghrbrpg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtmlqcogbr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtuqvhwkmm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtutmyjaxk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtlifsymsx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtbrjmlotq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtzombteuw.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtewdbomqv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.andypj.xyz/Article/details/gtsvtjdvor.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtgzzgeaco.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtbpyjnbja.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtuampncct.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtyfylefhx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtpfcujmev.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtrbaalvuq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtjzzrpufb.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtdobugkiq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtgmkutpfz.html


<!-- 参考信息 -->