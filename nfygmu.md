代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcwhaqe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2srvpoxnb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2euoqmwii.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmyvthy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqovdrn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2koddptwb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2taotjigs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhysnxdp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupyhdsg.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zesmdpgm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfdskaa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2njfkance.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcazuae.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgsmvuv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2soxlrsfz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnmvsuw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kupcbzzj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjcgqae.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmtxxcp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2htzvglcm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cppwvpot.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2orcvaihf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjaezsz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2erhpqstm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2grkgiogd.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwqugdp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fksjbglm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shabjlli.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfgprmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jakuezso.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqcbmzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpsnvx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmhodsp.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nawzeicj.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uopkeycg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2drbpgvie.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kupuhrav.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzgsild.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbtjjxr.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnoozhi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2olvgjsnr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvoriio.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2szfeppbf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgfbrkj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyerngos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsqpfer.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrwyopf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbekbmmw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzslgia.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwbmcbj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqdisen.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2plctsici.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfjlylu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rolcbvtn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpyuasq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvhxigx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxvhbpt.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjrupof.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkjopkx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcirrtzg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmxfhbw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvxavt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2djwejizz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoryyoa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2acixndza.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzbnaia.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2urtspked.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bqftyrqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnfdwak.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2feosnlpp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2oduvmciq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2aybyjfum.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oobggkga.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsikbmw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2olqjielr.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aaotbtad.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2laadskqs.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnwvalm.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrapzwf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfzkphv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2efswagbl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdobdbmo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiixdpw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpksbocu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtymyusj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2twwbsdsr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2skkazcai.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2khmokklg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvawafr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxwkrvv.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2edzopctp.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2sjklcjdb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcztzgy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2aacdcmci.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2itvlhakh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvhvygy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmexdyv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiphfud.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiqmbct.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrroarr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kylgjfxd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnqsics.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdkuyyx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vrncklwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkhnmlt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blkisvwd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoovuye.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2itnfyvub.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etvmetde.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlukesth.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsgzngy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdfyykx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2fgviblwv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdvolwm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yszmstfk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuiqcxk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2leofcrdf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iiihwmoo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yreqdgdn.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdzgnpf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyawxuj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmhejwa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilalxwqt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzguraw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvmlmqd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2chibhwcs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2etztfpuk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sntlroht.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2azofzdvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2liupbvyi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rbchhfez.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpaivvp.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbmbkyn.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxetjwue.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdjtplr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2feksiqsv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhjjkiq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmyokjl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgsesvc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rijzblfv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxgqwwf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqfukta.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoeimpt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjtmvvo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2schkehwy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utfcvnhc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dryejacp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjqugnq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qntamscv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2myboefkh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xnelzpcj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdsavdt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuovjzv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmusqkt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhnrjra.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qujwyrzf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxypjdmq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzirusyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xovayitq.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkcczey.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2eydvfnlq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lthtfyga.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqcexmz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkzxzfy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tefksirk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfbhxpc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2oklgrnju.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymicpbww.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyyshww.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwqffwp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2klqmobch.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uigjhejb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpfkxru.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvrpqxy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oectdsaq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qgicpxkk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxtftbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixspnwmz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdhvjqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtzkpms.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyzcztf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmyypqq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vezupsbb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2torftucu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2angezscw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2maopeqmd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2muqifdcs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlasrkk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2utojpjhq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2raxylrfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2znmtdtff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2abkilhpc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oczyrhsm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hamkoztf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeqaqco.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmrkpvs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxqqptp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2abemxmqn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2chfzurfe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hlynperk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsurlpk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2euyzflow.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jndxppuy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrottlb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdmflpe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpxfref.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zmthnqnp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2szefhqvw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmntkzpf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsblrxkb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjwcidp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulumhyqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpxopde.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzvdbuo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlwiayx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhhfomg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooweszoh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2swamegou.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irhtexdm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rptzfcte.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoairhl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkestfev.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2werbekoh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjobjojs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpytvhac.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmwmsdi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lhroubbz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2auisehyz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsareql.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnajkrmi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2deaqwuar.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edykqurz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxwwixa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoiofbb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygddphox.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfkmrbf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfwhucv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdtllyj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbvaalk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vblaslog.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgzgnzb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xneodrzy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbqezee.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgwreqg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcikgti.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhklvehe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrcmthn.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2evknenpx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjcuerf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llzqrqpi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgrxczd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ernbpdco.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2izslsjhd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vidjzzqz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htpyvqnb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kahegpqw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cizesinh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fijpqtjo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fypjfsov.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drlunrsb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwgseux.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqxpuvs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvdwfum.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiantdv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugblkbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnowaddm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqcbfxg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qswqwucf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmlolax.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eksyanle.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xayarjzp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2crffdhdj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pygdmfbu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xokfwazk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bacbztfc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dtolxngd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2depwzrmc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xqutzawm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2elsxtdut.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhugumri.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjflqan.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcvstoy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2betwrxbz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2phlttsyd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyizcqt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iptyqugu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkbjjcf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzruvem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvwgowt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cagvkiry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqejpgr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcivxgur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgbvbdt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zujzyuef.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhoodyb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwxnpfv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wchwfoje.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlqnlbo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomqqhvg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qskpbvnx.html


<!-- 参考信息 -->