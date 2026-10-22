代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgxohdy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxtjitm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzmwlwd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2adrmkplw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2lfijosuu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxrauwu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgyppzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuntoyg.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2razflcgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnudwxsr.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhhgue.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxvcxex.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzijqjh.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwqzabp.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2enwtxboc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mapxtbiv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjtoaew.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbwsohv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaujond.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2monvskma.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfbcjp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2rehsnbkz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ioebxjcj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oitrywfc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrjyvy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnrcalj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzhawro.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2akngcuia.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2leqavbbr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tysptjnm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzfrpdt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmcivfs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqcufhn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2onfktbvy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhcbbud.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqrhzys.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdqhlkg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjzrovu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kihbozyq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2egqbbrtd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvfzqno.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iwikezom.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjbhsbs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2sspvfzya.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsssyssf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uytauimm.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgevpkqc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2xthepewl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhgmkei.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtclmca.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hblvupsy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpyqugy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gebvufmd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2spzxwgeq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbzztpl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhirndk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjclztbd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gufopcez.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmmlnts.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiqsbnw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2auvrjgbw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrluaix.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxytzehj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2akpjgwne.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfxggum.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfcsmly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2foidrmbv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxcykcx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kkworixy.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfcjkgy.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hktpckbb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrfcfpf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnegfnq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bfayqqyr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2usvaxzon.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmvzoyb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfkvtnw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2argegqnj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ywluyprl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrtettm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjmbqpz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygufejdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlaiqpn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcojtnuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmudklv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhzuysp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpofcwr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2sefewlxg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubomrks.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqceizdr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxpbonv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqomhuoa.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2tfneavlt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eygtecgx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhoeuml.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhghkcyj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcrfvnb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpfvkwm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnqjyyx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbnghos.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iipbhtvy.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyczjig.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsbioqw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2amiwtnqp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2joaehrlc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2morxexze.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2frdtcbhq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnxwcsf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgrnrwk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2uasywaoo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hptskebl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2szwzhzit.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsvodnm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsyhufh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpmmfse.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2puvqvmts.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjzapsy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtamllzw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjycbfs.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2msfbtpjo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wegjcmsm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2izxtyvqm.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gitejhnp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hehlljxv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzysnxam.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnzrslj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dunjtkhu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmajipp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgedjgx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrspbwe.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ksweedtz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbomzmi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpktypv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2otiivnma.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqzrzrs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxaigvc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwivqgv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqapeaig.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxdjfkg.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2iocffvzz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfcpao.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjqjgrz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sggamoak.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jolhclrl.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cimcakcs.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzseuhad.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2modytzmt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2keyczdih.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nslfalsd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qctoxjwi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcouwyz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uenhzyvi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxifzbwy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqqlzcv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpusmplj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vsblbnwl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tshkqekn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfddbivq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtsxqip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lakzlfbq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2flgishyq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwwmfot.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvbolac.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmqhhmk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2quejqibm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeazgvs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncflagq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jckyobod.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2czdwqzbr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkayzva.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdzgnpk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cynyrysa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhlvucj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djxhzoeg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgkzgsn.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeyehhe.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bjslsfgi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vukvcteb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcdskek.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeddvpo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2oomvkawo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvlkmhk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2drljfwey.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xmadfrmo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eurjwcdh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2oojwbrkb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgbigzy.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2kciitowt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzotota.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zagmtzyj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tigutspt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjpzzay.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2borpnwqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glksxxln.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2huksctnw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqilgjea.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmjikjy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hremicfj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbwjtpd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exjgnskg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgoyvbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2svljnoro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzvpqgf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltktepco.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzmxyjx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kapetuzk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2krqymwxz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufknkyft.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fikkijkt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqinvzde.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qoitjrem.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nuinmcvi.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sckuqips.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gdljjgel.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljincfik.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsnrdng.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqmruvc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2goulujtm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwlzotg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvumrca.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdjankz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dcedehqj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbgtdun.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeknfjz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwddpcg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxinbzqb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvchizrh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2utkrzxus.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jsidtjxc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nndafywt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaltyvn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtrlxjd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfzofls.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpioftno.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfumhplj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnzgang.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjrhjhz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtatrxzy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xlywjaaw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvevhzq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qceannqr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgfkozp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyeslew.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrafhnl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjotjnnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhttkpmj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgwjrkf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqahqlp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuodqyck.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwwpgvr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnuhrxx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2juchfsit.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2undvegnd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjizjfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2edcjxlas.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bqijnnxg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cvstrbmd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwbhxqv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eojbdzoe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdoqxfl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmacwrp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcjvyen.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bghnwkln.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfdstbq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsohxvj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvxgtxk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2biurndxa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxrpmzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sslodypj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2icycexnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqhwxwa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvhnetp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujppfktz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2papgkrwf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqilyxy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvbnnho.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzarklqr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2haidcksd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vermbpgf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2clwcrefn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcrftvq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitmosof.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgdxdp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mwafjfso.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpgeudc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yimrxoxu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcqeljd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2euwghfri.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgynmhi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmdzxcm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yghlmyox.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxnlahs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bxydemxm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uwldyrxc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccztytkk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xagezcal.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjytpqe.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yioizxui.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgsgxrc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2omyzhhqb.html


<!-- 参考信息 -->