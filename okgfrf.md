代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2obhuuudl.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awyterua.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyfciyv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsyasht.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudbzvhz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaichyhh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpynuol.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmmuuse.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nodeionf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hihkmapf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxanmutk.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2drgzgspa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmohhygc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwranmk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sdddndzq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrwrnjt.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcjkbwu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzencwwg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bkarrtxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brmidaqi.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsggdji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmwpvor.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuttyfn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwxawkh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjedxqj.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2clkaorxp.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfqtghb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkhaihn.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2acmugnvb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjaotac.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaeeqfi.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwcwtzl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ipilxidg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2gocoowyx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wvojtjpz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvqjqb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyxncve.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdvnefk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2luzewswh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmedjuib.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkdhmkp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2epnxwyxp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmlgpsy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2eewyxziu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2oknkgody.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxdbwyl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2epwmaimt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjnlxjr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlqcpmv.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyimlsr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uacqfaia.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2skgwsiwh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yobpmoyf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2liohyxgd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2csvhwkcv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2aalfphxo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bojslsdr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpyxwmu.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbbioma.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdpbmbm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2preisqfe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2olarbkah.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgbwwny.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrjqsqc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqbwnny.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2awqbnint.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2slcqcfyb.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fscpfwvf.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlqqled.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2igfvxlim.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2unhnqklx.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfxcjea.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxuojhj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvmbthr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vklzlfay.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzunkcqw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2phwlgglc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlrnlih.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2emvjldhq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tphhcjva.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2khnfyrrh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmswrvzi.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2poykcsyu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2eicuslxz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiszrdh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rbytoqhc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmacowk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcftxhy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kogsgxwt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qssgyomx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdwaiuk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2eanwrxcu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyrxlcq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuewfckd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jervclpv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfaajxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnallphb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xldjubpm.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2alsmbdut.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2srgttsnt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2guixykbf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglbfahu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcoakhd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwnungg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlfulbt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjgqeoc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2einrjvvd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2amzagmok.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bivgeulg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2whcdmrut.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2entigjhs.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkwfmlo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulodjsnj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfzuibv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueicaisa.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2srgxogdd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhnuyxe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zasbwjvv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzxgurp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2htdccxgi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhfnnff.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhtpayz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2odzibvpn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiyyhhh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcogqyr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojavipdc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzndlbw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zayhifrv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbykrdb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkllfpgg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiolwboc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2obazprvq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2aequzfcf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2znrxzfln.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nodmhhkq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurqpkxi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwedphd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxpilpu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxrinan.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfytdbmt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzjbxdr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2kztqebif.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhsmmhs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsauseg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wukihkgx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iviyeomw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwnbsio.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrcgptj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhgvmdx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaglwil.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nohrznrt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jwivpcwk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qranxqrx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiugwtv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyynmvf.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaoygza.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aveeyjzk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuhcdry.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tolgtgnm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2axdhyrfb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iunvniun.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoledgus.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaugurx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjmyudu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hclsndbl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpyptax.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtyipeh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kuysvwak.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2paiblfuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yohopqsv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2stmeplnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cylnytpw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajekware.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosirtzt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvycinsh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2supvyzcb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nttpecvp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixyjtru.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rejxafvt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjgdctb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idnsviyb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvjtckn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2auriutqt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbnbdlv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2klkmsaap.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kluqrffp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnirsry.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahubgrkg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qalanqqw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwapimbm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfcxrby.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2phbgxyex.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnfdglv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvrnkrf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtpxtpq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfvynpm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmzyize.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpuedbg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvbvvfu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaidifk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afvgmuwe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdhwxhv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrqhmyx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eellohjf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctudorc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qisgwtsp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjkruda.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdiozyd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2axwqpqba.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygncaorc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlgwfaw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjdtfjy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzxpydz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2excyfqvo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpwmblf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2edgckfij.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqzxwmd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjqacox.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvugonrb.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfcrkyx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2obmnbccw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbrdogz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzivmwm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lforyrpn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xywrvpoj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gerkkhqa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmijwrm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ckybsgka.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vdljjiwq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaguuhz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2scmiypjl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyjzvjc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2znulbyoh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2oowbcvnk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqqeuzb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuysigg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrczdbq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ismmefbj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ystnmvie.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2modguqjo.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oibkqjhc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2revbywfs.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2utcsxgdy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lsehfldv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vynmaxbc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqltvjhq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtuxvoi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkhaknu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2brvwzxtp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvlwssm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cpafzfju.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiwbpth.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzxouqp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2brkiguxg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhslgxp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbshldf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciktuxtu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hioaqnxi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btwskjqk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkewjojx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsugolm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eduwrjvn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iinwccth.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2srylpzyq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imriiyxy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2waanapps.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oknxeevy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2otzjpsud.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rrskfxvk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpqdgmq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjufmvx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmtztel.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyvnfxv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2utxpxasy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoljusv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvywnkwg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2roenrpsr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwzmaua.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyewkgoq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2htlqwfcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvevehaa.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2iihamhdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmrobip.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nbafwdfl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuyjioa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwndflbk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhdgufu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiamqgz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2klytcqol.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwyyskd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaleuga.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcnczwf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwucudm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgkraex.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2icbgupxs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxrrqis.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrhyvdy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajefbrge.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2blwyzffq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhumpva.html


<!-- 参考信息 -->