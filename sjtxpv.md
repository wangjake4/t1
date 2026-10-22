代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2wadacsbv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwjugpa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdvbpyt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxbiiwy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwhymhy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2atpqcvor.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kshxzpzn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuqyxbe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyskroj.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcwyqcr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiksmzj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2buqyrmun.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzungtl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyobbsvu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsftkhz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2uleavyep.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwiltry.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2johrxxvb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2pznwrgll.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaivpay.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuedknxn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwzqryj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2euqahjmb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2oltiklkw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2qyayzfoz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mymxciwx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhndypi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqeqiau.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpavypf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nddhtrer.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2owiwzkbj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuyzwqu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2mncozswx.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcazzgm.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkcsnap.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nridpmjt.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhasmle.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2isqbxuie.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbfgdvn.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2heohfscx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wterknnp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqgxnvd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jlabsfkc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zimxdinh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oupomnlz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfphcztz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvorzrj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubskbgyr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2xxidwhim.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtqgxrw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mylijlfn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qafeoktm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wocltuaz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlatsl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ickbduwx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadvprs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2eorzkdis.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2rutshhrd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuarvtpn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udskkbpq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzwrfee.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsuutfo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fymebxhn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtbjphf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsplqrn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwinwfyy.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2voxehtqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlupdxc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkayooal.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ordlssua.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmcqnfi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2tywfhhkm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckatzvaf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrdrtag.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txnuttys.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2visvcngy.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbitomkb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2itqjwndo.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmnkjjt.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbtxgp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwqenbj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uksmhdzz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjykrtbo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2coxhmpqn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiqmspj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsbbacf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyzliyo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ruphwydu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvaalij.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyifjhek.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rauracxs.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2qeftnpcp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hhktfgdv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbmdhsx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2szrejxzp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ellgbklw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhsduzc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2olxziqmz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsfpdwf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzclzwk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnufvivt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxehfpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lklgkwxc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnlywmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cayyesre.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jszahzpt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvackbva.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tniovjuq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2htcdpsbn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfnolyg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhseiim.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nizmmber.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gibsbcng.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxktozus.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2amgwnigp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2osfkqxvd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqynlcnw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vczycznk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zntcokjq.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2caedcsnp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjdovgw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqhxnbb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qostmrpx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vimbtfnq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiwvcju.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzkmhzd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrtaeyf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuyfwqb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmubrmp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciplqnrr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nooqqodw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmrclsu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgflpgv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgamhix.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wuksytwt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoszltbw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzuncgv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhvehal.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hddsjvre.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqiioot.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qocuirfr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrutfcw.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhvlltk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmtpeps.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhpfrqs.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifyotx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyyuxwb.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdnqbzm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsxsugy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrbziwr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2trdqknuf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwulcyh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vakinvhz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2duqkstzq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvdxhsi.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjazrvch.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptztcysw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlufuwyl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrppgze.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2opxwzyla.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnleogb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkxsgdh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jwndoddn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuroztg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyzhdma.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfecfhw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2piuwxtdu.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjncwupx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwdannr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2crfxlove.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsourub.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2koxbvtqt.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrovzmw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzgompv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzdfhpr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtcximt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lmchvelh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nppgukac.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lkekmlde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrysqbdm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmuuvij.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtpkzco.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zputxjzj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gixpeeco.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2getlqkqx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzeyxsl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxyfqyj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwyhsax.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aluulako.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfhqisy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnzdnfq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkfgrie.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwymlqzz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otygcgrc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2amcvqsym.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbylqyh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyjbvcr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtncgbv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeykxxm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2coxihgpn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2anrehcjy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjyemoa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uycvxulc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nphcwird.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbdsyn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yitzrhfw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyljooz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2noscnghu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyrrdrh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmufgetq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmfkvor.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpxjspc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwvmcet.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfolghhn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gskotlqu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqguhlgr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hljfhqir.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvktnyo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznhxqfb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqzbezi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyqhimt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jahaarfo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmklkbc.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtpoteo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyblcty.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcwmmdw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2onbahzph.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyysrtce.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebynbkoj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwketys.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhnmmrc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxndfjx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ziffaqkp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dowiwlok.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbtdcdq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpxilby.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sifunzgs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqgwvnm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmkafnl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiyjzmr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaonfaf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2uskwglsg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpatcrd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2outbjjjo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2krbhyunl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdxeydx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiyqfsz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzczzn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pppsvszr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmixybw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xlejcypc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqkqqjl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iibnslwc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsawajgd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwymzkjc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgjxmol.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2clwbdhlw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsmbiwt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wutleypa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dakzpkzi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvblbeg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dmznekui.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaxhxan.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjswdtpm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bocfsukl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2onsvblgp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcsdobu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2opcwijdo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjiuodm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljipicge.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2egzyusex.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwrgnuf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgicqldi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsjakbv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uytdqsvw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgqwdcp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vrphmcxz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwvepbd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ssivvcrr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2resfzozk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kovbwjry.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2twlymntb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwmezd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgckcpd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mktvswrj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2quhryudb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyakamu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqomqzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmojjqgd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2voiweasp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amyjabfx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoygrou.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzehilxs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpznvcdr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwnzhzv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dxygrpjq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uskystge.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkdvak.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaigickq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ipumcjvy.html


<!-- 参考信息 -->