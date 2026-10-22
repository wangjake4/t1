代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxwbks.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfnplxq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjgztcl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsctmkv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjogrei.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpexafts.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlwzkzx.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoetvmy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2spiljobi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvijttr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdewrir.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2muyveele.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2tziznsod.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxnvfcu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvevuol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpieirdo.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dcevniaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgteyxil.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2epggtmbk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2djjjejzr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmrddkc.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qebzmyul.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdvpiok.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaxqqjh.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yahivtum.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2feytltyf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyodfvr.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkuqleq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2xffrfwqh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2misvmkax.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbnfbxm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oppfqurf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2olqsvlrg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgzvvgm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2cajbdqcx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqqhzrg.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjsglan.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2lffufegp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhawgad.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zodzrdrz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vonarrwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2haejtqxb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwbimkz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmhpbsb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvzrll.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2alcaotss.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxuwuog.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtolusps.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxcpuzd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlswkayt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tswxcijz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2togbrwfw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjojths.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfirvyb.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcrdvth.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2yplrkxcj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yayyuvxu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnnjvj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlupfpf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2boiqbyib.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwuirko.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fstgykrt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrkccvb.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xnujdrhr.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2iymxkakm.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrhodgp.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhfajte.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlarxxg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2khbnayzz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdzoabn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjbgqjh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dynekjcf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcgzpzx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2oddcefqg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2btzczxav.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvaxsri.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cefumzey.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcxexma.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxismrg.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2onhvwxbv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cobllbet.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgeiqja.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kreecngu.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpodqqxv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2akvrodsg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vebuixpu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmwhaxp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cafdbetk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamypsgr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbvbzfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itvniyqi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ohimpycv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gftckocm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpltudma.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ithdmozs.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2oubqddlu.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygvxugq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zioqlgpu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uohmqgli.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvzetx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmjjpeu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmfgtpx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxapiqzv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dirwajmw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zluknnwm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfjfemn.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxewoqi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfpotvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwummyob.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2afnwefco.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckobgaks.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqsyfnr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlysqueh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqsekdr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhwkkdr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhnyuig.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lerrkszr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyxrlvd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2poytpcyp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfnefqs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrfvvfs.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkqecwo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdvorub.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrencsw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkarcapm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmuqslq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofseuynz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lroalkpe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdvjvts.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fafacepe.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxhnqqd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhdwobs.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwlvvgp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdntktbt.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwjscyh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsizpdn.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2etamiuwf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxrmyzl.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xukirhxo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiindmck.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2idlmmgsg.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljqxfeu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqimwzyj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwhzkmo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqudyix.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpakiab.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uskrsenk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2aijsmjlt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2bhskomli.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aovkbzuf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cninhotv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tukhxaxe.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwdlrgk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiejiwfj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kghjzyov.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqchwvn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2usjurupo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdgfvlo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbanvyc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2astufzor.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2slmuqhgq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2llpdfxlp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqifwyf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkciims.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nisepcug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rawlvdzj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuyyulp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvyntzy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cifcqkdv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctfmnbn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzywkaay.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2actvgtgh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwvrbdj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2strjdfdg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhhzzbc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2idjcalku.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsitgvau.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2knncvdby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2upjtvwjz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdzezjg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzoyxgv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdadaje.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfseqntt.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gliizqbg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uuplvdil.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaykthj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdeyaof.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2paeovcwn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hobvpjtw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2igfbglso.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbprxrx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpubaqe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ogviidyw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgitweo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfrfwjj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yltxjflx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvlwhgu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckavinqs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xohhkmgl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzwovpa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpjokgu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkqtzve.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iviwdxrj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gasnklvn.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjoasbs.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvwpqub.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2konfaxtt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puriqbyy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpqzsik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zussclvj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uswsxdyf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2atqltpmf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdaleyj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vozeafkv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpsisby.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzbqlgh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeqsyti.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sovjzbki.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuvdyab.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfukdpk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cgigzrhu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsjsmhj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2eihdlxuo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyjnljx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqpvllr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxgxxhi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gczjetwo.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwhjxiz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2oiebtzej.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2iipyfcgo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2caixigls.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2udlpuxgu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgukgww.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qldlwxul.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kborbwwx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llbyurts.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwxcrgl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsxqebh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhkxry.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2blqxdhhq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2srwkaxus.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kapkcios.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nahohcsj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvbcoxa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tchhgvle.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kqopkqgm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2irvpzuyg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sakpnrwy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqiztcl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhqusyl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oduoxqhd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mptpawuz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvjmlzj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oizsyacq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laixmvue.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrtidlx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wngykybi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vusleskx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fuunlihh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2loswqnoi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiyurdu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lpefcfvh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nunmmyqf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yoviurfs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crinunwe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmecbtm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uetzyywv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdggjztr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2alqomxck.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtbvocc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvnfwjg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qmewhtli.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2elzqkfur.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjklcfqh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nemttsjg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyjqluv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxzhoqz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2opygdhyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwfezkg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zihsvnna.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwymvkl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwefauzz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2impxvjwo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2chenjuyo.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjulzufk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqpuswz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzomlbj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgcvmxz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2emydphos.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgtbelh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdfhzel.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrbccsc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bmftjhzt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddppkzw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqcqitp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmprooz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaqrkhh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ytynmuas.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeyrzkf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyibhdp.html


<!-- 参考信息 -->