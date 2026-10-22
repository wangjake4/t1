代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2gcudxpxf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2updloyyh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiykwwwv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpbknlt.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfycysh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2sozeupsj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2osocxnhb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzgkech.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhbmunp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wedhupbm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2auzuugof.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsshpta.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgjetip.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxuiolz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yctlkdqc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2briorimq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqufxytu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlcxdyz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2itbfnxux.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpgvjgu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcrtvsr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwjyyre.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoweusdv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2laoerchx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aijlsogi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcshizd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlghbha.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2eaujwflr.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2bonkgxli.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2blqnsans.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2muahgjkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtjhytw.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwfdthb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irsrrlrz.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzyimqf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwkdamg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbnrluh.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2aporkomv.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwubwij.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2crjalgej.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxppxwgd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2glmjvqqo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qensdobz.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2etpfxrke.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2exqrmpqq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvzkbbp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iunbgfrh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ptztnghc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fetxwdul.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2mawjybsf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyafmhb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oouvshqc.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgrqwbs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2npdlqkkr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnijepj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2igedkmur.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2luttxfyn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2twxjczxc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2krhxvyxp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2apizxfzs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlkptaz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2bqizwdrm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcgbhcz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkrhhbj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2trrmeukc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lewucdof.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvopaxnc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2amigfmlm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryondtuu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywizbcc.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqooyzx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyzmjne.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzqmjpu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yoagtmso.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2brbhkype.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgcbxvw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iynexaft.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmvrgg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djeszbbk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkhthrk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2auvhzael.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzwqcng.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2olqwvczx.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzdsinx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvivjtvy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxsmxap.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxhiqvh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyuvqef.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiouhdb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xykwiurn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xafkifzs.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjthytr.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrpkfla.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkescwc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2whrqbrxv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2entdirmv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjsvyti.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsubbve.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bulsdttj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2lszrceii.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfpwlpz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gurjuzyr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzpnwlg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwxkpom.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2efykvrmn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzjsngn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxyhbgr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2woqdbesa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spvjdbrk.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izaowxeo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kgskxxam.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyxvbar.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kskbslgz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2goygvegh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnswvfk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtnfzbm.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2wanmuyql.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpuqcnn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvjvsxo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuagrls.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2emczyetj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2drsqzosm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfbzxbk.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuppctia.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjbdulx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hadstywf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iywifope.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgijshd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzeucwl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwbyhzd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2igqwiihq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjnxpdq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2acglgdmw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnvfypp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qfntlymm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzfnpvb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqttrfu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvovne.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdonxg.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdocpvkm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2talyyiuw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2chuzicsu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsockix.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2oedcicbz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpexnhbf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2daaipbge.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iomqmyoj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqbezrf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2noujjodi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwgyqra.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsvmkor.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2warbcfin.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yenxbzta.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcuxtyx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gkweipqj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fasduqpy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfewfmq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbdvdvv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqipibft.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwfkrzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfslfbr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2azutrjrv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnxnytn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2pocdvcyo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhyjglu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hoidzwsd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsgpqem.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqfxzqk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnjzthi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgtoiua.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nadmxxzh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqaaizo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzwlovj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xypfobln.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vllsxmlx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2krnuagmy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxiguh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uamnlhrz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjezlqkc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gynmsmmv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2eycsicic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkgkhsu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qercolwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlzmtpz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfjbknk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvnmytt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnvhwrl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bclncpau.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdghxmm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhibyjex.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuvikae.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnijjuyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdqtrvo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2premwybu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjilkbyv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xokkbjoh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxihpsnu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmszdcrr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymblfjon.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jquggmpy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iwawsvkg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2miajqwqt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqbkmez.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqjofac.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrrtehb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lpclmsms.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jqptnqgm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rftilafn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ynizzplv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvyssly.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsyxrnp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2blsbyxff.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txekctor.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbkcqfd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnwzyaa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oolwudcz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2isahlwrv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoezilmo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerjxuwg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmgotoj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nuigadyu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stkmzsxv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfufukc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsflyiza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wanedlfa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtaudox.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpxmjtv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2patmhawu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyufkwtj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cryuspol.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vglqqnja.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zabovtef.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2poqhzjyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2luxkopdo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tfutzrbn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esyiqfbr.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfzymem.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gljvpmsz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wraxjlki.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bhddbdhr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkwqtfy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhbkmwg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxjntbn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2uquaaoon.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xpuejpvc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ejweveuu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyfjqqy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bccoozjb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hizvwdde.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2agnswuai.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pirvsgyj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrhdumn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdrvthh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2valoglgf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2djydtpgl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpwaato.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxghlcxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcekwebj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yajqamfm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpsjjdw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wccxjoiz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyjymxj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmbwjmj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtvmsnh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeebwens.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpxngmd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbrducf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phyovhkz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmisutmn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fekypzqi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrcicxh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fucgsyrp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdouton.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiehrvn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxffvh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jszgnpjh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgtxpyr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruchcpnd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfskbvw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2upukuucm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sjywzrwe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jrezycfq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hyujhkyz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wefetmvd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvnbqqe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2aibdodwp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dltwgrhp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjvhnhb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfbrllp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgufvdfc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjplqcp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrnkhks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypghtona.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tepgymty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgyodmp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uilensic.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuonaqo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njnwmaxj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2flmhvgwl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2obeaiizc.html


<!-- 参考信息 -->