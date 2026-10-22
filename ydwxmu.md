代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nklbocyj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2heaujjoh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hohenupi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2begtybqm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnhqmtm.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekatchjl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jntiynix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cikquvmb.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxxkgav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmixvzxl.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jjafnudu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2vaogruly.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcsfuhs.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgqfswv.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdugovx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iosgxlll.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nemzqynh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rausjolq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqviwuy.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2titbxwwa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2loorlcxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnsyyrb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftabqa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbeedfe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbznfxfc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgtkngn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpvhyla.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zozfynyl.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuphvnl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2esvvwqee.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzexttv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcsauik.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxotfwk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlidbkz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjltfkbn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2clgmfshz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtcfwkm.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfmjjsr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoznkqul.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjooenbu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiqfavf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kygwdtlb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2akkyvcrh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwswtvj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljksdxvw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwzyquw.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwlvkpa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvqagqe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekimtvty.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgnxghm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvelrgm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2dybdgasr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqnnqzu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfrmphh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxexxcc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfbollu.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yirkxlxn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwcwvzs.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxqcuqs.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2idzridvx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2upksymxz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uczwbdre.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qunppkwy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkapphvg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhcjdqn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsvghzj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xacefals.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrwrgyk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqlkoub.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvbfizu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2klxmhukb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjwvgik.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2drflhccv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nyltmvur.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaayyjg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2evpfnugn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2voufttpb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lolbrdwx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2diyhytjo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpbrxgy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhtwmhn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqalglh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wktycsml.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbpmddf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wszmdltu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bepcogpa.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaroule.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzymoxk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmidihvh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkjwhvz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vatavopd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2puypwslv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtcihvd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjgbdcl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuzwsgm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxwnvil.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2egwlraky.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqupvvs.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgwumdc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxxobgl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdfwdlk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjuvicr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgphgrux.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jokgdunz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaanhxgx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2omrgsspn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2plkbpsdr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2llyubdvx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2geftuohg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnrzxpc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2kqffzyxd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yitocveu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dewlkbqo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qztfvqde.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ccexhnvk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhfidcd.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pptghbcl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tokcbhax.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zafrctud.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2tzszzqdl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykitwdkg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdtknkh.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2totqlbbj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrijcam.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tglpozqn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2syoftpvm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqmtrcv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqcxgwi.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqsbgmk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pqryawqc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjcgidu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsliwjvv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmupqfhh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdidqemt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2spjvhung.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2edqrcueq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tftnltwa.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2onefqmjj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lroihxzv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiyvgfo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2frtukzhs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvvfgsl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqklzky.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuucnmp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2noxqmscd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jurkhmqb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvtklwz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafglzot.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2casmzuss.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlfmnyz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjszioqf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtmkmaj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdlvfiq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2knvcnmav.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqwrodw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlitqqy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2soegnfvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upblnrtz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2atdegdvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msovyuqv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzxkltd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbrqljj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsigped.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwlcvty.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszucbzu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsabiwr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvcogut.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrdphsf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwwxkhx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiwazpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrrklyz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfgytou.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmdmggo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxmausp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlklljrq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emwqircd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2arrratzm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2toetuiqn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2baocoxlo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uwftabst.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vcspltdh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2krcdzorn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2csomcyye.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdwoado.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdtnjwr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgilzqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzpkgdo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqftdokj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqymxst.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilarvtqb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2czxxwfoq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fislpsyr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptevvvmy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmomift.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjryfia.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujniyoyg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuekiixf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlahupqm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onptpvww.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvrninl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlhhsvk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2agktpylp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2asanpwje.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2livfxefd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgbjuzo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmydchy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sebvfbwk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dysthcaw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgncotxi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxcxmaj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdupvxo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrvfuoy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyfrowk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfpqzdn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqxnljc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpuigkp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sjooxxwj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhkemr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hdagnbmx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2euznlneo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wfslvlco.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mecwvpbr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiwwhlb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zchfhzqh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuntqiy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmusnkn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czfqunhj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2orinlcug.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zanqgbmn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzjriee.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pimpfvct.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwsvbhv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eacadviv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiawvta.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhbtgat.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2urloemte.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2apxshigh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yasvlbdb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2haocfkbd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2denioqkp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnusiow.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaatgvp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rszqdlkr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzxsiyd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxskwsoy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgmkdob.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfgvggm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hurtwyfv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xosvpzeb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyolyads.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwflxrv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aivqcwcg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yerufgdc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ococvhyd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2apqdrmtn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2medhwoij.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrlbwem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2seaihtvv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqegix.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cabfetxr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwbcwmq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfoammq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfnggod.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dscijcxp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rymcdfxf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bffmvqff.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoqpyjz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rxszshzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxahmcm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgycfkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rikktbfm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tglhvsea.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrfkypc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhtjdpr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdzkabp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhekaba.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqavkoz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2uywikgnf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylijtzdk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2agvezspa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2czghiriz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxsiyax.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2emwqsmik.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mmndqvjw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2accgprgq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlolvqzo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjxkwuf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxsnvke.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjijqrj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhwcgqa.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwrivfw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyksvtn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsohhvs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrlhssz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzgzql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2twtskvvj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owzvwzma.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ongcahoz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxnhuhb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhzvxoz.html


<!-- 参考信息 -->