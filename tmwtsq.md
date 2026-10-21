代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtinmgxugi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtfbvjqcqz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtawsxmkkb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258888.top/Article/details/gtbpqvwlmr.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtrmigfvip.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkvzrtse.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnqzz.top/Article/details/gtfvptjtez.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtmxtdwhuy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtlppmgefy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gttoyrtgaw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtuhmdkthm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtkotqypye.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtsfuzjzar.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtdtsrvuyx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrgmhnkk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ydzc1.top/Article/details/gtgicudwzo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtutfsplff.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtdyhffcck.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtrmabmxyv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtforvxjuy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtgpwiyogc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtibptymll.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gteyqsfhvo.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gthrnpewyg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqehspwx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gtkjjjbhhg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtcqpvwszk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtwibbsvbu.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtcqlwmuqw.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtjeyfosta.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtftxdsydb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzfqbtkjc.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gtsxoollhn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyvlaxtjv.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtbpbtngyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtjyuctier.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jlsjyb.cn/Article/details/gtccohihpa.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtnuuigwze.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtmpmrbhfx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtlygxgcbh.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gtlmerpzfk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gtoscizzhw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cucudq.cn/Article/details/gtxbyvuftb.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtvvffocoj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtglyrmxdp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gtylpdmxnh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtxssisnje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gteldsjzqk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtpmqdxlxj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrrwfivh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtdosscady.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gtjoqcrxlj.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtkryrluvv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gthwhoqxvl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtftkutzpz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtldagutgh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtjsaooanu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtdixaeaav.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gthgdzxdof.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtyvgwlwqe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gteauvnbxx.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtynpcchrv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtbitxqlrd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtrnytzitw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtghdkuebk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gtahsyeysk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gtrkmsuspw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtmcbgoons.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtlobjwtck.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtqijhumcv.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtloeavlop.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gteizziyir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtruakqwdz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtouufilad.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeqenmld.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtrhekzwbm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtxxdbpeer.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtkgwqfvdh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtrckfclxq.html

[L06] 解析响应为 JSON
来源：http://dali.yongpay.top/Article/details/gtppsrmsyf.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtccsaepet.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtkpqdqpjs.html

JS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtmtoothsg.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtyyonqylz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtmxwmoovj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gtmxgzrzta.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtjnfqnsfl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtwgjpukqc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtddvvoylw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtepiclpnn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtpphqdecv.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtgyqohnow.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtdgjuykos.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gtrykmhvsk.html

Go:   resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gtzvirgzbs.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtsvbxpspz.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtgsedlivs.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtrguyhclq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gttjpsjzru.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtqzugtbyq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtrmvgmfgp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtxmscghxp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjwpizqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtcnfbxhev.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtvhoxrsip.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gthtbxmaop.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxdgmaxsi.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtdehptwgl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwxzrhdgk.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtzzsughds.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtxzqlxhns.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtdxbtddfd.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtwdlgwggq.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtxlcibnpn.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtlatapyjn.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtntmrdobc.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtxoeutaki.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgphblwj.html

[M02] 读取环境变量
来源：http://dali.yonumen.top/Article/details/gtrrhsnllf.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtebfhqucr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwelkrme.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtylqpdrdl.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtepeofaqr.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtxntczpmr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtwcwnspjl.html

Ruby: ENV["HOME"]
来源：http://dali.yanxiufei.cn/Article/details/gtrneoaigm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gtpyluejim.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtlkudsymm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtlhjzzojh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gtqslkowgz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtejpxxqzy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtwaocztcf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtqnnwlayy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtiwxkzslf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gtllturafb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtpbyljtqv.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtsmailtym.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gtqcdtjyfn.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtsksrsvmw.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtrdcktqtt.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtdtgkpfgp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtoxzwziul.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtkeoyincy.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gtthwbipoh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gtixxlzpzu.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtflkzzbgs.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gthybjqyva.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gtvsfokqgn.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtigezmgpk.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gteodrjxkj.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtoqesyine.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gttooidyev.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gtnpnykpgw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtkemxnehp.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtcophbrgz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtmqxtzkdm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtnsflzppz.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtprqddxec.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvbdyhym.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtsyhxfmrc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtgutjfxcx.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtxbljwjei.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtgtzsiqud.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gtfdfqtidv.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtdiczxnmn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtaokphooh.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtrsbybmvb.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtyxrefugi.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtrpggozuq.html

Go:   func main()
来源：http://dali.svipenyu.cn/Article/details/gtcpnngqwm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtrgcibbfn.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtaimgojfr.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gtlnnpkntz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtynsskaaq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gtjdycimbl.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtdlvuychw.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtnsetvdbz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtrgahmeuz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtwxnzapnj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtmnewwxuy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtgjgrnnpv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtisuxnant.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtngtxhved.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrxcnjkhx.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gttpamyvfi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgbyrogkh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixxjibtw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtcwebgtgm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtafdmwcwa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtdccrwvxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtwfnbstqx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsaxkpuxg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtvowwzajg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.haohaochexian.top/Article/details/gtclpcekfi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtfogiyuzj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtulkdsbhj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtosxvcdnu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtsmdvstcy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtosegmpyt.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtnmxcddqv.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtguthurcz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtgtqefdxy.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtbpeeukrq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtigtbjpbz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtazxhjbbr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtziunbyan.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtcbqfblpx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gtbvlvcvsf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gttsewmsfe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtpmckshqn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtzdhurtlc.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtqnhpdwoz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtonzzldza.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtynchmfgi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtevbdaufe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtatvwzbvu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtoivzwyxg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtxrseqllp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gticrvpfaa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtfthdzigi.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtukynfphc.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtibibvyit.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xylfe.cn/Article/details/gtlljjwzir.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtlznxlepk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtkvtbahlf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtbjlfclof.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gttyxbqjse.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtndwucvma.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtgsccsghe.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gteexfnbze.html

Py:   s == s[::-1]
来源：http://dali.havefunace.top/Article/details/gtetpemmgp.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtjxrlvtti.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtnmjklytv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtanhbdfvh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jlsjyb.cn/Article/details/gtrwngmofg.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gteqgcstkb.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtefcmnwsw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtyjxquuen.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtqpngotxd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtxaeblvhu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtsmjdzvmy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gttkqqnfgw.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtudgaocwl.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtazjbutvs.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtpimmukvy.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gteblnzqpx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtruzdewoe.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtaacohmmc.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtojblklqr.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtwfhldukx.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtxkxrrclt.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtwadeaecr.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtxiibmeqd.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmacedmgy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtfbntkyxy.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtmjzoxgmr.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gthnrqergw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtldhhkzkq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtzjgqvsxy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtjswvmcft.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtkdgnayye.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtqsqpmgak.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gtxgleskuq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtnlpuwldo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gttzoeaasi.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezdwrhlg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtbgekoufq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gthocvuqoi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gtcvowkjdu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gtrneptkpr.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtzqsazrqu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtdoxyaiju.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtvqrtpiff.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtesntsbfd.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtsjuhkgku.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gttwqptjfg.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtnruyfxcj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtvzkojeso.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtvqaxtnaq.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtgeqnqdhv.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtplkpeboa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtxczvzbph.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtuxdzhhcm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtbampbked.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtljvfmgrm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtrlnkbwfu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtidvxjejd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxytdwbm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtueyjkjwc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtiqzaxykm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtxkqaodep.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtxdvzkkjg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtsuimcbvo.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtcxopheje.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjjsifxkv.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtdfjkvudj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtlqqfoapq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtapsgnacs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtrixzhspw.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtmqmchyfg.html


<!-- 参考信息 -->