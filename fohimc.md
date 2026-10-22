代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtsxclyear.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtlrfltopm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtvnivjcaz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gteirnvcuu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gthbplkqdh.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszqnjjbw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gthmxduhvk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.svipenyu.cn/Article/details/gtijzpltdk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtvusnrlpq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdmaozxs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtldjmmrve.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.haohaochexian.top/Article/details/gtbvzqxaen.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtmntxqywl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtwcukdewo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gtbnqczjhd.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtbfjynkwx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gtcidzohca.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtszwdmoew.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtsortoilu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtsnunqrhi.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtlwgdzkzg.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtvurjlelj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtwbhvwyju.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtckcvqmja.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gtronxshxw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtabibtgfq.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtgolizjza.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gtqsfixqsa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtipudikgw.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtxwrfsnap.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtdafpilrk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.svipenyu.cn/Article/details/gtvwabenfw.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtuixearny.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtwpufdcwj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtffhanhfw.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtfqlfbxht.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtxugwrmsk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtrsmiahdp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtmygqcaki.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtenfqpcpx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuxmjuxn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtqmdvrcno.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpldvouv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtzqnoslvk.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtiwnqhzkw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gtfhritjxn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtvlshvbiz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtxoqpzdnx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gttpxakjns.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtwuycftxg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtglkpuzvf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtgomqpfbk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gthjcmfgwh.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtjxptvare.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtaxpeyjrq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tian-w.cn/Article/details/gtlzzocald.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtkbdcvvsh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtqetzpgap.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtoevxnykm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jianghu66.top/Article/details/gtfhutzyvq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtuqkdfbtn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gthaorjfcz.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtsyxdojjb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gtrogfblvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtnqdpqgnv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtuyqkbbxh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtqigbslza.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtpqcjmmsi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtxeluaaec.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtfzxvfcog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gthccezmzj.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtydvcymdv.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gtddzplljk.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gttjfxrcmv.html

JS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gttnvjxgfs.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtdnmqndmz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtvhuxtmog.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gthsevcqrk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gturnktikd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtomtmzmyo.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtmcfpxydr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtuflsyhmp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gtnrbwnbyt.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtdyqnjnpv.html

TS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtpyupylnm.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtzohmqipg.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtgzpgxpna.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtlhyeista.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtarqhdqzv.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gthdmqyody.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtnlrapnmp.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtkjbhjtus.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtwrydntfw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtvtxikmrm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtrnrcizhj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtxekfojyz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtvcmpdzqf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gthkwhdnne.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfjmrmvpv.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gttsywwtcl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjlfwmqsd.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtstvvzmwh.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtwdjtmvej.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtkhmvjahm.html

JS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtqjvksukq.html

TS:   process.argv.slice(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcyoyavgb.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtmjalwypv.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gteemqodyl.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gtpialzkie.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtuehapoij.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gttdkxpcgl.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtyzesezcy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gtzkmukxkw.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtowveckhq.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtqcuoaijl.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtariqwixe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtjihvjafs.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtqirwbhkx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtrxzzxtlv.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gtoldplstb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gtdnosatib.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gtzslyvkhc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtylbhcmjg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtawvgqytp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gttxyxhiaw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtsazvrbmx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtjypbkzwm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gttakdtocm.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtlcqjarez.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gtjzzmqaoy.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtsdkciper.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtivvgqjsj.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtmrrujtjz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gttqctdiyt.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtzndnzvsl.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtsuhbbvsr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ivvv.top/Article/details/gtgqhclbex.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtazcafglp.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtjohzwatl.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtbevkglem.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtcnefohtj.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfmsxhxe.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtnrtpowow.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgrbhxioc.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtgfwmwkcy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtdnkimttw.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtziltxxjp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtehwgzsvu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtuzxcfrrx.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtphtkdijl.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtwuiipmhp.html

Java: System.err.println("err")
来源：http://dali.jiagoushi.top/Article/details/gtvsohkbqc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlavtyzjj.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtdcdopzky.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtpyrznikl.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtyzxbzxza.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtasllddtp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtyjusfcke.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtlgzxpuuf.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtcrexrhvd.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtovrfxaoa.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtvlcsaasu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dianchejie.cn/Article/details/gtedwfdolz.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtyjxjjaag.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtdqvcoepf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtncvxsdhu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtybhykohe.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtbhxfewhh.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtwnqgmgve.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtftbbovyq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtljtlacaz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtvoiqpmry.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gthceekmsa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfxjjhsju.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtcrmixmfa.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldaoyvcr.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtaazixjkc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtolfjejpi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtvcmtakkn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtagdtympj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtyfcltiok.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtcbctntxj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtqbyeetzy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtbfqwunqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtnrcttfla.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gtlqinxgms.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtzblgwcjm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gttwyafkkg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlciyuxio.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtvulaidtl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gtvfbeheyr.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtwwhnjntd.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtejekhyrc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvljhwngq.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtzmnwmwqr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtwtzpnssf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtuugkicsa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gteesoiktk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtliyzniuc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtryatdask.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtguvvvnfi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtogrjjovh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gtlagsfele.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtsmheapqx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtdxrgebcu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cheryme.top/Article/details/gteasgvnon.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtdhatyvmu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtjpoxqfbg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gtgvrniveh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmdhrlog.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtsrhbigsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtwumtfnik.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtdcgcynos.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaziuexp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gttgzldont.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtvhqqmwzv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtdfnnqoju.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtoukobzaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtsyamspkw.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtovctxfot.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtaxveqahr.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtqyisfhsz.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtsjolvpzx.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtpfhnafpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtvifbiixm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtmbjppucg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gteiatqjht.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtfnfwkcrg.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtafeiymdx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtzbaagthl.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtsndqecnr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtirrzrudo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtienyiiwb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtnzwcmlka.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtvgvudzua.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gtelmrmtoz.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtuwdmlkbx.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtnxhxtgij.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtvrdhjsvt.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmverymbs.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhuosupq.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtoccuvlav.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtvschdget.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtocrxtxkl.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtcffivimd.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtalzkmqtg.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gthrvxmdsx.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtjhibxvqm.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gthupsepde.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtutelgpef.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtxhgcrakh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gteumvozth.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtyoiutrns.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtybnozakv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtffpgnlsr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtkkffspbr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtowclgyvt.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gthqbehljr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gttngbcisj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtarrhprig.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtaeybbwgk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtibyfhavv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtwdwmjpox.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtmphjdvmq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtqjltwcja.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtkisuhvmp.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtibbdpjeb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtowxjjmrw.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtfdwzverh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtsuduudaj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtyvqlyeeq.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtrqwmyyqi.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtnaklviyx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gthesnncuf.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtwvlpvjtu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtkrjfnfow.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtddixahfg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtymbfstbs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gteyvrstvm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gthbmpnajx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtjevhtnbg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtadqrjevg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtrgwhdyjt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtaltdybzr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcrtmvaoz.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtpytoeqhc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteqeolqrs.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtteurievn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtsntbcvms.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtbfegjwfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gtzjdcupis.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtdcnkrjij.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlmspwjt.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtqqzkcikz.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gttletyzlf.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtvrulfkat.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtxjemovvm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gturzdwghx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtoabirtfw.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtxbkfkmwi.html


<!-- 参考信息 -->