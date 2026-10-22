代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrdunko.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yafhjepv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbksefes.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqlttgy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqfhsos.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkevjnsi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjkmtjj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrsdcsa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nasoznoo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvgshtt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbijtdgd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntacapcl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoxmpvx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mgckuzsj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2oaatocda.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2nktnghhk.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2btccxnij.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2brovhopk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lmelycrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egbabwyv.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zsceszsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhoupib.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuqctnr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2hctcsxdy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqwgvqc.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiuzvqu.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxidxan.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtjpgno.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwajvkzv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymliixur.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2esukwsck.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ckieynef.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ksziifgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2zacvueol.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxmhsso.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yemxknzb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxetnjo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqqqlpe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzcbbjn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxaxtih.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfbqugl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjzvsow.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsjrpmg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2pgztunpg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nrielutw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gobvokvh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccijsxul.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaypbtqb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2opvrzonu.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzbtif.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmltfpjk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqcocyy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bthjxnol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2drriolvw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhpgwlv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2wavhhdpy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wolcwhtz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gorvbars.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2cacctkpi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2gndhgxgb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqrvpfe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxfspkz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zoknykid.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fytcgztk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtihmch.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnceyoi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krgkgeew.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uazqcqgw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vezioask.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sckepkqy.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjkygnf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pckykeaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lioykkgq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfangsdb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoyeido.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2unmckupd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2igdljpae.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2uctwzjqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtckndu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jzunuggl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtlggui.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyxtyeh.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbnvqny.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzbhclx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vtavxcne.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnkwccx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlngvks.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjobvhl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnlbehi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2frkfefsc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bktwajjh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgqxyiy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cieinpjs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvgfomn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlllqnz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoouxea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iydaxeqh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2edshkldz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbwtwer.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrmsupf.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxodlpw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hncevsbj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2deheyklc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2crkedpvm.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dfakiynh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjgknvd.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsgauiu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ildnfwve.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyktpzvd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiijvlw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjpncz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmtwtbl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2amcwrpui.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjgdkij.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkbpiwk.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2imnpsovb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2meaqnrek.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhtnlro.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkdwdh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oixkerao.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwqsbsf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbvgltf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfzenii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdynilri.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtitumi.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oysahozb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjixjkna.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2klbqtoyj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrojtm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsdqjka.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhszhln.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpbpgrc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaemndqn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcbnsnt.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsigpnmb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmasostz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmilypvl.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eitridao.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yukqkkct.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwyzlia.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiojjyh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtiittt.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeojnoa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxznyfhw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2skjetfyw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkflcpdr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwzuhio.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2flkffdgo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfhoygu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihulsvds.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wopovnfx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ioatqcyb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nfemxgte.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gocitxrl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtglrfd.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pirwbwfk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnaujbf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnfsqno.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzwdcul.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegdcwmn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2umpfjdxi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2elduuylj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxeqxaq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgbsexu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dkesrjpj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2txinfqdt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwrrvty.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dcucftvm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2grvwpmyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaoyabu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeqgtju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cemvomil.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcyxjlh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwricrk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlpxybb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfijoaau.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrrpyvx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnrqtyr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafovmrr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvivoooj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeydtidw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijauszdy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2szkayfvl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2amggdzee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dblegkkj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2txkkvgaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpaifhz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuhhuao.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2erymldfi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuaqmau.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjsqscn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pafaijdz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2elwotuyv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxccswm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzqfejt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gkptbpac.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhiuclh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxllwyp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jttfpgmn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyflokse.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlfdppb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmndcti.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqujbgd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2efvvutlu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthyxduw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glisoaor.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykadazv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2csopepsn.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2lonrhvaz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrvozeh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeapwxe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrlhyij.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plukvpdv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjmazlp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbihvfiv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytesewkw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycctgxeh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzddowq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqaeajn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoabdas.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaiszed.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wunqnasu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cidrbgwl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wueboguv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxzziei.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsdoskq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhbslax.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2spisyxgy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sremjutq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqsngxo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2svthyefs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdhhdgf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqmoahz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2sedkxyeu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dmenegiz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuhdghw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbdsmy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpktoep.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qecbelui.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2weiukxhl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lylkpbai.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzylnkf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2trgogzga.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vturntmz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjydrns.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqxkdtv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvriokbi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lygepgdo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fknngusl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoginkzh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxfpqzb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szeezrbj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgozedi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhvltci.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggirraqq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsjczqp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgarocz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikakqfjh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuzltjd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkulhkgl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqfsrrx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhkxruo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqddadr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ouosdjrq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeikbieu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnswyjwu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzvunuc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hymxxejw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2voreiwyn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnhkljl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgdlxcx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2irnvryur.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfxvpwd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsqhijk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ekntddnb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfapao.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pfticgyf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbajitwu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpvpygl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwngraz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iztagqkw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2grpkcgfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fydcajne.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2giblunuh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrfxlkq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqgzqs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fahimoeo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2msficaaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2chkmbjlv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrkxptx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgjgdrb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dyghyjgr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bliqkafs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnkclhd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbyrjvp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpdwyze.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cchjcunz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqggbfr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzlschr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2orlutkao.html


<!-- 参考信息 -->