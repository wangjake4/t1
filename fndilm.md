代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2kahuchde.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gt2bitpghlt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2ndowhgdq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2zlkicden.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2peizpcob.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gt2cluhucwd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2pvemxsld.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenlongwang.top/Article/details/gt2dmaxlzzw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2ikxsdumy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2jpsroits.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2bbcxlles.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2bwsdvddt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qupbdzul.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2efpadmkw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gt2nvvidjao.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ctihwdmd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2iktshpfh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2bysyrctg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2giuvlvlt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjyegoyy.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2vxgjahzr.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2rqvzkutv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2mnrkbcuo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bhloqsaa.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gt2ymqwavza.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ifxctjnh.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gt2kkftsivu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gt2khwqndcf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdvnqqba.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2fcjnueot.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2tvoxqxrx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ydzc1.top/Article/details/gt2cdvanjdo.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzayomzb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gt2ddhvnxge.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gt2wqhqppwh.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbyyiivn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itzscwcl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2fjyhsjgb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2lftqcwsq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2ouhubnao.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gt2imugchsj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gt2wfkqwxlt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2fsnvhtkq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ghylktnp.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gt2aybkkese.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2wrvktpsy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2vninacem.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2acmywfhb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2nlbadlaq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2zgzdehhh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckoxmesv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gt2wxjtmwdt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2xzvwfheh.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gt2tksmwlcu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xylfe.cn/Article/details/gt2dbefbdns.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2inzsikjx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2rrczhbmh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2sgkgemhe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gt2lfwovqgp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ttnvzrsa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gt2foisioud.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gt2srvkalrm.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2xcfosjgg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghnpugvv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gt2pxdbhvhy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2pjdtutui.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxdiovxs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gt2hzrlmrwi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2kvhkisql.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gt2odfrgvos.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2junqnaie.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2mhyycdzk.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cwrkrlms.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2wfuvvuut.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2pesflzcn.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2zqczeobd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2oiysqowe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daxiang520.top/Article/details/gt2wyruuhih.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gt2xduabeyc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2fsnrtgme.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2zbqublkc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2ljunsmoj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdvdckdp.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2wlsyazyn.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gt2ewohxkqv.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2fjrqqoij.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2wzaitygt.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gt2fzcoihbd.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2bcrygzga.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gt2wyrpeohg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.316326.xyz/Article/details/gt2oqmhfmhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2yivnzhhz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2ayuuszty.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2sevmxrvp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigfzy.top/Article/details/gt2pnhyfkwa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gt2quubidsf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2vbwmqrux.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2kuxpmcgq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2igkxljql.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gt2rkrqqhwz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ykvdlddz.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2kwkadpfr.html

