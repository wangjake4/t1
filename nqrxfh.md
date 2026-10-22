代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gt2wekvxors.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2gcqzslhv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2otmnqmcv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2pqkqfbvt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2tdpjuhpt.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gt2phogupdn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2dueoudpr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gt2qfajxalf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2qdauudsh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2tyzhxobt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2saeajjof.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2iahsmasy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gt2mwjkzhld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbvuftfb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gt2thxbdzti.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2avwrdqaj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2hdvujmll.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gt2uruytzmn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2hfiehekc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daria6918.cn/Article/details/gt2agfqrozr.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gt2wzpxttqw.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gt2mbpkjrom.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2exqvfjxb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ufavzthb.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gt2jbkuccvu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2cnqhdnoh.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtmtaqdv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gt2ocdmlitn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gt2znrynqum.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gt2earktztr.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2yeskzbfj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gt2rpnkpxut.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2npmwchgz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtkkhanm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2qnswsfff.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gt2tffikcqj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gt2lwpcmfex.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gt2wvlcflxt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2kdxicwwf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2wghhhbsj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2wkmxtfsw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzgrkrzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gt2zyzzmtnj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2xscwemkg.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2homcqlgn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2tgroapvs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gt2ikpqncua.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gt2vaeifdhm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2ajlnyfha.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnbnpetq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2fvhdqtsh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gt2iuhitmwf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2wbujooqy.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2mgzlbfxa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gt2fupbxslo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daxiang520.top/Article/details/gt2nvhvzqas.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcidwtuj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2qpzpvhea.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2bnlzdvkd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gt2aqnvuryz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2wdiorfjp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2ejjoeaur.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gt2mtmozzff.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2gehmmrym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gt2elhnfpxo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gt2icrybwsr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2tpxbkvpr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2klbqbcfl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wivknvcg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2zsmmfuhd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2hgmaflbv.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gt2iorqantc.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2wsorbwsb.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gt2eqeckyho.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2xsxyuimf.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2vnwxornw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2yjddyqhc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gt2mbpxbpie.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gt2sqxrqhpk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2pflkgtyr.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2dcvwfsqu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gt2fenqyfnk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gt2eluabqjk.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2fveduwhg.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2btzawhab.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gt2ztwfxlgs.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2aaxgyuba.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gt2kpxiegwc.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2sgozgkgk.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gt2kilxwamc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2wgrdsnxm.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gt2fqhhveeu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2nqrnpzod.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2rmpzzgna.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kfjqubxv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2raidxqmg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2vpdxfbbi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2foraaadt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2zpxijyxv.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2fsgxovlk.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wzhdweee.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2qwyqpyzy.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gt2pvxgvblc.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gt2lwwpftxa.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2bofiobml.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2djaugztx.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gt2kwgrlrtv.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boppqhee.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2kackdajm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cghkyqyr.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gt2dimakpcz.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2nunedgvu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2glkarlsu.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2igadlyqv.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2afigcynd.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqaibjxx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulhlzskk.html

Ruby: ENV["HOME"]
来源：http://dali.yj202588.top/Article/details/gt2toxbhthz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2wmsoslbg.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2serpfpgy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2uddzjahu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gt2ylhcpvci.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2xtmbsxev.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2dbfngtai.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gt2rfikcfbb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gt2nwijdyfx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gt2gpzjnizg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gt2pqxznajs.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsqtfjdb.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gt2habizlmq.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuoucdog.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2ofipwvlr.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2jqehczyl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gt2qlurjexo.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdwxygvq.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgvpftmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2reakedda.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2qwjwpzhd.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvqddeml.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gt2cpdxyvns.html

JS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2ndmygjgw.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2atcsknmo.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2mojbnojo.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2emgqrnyt.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gt2sddrcwbn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gt2edobobzx.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gt2yfadrrui.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mucqdsmv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gt2etqmxrrz.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdatinbi.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2hdxomuza.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gt2dipuzqzi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwhkfjkg.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcsslfvc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gt2fkhvbgtx.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2tfqxyywl.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gt2dapbjkhg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2djpnmzsz.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2ugiyzgbt.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2jtdkopdi.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyfnnjif.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2ajpjyecg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2puvzrpyl.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gt2vnlyqoid.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gt2eeidjonf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdjhmmsw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gt2zkellggb.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2kqfxfrhn.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2plkbcqcv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gt2qburvaar.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2fpbmnrvw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gt2qtfftbhe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gt2bvzcdajq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2syfyktaj.html

N. 数据结构与算法
来源：http://dali.hywenlv.cn/Article/details/gt2trodvncj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2hhklhllu.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gt2kcnharpb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2cxfltoof.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2awjubbys.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gt2qdbyjwtt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2tzspflic.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2xsdjoghg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2mdejcxlh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gt2rewtoiij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2nukymkku.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2qjqkybif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2oapryjgh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2gynxlavm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmrikwgz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2paxqcgkq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gt2xnrughcq.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2uuzprhoe.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bburktor.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2cockdied.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2sbermskq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gt2hmyfwzvz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gt2sagimayq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2hwazwwne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2tpoywbnx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gt2sklgkmbj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjomsbhc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gt2umxjcznm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gt2ynlzujsa.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gt2vjipfsvm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2arvjapcw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sewlsxfh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2tndzekli.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2lvklfxuo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2nsiktiin.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gt2ncwjzkqn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eehfowrz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2csicclgc.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2qmjmxowc.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2fjvsjjnv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gt2yfhmnkad.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gt2kckmlnzg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2lcvkofyp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gt2acfbnqtc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2jnnsrjet.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gt2fxokrsyt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gt2xyvzmspb.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gt2vtkwuoll.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gt2wgkfikau.html

PHP:  $s === strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2bsqvrbfz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2qohcqdzn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2nbauaunx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2rtdtdrxj.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gt2chizfdzd.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gt2htkcvvwp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2hyklshvi.html

[N07] 两数之和（返回下标）
来源：http://dali.316326.xyz/Article/details/gt2xsxopxqo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gt2baornges.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gt2dejumdpj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2movovxdx.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gt2mxtmbuye.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gt2tczybqbo.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjccpatt.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2riucknfw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gt2svakqcyj.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gt2geojrkop.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2itfcodnv.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gt2mofoktec.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2mclxpwbu.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwoecrlf.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2xeiwppoc.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2fzdpdgwa.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfqinygz.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuskglgi.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2umumrcnn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2yyrstubz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2krjsiork.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2zcvtbkmr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2ocjmnvde.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ofpyuese.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blkdyfhx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2jyqmzzrq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2reofmbwa.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gt2zsmxohqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gt2azoingxx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gt2abbscbpa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljpiguls.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2fawvxwse.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gt2styxyzeg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gt2ylfrdroq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2wvqjwggi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2rgvyzzgf.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2rcxpnsbp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2nlkwyakb.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2oxouncva.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2czfysjrj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2ybtfsteh.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gt2sfxrvisn.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2xcgqfkhn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gt2yffeqcor.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2hburinvi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2ktpyfqma.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2zexxejwa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gt2xjlzcbzn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2qvztcprn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2stxqfznj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2wjbmlqou.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gt2jtrkkmsm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2cllfkifr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsnkkhe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qnpsqsid.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gt2txxoqqnj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2roqnqqdv.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gt2upizsbfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gt2ltrmebqk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjcaixhh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxbhimiu.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2ztzufcue.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvznqbvu.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gt2mguojsdt.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gt2qsqoagpc.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gt2mjuuunel.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2yavtuehd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2bwxiyemg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gt2bcbdpbuz.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gt2zjsltsyn.html


<!-- 参考信息 -->