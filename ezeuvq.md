代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcywdjd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnesatd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsmscwq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnzocwu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqmxlho.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyjbnzj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2btyyxjdx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmekcxxg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzonfoa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2akrrbndj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fayigydz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gakbhyrz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaztvol.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dklzeudl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwccskn.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tebqtflz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zojxgyoa.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rakebcdm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlbhayi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrgrepk.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdoyhkj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqqcxiu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tanvaate.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edpgxncx.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetkfad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckofoyvk.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2antzccve.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkdkfgx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2errwwndr.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2odidncmg.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbmgpjv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbmvsvs.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cakyxqpq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtykgdvo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xujgxiwu.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxtsyge.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsocirv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2zeahztuv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2khuwcxnj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2smyytahx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2djfdmmpb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2geazswpe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2acwihgly.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2algabzzl.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2snnzmrnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqidzip.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjygaidy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvuunoo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wxundevm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxibngqs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkohiybo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxddakcg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyobqhkb.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2yqadvkav.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhfcodb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlgnmdr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxdlrrv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfvtiqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmruwzcv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsgcrhz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2khqoktfs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2osjpghtd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdeoddt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nudfxzit.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuwzxqd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2huvuyexo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejybcbsf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxojkts.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrnodqn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmxbljg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dudqdmvm.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ektsxysm.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2usdbxopv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2opuruxld.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2atryjkbn.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbwmdp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmngluy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tarshjie.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkdutcr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhprntxv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yklwkfgo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcubtvgj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gktbyvle.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wyefuxow.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcxicpp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2trsevbgd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vljnoecy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmqlyzb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hantwwqz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qssiokkr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnmucyx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2azvruvgr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wixiqbxf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aemqwqqx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmrbunp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyhparx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnqrvhx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2saxpdsdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlfqvrn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuakyph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syetvxxt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqzyais.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jragbofr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqexervw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdupsse.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pskorfdf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfomrtr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiuazum.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yplzebgs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsupjvoq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbiaejl.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2inlyzvfs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2trqaxfec.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2luwmpkmh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyhwznf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoplgow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfeivaa.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvfiymt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtwwnxg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ezimeasb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pteknctl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbibuunl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjmbbzy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtkbwoo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlehivm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruclojhp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2folndlaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tezzezlu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kvarwhps.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymocsopc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmnzlqp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cehcpzwk.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xifololt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjqbnjw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaywnqhw.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dzogcgsx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2stpojqdn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjpexr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aliergvk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2byineqfj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoglvxe.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffdtpat.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aagwnbou.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpahwjg.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eljhgvew.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ateeacvy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qadmqjon.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnrkdlj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfllyif.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolxjcs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oljwfsmu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2frggllwv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2flilgavx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxibcdq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjoekuj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2lttivloj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqubzux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bggtjnjt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2avzcpyjl.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vuizdizo.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoittvwe.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2whekicnp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jboyillp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwypnxw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzwfuzf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2eakzlbvl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvqcexm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2owqnxtzc.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gcshzxhh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lptqxcrl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuxsumh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrpunqg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kszycrmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asgweoan.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2awvbijnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sskzyigx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2axowaupv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2skeixzne.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gobxqjrs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsppnhuz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeqlwbo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnnenkm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2esshykax.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2euigymtu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvabyyb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvpedlg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2knxepvvy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziecbfsb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdklvdkv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfosbmbb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlhramq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akfzagdm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jinslrkz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdosycn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrretuk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrmvufw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2luggcvmk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2onwqquhd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qaryiwje.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2buefjlsb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnssjlz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcvhept.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2itxxgnsz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmgkfah.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgyeapo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2biyhyzhi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xinsghub.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbbipqw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cadafihm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2monjskdi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tybbmbpa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2chejwtui.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuuxuib.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bszjaqkz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoeipyj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fypbobkm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvdnik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvclzvi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaylxejl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufjhdbm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezaplmd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdxupll.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtutkob.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvepavcq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bebufuhf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxsmlup.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgtmmey.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkzrjqz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzwsrkt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmhenyr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuvqbzt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiygqfy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qprwgzyf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2exandnhs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qziyydzd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2whowwbbp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxcqqfg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cytfyjud.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksayegtc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbodiibv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeyvwfw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpznfith.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaxjdmk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llianhit.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2unvdilrn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcpeisy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2juwarhve.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgulnnh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwidztrc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjkytcx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kawpnuma.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ecolnxjs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ievbxmdo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wenhszwt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ooknkjzy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjicvzx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwshiwo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kazrxvwi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjavsut.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cudkdvzd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjopvjht.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2busenilx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnmvyvm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmmdxws.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2myrircme.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkfqurp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2woazyuyc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2necqfsev.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkqnkte.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqnfktq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwjlyou.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2exmrnoxr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuzyyuu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2frtfijvo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsdzrog.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2njmaxjbq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pphiulok.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxkokkc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2frpjlpua.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsklcht.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlhdnxu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvamlpz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sknhvtei.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2btiytlzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyiioec.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2euaqqixb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srextfxq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsxmpvw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2djzhgvtd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvugobs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2awrlsdpz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvimpkj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwovpbd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaindzy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmhlhq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkctojs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wsylhgtx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tesrgrvb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hldmngja.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uptldcjb.html


<!-- 参考信息 -->