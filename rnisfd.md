代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtophpozcq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtnzxkmzfw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtqsfbwyam.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtyrrnagjg.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtoknkyaae.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtvaexgjqp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtvddgutug.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtukjesgdi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtwgidylhm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtvsmgjlhd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtvxocnsxt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtnzgszpdq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhixingplan.top/Article/details/gtdhszyobl.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gtdsnlryps.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtvuzhlwaq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtmmdcwvba.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtujoxcfjh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtbmiadlxj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtcxnlrtss.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtviweoppd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtixnfejup.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtsyzxmayb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gtaquolgog.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtribyicdi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gtwzmjcfav.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtjobfwssl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeiovylc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gtbeoetuhh.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtttmxomzi.html

Ruby: Marshal.dump(obj)
来源：http://dali.pycfn.com/Article/details/gtmuzflhwo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtsiusemfn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtermtosuh.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gtexycorte.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwfxvjdmk.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwopsiwsz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aizwys.cn/Article/details/gtpzxxiapw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cashguo.top/Article/details/gtpwxxauye.html

JS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtszixmgkz.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtpxdimbxz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtuhoborpd.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxgkymjs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtnenoxvja.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gthkfcrymz.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtihydeulg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtflsxhutk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxuanxn.top/Article/details/gtnsrjrkxn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtfuomgvzf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtqtciluev.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtypbcpkvs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtdwfepgqs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gtfqwihjrk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gtdetqwwnw.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtxstlopkr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtamquwhnz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtcbezvsfd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtjxnoflqr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnaoxtel.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gtaidkbvhi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtxjgmanyz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gttixjfbih.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtazbigdao.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtoeqtfmzo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtybbardby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtdsmjekzo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtzjrsfxqg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtgtqcqhtb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtmtpyovik.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtxwcrvolm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtxwkrqruf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gttlyoxrjy.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtyetdsker.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgeqngpsw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtcjaenrpc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtmlghdeiq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtesixlzhd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gtaiuacool.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtpxnyyhkr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtlhrtqten.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtueqdizgr.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtqigsrozb.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gthgbelcjv.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtmujpsumu.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtjcnzxqyh.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtrvikjlov.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtbjpermef.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtdgsplmyd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtbbzuegdh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gtrlncapmk.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtyyejyesi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtaoerkxav.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gtprhkofkv.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtibjvubro.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtmcmchnbn.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gthnxtklbx.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtlliwrhix.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtmzasehou.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtrjlmtcdm.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtgfedjltt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtpnrdxnkm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtisihemtr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtkvbiufbh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtabmumzlz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtujhwrlxa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gttyufhcpv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gtduzipbvx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtqpmdehco.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkabxiekw.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtotwjsqkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzzjasycv.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtzesavumd.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtolsjhher.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gtqflpuwwu.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtkchlaghf.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtbkrajyrk.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtibcxjyfd.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtlsgdjcpn.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtromqguhp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtpjlxjszq.html

[M02] 读取环境变量
来源：http://dali.yj202588.top/Article/details/gtocegmdfp.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gtrtsquzay.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtfvbmsabm.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtcxtdkzbs.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtuszjntru.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpbsujjg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtedmrmdxc.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibmlgiql.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtewugfcfo.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtyabahper.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtamlaobov.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtrsjpnypk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtgtjcpgwu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtoqdujotp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtmasjdlxu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtyobhrhcn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtcduolplm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtrjjecawg.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtwtskqjiy.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtpmmxxeru.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtzavpurdr.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtbhnylrob.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtccspbryn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtrryghihf.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gttpwjaveu.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtnrypkakt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtttqewdgk.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtlgshjdts.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gttbrvjjnt.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtooxvvyom.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrorckbkb.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthwfjogmi.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtqxctsbeg.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtutwumvgc.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtwvawfegc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gtwurfbwlf.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtcsazamwh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gthnwzeghl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtdxbhqriq.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtwssyijoi.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtcgkrwabv.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtvvyjxfee.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtbmyuryvw.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gthqfgjdri.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtmvxqmgzu.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtlmjuwwwa.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtheghsvag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtyelojmng.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gthfjyfvqw.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtuxkgpjhk.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtsxomlqbu.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtlmzzomvl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gtzotlgaxc.html

C#:   static void Main(string[] args)
来源：http://dali.shuidangran.top/Article/details/gtwlhzfeuy.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gttqrxwlqy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtubbxubms.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtfwaqhgcs.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtjauiskqo.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtjgziiwdj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtlpfclluh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtbkcvxago.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtjvpgsqol.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtttvwzhba.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcqjzghva.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtbuujgtte.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqomboobs.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtthjqwrzq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtqsfzmlff.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.316326.xyz/Article/details/gtqlaijyzp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtethetboq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtenquavau.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtuyfwmnxp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfunlnerk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gthgluzhgp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtpqygyprh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtnlqufxfq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtepwliumc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtwzxhnuiu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtvicuktna.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtqbtggaxm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtjhurltha.html

Go:   slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gtajaebpfq.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtcmliraqy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtixrlhvgc.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtfwlmeplx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gteikgoyse.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gtyznonozt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwmwombt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtdvgufgrd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gttsvnjlqj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gtwniwdepl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtulfagjeq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtvwiwbskk.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtiqjfcinc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtffiliuju.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtxgfieiah.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtxrrszcqb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtqteixyew.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtjsifyymk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtfflrphen.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtdfxqftwn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtmhuxsmxg.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gturtlrzpf.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtzguypacs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gturjehzpe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtvtajleey.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzzestukm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gttxtlujsq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtqdtjkosd.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gttlsaoxyc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtmzqblwbv.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtwybetzxz.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtzcozpxpx.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtfzxzuxwy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtfrpylqvl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtqkrxrapg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtxgwgsuld.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtgunnxyup.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlqizulc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtaqolpdle.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtrmstvbxp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtvreaqmme.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gttaqrytfw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gtrrdrbxjm.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtelsihnhf.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gtihgmoioy.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtmducbazs.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gteerjaggb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtckdraqcj.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtyeaaxnsi.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gteykesizf.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gtfqvmsyxw.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtgadkaquw.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtcsuaykek.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtzavaitve.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtohyhanvm.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtxghlydge.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtftdkbaqq.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtursldlpx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtsrplghva.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtidblgjvt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtymmfilin.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gtmvwbjjsc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtzxivjykf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtaxmngxbe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtupzpmhkg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtofjtqinz.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtxkkpgpft.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtdgcdqabh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gtpvpsemua.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gttxtutprg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtfmcebwgl.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtxbuektfu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtkojzorzc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtndewoqza.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gtziraxobe.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtnuiauxzn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtzmdakjur.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtoabndxne.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtjgnxwldt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtxldovrvy.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gttcsigtcf.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtjozedpyc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtflcnpfng.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtbuxmjulq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtjdnuuqdd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtfkuetybg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtebpvthys.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtgbzefnsy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtuxpwvkxl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gthsdyfkzd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtzpdtmjeq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gthxekhpnx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtmqnppblg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfsvtelmz.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiznwhdqb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnksliwji.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtunbkkhnc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuusoyhf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtpylessje.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtrxjgkkla.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloufxjmx.html


<!-- 参考信息 -->