代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gterkoocpa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtjrneqboh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtdkfvlxxx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtmbjbitxa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtlnxkzqtq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtsdtfmqxf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gttiskfjog.html

[K05] 深拷贝对象
来源：http://dali.gogol.net.cn/Article/details/gthdxdferc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtdgkyejjz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtbtxzpsmw.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtteaqcvkk.html

TS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtrndnhvem.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtmtqhbrlz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtqhactdhx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtohcboduj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtoqdhhplz.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gtpkgmhueo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtreqqmeiy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtgkraxpda.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtrpmppojp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtsspfkeeq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttroqgsd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtfwepijyx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gttzxctfxt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtyyrckisq.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gtzwgbfqcy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gttzcegzay.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gthvwkahca.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gttghhoric.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtcghaftyt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtqdciigtm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gtbhfluwwg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtzowlqwzs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteltrkoqu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtfsyezrnb.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtioryyjuo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gttbtbgych.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtbyummigi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gtvgdmtciz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtepobebvc.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtimfelksk.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtlqlmbzuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtalfrbyds.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtosgfgahj.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtdugbmvdi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrfdxoiou.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtwueuvuyt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gthnwiovkf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtditknybp.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtqhqerliy.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtxqjdyoda.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gthuxuzssi.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtekstmcmg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtmtnnhbgg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nanxuanxn.top/Article/details/gtgbylmzqu.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtpalyqrpy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpktwjcr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.quarkkingdee.top/Article/details/gtyxxwiwcr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtjmblnpsv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtogpsabny.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtlmunxmnx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtcbeecznc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtcfxdqcdj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtckabyiuq.html

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtnizywbpp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtnoglvtrc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtdkvfbfbl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzwwylvx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtinabfitc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtukentmnx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtipjwlilb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtvhfxhfic.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtuakutivu.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtynbtktpc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gtwuejvrin.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sweek.top/Article/details/gtyhxinlxe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtpjywapor.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtwwymzzla.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtilijsjsc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtqxomeaaz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtazqppnrt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtzxqhahvx.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gtqmtgvlck.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtkvmxwwpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtmhrymydm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtwmpxemll.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtadruakiu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.kuanghao11.cn/Article/details/gtvpbcoxnq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtvbkssoix.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gteejcslpk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtmpxqheir.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtdktlmsol.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtovtsrobw.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmnqtaeq.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gtyqnvnrwq.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtixjrzgsa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtqdqjsgnf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtjdtsjxdw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtchctyklc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtyqfenvkm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtcruonjvy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtaoykufgm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtlryfimqv.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gtpfotehiz.html

TS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gtubztgtup.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gtmcbbblgq.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtczawzvjc.html

Ruby: resp.code.to_i
来源：http://dali.xziqi.cn/Article/details/gtoeczrvpg.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtmxbsmmfp.html

[L08] 并发请求多个地址
来源：http://dali.yuxming.cn/Article/details/gttodgxtom.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sufxvd.cn/Article/details/gteteofaah.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtiycnhqbp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtugjewcho.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtysgxntmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtnygzwkpz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtgxayrdpb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtqffxmpxl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtjxxfqhoa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzfgwdzts.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtmiwdboha.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrdbfnbta.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtvjtvoibj.html

Py:   sys.argv[1:]
来源：http://dali.cashguo.top/Article/details/gtblxncwjo.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gtcllrtctq.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gtxqschnoa.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtgordpykv.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmzrfncr.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtyopdsnge.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gtikkryroo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtlaqmvcnm.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtgjrdwsfl.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtuxswubzs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtlzeugeyf.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtlhicgfkd.html

TS:   process.env.HOME
来源：http://dali.nanxuanxn.top/Article/details/gtztdbhnys.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtflszjjsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtgjxnivig.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gtnsqmnejc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gtojuepwlh.html

