代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mphlsjzv.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxrccna.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jczdknzp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2dytbeeit.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugetsumz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2znvzlyuz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezsdxei.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2viyitjpd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpsmxyq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdbunxu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2fquamtzc.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vobdkfyb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2feiqheiy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzoymbq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wffvywdd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhkzras.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2aypdbfwo.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfjwrlz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fvogurbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzealpre.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxdwaxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpzlbi.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsxcvnf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2kenhlnzm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsjpbwq.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbikqep.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2efdyvicv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlwnnhn.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwbasdq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeihkgdr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgivykhz.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lapjrzem.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzfqgta.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfcvhnh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvutrlmv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sihiefzh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzfnuk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2shuavcdw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ancctylm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2alqsarks.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjysjji.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2srekvyts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fglemofe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpsgiyf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2sbybaalq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2svzqeota.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoriigh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2kldmvdpd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcavaltx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vycwnnsl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnkdlpg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwcfvpq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlgodpm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fddgxqlu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cplefmwe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuhznxz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoammjzz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hevniiqc.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhnqakf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmjgluv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gutnkeah.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qewknbmt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hetcazgw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvxycrs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbtqlfe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeudnli.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2czqchddv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2esxcftpw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjggdjx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofydhcge.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2srdgtzyk.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mflbjckk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbfato.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvfgbqe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qefuwgew.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwothjc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpgzcce.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2brqtjfhl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfngqzz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwtbogl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfzkgwm.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2erhzcyit.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtkhywo.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxyptyf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jduczakk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgspdnz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2coexxtrd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwcwcnu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iudecwfm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhdkzca.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpuryqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ejedhnxx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptpyepu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2thxixvfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asurxddp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrfmxlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrokqab.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeudtbzp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2loqokmlw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyefdmvi.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooevhepp.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfnyepi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vewezzyn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uclrsamb.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2spzbhcsm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fstjghjl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzavkoqj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2czivhzyp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxopbwv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzvade.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xseavqkh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgvyycx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcdrfop.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnegequj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmogftb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qadhuzgv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2izegaqco.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbieze.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cccxysxs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whbepqts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpropql.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gewzojay.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrhwahf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2whxjsjte.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxvlmyx.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nknefiox.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqinhrte.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2owolwngm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwecjshw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqomrgzs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlknizzr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcojsmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yctsbhub.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrionpuk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsajmtqe.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyawiljw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2niunwhqa.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsawwcbi.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnniytz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2peayxtoy.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tjerilns.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrnrnct.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fbynxaqj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhjjquk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzafhqwf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbcyztf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnixicyk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrvzrqc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrlstdm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgywtfil.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2thzzcvzu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfovhxj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2szbsiixr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2swgazhsg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gharetmw.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgubcdn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrrzpjf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nquahtrp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcazcoz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2olyglfto.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2akkhedlj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlaqhbb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbjlxla.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lijizkqf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2furdirjw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywukugjd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zodklokb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qozftqbe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nlssicyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knvrqslj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xksqabob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvpgfke.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjozwqg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bufureui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlybobvf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxfzkuk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldhlypp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esoogknb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvmeogt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpbatjo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ituwuonh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhgexfa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhulqywp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwswiwo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyzvtzo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hokarhvc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdadbmaj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlmccpu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2czrkidnl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqwjevp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnanledx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wvktuwip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bgunkdpc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcumqxd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2smpkkmnx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzyxlvg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2spfgscqe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qhorybwi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gkheqhrs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmthkqvp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqncqxhg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mybgmzhx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxlhvzi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2etfnmuyf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzvaapu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcszebqc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frdkqleh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jckbfovb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ummsqqfp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azcwecot.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgesipsp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkigwsw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scsbjfzb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqytktm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksglfyio.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htyuwinh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdwlwpf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucndzfny.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uawirhvs.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xajmuftk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2whaaqbdc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2layvlaxx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrymkfl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2luakzjwf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fttpzsyl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tksjxauo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2raoyivzo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjvtrhr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmaofdz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbdjcky.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpbuikj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vaacrklw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpoggzk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2akkfzchp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxlbjjx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yireqpgc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzokykac.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgfngyo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fomotcop.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxswzwp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbtbfgj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmtyeki.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpqoloo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhwfqea.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utbqwhth.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrrfrjg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tedxxroz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiuujbw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2avbnirvm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqeoazp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmjucmq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twvgcrcc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuqjwgt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnkcxt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2omvlxcbl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycllwzgv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2putfkdiu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2unndqrqd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcrjhun.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntotqexu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdjpnfq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oufgfooi.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfazfxq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2edudtkop.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwehzeth.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzqjzeg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uokyueat.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbkqjul.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vsubigpq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zmszroqs.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hrglyemr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwugszd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2etdpjdcs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijhyhu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bldmfksg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlvojvn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzqajie.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2riclmhbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyszghia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oblvhyzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdtvgkp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qztxdgyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsdhqjs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpqmuvu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2itrvvsmy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wocnpktc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2elmdglfa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2woczggoa.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dodcovds.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpenryn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnbortt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcwfsdw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwgqncb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibormij.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xgflbxrj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gffwpzyf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2waivsxdn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvllrnv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsptlkf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmkbcay.html


<!-- 参考信息 -->