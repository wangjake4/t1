代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imtaedgw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nayuhroy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rremeene.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2kksavsjj.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jfibrucf.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwzqpwm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yphimisi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gompfkvd.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqeqkjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpniawh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbblgpu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2zccmymhp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiecvst.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcltzpgb.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2isxectxi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcpgprv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2otezuxpd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ituitoyr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2twcciymz.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nyswyoac.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eblexpxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsrqsfr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2leeznqgs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2obmwxetj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2licjdtpq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrffmce.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvscjfb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqltvig.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2efebhevq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2rsigolxa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2txjbysbg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wznkohzf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2onvtmidy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2psvlptmp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwitmox.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxqocth.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqiocmy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnzmonw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuffrrf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfpijwp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rsexvwuo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2euykxxob.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2csaavpzh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotyhuz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxobugu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jupmanfl.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2eomlprcy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vlorjkpt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzkoggx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ayahrxvp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjcfmyi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfnvfnl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duwljtzs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmkxnil.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzufyrmp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbdczme.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgubbeev.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgnxkmd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kntievct.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nldgbyxd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cofpbrlt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeecezg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2naxkxynp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vajvzfdl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vczlwwpd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2whbxwltm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwluxxny.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocmipg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqgphea.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsujvct.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2byaqmseh.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgzrkrx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jqigvthk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2clzgmmya.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeqqved.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynadkcil.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjwqdhr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnmfbcb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdzcwqq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ttylwaza.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wffvonkv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrypuln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivttjrxk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wrteurpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjbgzqk.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pojcquun.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyfwvip.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjngkbq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxrrcfn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwiwhqr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhawhzc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlgnfgf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2parxcvbn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qotrhmor.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hblnocmh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2apbwwrsv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lipluorw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2becmdtfo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwsufva.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2roqzfdty.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdejirf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2nddencwh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2equwresg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbrubvg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2skeqfobu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrsemkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxirbyxh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvssjfaj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqfpgmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihabcrrv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2blhsijnz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qypxqeev.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiuqerb.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbbntlf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbptozqq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzfvybf.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnzxgky.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwyblhd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoksblp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvqcvwn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmbogzw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgzkbvt.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmgnfba.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihkhsbd.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emnmhbwr.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbheeuhg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmknhnz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgglicmh.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gyupxcgx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqceljf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyrjdfe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclzcvty.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fosvgbfk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcygjmt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mefkylel.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kentqjob.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2popdxnhy.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhyfmho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgkezkd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdbaprh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzrkpjg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hocufclj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2acglsrsv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2unsvfghg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlicsifg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2thvdrykw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmwegwh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeijcgnp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxpomcr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpxrviw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qervartn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcenuhj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxohwrp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgpuquz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyuzwkh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoodeii.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fttwnhjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxkjzqq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yozpcbct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjpvfsc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzmgpun.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyeqbui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaxozev.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uknaavfp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hudpkfip.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgfwelw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmghtwt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kofmlrwg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2runvrifa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbloobl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjynuupl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yztrqhdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqsjwtq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmvgktl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2njaafdne.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkzjtxj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wrufymju.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhkyzgd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgediug.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxkdymb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2mfctcyzj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdpbbmp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgvjwcw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qguiaqga.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2volcinrz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2louhpmhh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2orxwfhdb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uefwyhyl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsffiwu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqidnvk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ailgydhm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsojpgls.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvlemrc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlbjqyt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwidazkv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiagfpdg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2meqtrvih.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpubjln.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrnfklh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfektoi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtpgegc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvghpg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aacaibdb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlulwbom.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aagmhhxf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtdqzyr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxecoldy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpyvmzd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpbnvkj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioihmfwo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lsinbnzu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2douzpyoq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2teakeloa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2omdkifdr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaetmjpq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dljjkxpx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lemqzsxw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiolqiks.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2izshtizc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2owaneqxc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgryccm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xogfxicw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcskvuc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjftmos.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pypclxbz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvnztmm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vnobbowb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kynfewhb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gzctjgke.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsjysxv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjygstq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2whcydmpg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tuugrzoj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2clfimtyf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxtgjsp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2avzrqbac.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2llqrczzo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ayafbddw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ylidspbb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoktfzm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cihjrhtq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjckluz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbdqnat.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvpuzlc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zajmaldi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxgnasi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inxhxhrd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwbvcwv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdczjkoi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gimgiogr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrebdjj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvdbtcp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygduohpq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcmqwdq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhhqcji.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azqtftin.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbybbhgc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqoyzuv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvtjjsh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eosrlpyc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2azslufmz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmvjpxk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdozsju.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kigpkieh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uwybsrxe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfysvysi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2buyzwdam.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzxwxms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwvpaih.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2akuugnqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bglfwvep.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqtqjqk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzceghbj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zuenfnal.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oukfgram.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaqbots.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaadxvq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcdgkmb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqsyqve.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcushdj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kepnoewo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhcergf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxdtjgq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxgbslr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qhprpduq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyjkivx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cigbgkbl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkzsyek.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyvtvms.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mrektpsz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rigkzrmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lppwwrvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2onolrihc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2shnajfnq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhtyfdq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iriciabm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdxqzpu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smwjnouo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzqkwca.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2edxhflqi.html


<!-- 参考信息 -->