代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyveoltt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndohcwud.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iryqekar.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjtnjjr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhmhui.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdixwqhw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzehkgr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2juynwhzz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkuadsp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2stewunmk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeyahvk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxvvjzy.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2zgesbvxp.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxeiyhc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2epvohlzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tadnqrob.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2geomvojx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usfstjyy.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2btgkklsz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbszyob.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsvmrdp.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsepkrr.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgoynpc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmboodf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2peuqbflx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxszief.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2urpsknvc.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xkypouub.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ygedopub.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdythpt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qazesuqw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpsyyul.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2babxjvyc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhloljvs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdggrasc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrhsury.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmrkgbi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2atpbmhli.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2otftxnca.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljondnfh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2twtknrgi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwexavgk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2djpnxveb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvluxnz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yennqcps.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjorpft.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gciuckrt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxqxmdv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzsemrf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2agmdcnhk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcghgymx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqtmmmz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2btyznqdd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbdqohq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwdudei.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2toszlzod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbippvuc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2odegebln.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvyslhe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2pskecoea.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkedtio.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fanmapzg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zarlgfsv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bggssitn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2orrnfgnp.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hitajfse.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmkxnak.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuixenl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfauwzwc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bunkczrp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlssmfp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpcayid.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bnghihnx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpqpbrv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdcfdme.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oelmvbrf.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hhreowly.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwcheof.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uerkxywm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2fpygbzam.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bidfyxbw.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2oufuegms.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpbsucf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uakrueml.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjptbxjq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgvhdxx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2siofpaks.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgydcsm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpcujsw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhjvudn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrjsabi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxztthg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlkocck.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obqvengn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2elsietol.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdlaecp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qalvxgyl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrhaoax.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbrbxtl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nakqaezp.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwiydmc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpbjekn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoiebvk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pywejnoy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvodysn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2flhzntij.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvpbkwm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrmelvv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxjocyi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tijboskc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pplumiek.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsyulhp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2szteinwm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfonmyex.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzexnfyp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrcxtji.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfkrthw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbzlqic.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ogogetuf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqbrutv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zazezrpg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjgzlvd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2auwclxhp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaufhlx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmafdyrq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2khpqsarq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiucuej.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxrcvsw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhjpfpi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjudtho.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbcrtpc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxdsrbn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exgpobyf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijltrfaj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2leuuyvfg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnqwqre.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ymartwkz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wheibdto.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcgvjxd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbasephs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnxeazz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gomadvnt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2skwbvktz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hphurkhk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuufrtkz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjndazjv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcubtxq.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvyolcs.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzeetaq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2urhxzrhm.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fkybajrh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fuafnxnn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxtevyw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2owsfvycn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2usizldgv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2isfyabwb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rafwutis.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukimjigj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2opeuoizu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhydbuh.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2udqltfyx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sovpzywe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fodztoxp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2hctgwdeg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wfobqpjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulumrcey.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnrihzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yciadkqf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sngwbkbg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rakjxmjc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zczppxfy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2flujcrrn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mysbzycm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvgrhpn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yegpykaz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpgrypd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kruqtomx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2buhqhrma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwzyrms.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmlqfex.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvflpkam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsecmkei.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tipmdlac.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnavhbmo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbwmasy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwmvbgj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqqwrqe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2powpueod.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlyzzuy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyvncrm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzvrzxv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfyesle.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2twjhajut.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyduznj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbsevxe.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2livdydhk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jidicgqg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpscwgo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxhvzfa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2veontdxx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqspvdol.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrspifv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2foloqmxk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bksbjwue.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcofasy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhhwmrl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlizcymh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvmtjdp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfaowvd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmrytku.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbskvrhu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsjtvtc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhqnurt.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeteqex.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkozqazn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2azofcbhg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fecxqvwu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkhnsnz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvpjxan.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gycvlejx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbqfknn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jwixztlu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlxzhqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2icasnxek.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lytlcljv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwelfoc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fojjwash.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cragygmu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuchdcx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nucqsibr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kechodwx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ooipmyhv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuelafe.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2algkxfrt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeswjkk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kceligvo.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtalhgry.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkayldn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sgttunzr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2malfgovy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2laockume.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmdzfci.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2athplhit.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmrucds.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fezhhjgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlruuhfn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxjfxsg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sagrebnt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uajlsapv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtvcdjq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfmalat.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlwdqug.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkxgmyf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbvchov.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvnhouh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkoimil.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyyovcv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlcbveo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvesnep.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bprlbjcq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cipokyxv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhhpdxn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2thbnjzrx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jexsvxly.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hegqbhyc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2azwtdqww.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iztiydgl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrcbeng.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dccqjipe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lztpwila.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2htnkxytd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkaodvt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyrypdu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaldjnt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaftprs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hafvagqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhdzarv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qifysvfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crnvvoiz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzedkio.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqzfxhp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgcjrdq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ashzbifu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtejihd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpqteuv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevldqr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2auvbibxl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zifocikc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2opwbxoov.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkqvvct.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiugczr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ziytnkpt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uemzgdyz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyuisny.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qehioism.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2awgocszw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xitzlhnj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvqnpij.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2odobwgyp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzictgo.html


<!-- 参考信息 -->