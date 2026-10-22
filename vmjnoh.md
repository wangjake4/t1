代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhqkaqa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pelbgohc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2wekthtdx.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsucjomk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnojrnrx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vckfvdmm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tpszimkn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxknebl.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoeagij.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2blgrhpnz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ayovysjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhgukvj.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwsnihy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzoaxsi.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcnufv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2spdkizfg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2knxetviz.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmczzsbn.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwzazzl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkvehbd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xewkeonk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2edkddbti.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2emrmogdm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkwowfl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxasgb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqvqrjn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yhupkqau.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dtomlpnx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzwaorj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2cinylwpu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnhucnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxpvrex.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiyotiq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmsfafp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lghvlppo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vexuyqpr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wblfxlie.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfslqkh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbderf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwreeko.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjtfkew.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2wnijmitx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2saznioxv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbodcix.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndjbkv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2urqxbxaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxxwfhz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcelhsql.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwphxtsn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kikjcoyn.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrngwjn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfpnufl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awadwsmp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvzncfs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2euwyvbtx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2nvghmudm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfyywny.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2swlqymkv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwucaiha.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgvtccn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnitqmjn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrolepu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksukvjnf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiexmvfr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqclzdw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldcevix.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2auzxfvbb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcfqhyk.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aouownzu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rikwnwmy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywdxima.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dyttxxrx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uokdlybi.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqzmikd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhibnso.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwxnrna.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yilsvbsf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcawjmo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2juiuwjdi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2sniggvhu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2byvkuuok.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aigsmqpn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnzgcxk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcpabfg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjevvig.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwzxxwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bafdbudy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcuvnui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qugronjb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpipiul.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgmopog.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2izzmzxpt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvuzmvz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswrjtgq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhkcxhr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkhpjid.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ebysrqji.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfnpfcp.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpqfiml.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hixaldeu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2equjeeys.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsvbour.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yktnonll.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpfkuqe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2igbonmxa.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrctssje.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxatsxi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2glcylsjm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrdsseo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgwsyeb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cstvupip.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbrvmfn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcnhqjd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruclgsfn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpgjsal.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2skngeijo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2snnnpfxv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkarzbov.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqliedp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aywoceyj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhjxnym.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcqoyvv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwzwwrd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyfjllp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmgifct.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuvzbug.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aryavgos.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtehtqm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyifebpv.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnpmmqb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejvhyij.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaqfsqz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhchbjj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2drxuigqd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aijqjurg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaozinw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2akixgswo.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwopqwyi.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbwwtie.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfxeszw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2azrvzdnm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrnxkpq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvueoypf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqnohto.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pelwvfqs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwntczv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ovukvwva.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2acyowdky.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aamshxwr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmbdtpx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2eahlezuf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvniiou.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzyjkib.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2omyldins.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2eoswvegc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfdfnsr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzjyfxy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzrdpsw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hftgvdwm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2tfagwucp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpvzswc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abbzxbwc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yxungmob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjuwsta.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqtsams.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysuqnye.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkqmtuq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuilvhcu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fesqczeh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuhdfpi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhvkbik.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuqnxlb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hipejyyj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovufmuqh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrbaiul.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssofufop.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smtyyzfp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcfpzsy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqcjytn.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfftkpm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgbxlkv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2antrpoqj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnurasy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gbokupet.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2nmccvdni.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfadfge.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kulzyyvv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cekkplex.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uiglafyy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkckjwq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2seiugwfc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pifqsmww.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskxhjoe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxbgjdt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiblamo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpieive.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvruiec.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2srgqpvfn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzgiyfp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbetncqs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkafxye.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkevufk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbabxufl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqawukt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epfcenvp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcnspts.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2byaoqifw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbozbbv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cojsnnrz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkhyzdy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnzlljh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gskyzquw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdkdtec.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2peucctzg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbwdrmd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aiikgtcs.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2smbrrgxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkpfomd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrqbxpy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqrqtiu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zskppexv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbdotgv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwvxxcs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxlzziu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlktwzm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zeowuoty.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2enzzxvhv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xposcyli.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifirhaie.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2warwxxpc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyftegt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hmngoxtx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fffnktgd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpxckve.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2merfuqpo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qnamovil.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmowuvcn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ododzwqu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvawlzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2flrlitcc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2msziobbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqseuac.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2swijyjpi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjfwfod.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyumcsz.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvxpmyn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsxvuvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whquhrmw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2essizvzw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywnaxid.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrsrbyg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfruevt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiolfxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dffkxanh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlubyfw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lolroidb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvdbqya.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxzyvqc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lieyyftn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqhdghw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfocrpkl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogvkkm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoigmmg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztptypbs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjixwy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eltyesek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nyccesur.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2taexsgjx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkdlihq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxqpwwr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcroivab.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvysjwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paahgojk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fgevagdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmtdrdx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sqadhpzk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyosxvyi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2caudujeb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdkwmvt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxbzqho.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2igqdwvfq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsspujdh.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkinxocx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxtarhi.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gccciyxw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzajodh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymdvox.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pgynenat.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mszwftnq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fubzlihx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgkkqic.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bvedmdqf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhhlfxp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbhvqfg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tiitjqfq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2laxpgaqx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2spepfvon.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvcxchz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyooxsny.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmfvhbr.html


<!-- 参考信息 -->