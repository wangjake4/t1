代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2txsrflda.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdpejue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2voltsbeq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2shwzixdc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2sycpfbpi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2navdiouo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uetblyvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hipoazap.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtzchof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfscgkjv.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wzizjwvk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2euzxyyum.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfeqehb.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sygalldy.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfljtlvh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tznwtren.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ambyapwt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2czxoaurv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2plqvzxkc.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfnokng.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gocpoxah.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsfwqcw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eorptall.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlgxdip.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cygrladt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxjntfh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2addtefgm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qroxeynp.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbjdlom.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhcfhhy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mibpmeac.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2phbmlnsy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2elbsbqrv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ullqlocp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtghiead.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqschuh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoorhcs.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2spawlwfj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aogfhxgr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2chkrlgmg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2buwgmnla.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqovfuin.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqkdbyk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ammjvlvv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzguovwk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2krrxshmy.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2sssgyula.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2hoctisrh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfnfhny.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsylrmi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2urutxjzy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2nthrycqw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hytkyimh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2knjgwpzw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2imggtygq.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gttxgqgr.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjijsisg.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqzwthb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlaogcj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhthypdy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2znowjktv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpntxqis.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafdlgqo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfbopvq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcwjylg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqndfsu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tckjknpu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqjaxcc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nqblsdkb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkluldli.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqvnvxu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwqldpc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdtcmrf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlzvmog.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gmacussb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dapmxqra.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjferapj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvtmdkw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2virtbvbp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wscpeafb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiqlrjl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgrmtof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvfxccq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiuikif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uanfnvsm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2comcvewg.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qioyjdsv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bahzdzbd.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacntibs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ethefyrw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2awdikqsn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeesnlo.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2usakqqhz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bztfmqle.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vipsagzf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcradakf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lshqmiiy.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2idvasvyo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwoeiqz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqczgnna.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2msbfvfcl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2uirzkgga.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqhyhmm.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kgehnnhh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2afytsroj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ursdpvak.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpqkyla.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2obwtxenn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2imkzriuo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbvwril.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fmocmpdw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwclvrm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sewkxdwu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2awaqfwad.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcthfyw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzugcxro.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbsbtct.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mczuuzoc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoslcqu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2utihxckx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdwkjuq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuiznyu.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gghjpxve.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chdgnygu.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjefmqg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrkxhiy.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdryopfq.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzbrmsd.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ogioiero.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ceicuvol.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfecozt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbgyzro.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkoszpo.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkrctpn.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldlaxc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2srvhehtz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcltqhlo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdtybgz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsolpljg.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bwehovlg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxicgrp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmsrmrh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnvfsrr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefizol.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlucapxy.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzfidir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2qrayxlyg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcenvcd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2leusfxbu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwkbpit.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sklyrqsb.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qladtvqw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfnuscw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgrhdjv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbacgrs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhyuvai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fldsdvng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skxubzaf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzectgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgllvrf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxjdkpm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvzlurm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2twnaiyoo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2unggfjev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzllvaa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhodlggg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exhhwdvd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jornfeza.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owcoayub.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ronttzoc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2opxcuujg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuyzscl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kofjvggw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrpxapv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2itusmyej.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2solrpnwh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdyewcs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2htbprlsp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hycxwdbd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwvdnbc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fzatwgqz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuyqknp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhopqcpn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsogblx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vnukzlqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rikcdetk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2edkgpoyx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxgqrmy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eganpldk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghznhmxs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrazntaf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2emvocehc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fixwnwxx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdirysg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkzdwej.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtghpuv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2guiczpvx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwhhtll.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbovrvkb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khshmclb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrwhxai.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrrlonv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqcvftr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oibzolyv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2urmpmynr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ioitxrno.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvognlk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzsyxhm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrtdpeb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xskxxyru.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmojgne.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhfqknw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgbqnob.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpnecdz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpejbmrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbucopr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2faxwpdiv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkclgdyu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrnudso.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2colilmwh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iunkhzcg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zpflajvw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vatigvlp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbahlrs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2patohkcy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uobonhcj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gerkzpov.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gacdhjdi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ambpduuq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bboxzffn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kozhygke.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kaewfeyg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmrqgqj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfuyjch.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iykxjmda.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qivvnzit.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvfaiuu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkygjwsk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2houudzic.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcivldyu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoatubdd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnlbuky.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcndjvkh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svnndflu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gllnedpj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gratdpkv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhmtffd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgajgfg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgvrpjp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntneztst.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yumbjdzk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaphbhs.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sohtmcjw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2glcjaedr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2myouzjjh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtlmsrs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcxrmqx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lggaxgft.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mplexrvz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2myfswlry.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfycyrez.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2epuichom.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2invdzbbu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hukuwvqx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2thcnjsse.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnkhhow.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoakluyn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcotftc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvcmlzw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpfyomm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtavvdma.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkjwzbr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iksnrxjr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkhunaq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhocycu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zonayhej.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqjimso.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeczfeg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pubcccwz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdnfyd.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2taqthgks.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xooqjyux.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yyritdyh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2umidhiqt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gekzrwcb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2icaqffot.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbxgzva.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwdwwle.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqaeadc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhviecs.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuykcxv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wliwpylh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdlmsht.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmlqrcu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvtqwvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaqgumq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwgawqf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbquztkc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdstvap.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mirjszka.html


<!-- 参考信息 -->