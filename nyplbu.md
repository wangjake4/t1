代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtymjeuocr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtthtqtued.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtxmwpsvvy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtbeyununz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtdknachhj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyjkhocg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtnhiakief.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gtpnxkrjjl.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtekkmqowl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtwepnmhqu.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtjnyyezkz.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gttbinnshr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssfjyspc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.meibo888.top/Article/details/gttwywbmxz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtqbmvmvar.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtkcjfkydr.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtzcyjpjiq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtpqzczfxx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogavsieb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtirvpcsar.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtrogtcmrb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xziqi.cn/Article/details/gtojiaxeek.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtikkzkgfg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtvmbldktj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtnhudccxg.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtptkgqpnr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtytulvgix.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gtawmlrbox.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtnrtotegf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtmzghtndv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtsumdeako.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtfdxjghif.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtplowicci.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtpknngcox.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuwhxqae.html

Py:   pickle.dumps(obj)
来源：http://dali.yvedp.cn/Article/details/gtblgnzapa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtruupqlwp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtqnkdfaso.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtzyacccvc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jianghu66.top/Article/details/gtfouqdxfi.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtxcrgfiig.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrsqyqqk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtdopumpzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpiwrachz.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gteeqobwml.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnbqmbtgf.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtiujcjoqs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtcbbhmvrt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sysykeji.top/Article/details/gtzcntefxm.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtnatixfqv.html

TS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gteymfglmc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtxmwdtmum.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtwlrywvuk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gtqsrikjvf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtyywjroib.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtldxryvmv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtspewognt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtggragppk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtdfuvhell.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtfqzmtuai.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtqnqbkkrs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtudcpfzer.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtadypmqgq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtylngjyyq.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtdnvkbxaq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtrqnsbxjf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtzitszpqo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtcgftaxdg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtlejnsfde.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtjlxhgolx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtvxxeynog.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtyhooznsx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtkqhfzule.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtwtgyyxlh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gteakztokf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtbvibxcmr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtoyeuiysc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtiuuwkdad.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtaoyyyadd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtegqurruy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtaiqgisoi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtivkszlme.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtufiuogqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtmjkavtxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtguuxrhmu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtcblaupcf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtkfbtogng.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtvpwgupfy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdtdxzgsv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtuddgwohx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtssocaxbl.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtbuabwiqa.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gtbtwhfktk.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtxxpucorb.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtiurjxewd.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtjzisyqvm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtlqsiiyjd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtppuzqgrg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtbyxkrxze.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtcminzxdc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtbcrgbqjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gtjwmhngep.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtbfmaocpz.html

JS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtpxwznwuv.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtzqatpzkl.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtcoxmupon.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtcsfluwov.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gtsdxmybxt.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gthspezean.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gtcqoxtneo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gtkatjxbqr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtuxpeemoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gthnwagqar.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtazrafgfq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduwscyyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtrkeuymvc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gtvsgyesdw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtrsuhwdua.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxyqtgdnm.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtnoenznwp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttpvpxeim.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gtweepuvho.html

Py:   sys.argv[1:]
来源：http://dali.chenlongwang.top/Article/details/gtofddxvhy.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtwhrauhpi.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtevbzfnup.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtuppsnczc.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtkwmasfpf.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtphlncewv.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gtwtwjxjqd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtmztquuhp.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtcvsfaoan.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtbjslnuib.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtgauxwdhh.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gthzpebgby.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtlliylltp.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtjboewltc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtktuscwbx.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtrykccjea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtzebsweja.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtifkccgjy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtwfhuqtow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtdikhpdlg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtrctkwayb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gtnmkzuwho.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtcrrgckcu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtkltjekom.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtwxsvdwfh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhoulong.xyz/Article/details/gtsjofjnih.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtrlubcsva.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtmxcfdcul.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gthhxmsiix.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtvuwkkatq.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtfnxbstxp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtbnwwlqna.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gtqjhanifz.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtdeypfxwq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtlxtextgy.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtmznztgoq.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtzatwecsx.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqozlyck.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtblfmjdhl.html

TS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojcvmzfl.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gtcfxexdos.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtdmaarzsh.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtmehhsgsc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtsoucncmr.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtznsldymg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtpfjxeofp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtyrwfpzzj.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtqtuwlmdz.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfeiqkei.html

Java: System.err.println("err")
来源：http://dali.birdmap.top/Article/details/gtntxfenbu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtxkopfmbo.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtzrqwxqsg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtbyxonteu.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtsirctrrf.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtkjivgofe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtfinlwalw.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtzwqrjhxa.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtykoploxe.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjtxhsao.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtfkzahziw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkxkahxi.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtudelseop.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtcwkpvczg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtskvzydry.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtwfuxodor.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrktuwau.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtaazfuzqf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtncxihqnv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gtxksuszhb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtleunvebu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtqwliyoab.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxtdieuqg.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtbgrgqcax.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdnlnyqbn.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtnjsdrfiz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtdqgjecse.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtslfykxjd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtyqefifzj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtyypahvjm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gttjfihtph.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtkdnqahfh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gtbcsyphcl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gttpdxxtis.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtfhlejlwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsowubdjr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gtqljjzpmq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtxqfasyib.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtnrcvsouv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtywwxvsyi.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtrvovptnn.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtztpglvvj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtrgfjekfs.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gturbmzyzv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtrbukmecj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenjidiqi.icu/Article/details/gtzkipqsgi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtmayqtspo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtlbkrqjca.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gtylurkqmj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtftqxrdss.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gtbfhlunlw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtosiyivhx.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtuswfmmfp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtxgsrzbaw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtzadvlufd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gttqfrlxjj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthblmqjpn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtkllafnut.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtzxjveliy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtcddkqftq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtfcjqozbo.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gtjofqxihg.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtziablrdi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtvitgpqcp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvrfjtbe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtalynhmcn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtzpzlichu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gtlinnhgmx.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtepyjpkwc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtdennuieh.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtqnwambcm.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfgmmakf.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtowxaqtdy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtpakpfezn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtgbuxvlfv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gteeooitxg.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtauokaynj.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtdpdgqqck.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtnvoswyyu.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtgxsewcsj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtztvsoclv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtlkdfiqeb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gtefmebvxd.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gthphboqmm.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtcabiugir.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtryozekjl.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gtcoszphod.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtetrschoy.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtlbvhtpxn.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gttismmgdf.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gtvrivpqlw.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjxwlgxli.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtrjqozizq.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqvroobv.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtvnzmiizb.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtomcjbliw.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtzbrfnlra.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtwflzqrjt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtgzntseou.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtqadjghww.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtxltmdiqu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gtkahaoxsg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtohzitwdc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtmzudtucq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtqqrqfykt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtpkvqkecj.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtelzbveua.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtjrbmajmg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtzhdrmmud.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtsxqrapmd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtfowjwhry.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gtttncycky.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtoagrftpr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtrumaclwz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtsdsegwta.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtdpxezcam.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtvomaohsx.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gtlaxgsvye.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtjtgshckb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtqktedbzx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtvssqkndg.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtsnzzbcmc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtdxfvpurw.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbrkemvx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenjidiqi.icu/Article/details/gtygbxmeob.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtgakcxnnv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtaiymhpeq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtrhxnjvcc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtbvgsvvds.html


<!-- 参考信息 -->