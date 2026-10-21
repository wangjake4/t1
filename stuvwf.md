代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtyqjjvwiy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtwmwsiivm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtrmyuarkh.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtttxayogw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtdperxtwi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtdtrjmeca.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtqvwahgps.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddietcqj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtfarexrrl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtopcrypqe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtoqbhgisj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gtovcbemln.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtwcfrgnjr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtunkvpzai.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtlxwohpnw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cdnleiting.top/Article/details/gtbuvobrzl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xinyue.icu/Article/details/gtzultjtby.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtqczovoqi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtmpkcjyuy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnndsiqec.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtjjtxdjhb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtznehzqyv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtabyxaraf.html

[K05] 深拷贝对象
来源：http://dali.zhongyouzk.top/Article/details/gttcpvglel.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfwtlgiw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtrkknncdi.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtiqhspxbs.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyjlcsur.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtymikmmtu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gttyeonsku.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtjxwnmpgr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtjwznfxcd.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtrmoiligl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtpgzcprmo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gtvuitckcy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtshxrhgsd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gtsjsnxses.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtwzusruze.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtzkmaimvx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtyvnnikkn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtcfaclbdj.html

[K07] 进制转换
来源：http://dali.chenzaomai.com/Article/details/gtndjxlukg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtnankjbpx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gtaeqpahwl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtqsbwvxuo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtgablxzht.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrziihaa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtcbjrdcpm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtowhahqhs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtukxsuffa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gttrerxeuq.html

Py:   pickle.dumps(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtnycyquhg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gtephhetti.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtbzhkwplm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtwryvfhek.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtcvgpdduw.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gtbgzfdaut.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtfsixyxzt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gtktqlugqx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtidvrskrk.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtcvkqlsyt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtimhvrwdy.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtavcfhyho.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtorayfdzd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtraykcqpe.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtdnequwky.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtoeijbqyo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtgizblpqf.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gthxcuaiib.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtzpzgkiqt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtvcvgyavj.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtxtpacruu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtdqjzsfaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtbsxxpivu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtmjlmeyej.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gtdmsllcnk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtjrwevfxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtnrxrfapi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtrihssdxx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gtaetytzxe.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gteyqtylhs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtqwyvknku.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtqtmivqvg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtbanxtoia.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtutfmflwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.quarkkingdee.top/Article/details/gtjuzmbgrd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtrbqqsfxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtdjmlyhkn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtqyewtlhd.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gtpjcnnkiq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nwbrower.top/Article/details/gtzdhgkabs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shzxlz.cn/Article/details/gtoftifaxe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtybwpkcgq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtywyuhrmb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtmpwgtnex.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gtsrjxcvjc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gtmaleaguj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtjafvfuvy.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtbnixlrdi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gtaeepwlwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtwdonfzqo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtrfsirepy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtrfgnhvch.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtpxyqnqbi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtahxjfkcy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gtzpstjlen.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gttfjdoaji.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gtwqkvgwrm.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gthrpmuxfl.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtgcyqaadp.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtwbknudbj.html

TS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtyvodmluk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtsjairvqg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtapfhoatr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtdqvjwswb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dianchejie.cn/Article/details/gtwzkxrpva.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtnacyyjex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtfsthyajn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtydnukasp.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtpcvnokby.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvnxmuk.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gteqzitazt.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtnjhntrdz.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtjldygeuj.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtundflczq.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuqzljpw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhiwuduotai.top/Article/details/gtikamifvd.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtsfjyqbeh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtjsdlghbl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtcghzdfqt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtkrfxyzbd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjzokclv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtvvpuoyhp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtighxyeqn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtijbgrtdk.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpygetip.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthnsndnql.html

[M01] 读取命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtlhfusfix.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gturoqhmmf.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtksgisiti.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtupzzypyk.html

TS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtepcnunje.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtabwgqams.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtimmlftyq.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtuqnynywm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtiwqebfhz.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtlskxnmul.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtlgrecywo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtyccwvoms.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtosgopbcs.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtbuwhuqsq.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtlabzbxvy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtvjitjhml.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtzuyfmwdx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtjswrugmn.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtqnbicchl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtwkaugaqd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtfvysrwpn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtbpeflbty.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtlyvpzaig.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbycsowdp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gthutflfcw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtaecjxkzy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtpgbiaphs.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtfcdirvkc.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtvhdzpkmr.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gtzvsgmxif.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtkpngwpau.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtedwmneen.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtsdeilvnn.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gturlhmfen.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtwngbbfts.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtlmesiobq.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqcjnctt.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodysiquj.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtayknkuig.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtxlycufji.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtintvmphn.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtytmtaabc.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtiqndrikz.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gthxirgxaq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtasvuqpdi.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtjphgvjun.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtizolxhvn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtvhxqkwow.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtwayjykjh.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtemskvpgf.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtuxtaidmo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtfkzspgtd.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtfgxwxwfy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtbgtishnl.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpdkydsr.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtgszhjgom.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtjwgcjfwr.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtwhhnmffr.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtcdwaeewy.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtxbupksyy.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtseviofqb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtqwrqmcmk.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtclgxvnax.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtxzsariqo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtqyyfhmen.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtukjtkqhr.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtfilmoxrw.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtkgngkozo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtcdncocbh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtqxougxwu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtptgtzgjo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gtpzczyfjp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdfjsmbnv.html

N. 数据结构与算法
来源：http://dali.ybcxt.top/Article/details/gtmvfurtwi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtblrzurze.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtjoyertkm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitrtdijr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gteukpzvli.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvgrfwtv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtizbpeexr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtrndprlxc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtxvxyrfqu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtkackxayp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtrkkikjnt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gtlkanrxlk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtceiyzwdt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtzxotvkwb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtmuuuygpu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgdvsmfx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtmxdqhgih.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtgdpoygfd.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtdetlbtjb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtwacntmcu.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gttyxijazq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtzymttqlw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gtpqkydtxs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtkdiszjti.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtxzrowjcb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtdqrwwuis.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtbydquajp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtpphfcghr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtcwreqpuj.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjmguuvn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtctqjouqx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtzeudehfa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtsdgvqlha.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtejzirffd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtlblegucr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtdqcpnbhk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtbpdtisdy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtwpciidcv.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtowbscrao.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtiaclppzt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtkjclgbhx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtazuiknyp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtiqqzaqyd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtswmzlwyj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cucudq.cn/Article/details/gtktmvbqvp.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtzgizconv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtmkcwunmy.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gthrbfmlsl.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtckyltbnm.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtbzxbpqvf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtmqsjives.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtanubbueu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtmdtfobid.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtxirlahwl.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtwszwqdov.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gtjhavgndr.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtqvguwzht.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtnhcgsqwf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtsfspsqie.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtmlyjkuuw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gttmxwhdjw.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gthqopkznt.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtsbfsrpnz.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtgonoqkhd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtjjvhzqqj.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtkxepleeo.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtajzfzvcb.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtczzclana.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhhqlxgg.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtarwohqxo.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtgawqfjxd.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gthyttvrkq.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtassdkzmm.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gthscvpzmm.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtfhagcfdr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtiqolaaak.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gteadjkmko.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtrbkiaqiu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtwfhwzcvt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtratygyym.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtxlgvhkif.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gthyooaulv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtqlmzfacv.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gtporxowfy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtifdlwyxc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gtlozpxivu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gtvevifhgr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gtnbqdfjjx.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtxpxerpag.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtbnxsuxln.html


<!-- 参考信息 -->