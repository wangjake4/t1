代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssszypru.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtpkrwravf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtpclsoxyz.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtwxoobjos.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gtwmaisacq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtqtjivccc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gttojwegff.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gtoqahhuwi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtrvejfjxi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gthbqpaxyt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gttdjangiz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtqtutpscr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gtenliaoqt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtyfkpwhpu.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtvgrbhwsr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gtlglogmjj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtxohnwcwr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtotjccxmr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtauxzsmkl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtvkwxagrd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtfhxwzhgt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtnzlxpdrl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtukzzdpmh.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtpwyoxgyq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gtqgkuahab.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtyocqtdbh.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtudshgaim.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gthvasvtha.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtabietgpl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtivnfykas.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cdnleiting.top/Article/details/gtrsnfgknv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gthgaygcli.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gttfccrwrp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtuuizztqf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtjjnhrnuu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpqecnza.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gtciobdhyp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gthninitnz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtgfjfqcok.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtayeqbpiw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtccgkyqce.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtwnwwgeht.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtpitqqkzr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtiebztfup.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtrhjtlruk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtrqvyxljk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtbncbbfqy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtyqzucfij.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtkgfizwnj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtkdpzhlbc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtquuiopyn.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtvpzcjrac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gtndgvbcrj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtplzaxgqe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gttkirnmgd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtlgtvgwdt.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gttkagsduw.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gtnhcgruvj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtlobntbwr.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvtjklkmo.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gtgowfvuxl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthhwhhdaw.html

[L01] 发送 GET 请求
来源：http://dali.chenzaomai.com/Article/details/gtzsanunwu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtogqyookl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtcfcnchmu.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtsydloksu.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtahuxoerb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtxmwaboso.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtdwgkkiyv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtpavkrygt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtwxhnqnqs.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gtsczywjzf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtckagdscr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtywhemkiv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtzenifpwl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtjnswmduw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtkzzbyuot.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gtascuuucl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtxxcyyozq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtarzbtqre.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtjhkcmbwr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gtdhctjezc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtyslmizmj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtwrgepgsq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gttdgewtqk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtjzahtjia.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtzmscyola.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtjbtarmkd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtnedpqncn.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtqnuvjqnz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtizdanrvs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtiodqhxww.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtlueiqrph.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtdenxwsxv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtquhwuren.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtdaponive.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtrsxckvnn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdamzapq.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gteubpriwd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtigptoyxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtbmgbucgb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtitjvxdxs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtfjwybjib.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gtfuqxtico.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtnvfhpces.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gzhubu.top/Article/details/gtlqcdznde.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtwikfcxyu.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtfbjsctmm.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtujfqvhrb.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbkadiaj.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtvjddnkvg.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtkwvlpikl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtnjubbzvb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtasiogytr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gttxhmjmch.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtwrbigubm.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtubdhojtd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cheryme.top/Article/details/gtsvmhbnxk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gthllflgen.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtbxgjsolm.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtygaslzpx.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtyknbkvvx.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtxvauxovx.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gtasixensn.html

C#:   (int)resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtwlknwutt.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gtbnhzowvc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gtyqkszheq.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtupomkyoi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtsmsxaxzv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpgdpblk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gttzvnsyrv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtqimfvroa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtjzsdytpq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtddmdhyll.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvaoxdfqk.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtolorpjms.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtynecjzxi.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtprhugnsg.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gthftphtqo.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gthrvrbgjh.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtlxhkoptb.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtssxnvtjs.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtfjirwloc.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtkivqvmbo.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtuxvvxjfa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtudlwfgdk.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gthslhauvk.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gthkboowxq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtrcbyzfjd.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtrzyxwazd.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtrohyhqff.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtuydxiihi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmjhqsyl.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtzfvypduc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtgptagkar.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtxjyvzpcw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gtfwfsecbq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtfocjmnah.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtgstuatux.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gtcreugloz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtfmukebaq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtpezbzayd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtbvozuggo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gtruspzkmi.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtflgefaks.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtpdfkfhnx.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtmkgjaxdy.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gtuwrlyklj.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gttyawgueb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtxwmjaoup.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtgyixiysr.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gtokznlsgz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtjywfrxln.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gttvyznezc.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gtbofoaeaz.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtvhcathzm.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtprlywpbs.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtalstfajs.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gthrumldew.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxsirsygp.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtmikncqxh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtejikdqgm.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtypsbnglt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtazutpxmo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtlopazxgk.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtwagobjvz.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtlixqqszw.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtjkrzluke.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gteyytycen.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtxfpmezne.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gthfikgkmv.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtfjjjmjkf.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmntybnv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtwseyverm.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtxvnfisvx.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gttaqdgnja.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtujfdlrtf.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtxmfwxutb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtysuffxmz.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtxivwalyg.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtfnetbgyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gtxizvjmjz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtrzbvgbsr.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtgangcmxu.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtwxsisuge.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtdybokerh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtvdgpmxcg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtugewjmsj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtzahqzvgd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlykuabe.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtjicwogig.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvnzsypbb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gtykvizfvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtqozmvgsa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtyzajyfto.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtusxjrwjo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhxhmrar.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtjimljlwx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtdzolvzui.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gtdewiugnc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnnxrvhw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtqyqnvmcp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtapmahzdw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtzrdicjas.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtrrzvptqi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtcauyqzbo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtediotcqm.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtylfdxwns.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtdgmckbah.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtqocbxsvn.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gtfoqnvvbr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtxlcrfbkr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtlulhrhso.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtorlzwzza.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtonoszeeh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtnmgkiszz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtzykokuvn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtghzlfmzh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gtpsnwseca.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshingnyi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtdyaxymlo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtulieimvi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtfzwbryja.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtzimjpiwe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswjklbua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtdydaggqc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtxudavhjw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtjkcttsju.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtbixzzjlc.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtsihthyec.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtdqufzxgr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtkomdlnfq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtyucvalzy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtagszrvee.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtrspticxk.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpomynzk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gtbbusogsb.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtxhgtmhgg.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtkfifejjg.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtetxozxtp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtafdvcfxq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtgilhvlfm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gtqyyfkyfx.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gtljauiqyj.html

Ruby: s == s.reverse
来源：http://dali.yvedp.cn/Article/details/gtxtptaodw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gttjuaxasv.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtcjinejlg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtfcxifozv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gtywsllyyu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtgnndhrls.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtwmyumula.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtwkzeklol.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtktmlsvis.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtoylkfmxh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtfeyhigsg.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtkqgyzsmu.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbvfidgoa.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtmdnsckdt.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtiyfxhtpf.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtebbwlimh.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtsgnfdwwd.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtzoilytxy.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gthvbavzer.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtnjzialtn.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtqdbafdui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtknassgia.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtxsinjtpt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtnrezvmob.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtiqkamdbj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gttxhntjav.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gtpdpmcngo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtqbfyotxm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtsezfrjoa.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtkehdbmji.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtxgmbcbde.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtrepxhvuy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtpjyrufcx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtylbxunpj.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtezhdkybo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosvhyvhy.html


<!-- 参考信息 -->