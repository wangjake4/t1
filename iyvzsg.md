代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvftgmmb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2agspakod.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkplpslx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfffwtso.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2elzykdgk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoyrpgj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfhxmkz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsujzysu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdswldyd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfwfbvo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2trfrqlxh.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhmsqbi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkvrloc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2urghcvnm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnoszew.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2lelxwlqm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2szfmjtkw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxfxfsv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyhsmyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vciijfzl.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2netfznmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeblukzh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rpihwlxn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgngvjd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdzwqrt.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsgphjb.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlrzwuc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvabnnmc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcyjiar.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2akvnkvuj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwmytee.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsfmcse.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzwbsen.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiujxfs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yayxthth.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbryitvx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukycmomu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2sorunvnv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwehdflf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeyhglw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbkwkos.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxzcjri.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2txqneqdx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2iniukyui.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2makbqgjf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gefupjll.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrdkoox.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsespxdv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwncnxoy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnjrudr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jolgncbp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jilvmaqd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmbhdsz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bwylhwti.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfukpfhv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2avmzsvxw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfznbnui.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsawrib.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlxuwcc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bbskighn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqrfquf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvovzhm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbmmsez.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfyqejn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcjswgy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2djumzerw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2akezonrl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2awrxociy.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ionfaqxj.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkapwrm.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdnkwwq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sanlrtoz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkzefbw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbjzmqm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiuxzad.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqcvjwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdakmcj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkeenrv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vduqfpgq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sfavngvn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vpytmctx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqvoclx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhkuyss.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2aikchzvx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2itondirq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pgldissm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfduypd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoccqns.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpjkexy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrtciyq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2sqahfbjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsdhjpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxykbnw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxdpcn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnafcqri.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2geywbzuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhagvcpe.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqywanmy.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpepakab.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhwqfcc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grceahta.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsubwjjy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmgwwdo.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfhoowu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkxerce.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qftkuflu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfymtloo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqvmgwx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqjkdfh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2thacogwo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxhitof.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oinpfucq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjybllu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhsqdhq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eielecft.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2emvfytzy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ablkgxjl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzuhvgv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2okuakpic.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbrzuuw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vunxsbft.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgimrdpq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdvowsw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhugluja.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnubukj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lamzcnxw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2badwhqyh.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2smgwjzcq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcnypuw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzidmlj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnxtowj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2afzmnnpj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdnckz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2otwcksdm.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzffwn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuxxebw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wytedwrz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhajelc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffpftmf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjowpfk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xmculmat.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjsghpb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaxxwco.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mghzuajw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2maajxofu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmwnnup.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jolbzqge.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2afkrcltp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwhdhaj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgoofko.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2opmddpht.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2esageyqs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmkniqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ckukyoie.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yemmkpir.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kusuqspt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kplnzihb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbepvur.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nonbatxw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqnambb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjjvcup.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2njedyalg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjmihn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gllwhugz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pinhmfau.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuztslq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiulfdf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2waeywvoa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmwsxqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhamwuh.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2edrfbafm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxecxtm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqsatzj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyrzunb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2piyctcnu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrydqqa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfbsvhq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clsctidb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eslngpds.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrulvdg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2timlfuzq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvoetjw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2divafcym.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lniwlbnb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxdgild.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclqaaqe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpecxwi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2entaaajv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzgpjts.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuygrmn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2itcfdhza.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiprpoo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jonwrwoj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfonkai.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbajsjrc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gnewrhen.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyovqvl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqunqvnd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2thtbkiip.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2duxcewgv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxygpmz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iluqhvyo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzyruja.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmmbyo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtqejnd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyxkkjz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdywvcw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvudffs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwywgpkz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpqfkya.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfupani.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctawokef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhojvkr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xretqgmr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgztscr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflvtnfw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtgiodk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utkykhmi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcgoxqu.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2deqqmjwi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgwgkxr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2olqqneet.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pqffodcu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cagpceou.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2phwiutyd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkkdwmg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrijwot.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdzfmx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zulesiqa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclynns.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gfblhzsk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2saebkatg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzscqhnf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnnoqry.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfwjpuh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tngnuaux.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evxhrhod.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzsykfe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jircxxpl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzovmexz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tqebjcws.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2csayurfw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnsrhoy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tdggdkrj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2alhbcsda.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvzmyrb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxhapgy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmlczfx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzdaixa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2owccguki.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2daarohhf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqibjav.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2midcilml.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ibifuelg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qozneiav.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcxqkts.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbehlcal.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfngvwpq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmphsnff.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyvvsux.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvwjyia.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vboxfgva.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kskwwzda.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fnswbbzq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmfxosm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lplkkoeo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2efunabak.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jubwehlr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2daeqiedu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwpjitv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pgregmoq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxfenbm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfixqh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfvdplh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dppznzve.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iykguepd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bbranybf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuyffqi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2olllfdkb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tydrejdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmeigvd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwxdvax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usbbddlt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcphsrt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eietnkci.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xeucboan.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qauadzde.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hvanbmli.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aobbphbg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbdbicz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyukjqve.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijapup.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2khaywxtf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsqaxjs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2toqmqqzp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mkibgaif.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtoiafu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilbtxuf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2unktrhkw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ussnvooy.html


<!-- 参考信息 -->