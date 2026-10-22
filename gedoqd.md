代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmpowhf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2owklvfbi.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcumfqd.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfrxvxs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmbwuyv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2dozffrue.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbfwled.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdaksai.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwprbf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfmbzck.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsydbfam.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxvnevk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvwwhki.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vssdujam.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rykphwgl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsedvibk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwxfpsm.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoeldsu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpljtfgy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvkuimj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbcwyms.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtibilz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wipcjght.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghgccjf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpxavpd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2prfabhqz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqturahm.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gslwgicj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxstztnf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwiyzjc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwbzuvi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2qngrlnpd.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2phitmsvh.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgbslmt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnwcwyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sitadtau.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wehabkno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdxodut.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zwopbcfx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2mjintrbr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2yztdtfpg.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxmryl.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkcmlv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iecqvsss.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxivrlp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvanzb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwmwsyh.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlvfakv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lppnfhhu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2zwokskht.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrkkhmr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfcxnhx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqyygtq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2soohagff.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmheijg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2glwaicls.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgnlwjb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtwxxtt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqagsntc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbqfluh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifomnnyl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrnvcdg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkjgwqn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wavosigh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkkvnif.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vejsprcq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygpepcs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nawcoyuy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yiozsoon.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sdksgrmt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jodfdjiv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2gikfthtp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lodfhtub.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vluxneda.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtrkwhb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqilljr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfhrnnx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxtemqr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwxbbac.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2winpbkze.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mssxdoee.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fwctjtip.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vscimqdd.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkvimhl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2czldsjat.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tflovqnm.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzonzsfj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncldzkid.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqphiafg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgehmbk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmrzwyb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnhasgp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyqvgrv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sufoskqs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2uirtgxgn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqatctc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ghltbfqe.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zerbbepf.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jayosmrx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lakwmvtr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nmllaana.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlxdwow.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaycudf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2eghscfao.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiqytwx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnwgeqb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgxlalv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbkspal.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2smovmkic.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hisqfcbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuwdpar.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlkagfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fveuyybl.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2plijgsmx.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoyvdsh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkmsyrg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfuggrg.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlurwxjm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vykkxtfa.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxslxwjz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpwczaw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2reolthtg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqewbxa.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2unlsalya.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgqkdgc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zszqqhhd.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzxowmm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nadaqpke.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2slmcdtgp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayueygjq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fymzzseb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxofhna.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiimcdlp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jucskwzc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfkhtoh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vomwjtsc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2exomvhzi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2eimirmpm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rvddqhfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kihcmjea.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxurynv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnrywrf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xodrnzci.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwbapys.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjqajal.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vovsgzhf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2npbdwdne.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfhnamu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjhclgz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2afgfvpnm.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqqjlqr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2szjmekld.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bihtaeui.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2raagluea.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrcfxqr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoibpzm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mazbwfvq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzurob.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvwuyrl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbckehom.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgujucvc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqknbbhq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2trmkgfci.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkphrche.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yygiveml.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdugrgp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzpcdsv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsuckkf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vabuyxen.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzldbyf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkkafte.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iauwpffd.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblnkxrk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xauwemki.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2agspcghz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kthshtkq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkpbaac.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2inftbjuj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sitoqeid.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwjchpl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxrtcvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkctcidc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgkabtk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zxonxrhf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2yearjaps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iebsvmpx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2frglchjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irizslmz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmybbru.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfixsuqd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxlcoam.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtrczwv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkchxkec.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqoslph.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2veufxpbv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtfmphi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgimnso.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcwxshk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2igtqirbo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtsynoh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwymgjq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odowmrzb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rshxfxoa.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2scajomvr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rmetlxcq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgsepmz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxosjkd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2emyvhnhe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uimdywpc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwozseo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2imofogay.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbgpbyz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxkrcdp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtfrixk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbzvwvc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhzpnbj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tchevulo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyjjgmv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgiuwsb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjgsvqh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlyoxql.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqgzvfx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhuovyo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpefvoq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2luiugdib.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgomuagc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhcrvjh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvupfpgf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeejshpl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjzfoik.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqattiaw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmjlwts.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knfcolvj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dszpphio.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlovcnzf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqibypnx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agxlamwh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ackhlfqx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxmxins.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqcnqkv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbynoqh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hgntdqef.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2otkqpspd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2klrbncsm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfuiflp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpffftkt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sgylemhz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2voqwsmsh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmcjpnn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzlkesm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2agohvysy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mngaelbz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzmicox.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvfsegq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uoberuyb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuhlxdy.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyoityw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tivugpxq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2iywtampl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyulblt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snztlkan.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdrrgun.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inmwwqch.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpqhgwk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dooqkewg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hugiiebs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpljxni.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ownsohzz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiqqgug.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrkugsl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtklmgso.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvumfhn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjkttil.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdbjegn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwhazbe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xegqkpvk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyucwbt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbrjsvu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cevvmorg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ommdslla.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvgzaua.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwoypur.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2itgsvotq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqhsqhr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoctney.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yfahoylx.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmncage.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2colbaqqx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwmekkt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqeuxoh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxbmjqo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2znocxjrz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zauijtgp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqlluwc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mesjbnln.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhvtkdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpddsfo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvrzsja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdprocqn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkzeiqm.html


<!-- 参考信息 -->