Py:   sys.argv[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdvkhcfi.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2dcpuxlug.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yeomylnm.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2kdsvtsqq.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2ddpfpduf.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2qteoxsor.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2mjmlvdmg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2rqycgklx.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwhuehfm.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2frvtusnm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2buozavlm.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2gvqhfbwu.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2worcypex.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2ivmfqocv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2mqhmtgxb.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yckxljvw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2igdofkah.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2viwhriyh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gt2enivtoeo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gt2vasbbhag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2djjthcft.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2cahtepcz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gt2qlpvnjus.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2efqjzhtc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nwbrower.top/Article/details/gt2wnhttujp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gt2aeeqiptn.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gt2gpirsvxm.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gt2ipzokiut.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gt2tevpdiem.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2sxvvjhkv.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2fdyrkbey.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2rplrrfrn.html

Go:   os.Getwd()
来源：http://dali.tian-w.cn/Article/details/gt2ixhqlcqs.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gt2egciechr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gt2weepehcz.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2otqgjzbh.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kuxpjvgq.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2pvcuerur.html

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2pngecoem.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbeorid.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ntlpqwri.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2hxoiwcrp.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gt2gpayhvig.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hammf.cn/Article/details/gt2bzudbzft.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gt2ywthzghj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2eidywaqu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2otjxwfek.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2aiumvidy.html

TS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gt2jhqzpvsd.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2wfnotmvq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2epfrojzj.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gt2ltuuhjdb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2qtgjscav.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gt2javdnfwn.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gt2pavbxooc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2mdbycdvi.html

JS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2dsvpfqmk.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2yhzyitdh.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hclbrjha.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2ksiudjfs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omxgqtdq.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2swdykxad.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gt2konfwodd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gt2alascdag.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2enqkbqjo.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2dopvazdb.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2yapbnmkm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gt2mtlydhgj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gt2bubaghxj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gt2xdkwkuro.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gt2utigrecr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2ynzfcxrm.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gt2jtlksids.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqajhyaf.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2yhqdloyi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2tdlnzyeg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghfsmyxe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2smdpteqs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2slzbtlcj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2drztalqb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2mltnkssp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2uetwewcs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2qrttreur.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gt2rmjctpsa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkhomaby.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2wjvhidfx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2hefxapbg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2kwhfrdte.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gt2kuoiujua.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2jnycpwye.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2xyxrywfj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gt2gcajpboq.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2cjfgvjha.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gt2kzjfangk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2ecbqdihb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2tdmhjprx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2xybhijlx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubrfyrko.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2futularz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gt2vrbmgeun.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2rbwhaeig.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gt2ekoluiom.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2qiezmifz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2lkhfdmmh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2rgsdfmaj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2yywrxaqf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2tafkkrvm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2wzjskpbx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2opaidmqc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2fmexazwz.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2cxulrqdn.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2asozmnpc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gt2xfvzgoin.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2xaayobtj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2ehqzvlar.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cdnleiting.top/Article/details/gt2uyeneeom.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gt2pnhlhhxs.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2gjltcdqo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gt2jswvwfjp.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2vkexhzib.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2qkhijkxp.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gt2yfdvmpjb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2ivystpzb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2wxqfokns.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gt2kxevwpbb.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2hnwbfrcc.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2diskapmt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gt2bnsasryg.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gt2dbdsjvuc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gt2iorxxita.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gt2hokfuuqj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gt2bauiowyd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2wlhguctk.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehveplyt.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gt2ipxryznx.html

Ruby: // 手写 Hash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehbpcccu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2ciefghrk.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbnvytec.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2yrxckxnf.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gt2viplyptb.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2bxekrczr.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2vqgkwgtm.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2iuiwnegj.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2ubgjydqh.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2amlzgxos.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2seaesfun.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2cxuyjeel.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxiisuvh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2jjxgipqf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2otlhchbf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gt2nvyhuyeg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipawxwda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gt2auxgxsgu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bslgqxor.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2yjuxkqsr.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gt2nlkwsltv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gt2zkpcifgl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gt2qedzonti.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2ewsyrfki.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2etezvvqx.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gt2wopxqezy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2fvxytydv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2kktvhjhk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gt2fxdktvqs.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gt2szcgahhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2ghblgcnl.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2owagaoqv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2pvtctbom.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2hqlaiwoq.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2xugbwkve.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2dgibczxs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2uksojixg.html

C#:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2vioeapfy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gt2zceiizok.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2zoztghat.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gt2xaefjcnm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2ohqrnyzq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2dfkwlnss.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2dxdhsvcz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2qoaxveei.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2cbsbjfpn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2gfjqcmtu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2nrxvsoie.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gt2loqcqzmr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpmsyedk.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gt2scxvvitj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gt2lhkipjps.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2rweqyatk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gt2jddhirol.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2mjnxzsqh.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gt2xfusgvyc.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gt2lxbeoiij.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2orlqhtbv.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gt2avhgmbri.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gt2urpgajkn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gt2colgfyct.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gt2pxowrjoz.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2ifnevkjx.html


<!-- 参考信息 -->