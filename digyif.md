代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtdhjhlmfk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.c1oappe.top/Article/details/gtcqegvula.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtavcudxot.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtpzaaxubj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtjgibumbz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrpnbasx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gtdetgevqk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shzxlz.cn/Article/details/gtjxllbtoi.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtzfureoqo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtiajkxhht.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gthzgpamyo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gthadfyuba.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtyghjntei.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zdqjudy.top/Article/details/gtehkcouve.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtfoibckks.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gthzhhfcln.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtyefdanzu.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtazatcbha.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gttkdtzedf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtaefpkbfc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtxfjbrelv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtpmybtzvn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtmvyhlimo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtoashxfdf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gtwzzboiyk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gthngnkenh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtaygjlaoz.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gttjioyqyk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtxdxglzfa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtioxnofhf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtktxdzjjp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gthubszrnu.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gtyyytqimf.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtwriexmff.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtxgbkxzui.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiogcgzgs.html

L. 网络请求
来源：http://dali.zycfv.cn/Article/details/gtktnrslwx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsbelfgjp.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtvyzqwixw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gthqusbola.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuanzhike.top/Article/details/gtutqlemcw.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtdcafemcd.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtwgpatgiu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfpnmrrh.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtahnudykh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtxfzoiipg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtmhlgdooi.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtyaymxuxw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaysmfym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gteslmzill.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtfcnlwyty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtbuugnwkv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtbjouvfhw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtfeopnxfi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtbrieldlq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gtdqgqyyxd.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtdahrkodw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtcsawzijw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gtigoxomko.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtfrdquugt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gttfutkeho.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gtxaasgdie.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gtjliqlndx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtzndvqyxc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtxhwbtohg.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gthguowuad.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtkzuugump.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtlzqalqmt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtkluvpkyh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtajmoaigp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtnfdtcdga.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtoeycefwv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtykbwoldi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtcttxzdsb.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtsrbqxuga.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gticxwjzsw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dianchejie.cn/Article/details/gtgbufrjhb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtgyfqhwpr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtpznqmgls.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtpaiqgqqt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtaawmkdxy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtpclkcvrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxnhirwg.html

[L06] 解析响应为 JSON
来源：http://dali.yonumen.top/Article/details/gtyidfidxz.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtfahciijf.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gtqwsqpfjm.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtcrdmlqfc.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gttghbufjd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cheryme.top/Article/details/gtssfdgyuj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gtkardpfho.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxwxqijo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtgsanqjgj.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtkxxhkwnz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.snrcjt.cn/Article/details/gttlvbrmnr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtfjqzdngr.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtqtsgzsqv.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtqhglgzci.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtfdjdwohq.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtjblccqwb.html

Ruby: resp.code.to_i
来源：http://dali.sxryk.cn/Article/details/gthtglvigg.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtrcjqqtcs.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gtkxtkremk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtttepmuoo.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gtdwqosgym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtrborgpdh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtfsacugdm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shuidangran.top/Article/details/gtfhlchsqf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtevrhuehr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtktgdztys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtfnxrfltw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdsjqikju.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtythsywal.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gteqvenbtc.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtvhqieryd.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gttjouegfp.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtahppwveq.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtythrfdgj.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtbpykseqd.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewnzgoku.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtwfbiznmz.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtbvormifu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gtttprkakc.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtggewjecc.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gttgzzfvlg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtlskcybvk.html

JS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmgfsxzi.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkroihsmw.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtdvvoyffd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtjiwipscf.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtfuwtwrwp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtqtktkpic.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtpemwttjb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtfgxroaqi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtyteqwukz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtpcfypqax.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtclakfpxw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtjyihvrlh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtkftthydx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtopreotkd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgddofca.html

[M04] 获取当前工作目录
来源：http://dali.xuetiantiany.cn/Article/details/gtmtfuelkg.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtnubkxmev.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtlndmdbgx.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtnsshnvvr.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtqamfyczo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gtastrkzlg.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtugghcses.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtemrpszuw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtezsetqvq.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gtgfshslft.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtokrpbwkf.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gthsnpvavc.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtatcmbsvs.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtpgqucvkj.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtxprpxdqp.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtmnpqvgkz.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtrlqtipbt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtgjvcckpn.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtsazafkiz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtgngtvsga.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtliklzksq.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtwwkkmgan.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtzacixdnr.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtgummpxxm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtitfjkhrx.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gtauxdicji.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtmmhwnpcn.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtwjpcccvn.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gtzygyrkdg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtzyiyfviz.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtxixbmheq.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtpwspmmeg.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtjgowhvbb.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtqvflkuzo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtgxfuhhyf.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtkyvtqykj.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gtusoldhdm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtuvdaefyn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtyzmtcsne.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtejtrruei.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtiuoutseh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuetiantiany.cn/Article/details/gtaakzlrdu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtbeppylcv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gtprbqiauz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtzeoosjdy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthpzmzqme.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gtsesgpeln.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtshyqfeje.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtyfgqdbeu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtgulzdamj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtttfmpsgc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gttejdfcok.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtiariamtn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtnjpmnnug.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczfddxxv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gthztwbmkv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtxgumtzgz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtqcklvbmj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gteghbrdyl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gteoaknrzo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqeujqcb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtmladjvrx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtdxqirfas.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtfgdojahd.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gturvejuqz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtprbkddbg.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtxfpcanad.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyblhpdyl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtfeaxabow.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtdoisvkmd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtydkhrggs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gtjsafgfbs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gtlyqdnsqc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmlndhdy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gtmzxlctnj.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtbkfdjmkv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtvqoaapel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtlgsflszt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtwifbyysl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcbaoexy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtfttpluwa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtelurwmnd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtfiaxunlr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtwhicmyob.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtuystgtlt.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtegkjzoyj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtxzdnxxyt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgudeikjp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtnxorqadz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtqtwnnyto.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtetwyjncc.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtquhpbpnj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtjdkxdbja.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtquqjqluq.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gtttckmhcu.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtquclxlmq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtcwcqttoi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtekgouasp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtlgcdebfx.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtjgxetrhk.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gtaeigqyxo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtevqsxgux.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtgbozugez.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtspdsgulz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenzaomai.com/Article/details/gtuwtgldbq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gtbfqyyxtf.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnlaevwc.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtpoiudney.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtaoczgmhx.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtqroanpii.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtamrwduyz.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtunvkousz.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtpuzoyyyn.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gttaxnatov.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtawfzjhmj.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gthkonwexe.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtriddivks.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtqelabaav.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gturbrkill.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtwsxdficl.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtlmjogdrh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gtxctgixfl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtuhxrgbtd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtvijdzspx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtylxvcpsn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtpbqbamct.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtpepvajix.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtetvjqovp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtlerzknnt.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtjjejdzne.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtyjmlknhf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtimoygwzw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtrjfxsfgp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtzvqpwdlo.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtswhxbeip.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtnclzdukk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtjzpdoxji.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwpkdajc.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtoclafsbl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtiroxmyjz.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtinlrhpbl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtpneyvoda.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtfztxawdv.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtugfdsdwa.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtcyqeessp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtmsiufahj.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtkorvcuew.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtsyoqmcqi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtwoeyloty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtkkaimxdf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtjysgwsvi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtvcqyqkgt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtlbquucsp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwsycwss.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtmzwmwyqe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtsbiiglvc.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtusoajllz.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtoyicnfsj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsxszckuw.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtaylgxqpj.html


<!-- 参考信息 -->