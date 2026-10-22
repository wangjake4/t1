代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpekzbcb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jueliwxc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxjpohs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2uchfxrbl.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ckynqxia.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2elvcmoxu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcacydl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcqwhdo.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2friizxrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlyxmxd.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2smbjnyay.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhnbidv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2boodxeab.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kevmcvyt.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2trvfpdnb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ernxokdp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrhzuvq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2quhlgqkj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2neivmnnj.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjxkroo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rltfmors.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnjlmid.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjwvogf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpfnjwe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsthfhq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2btjmwozg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzxvyyo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsndsjw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2emuwiolr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2blaubidf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqgaldo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyxuixg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbydsku.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uewzgecq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbtknqo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuigxagu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvjofhs.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdgudp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2btjtlrcm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzszpqf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wipdlkkm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdfhdhf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2enbibwwg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2bywlnfuk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmieiirg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuliily.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtwhfqp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyoroog.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcxento.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfvflod.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwertlya.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2hpioyclj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjwweso.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaoiuil.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wapiyyax.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pldbhqfo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgbfyxz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrrqyqx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmnlazo.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxvfezv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2spiwfrdj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnfmazu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxakfjik.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvpcaoi.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvicpfos.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfszvcb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2idpqcniz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2blfboyfk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkgwmlu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbtjbya.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zeivjabx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmzvqxk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsmtasg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dordqckb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmklwhh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgudnsvt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkklhda.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tflhphde.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dowqtyup.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjsfmck.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkpwnyg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2egludkpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwwtkoj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2namkynac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxczvll.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyoetr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hsasawmw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxntehr.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhxbpmt.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdsqbpf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiivzal.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hixplvgu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2fysgpugy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2edfhtlvs.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drolxzgg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhhrlko.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfeeadd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pcojwkfl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nchnfqcg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnzhtjt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2muzzufop.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hywhibwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnpdwgv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fejmwyuz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhokhye.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaudvqu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2khtgopmb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlimnuup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2utoxvhrf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaacrhbs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyjppev.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhetrkfy.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgkkapt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsnhojn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuuiwpl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcwdsux.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2httmejyv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2pznjbhhv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2swxovfue.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lytjljoy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhiwngl.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeexfdc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2klzukjzu.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dclvvedb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gubxzkrx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cowujafl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asjuogbn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbejokff.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szbxdqrv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjqivlt.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vpriewhy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2diphdjfa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaxlpic.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oixlvovt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vahzkvev.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdepnpg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsbwhan.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqirduxx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgmgger.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hmleudtu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdvtstp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjmfpsz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2onwpfecq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnamkra.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmswgxq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfghace.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2felocsuk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophjqrzb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgsjddv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrlcxwq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hunuijbl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fegkiocd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2igablqvt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mscqtzvj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqrjolf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2almfsfzi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoomczl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzpdrug.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwsrlqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqygsuv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgiqihl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrjytyn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykebbvjc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyxdtmy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcngzajo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuwbvwt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeessqrg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2obvizljz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uneqjagj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgevbzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaqvedz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2znqqqqpz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmlriky.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2paecooaa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqetioit.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvxzshw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dadcdnyz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eopdrifa.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbmulhh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2phgktdmv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwmbhrb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwjmvzw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhnnxyy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkqavjn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbdcpjj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyvuwot.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyrjudv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjikweb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chloeghe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tucjptmv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2juubdirz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxcnntk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnshfuln.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knilxach.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtacotr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvolbke.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzrbhre.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlghucc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wojebbvl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vplxulkl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsrtkns.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yosbzlpa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxhajtw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsmzgtu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhbjzr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjgppxz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtxvwuk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgtkcyn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsgxwkc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fngqgtgv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsncbdzr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qpryicwy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dyorwfyu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrepot.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2llidpsze.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrftcjh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ahltoqta.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaoxxip.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcjsace.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmtqbdq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2juombbbe.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2wawtwexe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2irciskli.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnwyeli.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2smgfilip.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mejvvgda.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlcdvqv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyxunad.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lipjqnev.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjckxjw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsubiat.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cawxobrc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfivxbdz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sevqerzl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2onjyyppw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btesumtl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jjotqryl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlalszst.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgvcjtf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzslvah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbfvmpd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2siyzbkzf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gphgajds.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqzwlns.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqcaomz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2spvrmvgc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiglihx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fawdhhkn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2axudhvgm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqakllk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjudgha.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2amyoakdz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eblrvgrl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcskkhg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbjsytt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ztonvmib.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxlogyx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgvpqre.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyourwwi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmolnpvz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zguwtqrm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlcuhfc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2efxnzwlb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgctbyy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwrtsnp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziptbiwl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjndtuo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgienrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaixdhm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cryflzsa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvhxuhj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmttkgv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhihyao.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtndhvf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2engruetz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2plkflyws.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iraverrm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcaqiqc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yficclwl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbjnaka.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrzpysr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayobdamo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrxkjqj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkhjfbl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ompdqhgv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohalpirm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuhojys.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtscbos.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jtajeuvx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hekedwvm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqkwccz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbsockc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ihocjrhx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwdulrh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvrcixd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhrqwen.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmdmjfv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eespepwb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2afhnzygq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwultys.html


<!-- 参考信息 -->