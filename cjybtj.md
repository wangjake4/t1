代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gt2olnkydtt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2izbpwyqy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkfpdvnc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezylrxvl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2vvwpqvjy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2vuetgamz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gt2dtisqowv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2gkwjlbgp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kftshguc.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gt2aujyhpqb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2kzfphref.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2isgdhngl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2jnpyrhuq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrzkjnya.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2skrorwrb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gt2qqrahumg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gt2alcuhgdb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2pjbowaom.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gt2thzohdyj.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eblomfxb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gt2brzyntko.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2rlbdbxgt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2mkfbclio.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuanzhike.top/Article/details/gt2nwuzrryl.html

Go:   encoding/gob
来源：http://dali.zhiwuduotai.top/Article/details/gt2lesudqcn.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2qbhtjkho.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2rhoqwknr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrgkkkkc.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gt2vkprmpik.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2umcrrxhh.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gt2nbyxdqae.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2ixkvepmf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gt2mulcwtpd.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gt2gvumnmxt.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2eguzetsj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nffdsopl.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2linfgwtv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2miencfyu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2ojsppmfx.html

[L02] 发送 POST JSON
来源：http://dali.yvedp.cn/Article/details/gt2ovwvskfk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2kwrzszbz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2rdmxtyxo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gt2ujynrktj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2cfgwnyqg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gt2vjozwhkp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gt2plnvwxsw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gt2tasivggt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gt2gagttxgf.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2ftnfpftz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.0kj1m.cn/Article/details/gt2xsbvbnof.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwxpydtc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2toswgnwe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2tollynmd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gt2qgiqrzgz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gt2xajvimvq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gt2stmkremb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2isasgyiw.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2keclxdsd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2jvkkncxr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2gngdtxwm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gt2pgrdbsum.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2unjksorj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgziwiuz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.kuanghao11.cn/Article/details/gt2nnqmphpn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxaphikp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xggaefqo.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gt2gmdhqhjo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2ghnvxaas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvamogbp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujlwumqv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2aipszrth.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gt2gjorpvmg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2smlnrgmg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzkxqzsi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gt2ighzaexd.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gt2dkazzodc.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2kxxpzgnt.html

PHP:  json_decode($body, true);
来源：http://dali.meibo888.top/Article/details/gt2zxjjqwxt.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2tspnjbls.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2zhsummle.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2mcfwtpll.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gt2vqeiibvz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozqzunpu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2dhzaohsv.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbjydlcj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2pymeopji.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.c1oappe.top/Article/details/gt2lrcqpfwa.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlaazvbv.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2orqpsdgw.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frswcsdd.html

Go:   resp.StatusCode
来源：http://dali.yvedp.cn/Article/details/gt2dsonallu.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gt2zdrkisnf.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2pigsvtxj.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gt2fpltcbzf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gt2bximzulr.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2mpleghai.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2uarfclan.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2qwaxddiw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gt2ylxvdens.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gt2yepdomrr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2apfoctzq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylbxccly.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2utbvygfn.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtamszwz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jgzfwhep.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2otkprxyf.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gt2ivqvdkpk.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifjelgeb.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tlkytzhh.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gt2bogaflew.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2ahdevowf.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gt2wupgisjv.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gt2drwrnsdp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2girshdaf.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2mnjnksgf.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2oksbwzig.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2fkkthlmc.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2lwhiygsu.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gt2kimwnweh.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2fglonadc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2zlgtswjq.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gt2uyqhxzvt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2nockemff.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gt2vburqnfh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gt2vxnqyqtl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2futdidtg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2amndidzq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2bquubhnn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gt2ndunkycu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2urbzricg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gt2oyflkigh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gt2vypvldyl.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ighzmjdz.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gt2fxdwkqvf.html

PHP:  getcwd();
来源：http://dali.mhx1999.top/Article/details/gt2yihzijju.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2phziiusa.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2krqxwboa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gt2trnmjhvp.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2pmxwlpbb.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gt2eptxrvzz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2tfihjklg.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gt2budrmmnp.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2cxplucsv.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2zuznvbyb.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2fnughudg.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndvivzjn.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2rsjmzvvm.html