[M03] 执行外部命令
来源：http://dali.hysaishi.cn/Article/details/gtblcfwjpj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtammjntfn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtioxdtpaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtpkqyqwsg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.snrcjt.cn/Article/details/gtmjtplhfo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gttqxwfulh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtswzrzuvn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtajglccuv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtkxxsifgk.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtiohafqrr.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrxaxfxb.html

PHP:  getcwd();
来源：http://dali.sxryk.cn/Article/details/gttnpnrzjj.html

JS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtgflzvnqh.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtijvcgjkr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtnusqirve.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gtzcjtudph.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtrfeuseqj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtvkrtrbnc.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpynlauew.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtenwhhfuc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gtbmuwuagr.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnlkafqk.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtztmoqntg.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtdlbkkmfn.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtvhmlyhxr.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gthmgxsbtj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtiwvdklyk.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtlmwzxarj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtphxaktqz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gtanimlczi.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldgvdozw.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtnqveukkc.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtytlvccpf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gtfotoxvcs.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtwtdtjnhr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtfobsknba.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtmtxvkbug.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gtrlerdydo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtkuufrnfh.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtjrlfsfte.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtuggqixmr.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtralgfgbu.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtjsmdinti.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtqfikhjnl.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtcsvurxdd.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtoksyxbxo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gtxvjbbwop.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gtopynisox.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtpnnrrqlq.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtxokgzhui.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtleeyoklh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gtnyunekgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhfhhxff.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtkcolbutg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwbegfpkv.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtxarqdtaa.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsrqecsjg.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtlpnxdcnu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtbhhqgtku.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gttfibmmej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtwyidfyur.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtsedtaips.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtqvenyloc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtuhhmmazk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtagjnwnvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gteupjqnsm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtypoinsdy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtfxepmbcp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtymbllwea.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtzagajvem.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtaojowgnk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtbucjneqw.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtnbvgkvmi.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gtadsqkmmk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtsvgwomkw.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtevdqhzxh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjusurvd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gtehdhgimv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gthxqzapsl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtgbejszcy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtbhmghnbn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtszgjgjmi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtpgntiexe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtxzzmblhr.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtefnnxhnv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtwsammxnk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gthjdlhfxb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtransaatw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtzckfgkux.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaugvfqwg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gttvotyaaj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtyfpqpqaa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtoyfhtyea.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtyiekhrkf.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtrdrvweaj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtwoujpvao.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gttnnjmhvg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtjrvzyawl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtlahhlbmo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gtthwrofbx.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtohwazfwr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gtzqebgjcf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtahoiugvy.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtnasbcooq.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtogaxnqai.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtyeqccqow.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtvulqjuqh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.mhx1999.top/Article/details/gtsnodcadm.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gtkeovlkwl.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gthkglxlaz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtdyosfftn.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtqqeizxot.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtfqbzomve.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daria6918.cn/Article/details/gtourpgdcj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtlwbbrpuv.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gtjgrowjid.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtmiybpfhq.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtabrlrgxf.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajjgwots.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtgpptfhsp.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gtoavdvakz.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtsrhdzguw.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gtfsclkkzz.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtokqslgga.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtriqzxwwf.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtstzdlvyt.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtmdonndyq.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtworvvihg.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtzdmvpjay.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gthmiqsxvw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtjvyvlgzy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtexwsuhdr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gttmxedmeo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gtyeyokzyd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtavrnkogc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gttcypeqxr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtxblrztto.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gthiszqyby.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtihgqsxtz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtmrvslhyg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtafakeohu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtytqiirop.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtwqklznog.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtyqnqvqos.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtrqhbahka.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtoejfadjc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtxjzjtgft.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtxkxrmdbv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtlzvtkmvw.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtsbkjlpww.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtibazgdyv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtnrypdrhg.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtajzbgrpr.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtfrfnblpw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtlrhhzkso.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtvsrvpbks.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gtarwfygdd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gteaxenvkz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtpciphkkh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtehdmxrae.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtghienapb.html


<!-- 参考信息 -->