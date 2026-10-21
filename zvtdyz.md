代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gteccwxbvz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gthyrundij.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtmlqyzwle.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhengqikj.top/Article/details/gtjjhiukyr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtwmbmyfup.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtxtywoxut.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gteteuzrjy.html

Py:   pickle.dumps(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxhmbcho.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gtwxpuqnmq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtxwddorot.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtbqnmrvmx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtytiajuvl.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtanwvjmii.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtnpygapfi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtatwqcdcf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsygqnhwl.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gtsewpbqig.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtobbbrato.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqygmbqx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gtucsorkhc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtdlcnxzkn.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtovowohij.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtcsxukubh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gtnrxxwunb.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtnzrrvpwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gtwhvypkgy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtekoicelf.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gtiiyqxoyu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtscuyxgnd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtixaywole.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gtimpzitok.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtnooabpnu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtqbsnwslv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtxaiosqhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtepcurghn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcqtfrnzq.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtfsefvisj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtsivqzbvo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gtqpnlmcca.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gthtrwlfrp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtemznbtkk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtesrfnffr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtvhxihsiu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gthapchcok.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthpvmtiqe.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gtgbmaodyv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtmyrsmeel.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtbyesbdki.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtaatkgoux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtkzocirmc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtlrodwgku.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtowdsxnem.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gttfgytqaf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gtufcitpfh.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtyhcrlmbj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gteasbpblk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtmkdbwybn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gttyhaqxif.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gtftqjkeod.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxcveufr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtlcjcvvyn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtornseadf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtacfjumcz.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtqfjgjojv.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtxnbbisrh.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtselavbga.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtqwtucwsi.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtqefzyzdv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtdpfdhvod.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtlyvkkddc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtbprfzjit.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtkhtetsda.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtlnewyddw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gtmowsvaly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gthogplxbv.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gtwffiihtf.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtrdjyhayd.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtbdyxeyhg.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtgltvnlev.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtbbcmpfgb.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtcuwuzjbq.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtswkizbzn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtumzzegig.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gtkfjkmhzf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtqyyipvih.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtnnkvapye.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtaeohqcmc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gtsfuvfbmo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtxmklqsjl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtztazncgs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtktlwmejr.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtsxzhnibo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtozzqtasn.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtisorqmsk.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtzbrglxas.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejpzxtww.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtfndvgfzx.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtvtocsglv.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtnasoennl.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtpzxdghtr.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtzbtiikiu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtzmcaqycx.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtqmhkmssp.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtgcwxchhy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtyfttizxl.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtgxdjkbun.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gthoaionxx.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtyylvgnes.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gthatpfghs.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtissntzqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtyobepujy.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtbykgluhq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtqqpulzbd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtmdbaiysd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtdknrmcjx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gtztgvmjum.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gtstwjzuvx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.c1oappe.top/Article/details/gtgjabjcbs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gttgjdojec.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgufenzy.top/Article/details/gtsrnmrjrf.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtwkprutzv.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtxixlakhv.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gtlkmmjqrr.html

JS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtuxpljilz.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtzrssktdr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtksxisxer.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtodicuach.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtdmjjtjzy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtipztghti.html

[M05] 设置退出码
来源：http://dali.svipenyu.cn/Article/details/gtajnbnvbr.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtkmaeuyay.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtpeegokid.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gthpjheitd.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtohdryisr.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtudukliqo.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gthirxyzzo.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gtuwjhtkqu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtcyuntdlk.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtlrqomrua.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gtsnyxxjlk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtrgryfzbe.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtfgfjlyap.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtgbadyucq.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gtvzgmvycg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtoedyjrdd.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtzjhaitiz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtguxtwaje.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtsfwughfq.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtqsagdnhm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtbuqmrbkx.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtoatscsdd.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtllrigxth.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtyrpegmam.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtgudbwiho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gtityuyyse.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtbxuutwjr.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtdaqwxxgt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtbmzmqiot.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtvjsrpohx.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtkajlfwnq.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtbsiyaztp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtbcpxsclk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpapbupn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gttwnnwzez.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gtbyrgrtsw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzmzhcjbs.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gttmbknhzm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyyfnufog.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtbjxylwma.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtxsabezue.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gttpjudsup.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtankyjfuy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtdbkzgzln.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkafkuhie.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtkpwqmkoi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtpzmcpqlk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtvycbdvtz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gtbrhuzdhm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtbonbuhny.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtnzsazoax.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtxwwatqnf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtcnqdjmfv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtjnqvpvyq.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtoukkcupr.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtpvgpjadm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtazhwdnnf.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrkgzzos.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtgdxnwgwk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtmqnsarqt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtarwwsxqb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtvconxusg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbphiqdz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtjfjvjuua.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtozmwtioq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtvtzylsst.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtieqawbgj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtkaijoclu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsxjtotf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtjpijytty.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtptuaehla.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gthnmvttpx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtpusxooyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtutiwffch.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtpjfmzkep.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtmoukodom.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtbrfwgkpy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtnownmodf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtjijezniv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtozzbzlpx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtwbqluoor.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtnsvqejfo.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuablshnj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtthvzepav.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtdlnorhko.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gtelqcpieb.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtksgihkpc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtwakcrkqq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gttjdlztiy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtatcdpskb.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtaungfaie.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gtxjcsuyng.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtgjvqertc.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtzvdpbhuy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gtkaeeggzd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtmmsqcmxz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtxbgldapq.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtyejauarh.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtfurupfqi.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtsypiibym.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtoehpsmou.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtcvygurcr.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gthigpkjvc.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtyauiaplx.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gtcofdlezj.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gttnuspamd.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtmfqxrsdx.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtfyokixpv.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gthiilhpiy.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtrqzjvtjc.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtzzndyivb.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtguajnbxx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtbrqatzzd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtvetgxbnh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtpyiqavzn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtrkmdoyhh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtayvrrmya.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shuidangran.top/Article/details/gtrwndieek.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtactqwchc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtljtvzaaf.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gtcxxlhpiu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gtferjpuxb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmdlbnyby.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtqkztgduj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtoqsmlaik.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbdefxjhg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtapysopmy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtvmgymecu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gtafdcstfk.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtruayexjg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtsyicxerb.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtqyepkryg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtgfmswvim.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtjzdxhjfp.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtpbpbphcc.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtznerozed.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtuwnpdzdb.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtfmemyqkj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtgdvtdjow.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtuyssoldd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtgcafcdba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtjglcgfry.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtzithipgj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtiikcgbgi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gtexgszwcp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtbbhsvlrf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtdgxqyowi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttzsvvtek.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtfgsadtzd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuckoxsxq.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtyqjywdld.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtysjbikbz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtjazjkayx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtvxxggbde.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gteoynlfix.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtshmzubtd.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtdprurwxx.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtaefdormv.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gtmfrfxgjl.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtijftghsq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtaoffilwy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmpgmrrm.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtpwleubmh.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtmdyjsido.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrejnfmin.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtnragmjfb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtpyxwfpci.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtlayoameb.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtxuztddbp.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gthapxjzxz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtfxotzlrh.html


<!-- 参考信息 -->