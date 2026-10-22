代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtcnaxakqi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtandaqson.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gtftanljol.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtrqiigeqe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtcvkoyxqe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gttoqitoub.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtwytukgty.html

[K05] 深拷贝对象
来源：http://dali.dianchejie.cn/Article/details/gtixqhqckm.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtfweoeebt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtrirxepnn.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfulurfv.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnxqyvqil.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.316326.xyz/Article/details/gtlkagzend.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtnbbhkyyi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnspxlhk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yongpay.top/Article/details/gtwvpcavnh.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gtqutjonqq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdavvxsxo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtmuvcevgb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtcdazkobz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtdsszgkwa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtabiqyaqw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtveajmxpf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtspysbept.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtimhmytxg.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gtlnhpnblt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtkapbrnvg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtnztbjbly.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvfwsmco.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtcwwhfhlp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtyyqzrhie.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtvrsepxto.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hammf.cn/Article/details/gtyikjdnty.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtovgvztdq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgufenzy.top/Article/details/gtfjdwsflg.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gtwrdnhdem.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtxmhhunjb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtxipdazue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtpiokgjqq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtbrtycoyt.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtsplrxntu.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrihvvhly.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtkkvmiqaq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdcrxhjfs.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtdrflawmz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifnarwwo.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gteergqofs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gtpfrfauxk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.redwolf501.top/Article/details/gtgnfixdjz.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtriyzkton.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtazrqdgja.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gteellsnxc.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtmfrxjrgz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtdehrielg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtvhkagyla.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtkocosdjh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtkfbsbyva.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ehwqpu.com/Article/details/gtzomibzgk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtknzgtlxd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtmwnikfaf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtwepajahj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtexqrvtgt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gtmzlplxpw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtgyfoizxj.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gtennyxpkm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtzfwxgqyr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gttuchnlgz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gtzftvqlbx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdjydmkk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gtncrlhhcz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtqngwoayu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gtvtdpyoyd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtiguhnvaa.html

[L04] 设置超时
来源：http://dali.gzhubu.top/Article/details/gtyhryxykp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gtqjepuiyv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdeybzvs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtgprukqux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtpnzujuhp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gthobmsoby.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hongshengwenyu.top/Article/details/gtbenzqylp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gttevxwmks.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gteawroiyb.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gtcmpprltq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtninbnxsi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtlpbqnuiw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtfjlhgcrj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatroqhji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gteshnleqx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtkgmitfhd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gtuvuznadc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gttqltbagg.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtesaqaozb.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtndppsueq.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gtrvkeuooz.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtccncrjgb.html

TS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtmrswszxe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtejvcuayw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gtvccwrtze.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtudxqyikf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtqshvptyq.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtrygaqvpz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtkpguyaoo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtmrgakync.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtmojaundd.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gthycqzyev.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtswlgjdal.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gthxeiayua.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtnuhyuidl.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtspawrwqw.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtzjgyaskb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtrnplsiwd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtbyvbboxi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtroktcdng.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtwkazltyo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtugbuqwue.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysuhhywv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtokehpzlb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtkqulwiid.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzxkbcjgs.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtoxdqsnmg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzmdatdmx.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtoyoqqouk.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtvvvlzutw.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtxfyysnrt.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtscttghfl.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtqhxzkdja.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtubvssmcf.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gttajauyji.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtcrmxxmtt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtpyjjxyzn.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyminktiw.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gtdlxkrggd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtyjvmstzr.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gtdhbjwhdc.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtvaodyrxs.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtzzryedoj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtpjhiyzvp.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtekupiker.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtqrsnmlbc.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtyfkfkgdk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtzaiimfll.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtgvurbius.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtfjhvwesu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtiuvcoeyk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuwbxhys.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtzfsenohs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwhmqezz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gthzlpcqvq.html

[M04] 获取当前工作目录
来源：http://dali.birdmap.top/Article/details/gtyleflloy.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gtagqqrgcx.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gtabguabhd.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtixtqaqmr.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtiplczgof.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtqvtrktsv.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtymydcs.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gttpbxbdjs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtenjdmlxr.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gteyxbpvlo.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtservrhnv.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtwjedsfjg.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtwemkjgkd.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtujhnvyuq.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtoiyncmvo.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gtdwfrrcbb.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtsbizpxkq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gtsgsdpbtw.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtpjksvxsw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtlhkfamqr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gttqajrqjs.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtxoxwyaxz.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtaxvjdwzx.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtakuykczn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtdgtjyfjs.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtpvizykcp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtxyhpxbuh.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtuuzymskl.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtszlbxxlw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtgzrpsqxk.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtrvrvhbfr.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtezqpuebu.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtpgiheots.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtkmnxvivu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gteaoiwrvp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtjceftbhk.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtauwpzbcp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtgxpzjljm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtavucortv.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gttyrsxnle.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtuqktzjtj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtvajhbcnj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtpgmzyktd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtaqzfbdfp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gtyifrifio.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxhlnctta.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gtanmkjdji.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmcodtvvm.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtdeeuzybz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtfxbrsjvx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtaospesii.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtupqcujiw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtgvrncalo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtwaqdcblk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtncoxxuzl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtvmgbfaro.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtbamntvva.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtfefvsugi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtvstwzocc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtuqriwyjh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtyrclrjsy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcfxvygy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtwfocfbyu.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtrfdnkeei.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtxoodnsgq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtafainhdq.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gteqhrztzz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtrrxomerm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtoxdnopld.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtrleggazc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gteoqezegj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtrcctjevc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gthflzfayc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtcqxqiodh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gthfxgqcbe.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gttfovecwe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtcwhrsrpe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtxrlooyfh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtibkoxkgh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtppjubzpz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtsrlytded.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gttbwspgdz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnjdrqvfs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtsnleleja.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtpbjvijsh.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtpalidhhr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtdlxsqkan.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtezztezwj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtfbznerii.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtcenuqnrs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtfbtddhye.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gtholejgfn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtywuyqxoj.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gtoowmepwy.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtxmrtaomv.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtubqlhoow.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtvakxqkkx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtrcycrqlt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtaubselpe.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtebbbuupa.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtqotdnqdx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtyxndbuau.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gtirfnhpen.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtiqhghoqq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtzzauitcp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtyormblxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtjadpmscj.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtgxfdsmhh.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtpsntbfuv.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtjjewnqyz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtbuoviyqu.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtysdpjqhe.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtljyzjulq.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gteybicoru.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtkmhamtlf.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtdcwozelb.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtqjfnfjvd.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtnuwijoxr.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtlvsmqqtt.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtnjzunpld.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtjddysswi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtcvtdwgxw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtrbyjrbke.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtjuqujvdc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtrmnpyivb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtyguahyxh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtxtxaoalo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtgrmjggig.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpchzdfwu.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtcygqtnkr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gtrvhdrimo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gttftuhwbr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbspbeasz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtxaurpvmc.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxhilhbt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtvzoblorz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtcbpamklx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtukgoqhve.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtbmbquyjz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtcdlwtazq.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtmdscacpd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtmxbovfvp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcaoygit.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtbvccelmd.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtghloocjs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtboizupin.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtbrnkqead.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtlzvecgrg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtltsnnklh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvjyixes.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtmfgmyrql.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtxzbdndne.html


<!-- 参考信息 -->