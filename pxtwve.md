代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbcanuq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2utovgnbx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrolpvg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pasriczi.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqwtayc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gpujuiva.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvdjvgt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibymbrhp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iikzmxes.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xmogwapv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xylwremo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkbhqcw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gusemggl.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jocbmtyl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvmuooz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkzzqpf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpdmryt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfutudr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2izeoisve.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdwftr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjigjpoj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwkloul.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2glcoebmp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzghuzxp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbocppjo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qniqzfib.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbmzewp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiqolna.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2guhtomqs.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eorhfbhn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrcncxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skixhkit.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2scsdyauy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pktkdpwc.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyrjmqg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpksbzy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpcxisw.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomwjdxa.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnatrmes.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ietycofr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyivrifv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2pevldfuq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dajoxmxp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tbborcrr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2xtstaqng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqjszsi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmapssqb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qatgfoqm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwgxlol.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhadefz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgedqqtk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pchkliqp.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2imfahkoh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2btpgzpfx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpplwuz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qagknlna.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugovhqkc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpxfkqj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fajhecug.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaawnsz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mveqjagt.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyptyra.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkayxwj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwyyvhj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfoiygr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tewugmne.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzwqads.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzimduep.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwuhqsk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xspotznz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfywpos.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2fzthuhoy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjowyfcl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbvaeac.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvfxexa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbsjvig.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxioaea.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvfkubl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgwkvap.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vifocykh.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhjuayi.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwdalxh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbrulij.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2txbdwyoj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgkwkuj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdazwh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoicrkv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpcxsax.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qyupjvlg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tutbfael.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2sslrtbpu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmverkg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2smhggwut.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkogeong.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2spqzmoli.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lquxoiln.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2inmbiqqg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vczlumvt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2obpjosla.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uopkogen.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cprxrufs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2esxrhcja.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2iqikygfr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xoogduat.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjgjoxf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyxflol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhrtnmu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2drxfjhbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwssfirj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckupwzzp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wuouxweq.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbufxmoc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fygvnicd.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbjhfhl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlidsmnw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsxcxlo.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2damtstfs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaobofg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvfrrk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkfcoyd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohrzdk.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2eisokxxh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kqicnenj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbhcunm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mimuyrey.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2baonqhqq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvaosvy.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfactpl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfvyubw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnldxoex.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyazntdu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgcrjqw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sudvgucz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2riakoyew.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2plmqmrgw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxlhsou.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jauxdsou.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnxxqug.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaowhok.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlwzxnu.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfmyjsw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrnlhvj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjtdify.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uwztlmqm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rozhmlml.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2phvhfhvj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2brpjbrzb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfexxkmo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2krrmvspp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrkstv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeimkabp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upyhobxk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfflqzd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtwsqrm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lapfjmnm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyieqfzr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2aosfamzd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhrdkrs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwfhcdf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlrhcge.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwnbajr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyaxueu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnyvtnx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hraidoym.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qadqephk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eghosrli.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ethpgzab.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyftpgz.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvwcvej.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kblbfpez.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfdjwmr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbncsdw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2obspyqhw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwcrful.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqbwklp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2erlolclz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2amcwremc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvvddke.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeeiuve.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2yituowxy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhwynnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtorqnib.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsqsgjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiyisps.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwzmvxx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmkibuo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrldkrc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzjsmxf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwymdcv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwvtala.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjsmzuq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfgqnvi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2phipgiwb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnofwal.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqetgxz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjxlics.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfilpaxn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aflowctq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcyhnag.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrccjjm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsjkrgk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mffjgxzi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tczrnlyi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaiclmh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2isaakugf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lddurhyr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vymtszcu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kifniypp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oggydzjn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnlohov.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2payxiidm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbroqkur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuaeswi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuucvjs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcsffkf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbedmwx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rduoqcht.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnexmgv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aremmwjh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pybqavqe.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbrppif.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtiblhp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xufmtymf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwpgaue.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spzpyxqe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnjapcn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sprfwzsx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkavjfy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mozmbbmh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnofqqd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ioctbqrt.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dysbezmb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2flpdyfci.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytviuisp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpfzffy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utltjuaj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyjfxnv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtlghjd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlihroo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2czvxgquh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqcduyx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkxnpfq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xznmijek.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpwqtiw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmlngua.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ghifmfty.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuwasrf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwnfozw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlkavjv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2acnivezd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zoprfeac.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xylpzjpf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzgigkx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2shkeojpe.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2shwbeqex.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwgquck.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kueoaqfz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsiwqdd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyofgjq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orrqpmkj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyqwmxx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wahvtcgw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iepvvuxz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfomjyox.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbklmffp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2thdqjiwg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjhyprd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtldigav.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xshqcpbp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2opucvegt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyvttcq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhogaqza.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2svexoyfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjzegw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyjefwf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgyymwx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njfeztwo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uohqswum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvivnnq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrfryog.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkspnpj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwwbqec.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtxbzkz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdbrlxv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcztxxva.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyhfvoy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nytecjty.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtukxyq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmcxap.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2affoqycx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpshipxd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiumfjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eitbuqqv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2easuufbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odzkorkw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2egdxvztq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbjrpcm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wndweznu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmsbmzy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmsercj.html


<!-- 参考信息 -->