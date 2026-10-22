代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgdudwt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgpbpz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jmasfxmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpecitm.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bcedivrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrlmcsp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xktwsxem.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2aipwvleu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2otdvcemq.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrzgmnk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2apgdewuy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nnplwscz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyfozue.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2pslkrwra.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbaagnv.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwfbmic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2krfzeyuk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2wajjjblz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwnrwas.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdefnwl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwlujhf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfslyyt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2rirgdcrk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2seqxtjcy.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkcamlj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzdmmpj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqgrtod.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2farhpuhh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmvsjmz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2udygeiaw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2eihlpcte.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2sanelhoj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfufqzjw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvntubi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zndknfjz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjczdm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2grppvkyt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyboqvf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnfgdbw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqwvqme.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmshjgvb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkejrwor.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaixzjba.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2jjajgppt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nevvqofq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhxpoli.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdbpxwn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gyacdemk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeldtuam.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2olkvfkrm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2btrpqspc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bumjazwn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfplhkpo.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpzxlpb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyzpgqr.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2npxkgzno.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgpzgkz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadavxnc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnrbitd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfkipsa.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeakcxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzczuvfo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2stiqpuiu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvrfdok.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2afsyostn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkvzfpx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lirhvxrz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvisvqk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmjghrh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoqyjbf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2lerqykoc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2augjpebs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qukxtabo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpylhdf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2alkvqopw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiejeuu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewwxnjg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhueptcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcykgid.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzgdygk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awwqgpny.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bckwktyd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvsjeao.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbpejks.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxhoehm.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcumptx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2afqyepsg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtqxuag.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rulslcxq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2anvziyir.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gglrzyfr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhdaguw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmqbtxe.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyuozuj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2thvvmjpv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2crputajy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2htdraekf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2thinupfo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sppjhmnx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqifvmh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqrehcu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pynfqqmi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2crkktzmy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgtqzwm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkayqexm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzoifmj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rkctzbzj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxamlvbp.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxxymoa.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeyutwe.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxmpwsn.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2namfnrri.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuhpppl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfteopqn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iujnrkhc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kmolkxvj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2okwvvaoy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tocnkhvy.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnfrmtg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndtrgul.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbpxbrj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnlxocp.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkdzteh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fritvaan.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeaisuo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgivjqt.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2viezhnkp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbakhrzb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cofkjire.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tutkszex.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsrfsgb.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvfoyfg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyigwzo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhzpknt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiveqez.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfteqbs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fcprptnm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2smzjpqjo.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuepzaz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbdxjux.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkrlnqz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnchikkk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdojpsa.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwprswu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2atkgtuwm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpcgbjf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hoehyhdh.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvjoqpf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dxalywfj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2leapouic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzaylqa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dfixunne.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpynfpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsazxtzp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjdarlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uekkxmbv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqljama.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcihhmhy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkjloxj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdqkbue.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbmgqfz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpzpnag.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2twnnishf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2juxdvhsr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwwjfdq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfmzxlz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bigjblju.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2smrzxhfp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dstceesf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2efcsucel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvfeqaf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdawueui.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mppyakxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpertmb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsivsss.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2scsebfwy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxjfuxr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlhxrca.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gykqmcha.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2orzjocfg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2itixkjwn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dynvnsyi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oocvdbka.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2weaxbmqq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjjfqrh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzqlkcq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtnoczy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfupcuq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsqkikj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjeophd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sugtbpqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowrrxtt.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zidudfqf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bufiqsis.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyfknla.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnfpozl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcatsxt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbokdyni.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooftusox.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbqmkrh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rclnpeel.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eatpxpsc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2daqyzcee.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmhhtcg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcfysdz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrukant.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cwofnsax.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcliofd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hlghhxsd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wstvjozh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2exuaudoj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2saeilcgu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nggbmqwi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgjwhbk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyrctnp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuqyivx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tphiwzda.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cewvcmea.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ldymkbxb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgovsmpd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyhxlbn.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bowwvwdx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqfkfwv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2owhmgzlk.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fgntuwjn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tpejayyc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsrqqxu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrqclco.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvixzvug.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nelnsmec.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpajznky.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpxegrb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoceggj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pueybnif.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dzojhloe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjnnccq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2woqjmgln.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wymnwjbf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pudlupty.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pidjwous.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsffrsqd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuanfsrv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okttehdx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxaueuk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxamzyf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaelfbp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmdztmx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnhdjce.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nemfjlff.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2prjzuyym.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnfaaua.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfqpcrm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrmcdts.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhnsbxn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ahibhzcv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2faefwvfp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eklkndja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbluawd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpkfzly.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzdsick.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vghouuvy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvpuiej.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxfnngi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwczrzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfglnfcf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiglion.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxfvver.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsewofq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkyneyu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvxpwpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwdcnrp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dknolegz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgmktrp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bowdlfbd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhipyfkj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtjntct.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iblbodki.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qomzzgne.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wexxounk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pmopxjle.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2chrpwgtb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhspcmbz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2enaulozq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsekryy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kswwgguh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnbqzfa.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfjptpl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2smiximkk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzodxsb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbhitzy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnptzdu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2efljkbkc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmabzpx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afahqmsp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2beeanbaj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmiwkjm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aohhyuky.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xldbgkvg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzmotbu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mmysxvkv.html


<!-- 参考信息 -->