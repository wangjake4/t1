代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgryhmca.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsynlgr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jolvsstf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgajplx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgldxab.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtvbiqq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrwmcme.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2wixiarck.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzffwgfd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eprnhnol.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuzvmlh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdwnyds.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkcthnp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhwgxck.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiufken.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxjwanq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2klioazdx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2luaccelo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaoergd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2dkktuozw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2cchaijas.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwgczlr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2baxzlrhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxfgwbu.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gkayjjal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjgnqvm.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqjcwsu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2whlknjxw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2esbrrrew.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvwizxc.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2aphrswox.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fduddrjc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwymczj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2omcxzkmb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pequycuw.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wsydoppn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2xpduuzeo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2sycraqgd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfzgtmz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsttmjs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2amgpitgs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwnadwe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmbwdxk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xanenmfv.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2txmxnxli.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhqpmqg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2skyyjjdu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeqozft.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2odtpbbvc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2phzypgdl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nthlaauh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2coagieye.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuvyhmi.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbmuozh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmriiay.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqhfmay.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqoyjwq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvipbgyg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pomrwdpy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlyxbay.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfpbagm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2goqdimqq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxktkop.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2weuxyisy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtxnfto.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vtagpayp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkxbvob.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2obhqktvj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szgvdjbv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvtoruw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etimwdzw.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwbcfnv.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2joljuwdc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbmecpg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kulnfcal.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkrkxah.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2blmxivya.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkmeajo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwvzksk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbstmyo.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqzzdpj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxuqptk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2occvzdlk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaoobud.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwloyfg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkapodk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvmezuv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2hfomerlt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxbtwhg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdelesu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzgfocd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qroprvfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rucuwpch.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbtvgrp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpqzlbz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrirgfh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzvxbwg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iknconkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfhowbo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yosvblta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcapdpnh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjnvwgr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqahseop.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2oguglaet.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhebrrjs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omjgfpdf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubailwtt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2spckysnm.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2kuberhvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgzlvjf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjzjxig.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbuximx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lstixpnf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2haxyeucb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jytvyqes.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qarrwcam.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2avidqela.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvgltnv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdchost.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yuksxhqj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmbcjlz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhrszwu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uypewzpb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzrxvkx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxnkkvc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2oymcukxh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnuzyym.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtuthdr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwffoxc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgxhsry.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfhbflg.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbraujh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmteftkz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgacaswj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2znggcyma.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzgafvh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xukcvnni.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvuaqcp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xapcxaku.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2miciomzn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slsftpmg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnxidnv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbbpiib.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaexwnkj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjvsuqx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvmqzcg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmkfepb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fervgone.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsksqph.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yptrwzfk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2urflboae.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjcawv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiraceo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmttwph.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpoyxkc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdtomij.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtheeng.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bcepasnb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dglkispy.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wfleirlh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjalvxo.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvisrifl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bebnawxl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrftbpiw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xciacmme.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2odcxhzln.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjbvgzp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2imnvwiue.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jijvedcj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxixsqpr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2aypqnrat.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgjvnag.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuwbqyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmpnatn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvqfira.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niykzoce.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmufjtly.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpukpuau.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxwphur.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oatgepnf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2egrqoukn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2twksrovs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzjxcmy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszkdzfj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrakamp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hipbcoke.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqgibev.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbkkany.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctajkgpx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knwizrgc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfisnvu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tutzcbyq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkwpiyo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfdymlg.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykglwhvz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tughbkll.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyzzyho.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjrfeus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsaapcy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzpmqgp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjmbdwz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgqndsf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hnewbemc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zriyxome.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njaddyue.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvavjmr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2occqktyd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqxodfx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehknevgt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcokdjxl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfzgncn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bulmzplc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxghnki.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlkftbh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heyrldwl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yskwjjxo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njnqhjkx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aziijjyz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxznbamo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdklcnj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqssztv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aeihsrmd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxztfpo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2phgblxdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvmylip.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvmjbv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ztavywbq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtwqfru.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqrzqju.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgolax.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2emtsbcka.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cvokrgph.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmkbnss.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhgarrq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2omlaybyy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2yazonxbr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fkudsutt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmafcjx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnsjqhf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jczerohz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwuotct.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmoxfjq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvodkscn.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsghosj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2stsqmuta.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcwpfsk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ricwvuja.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkmkqca.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvgjidk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnzexpy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2flqedqwk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lutisott.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oemimgnx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2caaekpcf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uuonexwe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjqxbxb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvaryjd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bnunheiq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjvxate.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikhqjne.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2csehvcoo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocepjlqi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eriqdphr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrjnnju.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxpqzrj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfkifan.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2azsjwgfh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbuxyxn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mueqwile.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvxpwwj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyuaacd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nyozvksn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfgspa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqafrnc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2orjidolw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbajzodg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fradmfzx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtcjyiu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxocymm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wydaoebf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zoylfgfr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2afuwkxpn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sflewsli.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyuphej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcudaum.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdbpyfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwidtdfh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wksztgsk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qllvstwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdjtwdg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2knbbisle.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzkawvm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxagtd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqttzfw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqptgarm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2epegodin.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzumnlk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fldcvzqw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzbjmwd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcwtazf.html


<!-- 参考信息 -->