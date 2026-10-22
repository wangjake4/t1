代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtlyvje.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2efmpuyto.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfyopeo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnflfgsv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmykwfm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuafbpt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zleeydvj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrjxvu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqiuhbr.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtqcynv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmklkrtw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2merwulya.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2psjezruv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqgcsbz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jymtrbcf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhddkpg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2woduktuf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zspfhscf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2whzqkcel.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uffmurgl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gueddttf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bimzlrrr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gceouhvn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2uibfpqpu.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhsjuvw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mquvdlkw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkomquq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmulsni.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qlepgkda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frigozag.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkywrcf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuuiudd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2loggabvj.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtczvkn.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtozufz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nqziojjt.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpgsvwq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2vurbjhxk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywizdeic.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2remcomon.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2snmqxbvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwlhokv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2djnxnehn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2protddxl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fafvipen.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgdxamm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbswrub.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwubvqw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2gguaqlis.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgfkqjm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjouqbo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nystxrmy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbvczlr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqdvweu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbekgglg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrjlgma.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcqqxmk.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiixaqj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeuffeq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ratdtvil.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2irxxvanz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pymrwvbc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcixesdg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2iezgtrnj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxiisgg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxwetic.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2kviabriv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2puxuirrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nepxjzso.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppovsqzr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2uojmixyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2dppzufvt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tajycubo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gojefeal.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaovnadn.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cieawcyx.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2exhfjohi.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfbrjeg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ficitvto.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uebamjxo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxcuesk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwyjzsj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mshtgbjm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbkshef.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvowhtpk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2adpgjmfq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jawoohgg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwewgtr.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2igrdltxz.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhypugi.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpcbglz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ragpitrj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrxbaxr.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hsslmsta.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxngmql.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcksvnw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbijhxr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbmaigt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpsipqp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgnejlf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2airznvus.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtgebpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfrwoei.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2psihymby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnfomok.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jodaxdcr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xisakitm.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjyetay.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfrdtjf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luhgjmsy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xokzxyis.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nddtxrix.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2aotmonza.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2irxqjquc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwythdfk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfyzbmi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdoutit.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ytncavgj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnudkld.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvcdzgv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoisteoz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bohtktmg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwrfreh.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2drjeeqkb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlmhafm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgczcgaz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zskvcloz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzslczq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2labjnmkf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxmfdnj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2sonmfsdi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsevttb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkfsjrw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzisxea.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjfcons.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcznagup.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2apadxzqt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzccsjsa.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlptjuz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2pgalyddw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnbxwyx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jinvonom.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzzhxue.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zksipejf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhljipge.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpmsdmc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbnvlno.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jseattsl.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dguhqjga.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2kepovvzu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvezgjd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwiyyej.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndntmhiy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2abompsfe.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgxyqjn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2omnohzdd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqonmfz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2otftbxyt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakgjclp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2elrzzdqe.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2adudwrvh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2czpnbhje.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuwkxwu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2izevjkuw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftigfsbt.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgbrtvz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvkxxqb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaysvkf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uinrmpyd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jldgcqao.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwxjqwd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwlydtd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fzckbeks.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqmbrqj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lysrhome.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvknxti.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2razufsat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyortrla.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcdyibv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klfrsljl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfglvfa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaarevn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kidngzxa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucljeunv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbhyphv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjhnwbz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfstfpr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gorqncnm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gumpzmyt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2whfjpaln.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mupdkuxy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2geyhacnz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtahfet.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fletrept.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshfzbrr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oabjbyou.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzkneid.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcjyeue.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kymooifk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2phmcxtbm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyoglsn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjgscoq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2asdnoyxk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmspnb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lgotebas.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzsezip.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yegeiwbu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdkeekg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuoqher.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dopreqth.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbfszey.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqatrof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmgeeaw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2foglyjze.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2azslqztu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbboxla.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2seiksmfz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhdyvsv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtnidbj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrtegko.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhdoubw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofictdok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2omqozvyo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizkgdoc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwxmzwi.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fknqdygr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhjwyuv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yspdawvc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nulpicjr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2upjmdzkv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjfyojy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dhopkcln.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2grndvyhh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfcvjcw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcsuszb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2yytldszp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2imwwwcyp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpogmcjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhgdlgy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2monihxvr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqgzeky.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgbdgkm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpademm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2thimjmai.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eazlssxl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzdrthl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlravmy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2njeaktbr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyvnlfo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2augyqhmr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrrryvp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnctpzn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eejrcbdr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpneymh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdmcroe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2khaxcyuf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkzpvan.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqequty.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnquvgx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pitcptqk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2makgyvdi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtndtug.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaoptis.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcejxqy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dalstuxs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vihymsah.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrxvjwu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiphuxwj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2emzusush.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvonfvk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2faqpppsx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2relkdepx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2myxonzix.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgbgxng.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqbauiu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzekviu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sikdniwg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mxspngqo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eduzylrh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlcabxu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2odsfsend.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxqqsxq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjbbiiv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkwokha.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdgakxl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjtjahd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2desqsyas.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsrjpmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfxlkkp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjeerjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrturnr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2moybgmcb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvxwsco.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2frfvercf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xygegimo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2avwnztmf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2opcvindr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdvepwy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrbwzvv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtsvosa.html


<!-- 参考信息 -->