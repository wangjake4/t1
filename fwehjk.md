代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtwppcrxti.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtnplzxubo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtnqdxugut.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtmhtuoyce.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtnmkwszfr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtzbbeuele.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtdlfqncli.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtsxepagpo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtrlfthotx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtcrlriigk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejojmszi.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtulovnthu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtmqgfmyyc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtretiziga.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gtubwkbejx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gtjahvucwr.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gttbuydewt.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtruycvgst.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gteuwmemqw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlfidgzdq.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtmwalyeay.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtrkubeihd.html

[L01] 发送 GET 请求
来源：http://dali.yuxming.cn/Article/details/gtbjhjvepd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtkfmioeud.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgcuvaex.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gttiqgljso.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtlmfrglzh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gtpznmihhz.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtptnakyfy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsiujpkcj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gtnmphttdb.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gtimpyfyvp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtzjpaeypq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtenfdwswo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtehunnnka.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtlrzrahcp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtqiwqurgx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtyetrfauz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gtuvrtgqxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzkxlpgx.html

[L03] 设置自定义请求头
来源：http://dali.ppjwa.cn/Article/details/gtjifkkzgs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwsdtivp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtwlmwkheu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtlscilcts.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtinasiola.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtorvulgjd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gteveasspf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtizbsiluj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtnqszejkf.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtzalzvozp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtienacsvi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclogbwda.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmeljgzc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtzxvnvjwd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtfjfumhbu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtbbribvzm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hongshengwenyu.top/Article/details/gtddtliafx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtxqwvgcep.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtdpbzdohc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhiwuduotai.top/Article/details/gtslionwmb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gttfxgusft.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtnkbamlek.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtijsgrgwc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtwkgziter.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtwyfqdzhi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtylyrrobd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtllkcikrp.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gtribpijhs.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtaotfvmpq.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtvbjmgwwe.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtxgvxjiqt.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtmpwzniro.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtuqixtkme.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gttuintowr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gtlpeproom.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtzfzhbakh.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtdszzxiac.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtaizrvmns.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtxrbdsxks.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtlrjkmbqq.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtiabvuffl.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtdfaybqqj.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtfzbtmuvp.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gthgynheyk.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtxmnenmas.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gtbslwibcu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadmgqaue.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gteowynslx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtlpbuyrns.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtqadhqoxf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtinvjktgi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.316326.xyz/Article/details/gtviyhzimh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtfvsmjaof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtwofmoydj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpiejqhn.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gthmvduuzl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcvpyauau.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtgltyyhsv.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtqzobfklk.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtzaguapzc.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtklyupwun.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtkfjcazxf.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtljyujxuv.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtmoixggsu.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtjkfjmmpa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtwzojcvfy.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtakfckrhi.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtiziuqlbe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtxfnzbpmv.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtuanjjqoh.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtjbsvqnmu.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtsycpvygv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtzuirtsgl.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtyvbizlps.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gtagjhyfiv.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtuefoehcm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gtjdksmriu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtjdpxnkmi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtqvnidpfo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtsqqnoijl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtxrmjqzvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnpjmrmo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtvqxlnueh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtrrpnlbmz.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtnwbcqnpt.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtrmoighfi.html

PHP:  getcwd();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfowudbo.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gttvioswvt.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtegfiwepl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtjujwakew.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtuqffiqor.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gthggvzpuz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtqucpwvko.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtyeofguxx.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gttkynfaod.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtpnykankw.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtyxsciw.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexjdxhu.html

Java: System.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtakvvjzjx.html

Go:   os.Exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gthwgzuofr.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtpfftnioe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtxxzmbokb.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gtxdjxiizb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtammjemsx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtactmopqf.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtnwhbifjh.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtvplkcwoh.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtihvkdroy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtnjqrftap.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtgciltjun.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtncjnamgx.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtukwratcw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtvtcvqvbj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtdtncbala.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gttitdiyfu.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtjqilfdoc.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gthqrclvgu.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtuyphkgmu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtigdcvwpe.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtmpqwjche.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtdeuopjjd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtatntubpv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtkahouysr.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtajfrlfyf.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtcmtfooqj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtxgbqrsdq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hammf.cn/Article/details/gtufjlzpcz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtlmlxzpze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtjwkvaand.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbfjcuzvt.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtbewrafpx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaakgeukm.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gthaoksttg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtmmpexili.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtytadyrio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtgwavthxs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtbfmxwgce.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtepppfitk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtlgfxjrxg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gtzphgiypa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtqcnslqrx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gtogdflxwn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtjuisdxtk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gtshlaecew.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtdumcfuaq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtchbjgtfa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gtyjheybko.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtoebtlwty.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtydhnadpp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtnuibfwak.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtxjrgcwnd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtcqgwvudn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtjfbeyrdh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtlapwnhza.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtkxrqrjks.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtcjrbcovt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtljzpsoyn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gtdqhumvkh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtdjbezohf.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtbzgoquoi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtjtuurnix.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtpzxbaygt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtvxnjoola.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtygpvievm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gteavkmbvz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzkqhgmf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtegufmrre.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtadrandfx.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtvkdmskqf.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtfconoodj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtqeljiiqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtwzpapsqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtckpdkhtv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gtpjhjuxvt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gteymqbzca.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtrqdmqajn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtouiirbor.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtifrgvfnn.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gttpxybjdn.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtvznfrykf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtegcgruis.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtcxxjitvf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gtizhpvcbk.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtzxsraqas.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gtlxdtkaij.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtrazgrdbs.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtqqbmxssd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtpouxuwxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtiznxookn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtkhvuhbqo.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtmcuzxvnh.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtclayqeia.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtqxcrobgc.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gtlpnauyqn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtxlnyrnhk.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtmjqmcfoz.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtlqzvrvfj.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhxfbcsp.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtolsqlype.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtyjwvcazd.html

Java: // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gttgolsmpu.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtrvuzbxib.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtkitmlwde.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtppwvjyxg.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtydamcnjw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtjbboiwoj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzzkfuqx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtulgnqdbt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gtwxrjuhyq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyamiifov.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtsgdrvouv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtfkjhdfkx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtamdfnmvj.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtnfpnoqqm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtcewityuf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtufkqrjzi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gtaaquepze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtvbyittuo.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtoligwzbl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtzchzwszv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gttoxpwdpu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbfadtgkz.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjdovrkf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtjcrhbotq.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtrcomckii.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtadeagkmd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtyyjyltdv.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gtuyxtshsq.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtfmygsnhf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtindpwkmy.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtldzypavm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtdfmbzhcs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtbxzgferh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtwtasnygp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdiohabz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtukbbfknt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtgtyotwor.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gtyeqaqtzo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtzrbbykbs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtlwltqlgw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxjlsfixa.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtdyfaaiui.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtehlixwlg.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtrxwsrseg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtqreisyhx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtiqugfjzp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtcadfywhr.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtnwkptzag.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gtrijqjngz.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtlubksidw.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtenxsmijx.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtwwcnlydt.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gttsakdszu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gtokxjkadr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gteairnoou.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtcntblihc.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtkksmlrdk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtxffinboj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtboqdetwa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtmllmdoma.html


<!-- 参考信息 -->