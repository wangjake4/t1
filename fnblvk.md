代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2lndbpiwy.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzynsaan.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2aheuicok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iutpzfet.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxsmlnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diclijga.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvvalxp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwyaqrc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2kikcredn.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvdnkyg.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnolscj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjvwpsw.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtvypqz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqvtjbn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiiqtmm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwnxsfm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjzxulm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyeaach.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pllhvoin.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoukigk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwtjpmu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvhsgod.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlaamav.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bizjbvnw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiqkqxl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiqnbda.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pknomsig.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbgmlxp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ockrjpos.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtehrlv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzdvuhm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfivfhzo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiycvgz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeapmyl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtahpdg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtmqjuq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qykzbfno.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjdocsr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdjeiui.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfamlrfz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vemgqxjj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2porbqujv.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeegenr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqqysyg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2knqbuhka.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2amrpxdlh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnuywdk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbcbwtx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgaduya.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2barcshsv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxarbpiq.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mchdkpsc.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdufzvt.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsndzpfb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgyqfli.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjbmlkw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2alukdtqj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2choatglp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzypfst.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmuapru.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqceflnw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2piamrezf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2spirebzv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tigijiuw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvfwtri.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kujgaalx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hpscvesq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2rodaprul.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdzmjoc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcctdiq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kgywppdn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkqqurn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2flemrzaw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmbmrmz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrmzpwz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvzeghn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudcknb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2olwovvda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjyjeqw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkhmxxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oulasqak.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqcyuci.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyuupim.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiydjzhn.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxfxgqv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaqzscx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvaijdx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbfghcn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2afiyidsc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jidxrdvf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afxaozsn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfppafqy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpghsmp.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2auzrkzsk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpyxomy.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqnthro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpynmknk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpelawl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnsdctk.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlxckhh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmsjcqr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdcmnqr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpadnoe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuopezvg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqnsjnc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrusmdnx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qatpujgd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2slexffrk.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ibobtbdu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmidzfy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvvxvtp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2affnyohg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqswihh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpjgpbt.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbspmted.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlcuncx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbxnfvc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2uteiyfoz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbxoxym.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfprjzp.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yggnjjxq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvamdgwb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrkpxnn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qckajlep.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bsebrkks.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkpaupg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmxliwc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2orlnzgfy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwkzcfq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaycbeqe.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfarlcd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlffahb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqkdfzb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvramhcp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2junbswox.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrymgvj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2iofazcxx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmafusv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuajauw.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmrfjpe.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaxmhdi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyrxksg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaoxytz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2axeflemn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ancwfjvv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxrfssn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xihjrdke.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbgmweb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhsdldx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjmtghc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2berqvbwi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jueoqwjo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmsjqou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwilxolj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfquwub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwhlbtq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dobylnqi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvmwzwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2otqhvkee.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjthizs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvwcpbn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvzadfw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myyxzpad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqpmaiu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2szatcqef.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2byccjztu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqkgwvb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsijdcu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evwtghuj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdxqlkl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkztxryk.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2flqdyphc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2znaggxpe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjauzbtt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvqhhc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdnaygp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdchyye.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2drnlqyjt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jillzlri.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnzcmoi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxecgdv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwrhoga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrcgjch.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpclvrct.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmemdefc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyqxinj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fifpoghl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhqkeyf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrggbwno.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrpbcib.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efrbkewy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvlcipa.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyitrszk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhwbhkn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgagcat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnhtdrq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdcwjjw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtdrilc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfolatzz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhqpifx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhiettz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnwwwjp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hivhlyhn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpsuzpg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xocgdagr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxdmzco.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ywymkvpm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkloedw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2djcbsvzv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nfveznfm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzuqwhg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmsuiab.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fcczzrnt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsebtlu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2geyukdqn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgiqfey.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rfszqeme.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2keazgmks.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hybicmdi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmffbqwk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijsxeep.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvvnzuy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcltsxt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2astotkwj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuiaxaz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hotlibrt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nomruvpm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bhipndoo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgkdxfi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuziyjhx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vurxxjoh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2byhalwwc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfppneh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fujqcgkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwxpzbc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrcgqcs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzqjawl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqfnisi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ficqzzxr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiasorud.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapfgtke.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkcsvdy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beozbpcb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppisslry.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxblcujo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlhtdgp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egbieanx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxzfahw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iahtjluj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfmzmdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcestja.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvurqri.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cobjckic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jootnfmg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mslpucgx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sohonliz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pflclkhy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvrssni.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zuixleyc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2glvgaesn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zlchmblb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enwudkmn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmciimu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgguzht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkddpbt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2aqacxlzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pynfeawd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhgknnp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxzlwxs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaaihey.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgqsvor.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eshgrjkv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2otboivam.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqogqrbe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvnrpoq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpovztab.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqxenlg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkiiqwx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxnriww.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ijymzuwl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmsgmub.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyeaixj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecohihfb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtadcr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgjzxne.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrjtkdb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhjsbqm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hmultkpf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwshktk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwjfxbi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mormwacg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugklrpdw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpdgwdh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuowpmk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2anchxtxp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvltgect.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqljavr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exkhwjmx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hizbcywz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2czpzrnkh.html


<!-- 参考信息 -->