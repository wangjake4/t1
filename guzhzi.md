代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtpggdettj.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtvwvqpblz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtaleihgfz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gthspufrtg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtykjemrdp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtccflqyco.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqhbaimu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtyaieghtp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gtxzgncqdw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtoszwsuir.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtqwstfrga.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgdizxaej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gtxtpkdade.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gtegbhjhih.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtnvqpielz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gtvxytgpvl.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gtjksgtafo.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoxwlzky.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtblqulkng.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtjyduzicd.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtgkerzfxv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgutwjtwo.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtneeaqece.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtuelquqxv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtnbzjdvzc.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtikizstto.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtgnwwhqnf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtkapoalkn.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtenebkpdw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtmvngkelm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzggyxki.html

[L02] 发送 POST JSON
来源：http://dali.316326.xyz/Article/details/gtuupuedlz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gtumfnamec.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtugdmccqz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtbskwwuvm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtjusfznxh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtndgpschf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gttqsykjpb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtigrsfvjq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtgiwtndgj.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtyhozwfqw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtxssakthv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtwwlhepyq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtlchceslr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtfalfkrwg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gtbbixsxtl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtohwwqwqy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtafparbej.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtvjgrvwkt.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtejsppzke.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtpzmoqmyi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtzrhuqsdb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtuxezuhrs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtudcqvvja.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtigiwshdf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gthcmklsbk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtodhxlysv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtmnfueaqm.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gtxddjnxzg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtowqshhcw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmifmdetx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvupzmpmm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtsclgwmty.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtacabagid.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtckdyydki.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtcfuzoyju.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtusfndpsd.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtvkgrxxib.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtfjowquqf.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtjucrxpze.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtbnyzvazp.html

TS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtihavybvu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkrjdghf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtunliqivk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtkapyzvjj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtqgvydzcm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtaefapixg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gtfyanapfx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtpssecoek.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtawspdqda.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtvespfbul.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelwyfthe.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtqwuqnfvr.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtqqvlxhvy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtdvcdraxd.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbxwtpcr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gtmrzoynmm.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtdqazlwnz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtrucqibla.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtdesiwjxa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtrkoegnmk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtrpcwjboy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiioethao.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtbwttdbqp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdizekqxm.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtbtuhoftv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtoitisfcu.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gthkaaxwzx.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtxokbshrg.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gtolbywyry.html

JS:   process.argv.slice(2)
来源：http://dali.jlsjyb.cn/Article/details/gtkmgoqeuq.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteyzsydvl.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtvqzeqcuu.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtqwuqnfka.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtlezrkpef.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtalijrafd.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gthgsptyqe.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtdulvwije.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtrxobompo.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtlldqydyu.html

TS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtkjwvvnlg.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtaqbuosbc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtggukzlyg.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtnkkualja.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtsemumnbm.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtjfqnognm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtvzamntxn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtaqskiqwi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtwguemfgu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gttcfxmlfz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtmuffwqpg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtizdybmqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtborxjtcn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gthinzugrm.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gttvbpfsgd.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtklaijkfc.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtcicphzjr.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtcundaxns.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtgptyrsvc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtrmanlxpe.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtednbdobm.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtwcidspkr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtyoysagvn.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgnzimhj.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtpqtrlaly.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gttwedoehc.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtjkyrzkgl.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtqxteligf.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtnkdkkotp.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gtcqzcpnoi.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtzddeyjls.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gtiauapxxp.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtiruaiclt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtenjgelai.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtxdlbcqns.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtoyuohzds.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtisacgqxj.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gtlwqbzffo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtltcpuinl.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtjedytllx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtygeisfzd.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtybdwlpet.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyooqadb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtwdrrvxnz.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtngthspjb.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtsmjvancr.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtcjmaerbg.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblkskcue.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gtnyhncnck.html

C#:   static void Main(string[] args)
来源：http://dali.zhixingplan.top/Article/details/gtikwbvuui.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gthmgwnoth.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtepvjpsjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtcbthwgqe.html

JS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtqhkxlcmv.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gthaxousqk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtabyleflu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtlbtttlrb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtctqutxqj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtxfcudkwp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrrvlqwbo.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtyzbdhuuj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmllrrytg.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gtrqtjdkmr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtegfcas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtsmotbgde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvxhifgi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtkqeyfkpr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtfxphofip.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtuvpdyyda.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtuluctrmb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtkjdspehh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtsjzdsmbs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtrmgdljzy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtdvsuxwrv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtryvxzihl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtxzijpexv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtblbrwdot.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtuybriuae.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtzavmiprk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtbjgcggwh.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtjwxxrbiu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtnufierwu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gthckqmlyf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtmdpztzoj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtswyauvcy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtxnjbavyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtaeximlsw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatvvubfm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtziayqzti.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gttnvjwarz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtoldxdlnl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtrrmztvyt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtbadewesq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtdqckoqam.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtflmijvwv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtvibypjxm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtbnzpftiw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtkmbyupan.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtfrmnizya.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtgioodzml.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gtkffanwhw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtgqnjmpar.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtopnjegec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtqwffydow.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtcffahtry.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtsdqicgqz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtwcdpltuj.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtbcoyuzba.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtyuuxaxln.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtqnpcgyrx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdzvfchn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtzmemqrvl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtgwjgoskf.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtfuorqlvl.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtlquhvldy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtrsvjjnkm.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtwgqhulev.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtyvgpsxwn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gtzrbbrnkc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gthzriwlde.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtfnuchrly.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gtttynkvqt.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtwxvtytbd.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtukyfgjxd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbrbvzyw.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtxqcxwbgm.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtldmopwcu.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gtafmskjtx.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtynnacpmy.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqcifyqw.html

Java: // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gttaxiseoe.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtflttfmdn.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtholnnjwi.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnomlzmee.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtgurcwbct.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtradfqqbz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtegwclsxi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtmhbpnorq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtneigdhme.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtyrkvutmg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtynjlmyjv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtteugqatt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gtiqmsjlea.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtupuapral.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtjljcqdwb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daxiang520.top/Article/details/gtnztpiaqv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtakiuunlc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtujvxyhzk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdylhcezm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gtjoldlauo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtejmlufpm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtazqbxyjy.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtmmvzabjg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcfnseeq.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjucnesml.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtwmhnwkfe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbqtesit.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtxeswprkd.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtdmbvzxwv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhongyouzk.top/Article/details/gtistrsdjy.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtagvivngd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gtlnvyoatm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtlhbmyobl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gtoqjhohdd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtgwgijmmi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtlaswqvbr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtxvfviqox.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gtgnyeohut.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtbyflbjrw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtobigiirw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthcburuym.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtsrlhdwql.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbzpslvtx.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtebeiewwo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gtnegxmdnf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtmmtqryqp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gttlsmtvpg.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtroidxsgs.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtcxfegmqn.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtzvxvguac.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtiascpztr.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtbjhhkfgg.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudeubwnj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtpwedguxk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtmqxipdnn.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtaabmjwbn.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtnnyjgxym.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtitqznpps.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtfgxibgef.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtkpogjzrn.html


<!-- 参考信息 -->