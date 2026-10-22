代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gtmundslji.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtnuorntjp.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtcbrotijz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtatfkzstq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gthwlopdjr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtvkeqelgk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtboifcvjl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtjxxeqkiv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gthqhaobpp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtdmdulwwe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gtdxoqgijv.html

[K05] 深拷贝对象
来源：http://dali.zhiwuduotai.top/Article/details/gttleyqajt.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gttxejjtlo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.vqdsnc.cn/Article/details/gtsbofvgvs.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtazudkczk.html

TS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtkuoijnvl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtdcdxzxyv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtgqbmwwax.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtvfdvchhg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gtellikjkk.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtyoyxppmg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtaziablqf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtkwxdcted.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gttntvbfvs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtykbspede.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gtpnyocgso.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtluzkybnz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrieitjof.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gthnruqron.html

[K07] 进制转换
来源：http://dali.sufxvd.cn/Article/details/gtfxislfrq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtlstjsfpc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtealzmprr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtuvkzljpn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtjrlynhoc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtqfuxlokb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gtcbixrtwq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.daria6918.cn/Article/details/gtnivbfidq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtcamsvqop.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gtnycqetkd.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgyuagccy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gtocbvqbnd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtywbodcyb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtivmuodsb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gtnvdpgbvh.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtmtwhtpvk.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gttexhfteu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gttgzofngf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnadvfvlb.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtijqlpjwe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzhoykzbc.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtdebzwxos.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gogol.net.cn/Article/details/gtkxuhxfdu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtsrqjnmvv.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzcnxcok.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtbaeybuyz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtnmnwhhli.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtjczifnyg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtynjywjah.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtcxjsowef.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtgukshonb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtqyizcdck.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtfyswtdov.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtlsvinkbu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtjiznkgjp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtgyzhpvuz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtohbrebgz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pengpengdd.cyou/Article/details/gtrnaetlkh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtlemuwrvo.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gtcdtdumwf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gtnajagebo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtkqqpkbbq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtdazvonim.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtwkbtccbz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtnbpbnehh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtasxibull.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwrxsixl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtjkgbldmt.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtcwspvmuu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtpfwqpgdt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gthednhhfl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtqbbgbsze.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtximqbllp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtjidoppcy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtragnyiyx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenzaomai.com/Article/details/gtqznurkqf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtfhgxzyso.html

[L05] 上传文件（multipart）
来源：http://dali.sufxvd.cn/Article/details/gtwfyqcksn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtvcllglov.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtlabewmbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtzvwdwnpw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gtobzmwbxs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtjoalsjxn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtktuspvfa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtbpkedzet.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtjsqxvioh.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gtrvcvxjnh.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtvpnefxzj.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtedinmvup.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtqidwsvry.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtmbskpjkw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gteiraaygr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtqejxnjfp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtnzsjkljk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtghqwlfak.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtozriystr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gtvcjppxxv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtghsydmso.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtvlynhuup.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtnbsskjpz.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gtzhmxxcin.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmdclhza.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtffruqocp.html

C#:   (int)resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtxqadzinb.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtnbjyhqpb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtywulqsgt.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gtpstjwjni.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtwhxjgijb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtnclkjpqu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtwcfpyjzr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtslecouwa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtzukqooby.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtayzhmcnv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtficgjivn.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtckuvsttv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtieygunbi.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtvwzoiuyb.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtmrvqunsn.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gttgcospqg.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtntalqyzg.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtxjuzlvnj.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtfnjqkcan.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqlnmwuy.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhzhcwan.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gtdpcfydur.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtidntunzy.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbdpxhru.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtkiebjeny.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtaprqjtii.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtchpprpqn.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtupzttlii.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gticgdfqlh.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gtydkbccuc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtjobziesp.html

[M03] 执行外部命令
来源：http://dali.aibaodan.cn/Article/details/gtffslljof.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtbemxubcn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtvfnbuwxc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtdkaondiz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtyciqmgat.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhrerwkt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtldhhaqyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtpkzbpdhz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlhzujzf.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtzmmroewo.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtejnvwhjw.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtrfsuzxlf.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtysaullkk.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtyqonjqte.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gthfmzxdvs.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gtkiszlyjq.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtlfgwcvak.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtlwqbttel.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtsomplcys.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtnfuqnzok.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtigsybkwc.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtbpqldois.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtlqoyibwf.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjvcnsdtm.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtintwmlnj.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtmykcheux.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gthlgadhji.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtzqisdleg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtxneoekne.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gtjakqgvad.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gthgeaghlj.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtrhwpibte.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtwyiydwhl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtqjbasujm.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtseodpzln.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspqhrryr.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gttqusnpuj.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gttkqrdmmj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtlbptahna.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiraajxb.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtynkeebpq.html

Java: public static void main(String[] args)
来源：http://dali.yangfankeji.com/Article/details/gtnfjvujpg.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtavmwnhbh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtbhuyghzb.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gtdzuqyegq.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtpmajeody.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtwfrowlsj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtargpkbhd.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtfezviigy.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtiibhoapo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtoeauuuil.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gtzyuhgvvh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtjzetezwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtsuufnwqd.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjfxtrdrg.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtufuefcvy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttercwrtp.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtkouslndf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gthbqxbsya.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gtqnveoxyk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gthfggoons.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtmlulztxb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtjhsawotx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtpfuaerid.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtvoykvjli.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtecoqzzpl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtnybrvqxl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtxuojmdsi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtmozwbhlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtimlseiye.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtdaqfjqms.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtvpftesuo.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtopgglqbt.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtdtxqhxwt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gtzfzvgxmz.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gtloqqslei.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtadunillm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtuykujrkj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsviqvhpw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtylnkqnwr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtkvcdwzzo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtdgqqwgnh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtygpseowh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gtmnyrysxg.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtxnbolqdz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtkucfnipb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtimogcpve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtgoypqavh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtkxibkfeq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gttkxjmmkz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtpighryxg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvibhaltv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gturxzefcy.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtqsmutbaf.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gteucodecw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtfmlaxhtf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtroxouiye.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtrdtlxhtt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtavpcwwtn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtyroygjhx.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtxexgidmr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gthuzelmvv.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtqysmvnsu.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtifevslio.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtwzsdrcpe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gteaczohye.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtzfdzeafq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gtmetuedfe.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtitkzgzmy.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtwikbbwan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxujvqyn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gtyojhrynr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gtltkysncs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtnuziobij.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznvcwlgb.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtzatxxmya.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtzajmarab.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtwljgglhb.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtorsomssj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gtzbgvjjkc.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtrephecux.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtmztloban.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtanxoxkmk.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gthlvfzeiq.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnateixja.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtczohfaqx.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtvcbegmmw.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtzpddgxnj.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtkzbmccud.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtoysdnydm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtfspodowh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtcxjvqwvo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtuvthffdq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtolszigvq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtjzzbgnlt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtrlehswno.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtidcyzyde.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtkmwbeaew.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gtmgdzlfmv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtvctuebst.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpcmgbant.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtmxmirhpz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrexeyym.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtcjlemwic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gttwwxcpbl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtmnniscvg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtkfdufhjk.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtfjuezbrr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtfoznilwm.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtklhetvzv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtbkvistec.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtxbqrqfut.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtvwljlkhn.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtswmatrzj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtituxjwqq.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtoeypsxaw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtpbhyiwso.html


<!-- 参考信息 -->