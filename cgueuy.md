代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2txgdjxrd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wouabjto.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmjmhnl.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdwhwyb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rntzmbsp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcvaahq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmpzfai.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2chjhdzyw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsanekw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvndxxu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmrblbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmyzeva.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2taaxyxde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjqnsnl.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2myfmjxxo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxlziun.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2eablpltu.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeavnop.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wozcbeoh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2raklvxzs.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvasila.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwflcdv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2imichqxx.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vackphxx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdvtctm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2revivhbe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtaxcnh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kewzqvda.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqxpnxz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2rozekdpy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2bukjxgpn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2akzrcbpc.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcivvnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2bamwkbic.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtdbbql.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2eforwbvi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjbpcaa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtewojb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lreoixvd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbshire.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqzhyky.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbyxyxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkjykcs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbopbyo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyasntg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nckoynrw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxjoslw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyfrjss.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oablksyk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuawujz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmufnqw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2fduonwdq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcumiiu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2llgscqaj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2quzrbbvf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzgusvc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdjskan.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2eontugjy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knrhgtqb.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjdjgoa.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2trlfdyyr.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbseqfye.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2brikbact.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2goyeiznc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqltfqt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wifbeklm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2pueidmza.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2isyssrla.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrqqutg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsxkitw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gftbollz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vibnptke.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsqqbeb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2twksjtyz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbejzcb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbylseg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wadhpxtl.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsmchxz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyadlhs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2nflznwqz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmhaunf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwlzutr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xeivtcbq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2iuksesdo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtuvboa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuixnxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvorugfc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mitrpmfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vggggdjq.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2znvfqlbv.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpmvgnk.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2znjdnkpa.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhjwfdc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2myignjxy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjymruex.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2imltyhsf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gtejryrq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwnolrl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exxwcmre.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2epwxkwiz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2glgtqlwc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqsudrz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsnhhdu.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xljmpzbi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jngtajhc.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2igwqwlqc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfjruqr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiwjiok.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eecjfvug.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtkjjoq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2akiuciko.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aonxpjfv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtekkomg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2glwnmlfg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2evjhqurp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2btdyconb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlsetkk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyemhrzy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2feblozqw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lijvdbpp.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhpcflf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbcimds.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcmgqps.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpvlwlv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmchnisg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsuqkzf.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafwdnhg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oamwuvgc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqzmdci.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkokxqh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtdeagl.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulehyeuj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcphmth.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2deeredel.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vgahdlee.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrizgqdr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vguuyqiu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2todyylqa.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyyucon.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiwplbs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyadvyuu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxdgkbb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2llsgqini.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaspdbz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rendnyip.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcgxztj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2avozizuv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2weqqxytp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2swlazlzb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhwbcar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2puyvunyw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aarfokvo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rkywdmmi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyiujpm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xiufyhbg.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsajmpm.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcgaxex.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2djbczemq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2urmiwmyv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwckhuk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfyponu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvapslxa.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2tkonjrpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrwfyyx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2brjwogqy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqmhfgr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywilpdfr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2drjghrzw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iglbpdkz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwgawua.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsfomvh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2avleuxcd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qipgdtxw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnurbsx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvohawxm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uljhrlxm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zexqtgdh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipvayiu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2whrbrlfz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amaxlhlv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emqmobum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioczdrar.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsqlcjs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqlfbns.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpgvrfi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtlfmbl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vptfvxqf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2grtgoddq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqvgbwb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgbudfi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyvcbqt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qusxkpbm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulscqoyq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emyhxqvi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2coxpgtrh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2krbmqfhg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrofjfgn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqjosvu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfyyktn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2feichuty.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbzaegq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrbswmt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxlnhef.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbejvxe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blggunaq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2luvslqvi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xucsobpb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkatuvmm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dghiehkg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mohxebft.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjopsmew.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2omxgpikr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2enttpicd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhpbgdl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2owasqpju.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtycbvf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvftnfx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyyrtzs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2naahlysb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfgdoae.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2obqltkep.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfacgxb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2urbyledy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxphifb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvggnyt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyxkppj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvtjqvl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ticnbynw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzyvrk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nprhsjdy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcxofwc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bmemtsrb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtfdoju.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdcbeuc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2crmrrpkx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkkzkbe.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmfghrt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qemaeytd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpzgdsj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeayuok.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqlfmha.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeodhlz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2skywrubl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzspyqp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2warmpkpv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2shelljez.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdwcys.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvkbfei.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbopszcj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvrwsd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgvtseg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuukyzh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnmesde.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fusksdmh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrvonae.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2svsayeti.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcsmgjw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jayhexgg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ooksdnfj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqymsixq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwkkscf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2moddiixz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfqkefx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2htxpsrer.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfcirff.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhduruo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnhfkea.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2izxbqcmm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cmozsugn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2igyqupcq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkctbhm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynvsvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyprblme.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oboplxio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwurpaf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhrqjdc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvnueeq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadzgcx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyfcgbp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2onjznoqe.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2usahfqik.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2znxvpuoh.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebncehbt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwdqggc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdmacyk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqijaqrl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwnkkhs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aomzebvr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdcqain.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvahpcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2oujpomas.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wstgfvvh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rzivagur.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pajavjhe.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xglbfygr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbkkgjq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vnatbdjf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2waxzvmgy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbxezhf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iytacglb.html


<!-- 参考信息 -->