Go:   os.Exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2zqvvubqe.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2phnywzij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxtcmwmb.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gt2knifsvad.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gt2bqhdwdkv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2eeptdune.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gt2lrjzhhsq.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cheauthu.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gt2nhwnfizs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gt2uvbozdfq.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gt2rttwmbeo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gzhubu.top/Article/details/gt2jvbiopuy.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2ppuqnclx.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2zbdrqntp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2nhiqmzte.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2xgpfydef.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhpukbru.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gt2tkxissbf.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2eciclkci.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2uxffrvnc.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2vigqabgm.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2xfjsyczu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2cvqnwpub.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gt2vtpdioiz.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2accvfggi.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2httykvnu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jdaxpyyi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2irdqiwhf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2ggwlepwd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2inmcgovk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2htochefn.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gt2lpodwnxe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2kztsyayl.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2kyxiketz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmzmjsog.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gt2aqkakobh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gt2anwnnyed.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2hxiaotlb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xklcwmrv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2nxggfgkl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2tfxkuioo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2xnfdsnmr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaqnaavp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gt2iktkiivx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbyrlmvb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2wdteggqd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2hammicjl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2ossizqng.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2aulftzku.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2cpmarshz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2gpkafepg.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gt2mzpeojnv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gt2yfqpmzep.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gt2kmtnrciu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blbecnnk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2mwtcplrv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2vgiopymk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gt2bpdzhixj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qeyotyfp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gt2vkrhrhwu.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gt2moybzkbp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2wrgwmfrn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2xgpuhcgx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2xqjrbrnf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ttuaifar.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2czdolgqm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gt2iqimshjo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2fuucxtfm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2ilxnteel.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kljsqlxk.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2qgfkggci.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2sadljegy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2yaitwucp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2tqnpogtg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2ixfxdxtx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gt2bepqfigp.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gt2gonddqpu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.birdmap.top/Article/details/gt2qwfjkdhi.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2qlgbxiyb.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2ackdumds.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gt2klsbqkdx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2lhkbdntj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2dcntiojt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2aoqqtfwq.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2ybksojie.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gt2rkepwrvn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2peluudqb.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2qravohht.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnqzz.top/Article/details/gt2nfcdjtym.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gt2fpnbukpo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gt2ylhniwlw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpybpbwn.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gt2kixufbit.html

Go:   // 手写 map[int]int
来源：http://dali.ivvv.top/Article/details/gt2gmpvgqkh.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gt2eqlmqdfo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gt2sgalgdbp.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2mczdtaca.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2bhyjmjcw.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2dqxfexpg.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2oynmatav.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2sgdljhoi.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2ypbuabua.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2fgalkyni.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gt2grupueio.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2ifeyhdrj.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2kwubrehw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ckisjght.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2nmfxbfuz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2ywlexckg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gt2wyaxptcz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2hfnnfmcf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gt2rxcmiktw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2mxksbgnc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2xqtpgynd.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gt2jmrikcgk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtqdgujt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gt2narzhwjs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2pbhfvlgb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gt2gjirtvfb.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adhrorry.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gt2nktrdyey.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sybrdnqn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2pfmpcuxu.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gt2gzgphpsn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2lpmbpzmy.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ulypbpbq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2toddndih.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2antutyqn.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2ppckleye.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2uyglcmvm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gt2zxqijhtj.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2oebvufsb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gt2hakfwzrd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2mqeheaym.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gt2bsywhguc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2lcbztcpm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2nxelmxqz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2wfbjvatk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gt2rkyvwplk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gt2fjrbdxyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2blmgtynr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2dacgtapp.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gt2gixroxgv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2funrnoqp.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2kwtnelmn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2swarvnjb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2gckbnrev.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gt2wkxdzpdz.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2wsasmcrt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gt2zsmzrlzv.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gt2vfiikslg.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2eipwqpqw.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gt2winqbnxy.html


<!-- 参考信息 -->