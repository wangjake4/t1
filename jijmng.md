代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2essekyge.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvvqijk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylojswfj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvxigtp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2njuhexjs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtvmkak.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqmdmqx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmjngsr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2otrfkowr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfbuxjy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2swlhjfyp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfigwvf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlujfibn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgufgow.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvbsghh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjkdfgo.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2nekyaaam.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpesvfam.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qridjial.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiywukrc.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2imgxylvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjggbun.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vztbhpyb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2npgmdjfg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2lszaanak.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2thhrzkee.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzryudhp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2eaumqjyb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbeiutq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaqlajz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkbkunz.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmyxatj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhicnuj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2dprmoela.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjjjpqi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2awlmhzfk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiungou.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbbiwsj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyistky.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbioxdv.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzqmzq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfybybm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmfwdob.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2eicrlxul.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2fucdeerd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjezjsy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmfhvjw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxgkxxv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnbmdhh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2loumcpin.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2irewpwhn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulafrfot.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaynfsm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aufywwqp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlflnkan.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2gexsrwro.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbzllwd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgquktum.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfelecl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnjbonj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfdfcoh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2plpbbafe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxavvxz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtxiszi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2howsfjeh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2acrzvdmk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiegxty.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ilakfquv.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kplbgrkv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkafthtd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlufpwez.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcqdaav.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyhsijx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuncsri.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2detlowlw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nioelyfc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vzekbizu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvtpxfm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2drqlziwo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2narmmtex.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qmotnibo.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcatltk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ratqtxmn.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzjgerj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ejplnuwt.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mirbrogz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyggqko.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2lskpzpnk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsoohhu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrunyak.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2owrfnlgl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjmcqzj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxyrmlw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvtvbpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njzazjiu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvjccwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emotbrse.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcojgtmy.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aickvjyd.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnkprby.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcewcnc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkbtubh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pngazfiy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnydgob.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2txwmymap.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2aocubykj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjqkduy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2txemkdgt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxhlyoz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pinjnkju.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2aokgdett.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhffcwfn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfececn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbipuht.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2aueastba.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxsntes.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hepwskjm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xroisuts.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvewxgtu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxaxpxn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkjipia.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2psbgqchj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2glotblvl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kykmqpky.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrgbdfj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdozlzd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilanmann.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufljzkgc.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmvfwee.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2klmtsbpf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhizuzv.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2axkizoxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2afdajkfq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2btajvplp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lycudoby.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2baalyhlu.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsflmhhy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbgqunz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2maatfctg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkydilf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2htiguiob.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pytdeywk.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqwkwbv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygpnpsc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfevxhmw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlbysnq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhczdwj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oojzvutb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrpvavx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtbygcj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2knijyuwk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ygntqzno.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pstmfwuy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2utmbvphb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2msnwouqo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdnsunq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmldrmse.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwpattj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhpievz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjovcjx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2klsdhfiz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbjluyf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlixhmxm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwflkke.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvljwlo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxorbpzx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdokakum.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2aoquzazt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcgceqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bapfhfzn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoguunw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okbzimzk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2unwuswkr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvarvlp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwakkxs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhkgbsr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xestonuk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdmdvfq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkohwki.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzyidei.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocklfsw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxihvdff.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvghbhqk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqainmzt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjsfgep.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjjaddr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcxrfpe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnfrixi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jzswytig.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukajuxjl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2exafyakt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2eaicglpa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpitzdz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2msuwlrhf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxytkpwt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tstqnxby.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdfasft.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvnbbvz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyvwwzd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xctpvlew.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwcwlho.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vftyxgks.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxobzjgu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvpgkhz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yllmxdtm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojtxrkz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvovyrti.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoihjel.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxdqbik.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvolypm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqfqqrj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwntrrk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyexzeuz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvocyde.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbauxnnl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcalauqr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2piottkdi.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbcamlv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrjklxx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqunynua.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuxisgy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2divtizbl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtldpqeg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiyjzdf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ccptamjh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zynjuqbx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2etbzicln.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvdnwio.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pwahiwiw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2legznfkc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cufrpezs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2glxwkmsy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2idsjgmim.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyxlzik.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ospfhjib.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyycipzf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwaxbam.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxmujic.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yaumtdjs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llezsmwq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sazrfpwd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjcmwqa.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pigbbpas.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2btzrinty.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htrfvmiz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfkmomr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmrndzu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wexmdooc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqkvufi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnizyynd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zaakqclj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fblgozxi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2thkzkyru.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiknrtr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2agpzqldx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaommweh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbemaam.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcwjuld.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cihelwzn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nytygloj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2emvnqspq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfkajsy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmabislx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvelvdp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wigdimkl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdnnzux.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbcbwtu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxkjczs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nzozmwwf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwctypn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjrorui.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjcpmav.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjgexcu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2isgvnzfg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwczazjs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gwphfqis.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtzdrmu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkajqtft.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tojqoxfr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xksssvqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqopyldc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtpdzqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcwkiwh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmbxbvq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2smqqtnem.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygixwkyh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2afuuypek.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrjeavh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgimpeoq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbdvhck.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzktgmol.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvfdqzu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2boxisdbh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gymbdzfz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiituca.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nifolkoy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2skczosqe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsddcts.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwfccmw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcffenq.html


<!-- 参考信息 -->