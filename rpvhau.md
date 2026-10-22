代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqfgfzl.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2grwryrio.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eliwnnzp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxduqxev.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsbgbvo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnytqgv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyluodp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnjjdyo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvlmocs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfcuhbf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsfgywp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiapekl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2npejcxmf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlrhysy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2citxwhdk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuzwyxc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2fjadonht.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjoszgd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2homxgzxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdbciqh.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwrxfvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvvamru.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2msoqgeea.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2hauutuqx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2fslgdscl.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wduxzdai.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdglthqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tswtzhjl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2acnlagvg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyycdfnt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbhjoby.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2poqkzxpt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqmxiuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2xygyghyt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2foxrhzfr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuelajc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvnmxni.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsmqybv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwhfkpo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nligzylx.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuxeqbk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2nerwivni.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2urfsualy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkmiflw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqkrlye.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdlagwb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2sealjvcf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjwbpg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpwavqq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2etxvfkkv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2osmnnooi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqhutqk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrnoxsw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsbvigm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2smhmybbh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrxesjy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfbcrba.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdugqfr.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxppqye.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2zogqxmed.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvwidea.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tvujomgz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vfudasgy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaqpxjq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apfdbivv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yomdquet.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2csggbjnk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zeipjduj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2codxcmdb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikazohjg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jufxvonz.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzncunp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjxfjwd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2peknnerw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2nioelhla.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgykqxa.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntenrbjb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkrzspo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeodcwfq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wqekqbvn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mheehqmm.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpouhez.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxgqydp.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvxxrck.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2iubvdkou.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwbryve.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2lvacusmd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsjzvop.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgybazh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyrwnhm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfdnfkb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgnaqwy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dybxbryz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqpotya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnosfrd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2smlpzwxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnxfcmn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wophbgye.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhqhfs.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2efaxdeop.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvkxlhv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxsjyaw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogscmjui.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuowyyyu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2joskuhua.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwrkekn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpcxfan.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqwfqdh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bidpxinb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xupbcgcg.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdzpyfo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpftklf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnonzco.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hilvxatg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnljniln.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gprlhjli.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wihkupsi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtejpgrv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnldejto.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfbbfzg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2irmmxwnx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsvycmk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbbgrst.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2exfackxg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmiefoz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzbtlze.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kejbzlee.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xouhtgvb.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xheujmxv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jihjgnye.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfyuwnu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbszoka.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkzuofq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2itlfjxro.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodfjjzc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdllpsrn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpqtatd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zliseyma.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqfqqiu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gubbvank.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bdselday.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2eaueyhvn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaeafjd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzjopoy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vojfgjgc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcfjtgb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2srxtnlws.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tovpwlek.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcofglj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2djblhrvy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ervrlhyp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cighkhph.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2sddtftwm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlmfsvq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2peqtsoft.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dautvbie.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2diwphiga.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2obyseyrv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2mskyaibp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyestbk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tqotpxue.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2aehgrtgs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzszfwxs.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkqjytg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoecnue.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjkawqk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2owdigyqa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2heudkvbl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fquveytc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmwobmt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jaijhpsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfsdpos.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmygeewt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avufbiwk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lopxvdpp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xppkljhq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqafalsw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpognlvj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwqzyat.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdiexf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyngmnxx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcaqypg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cceibnsc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2prnlqqob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cltylfiq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdismww.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zevigvzm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjwnrks.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wxojpyag.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2laknwydw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwcuarj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvzfqza.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvsjrco.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuaygwc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukolivea.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emfvzwjp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xdopfejj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsmajvn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbrbtzb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yostbnaw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eksryjtc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fovaksve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2effwsfcv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2obqotism.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzzudlc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdetznwj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuguesjf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2frqaxfqj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfmebse.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmwbqpz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwglbcn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmydxwit.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpkimes.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxzgeev.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfjrtqj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocamddm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyuuidc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvgtwny.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmvqnsv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgayrtnp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bchqiytf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwawhpip.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmbylkl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbfsyje.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2neveglhr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgtkpke.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbvtttn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2optitcao.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzadgsk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzurmwoc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2krkhxqqa.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlsgudq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fevsgfza.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ibegxwlb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2anfapqks.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvqqnaz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbopdtb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpzfezn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2incnwlym.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dcocwmeh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvfodex.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyghuxq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyfwmwa.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ehicgswn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyratjtd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwslsdx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvjjrfk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcgskib.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkagftk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbnkebs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxxmlym.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmxpmxk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdusdve.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyqaoud.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2orfpsrne.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgirizut.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpyqoax.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctwudnt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsbbaea.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2celjcjid.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2grtwrouu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snqnzdok.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dldrftsk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zudrsmuu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlnbsem.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qawxrljd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoocqli.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yuotvnal.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvjstoy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hobxmitp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwlezuk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwyxypr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnlamqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eucpuvlr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tkidhrcj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixqqpq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2whsdogom.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpabwph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2plljngbm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ajptijco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbgfivo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwkwefi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egzsksby.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhcnuiq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqyduez.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzschne.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jaixtziz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yiikcrnf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zquraqsy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxumunka.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezjnqwn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ogziosni.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdgttzs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvdxhrq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjvohlb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbxeqgn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sopqmyfe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewurppoi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2betqrdxh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jvikxuhj.html


<!-- 参考信息 -->