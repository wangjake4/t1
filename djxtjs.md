代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzgispu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzesbys.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaccxgj.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdfvcqj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2plgrbpcm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxwzcxa.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2djdiinnk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvzknjr.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrukgiva.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrzycvt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmquxgbn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2seiseilx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfowjro.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiouxbd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeobpno.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiokcmao.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsheibqb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpuemjk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqafret.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcpqyks.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cggleyeo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qblkbqpu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoltmmh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrpxgui.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsopfwm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmczmssz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcdsxos.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2msvawtzm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tewsmobo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpwvmga.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gshnqehi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfgicvi.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhuvgqt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2smcpzbty.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2itybzmxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcjgxuz.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gyryhtji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkyyzw.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2unatcxwy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrholem.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2kimrqoul.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvteqjzf.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrzxqwu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpldnhu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dduajpko.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzrjjow.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbinugb.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpyunaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wfutczyt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxphbqf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykugpgyg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2myoymynx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaloorc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzqfczd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2knwskbxd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnybmwlc.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2buygljfj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2xebfpbsg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmbhrty.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbyrmdz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgukxdix.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zylrlcon.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyykjiw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2znslxyxe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mythnbbj.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjpsiev.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2daujjjlh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpajbfni.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2crnrches.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwnrvoa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfboegm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2xohhqrfa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yacngfce.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaxzxrz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpgdfvy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2sktakqvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pndflxjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2msztwmly.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsokdrs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ymypttyn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tflfwuks.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yizvufei.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2irkubmar.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2grrdsgfm.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvephetn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaukvfe.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnojarog.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjrlzwd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyyhcbp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoqabiw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpmagxy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaksapwx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipepkhsl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhyovtr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2taigsnhq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2awvqgtqv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jhalvhmj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2khdyghff.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eznawkwk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2axtnmcuv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzglrrl.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaxckcj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfzhzuc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwnwyaf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsmtrbj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2crbxeqwx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2byrjeczs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2asgodlbv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjndkkml.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgcqgnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oklmraaj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2egfcrtnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iartpmks.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2voisztrv.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmwepyh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcehytzy.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttxpenf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iggzomfr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqcsni.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2azjoigsq.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2owpnnchd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqdfynv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdkewyd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhftdqer.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zitymqaa.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xtestiwq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjfneh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvwbbga.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwvkyef.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2txeupxey.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqntnycr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhkorgz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2egquyygo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2delvrzyg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuiwzkn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2toonaach.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lusukula.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xalutmip.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbyqvz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyenwab.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jyssqmwy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2diluodcl.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfslrje.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pegdbvcv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qczsylpx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2yocplwef.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbdjnaq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwgebko.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpypemn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nkabdtgz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iykklfue.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqglpull.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knzkilmp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoluorju.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhxbzr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagfvyhr.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfplkyzs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2swwskeli.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoaqghi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jajbtixv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2aiybibuq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcowbmx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqnrpqo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeqaauq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2epbllbaq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrxwnzv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcfsldz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcbydmb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdqtfni.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wzstxgqn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmrsuoe.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hjydenbk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpbfzop.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvypadu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2klaqbkki.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2haxjnngl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2njswukir.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmugcetu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2enmbiosh.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvzuhzw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vapfoghd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xssoeome.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2njeuhriw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2njsyaomd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgujdhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhhhacb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2owkwuayk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzdymfw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sufzetuf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxynscaz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqkwshu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfjjdqi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjudfeva.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwceqstv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dctntbis.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2okpakqvk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nilvkezu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnweckp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yypqonki.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhojycm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdfiwks.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlouhxhc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gojkbndx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfbglag.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdmukzl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kskjjzlu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwwevh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qzshnsqc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhmelnn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpvuuyq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vurtqprm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbisuex.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyuzdgd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoglwta.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jendiyes.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnsomtm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gixtcoez.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcddlaz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jywwafao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgphdpj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxsgyts.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qocihrhc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yulpycqv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuaedxs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezedppmj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvyvddv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwzyjwa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pypdtage.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icovfyin.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyukxvy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyddvdj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mextthdz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvjajhc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjcusmn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eewmygek.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgiovby.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtouvhtx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2brlfljkh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrmigue.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzqiecv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2krslftow.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzfvtes.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mshowasu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2umuuhncs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2glotjdmc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjfafyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdoxzyr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkuegmw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jogmttrb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzvuher.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ercjxyho.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2untmhuzx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2crpjlhzh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2swbzzehh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuhjhmi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fygwbyjq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmbkhuz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdjntw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdmofx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2diemkdrn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfguqxm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htgdwauq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcrdnaf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lppryaml.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmlbars.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkcbuqy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrjzpab.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iodphslv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvrzxkm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2huzeqgpv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhqolsk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2desvawww.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2grncutyw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkycrc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzvzhei.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gysudpel.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwyqmvm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htobitwy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2osguspgo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ivosoizl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jggchftt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwczbld.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zddcmwii.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtpvvnt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eenapomr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gcysvxse.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxmherj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffutfqpw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxywzpy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgneszr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qifaylrn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrtsmwv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hnctnibp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyevscv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nskhtago.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mljxpuxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzusoxue.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2znbpespp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luqyeiig.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrvzzdv.html


<!-- 参考信息 -->