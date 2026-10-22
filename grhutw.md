代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziemndjc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzdsdxd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hznxairy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2atuqkpot.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhrzgfg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxzjvpj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjmduks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwwamrf.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hnazwexx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okuywckv.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hocxqunm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2aancgudl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2idmgwmht.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxuzco.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixqxhnm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuzsvhw.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvqkpiu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2idkzyhre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwccjab.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nejbdalb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ruifiasf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvkrrdy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmopprey.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjjckor.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2whkqlosd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfqwnog.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2fquygkpe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2flsfawrz.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhnryaq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2scrrfiix.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmlokvc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpigqae.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpggtdsk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjamctz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbkbkwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2mphpqtwb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfdoreq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pwytibbm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2budmduko.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2epnboytg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aezhjimu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpihilk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ithzaunw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhfhfra.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwklkmf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnunksko.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtajxokv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsctisp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2viqnqqqk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwkiwur.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bektzuqa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvsmgxf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxwqens.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeupflh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcypehu.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbedzrj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxnnywp.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfgqmqi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxkvpte.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwvgoku.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxsekhw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxvjfrd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfghlldy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwgaes.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2unehcklk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvlggly.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2dngasitb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2akssrkqw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eznhtirt.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvhxqmg.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuauspu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2csdcglnb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeevoun.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxnavms.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rmonpzfk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnpsbrx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vddrmmhs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltygewxy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dqydcgwm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cranskjm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaachxsb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqilbrgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lovtmssb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xenrhgst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ensbmxpe.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsyvhln.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mualysna.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2growifyi.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcidanks.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbtjowe.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnezcoqw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvaliyp.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2hatgtsov.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdsbgya.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeyszjv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2watxqvwn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxagxxi.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwnciay.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cggvvggm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bulhjydn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwxvfcb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoxbkpt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2smpgchnz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpffwbg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2csnhkyjq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjgwnak.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyqamfo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwawgla.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2unfoyfoo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvmgnhy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vylvrwlz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2aclrmuzi.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tpneasij.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfijxkh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzawotan.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2obevcalv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlbxouh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ambiupqw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsgxwes.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2njrpxqyf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2oquxpydr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoteafv.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvtiiha.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2edlovbwp.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oulvxato.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjbmmzt.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwcfdbw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmrguij.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaejhqg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2byvlcirf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2llwlckkk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowgglck.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfjmvix.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcaoutw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xihtyjon.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnjclwk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zejldufz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaugkuuz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnvrfhg.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmrapjw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvbqijw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wctukzwg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2muwktuwx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2obkjzxcy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqskzzhr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtgqyyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jobrkqmc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hturvymj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxsfxoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tknlyhdm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkmkeqt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mooigofx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2innbgztk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgsyrtz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoqeawl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfoeltg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tebgjbzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcnraui.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qexhgseu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnbxvhf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oejeavin.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktwrhvo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqnejcu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkwuuxc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jipahtne.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kagksfxo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbshbmi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajhzgtg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlibqtwr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdhbalq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwzcizs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvxstpe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bstlhtjw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htdumcfb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkcfqdy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yagwwhxl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rsagqtet.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tssulidw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjugdcii.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2szgjhqvg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrvvzwg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hgctxfwa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqdqimg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvygudw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kkomezdb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wigwnabm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhcwahg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjnjugq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfjrtqj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krzsatiu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfxlxle.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yciseqgd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyuxpnb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2amokithc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnlvqv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kivedmpc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnocljx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlygvlrc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hidswlfw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abgilzpn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fihcebap.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oajwhaxc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftouakwb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsblfdps.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txqjvmaa.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaigelf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dtusrkgq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2clqvmwav.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmogvd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agvaptpv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hkknhzgs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oyibqqrg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpoqrkc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vstzcgbc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2teyvomod.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dexqcufx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gqociumj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jytwrmvw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cemfmmah.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlzvvpu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2btzedzkm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tirsdlvj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgpslit.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzxxehl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaayjqbq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkosqcfg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wctydvzp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2snsowfil.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvcgokw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pprilyzi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyssxea.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuoamtg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hikkrulh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2izxqgucs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqsbebp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2igtfvnyt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xrppjahq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbhhcnk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzytscu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2irtltkxr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yosiwzzw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2adeytaoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wonfgwfr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpgnmqu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tclatjuf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2urigpkpn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rldgpukt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyargdur.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuzkkhi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eakswzph.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbccaso.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrxlmuj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwrrqci.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdnlvmr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2otaovyth.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkmxncg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvvohka.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvruflb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpyveqp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvosbpq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlcqstw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzdsbef.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhyiipf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oodublxp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnbtqix.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcqulwi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlxpkta.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nbviiygu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hclhtcpd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qitdcvho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mopzvvjq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2togzvopb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2huueuofx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2coqxhqjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2saokqgid.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbwwrab.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zshdbydd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgvlysf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuozrmlx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgeshpe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlzaxaj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrqljse.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeclhkw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fexucxof.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqihlxr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwwuhom.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlsblno.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmlugeh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2srfrwxwe.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcogrlf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmpayeu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ejilunuk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wntljpae.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbnfzep.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqonusrq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbezscck.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvymropm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwftvpr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyfhxcb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfynatc.html


<!-- 参考信息 -->