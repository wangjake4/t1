代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcslpstl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsydxeqg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpnrztd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsrribx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsihpryx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hndvtmum.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxwsap.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2srxpmyhr.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqadhuq.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpidzba.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjlbpfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfpmnle.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kirugigk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrulujp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2azujuvbn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcpkimn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ewznvfdd.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2oicebaks.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyazrod.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fosxailc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2waqetram.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdfyuig.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2byxivjdo.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lsncjopt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrjzjqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2oaptdcmo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2isknzfid.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkuiwqw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwraers.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2iiojvheb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrnlvbo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2arurkppt.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlfzimb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyuepuv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2witsyhpq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxofppu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yshwahaj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzecwztd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2arcyrvxm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqhvlci.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2oclyfhrq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2sjegehbc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxaevag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdklblel.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dllzamaj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyhivzh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jahqjptx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjwucrg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpmwayx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qofwbmrn.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkfqcej.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrgpvdb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfsnmwf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbggdmp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ummhrkda.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrqsfdp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvqbnrb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtockfs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krqdovfp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgsxxwr.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2roazttef.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyuqrdf.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wurtpypi.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2idqcsjwj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2anhbejux.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uavhslit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2owhjetqm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcecjfvd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvcmqzf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyrriou.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2onkinzme.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaafomx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2omvgivym.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2njclndul.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lchefthh.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdqqgrp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rciwjiyr.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqnigvu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2sobcbdhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebytltqx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtflwucu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ighuwhlk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dbajsvxm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbcctzf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnavsuw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvubhlrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ervwbkbt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpwkcxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvsttwo.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrrfzdk.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhteaqay.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoonxnt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgosufj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzeugia.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqzzdnp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvqnggt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdmlwnl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpyjuru.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2scpvyfrc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2brvydtme.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhkkzyw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nogwaygy.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kswrexhb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjofcqpu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2guvtxoba.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2oudulloh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgimubn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2holdlnrp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqevsqz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnomkhn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwkorik.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iapukspf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxccszb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgtkkiw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbnjcpp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qugprdej.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2halukeib.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcnxwst.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2alithdit.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsvowco.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhwjfxf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwdknpf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjrucvo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2aafkztnm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfkbyza.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubenevwb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxizvtqh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaflmho.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmuwdyo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfidxvi.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhwjfno.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbctglj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vemktndj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uznnfian.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfyhsss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tisikmmq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpugqzc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtotzbe.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wamihocg.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqbbwlg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnclotef.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijorbwld.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmbytqz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2efmfpytt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyzdlkb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2imclnuqd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2npsrbvvj.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2flizkrnu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjchutbg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nexibzfm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvaeurx.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oghjdmbp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fcanlbpq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfpjwtq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vmptloyk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcfnfox.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjstec.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhntrsxu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqeuit.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2seeputsz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2cbamqkdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nphqhcoy.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2justfecx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qesxqwcv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwsixqv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2duqamwxu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtozxit.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjsbbff.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhiuism.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2deilxpel.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfqrzrs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytazavri.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpcbqlp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cagyjfge.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zodumtjh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfykofei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdxjxzs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gozcqsjd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywiiytw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkdukqb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxqziqa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulifswre.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfulfmgs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tnliusjl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnilmmx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwzmyhi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnegngi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2penglvnj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2puyugegc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nepjlveo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rkudmonk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2shuqcehh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvjhfcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjrdfbi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzkljym.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcggexb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sggdqydu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dujrerft.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvfvbt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcwzofa.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2esrmxdcw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jukgmxrc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaeehnl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sztgfrmv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhytzgzp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsukysd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjpkcrk.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2navcwcgo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcbetec.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccivcyaa.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jupfdavp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaionumq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxslwdco.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfuppcd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzhbstx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwbhlnk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bblpxipu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ihohgnho.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2esyicuhv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nemcnmsk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgchxnp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxjdrct.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rplemhps.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgwvtun.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2egcmioux.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvxfzvf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2elevlyzu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2syuybwil.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyffzho.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrozxto.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bpourtvn.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cthhafkq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kimuurmy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxveqsf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2stipjiiv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gkttjlup.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlhhozj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmzprii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcybskyi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxdildh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nsawsdfd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrowwcwr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhgvwxd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxqidor.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdwgsqy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2payyurnn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2znjpiyuv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpdkars.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtpscyb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yasmgduk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpdjgwf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsdzjln.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2msqbvnvx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jddjbceo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpfugkn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaleqwd.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjeibmk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kocmnybp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcgkcve.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhzbozo.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yodwyrzw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nedwfkux.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnrexxp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2occhzsvx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhytwhv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yamtaitg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjlrcye.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uremisuw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2simetedb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uglrhzpl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjzayhb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fxppsdme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgctleoe.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhuksmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xabiljsc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdgvovw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2terytjvi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snezlhbe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxsqmnq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtgsler.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiatvyq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycejzzsg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2whuwlwcu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjujshs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jlefwxws.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvnxkhm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wztkacsq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcwmnoa.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdicpao.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnufkpuj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tfngwqai.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ctddrfdo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzsdxic.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kidcnski.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyxprsl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vznjxqbu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2aziokquy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fnagvebw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhosnxhq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuiqnht.html


<!-- 参考信息 -->