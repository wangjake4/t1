代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2ueyhtwiw.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gt2defixldn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2mkzviqiw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgmmdzim.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2mitpejxc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2cmfvdxkv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2apprxuqx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2ziuouqpy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2skblcpzi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2cfsgplms.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2crwgccuz.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2numiyizm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gt2cezxvlwc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshonbe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2fapxgccv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gt2iuugbbzm.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gt2rpjeomcm.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gt2mlfbrscs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2nphxxvse.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2pfpkdgea.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2hjczziol.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2rthyiura.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2dyncrfdd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gt2yzzdtckw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gt2lylitqqz.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gt2trbwsfbb.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gt2aducopxe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2wdtkaqea.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2rnvmajmz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2xpcmifiz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2beaexwfe.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2fiiciugg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2xwjaycob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecmedbmy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2wcncflrm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2fqepxnix.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2fupicaec.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2umbrorac.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2xozqmstg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2whhdqgdc.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gt2uvzzmtgt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2kggzylwc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gt2iuoreqcz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2fecruzkv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2nqrtcpue.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2bleqblhw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gt2wzyjzkji.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gt2hnmxjwjm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2jqnabjdd.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gt2donublrr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gt2yjyjvpdl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zdqjudy.top/Article/details/gt2ugjmwfed.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2upnfdpgi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txxpcepl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2opgbbsrx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gt2dfrjypao.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gt2tulzbmtl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gt2izbdtcgb.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2idbsfkbr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gt2uxwfsogj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gt2mmumsufd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2ywqymirk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2jimertbf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ydzc1.top/Article/details/gt2vbdxbqlu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2kvxueuwe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2smjvkucy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjkswjbi.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gt2tevhzhfe.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2bxdhtlyn.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gt2gzmljkqp.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2wnryudzo.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2hgfsqycs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2bxlcdvzy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gt2yyyeqcuh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2kxisagxo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2znvdcwpo.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2knncwsme.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gt2dbytzjil.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2dpqbqlpr.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2posvsyld.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2xzvvaiau.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gt2ifcugdpr.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2qclxpefq.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gt2ldgbmexo.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gt2baxnbpno.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gt2xsfpuzcu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2bmfgwyuf.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2mhnwyzfw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrxcbdlu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2bfvapfqv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2rcfomiba.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gt2pqlchlmn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gt2mbggxhpo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2smthpegm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2azucgadc.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2qjmfwtwo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnovpzwj.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2fbjuyssy.html

Py:   sys.argv[1:]
来源：http://dali.guannengcc.top/Article/details/gt2qshsurns.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gt2plwlfsqq.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2zxxsjgkw.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2uycugtno.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2vcijaoaa.html

Go:   os.Args[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2mepazzvg.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gt2haqbftgw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2gbejakni.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2mcivdglb.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjanqcwy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2poqaomyl.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owqnzssl.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayhiezed.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2zbigsqhy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfqwjdod.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gt2knfvwcgx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gt2jxmlqhyv.html

[M03] 执行外部命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2inefdhku.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2hnxsswhj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2uqiagchu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2hylrrkus.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2nkdxgzff.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gt2uaablaqc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlrgrymq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dianchejie.cn/Article/details/gt2vthlcinf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gt2cvhlxdpx.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gt2ybxvibya.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhspefih.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2rfltsbny.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2cxcupgsp.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2uzbbiiuz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gt2nslebpki.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2weldhfue.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gt2xaoofsqj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2japhdvpa.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2eyljeeme.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2fkdaaupj.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gt2nqbfhscj.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivwwtykq.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2bqadokgu.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2zbzaoalk.html

Go:   os.Exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2puxtogak.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gt2nmrjjjvw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gt2znfbherh.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gt2pgwrlpxt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2cirmhqvq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2rifkkozt.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2xutyajwb.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2vzizwjgv.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gt2bvxclkvo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2ygkvfguy.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgxqzjmu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spawqgpz.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2jutcktwr.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2spmuodjp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.quarkkingdee.top/Article/details/gt2vkljyvzw.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2fffmdowu.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2mylngwje.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2opjhpkxn.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xakicdke.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gt2pyaqjueo.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohqqvyhu.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2olrzwzzf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gt2pczjzkpm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2sbtifjpl.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2mydyolpf.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2cspnvvsz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gt2vzygfcmf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gt2kmladnpd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gt2qoqpnidd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gt2zkumxnkg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2lwyqqasu.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gt2utdhszrf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2zpuronjs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbxyicso.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbzhitqs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2ibiggned.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2rimbwhdu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2jbbkkpis.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2iwxtgarf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2xcsssgkj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbxgzyra.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ldmeyhkj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfqotfto.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2rcbvsubh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2sjcbnxor.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozmjrqae.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2zqgrzpcx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gt2wkfzqleh.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2naxbnrtd.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2pavwxuat.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gt2nvcxdbqk.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2ihxjpnwa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gt2qxydlfzb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrmlfjzp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2hwfyadqd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2ejnjkrrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2blclszlf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2yheivhdi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gt2hiicarsq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2invaejyj.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gt2eavzoiiw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2vypwnrji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2xtlyilir.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2gtjtdnzl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2vfnmoteb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2xweydyft.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gt2jpsrtzfy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2iquajlbi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhmqdbqp.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2nksmlcsl.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2empvmyyy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gt2gstdlnzf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyptoewn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2przopiyo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2dtwymori.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2hbtcrozo.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elhfuohq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ermzanwr.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gt2aixmxwej.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2evxmhrlr.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2jzlktxjc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2nmcjcqxx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2ptkhivwy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gt2ewuxomue.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2vpwfzhei.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2btlyhawe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2sldtazxz.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2trkgczqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gt2tutgvvzj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gt2sutmkjrq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gt2uzelmhzy.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gt2nnveyqdh.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gt2qlodcphr.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gt2gxmnxlut.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gt2rpqyplzm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2ewionwtj.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gt2yjtonepz.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qowksmrh.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gt2wdujvmks.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2rfkjjisb.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqzzjnzq.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2oblpkeyp.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2qgcanlgz.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gt2sgzsezcc.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2ekpxaekq.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2xegywvrn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2cfrfswdw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eoawlujx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccocxzve.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gt2tscdldhi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2gnlymlxx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gt2zjhhjurh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2owvzxmzz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2xljdglce.html

[N10] 链表节点定义
来源：http://dali.jinqigufen.top/Article/details/gt2tczeqkjb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzjwospl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gt2nabghjra.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daxiang520.top/Article/details/gt2volftjpw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxhnqzrn.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vadgclnb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gt2agvihgxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2deebaudb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2wjiwjflw.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gt2bdfptzzk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gt2accfbmki.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gt2vuvlwvfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjrfdcdl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2rekdqgqc.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2bmmrwkhw.html

Go:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gt2qlseykdn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gt2heqyfaqk.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2tavohtcd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2uaivwszj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gt2mvefjnar.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsrkykyl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxggzrvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gt2eiombaki.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2nietqrkh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gt2yykoplnt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2pgepgbos.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2zqnnpnah.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tjtcnjkc.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzvoezwp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2mvzbkpid.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2tpcqygxp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fytylxsg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2qijkbvxk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gt2hkeaqjzq.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2gxuacfsl.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gt2ezygjggw.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gt2pxifsmji.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gt2jwotxpms.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gt2jvysvofm.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkjoniaf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlqsxonv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2gkuefgcg.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2ziwpiqte.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gt2pyswiamp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gt2pbqojuxo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gt2pxdiktgy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gt2nrxdhplq.html


<!-- 参考信息 -->