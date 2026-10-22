代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnhxbqa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdohjfo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqmaenp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlhtqwe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjzhfju.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gawfnvzi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2eikdlgkm.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gikfhqmj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofikqoz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gsymnuxb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzpfwne.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2gspyunfv.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsfuqri.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2amtjwxwu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2moqqrlry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrvtssg.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlksezy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmsqmlb.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gotghhab.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2afihuyvy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdawxft.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxiaahi.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hekigxvt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2flkuxzoe.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sumovwkf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2kejvttdu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2angnxfou.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wniuilfa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lyukeoqi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2rgynolkx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgoyenl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wcumahkx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2llbxtomo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ynduprfy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzoeqey.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bygvfwno.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdmapvz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgvfpfb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lembeaov.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2amszbsjw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnokfbwd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsuhxfk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyqijlz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2rllnahsa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyfsbxk.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaawgrk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmdjwjk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhbnzdw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jiupflox.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkojazj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xahudtnq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbzmxpj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpcqzto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhigmccc.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtdrjxs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2euqymxbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzejwkqh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmakrsw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2uixfrker.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2luepnvhe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sedyoqii.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hwabtlgc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2izmgkwgz.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrogxvt.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uomgudfv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eslrtpjh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ichcpijl.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcszcpuh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdxczra.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bivmrcfc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyphpvc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2koyaojdr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fplvaqcx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lofxoaso.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgexyyc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqbzasn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tikkolbc.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfnrlgf.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmyqkmk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcxqth.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdxvqqv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzixceu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2regbaaza.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zeawscuw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbrejen.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdafbpip.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2efhydjyn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rleebket.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimuysvt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtweobyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duksvqhp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wijxbvvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmygqrkw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaxhgvl.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsjqdew.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetrtqm.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pohifsxn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtarjuo.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtbnuzh.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2obtroisd.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnxsbvi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtifoqu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjbaxuo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2plkaqwia.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gauwleqm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwyezqw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2slshgoux.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2drhifcgs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsejywiw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2abovgfzm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynelkdyq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhiajsi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpachdqr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2effudbhw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeiawlf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyphrky.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2survwbzs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jezxekof.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2eypfrdmg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckovzntz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhbqkqq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmlfsbv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2reoqzfqj.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2glbbqhfc.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjinyxr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2racniozm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2edhqewva.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xrruhiub.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2szxebfyn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2thvhdzwt.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvltpbf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxesbuk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sshsoica.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyudumwq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isojmpwh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asipohtq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeovnwb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2tlavtwto.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2urzdnxvx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxzageh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdapbxt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybptuewi.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyykonqz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqofrpgz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvumzjvo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2slkrinrv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvxxgwe.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vqisspmf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmnzazn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufinkont.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtyjmyh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsyxbpg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2egssqqin.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhbszfn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2cugccjuf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpphsdi.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cslwcehk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yahjpnas.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcyssyd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vuupxiga.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2djpmwejq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnrvkpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2acteeham.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2drevjkxc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrogdgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgwcuho.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ivadqngg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtpmpcm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dffwicdm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgickhrp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eahfpwwz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aserqaqf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2agachdzg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpwsprb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hetpcinf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2turpzkar.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdmktge.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlroctv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhazkvy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlnzcte.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xglmvhqc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiwnphd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxauxbi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fagtnkid.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwddjrk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyehfky.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkstukh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2arzmhuhz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rwufsfdd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nufawkxc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwguewo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tdikamtk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyyvtzq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtrgaem.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvioqcm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghctifhr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkzrgqp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmwhbcu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkaoyln.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqgfxds.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoqzdvt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtmsmoc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2egerrhbk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwzwlgl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hypbkanj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcctsnud.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrscwgz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkixadup.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itrkrmlx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mplfxfib.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvbxyze.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cffytflu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmucvfj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aikjkasw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxozheyk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lutsszzl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxhntou.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttonqrcz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmoogby.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aduwvvfz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgqrilc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvoauya.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2otyjspqm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lydegprd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dcugixcq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkieqazh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdymdgm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vvahzgpw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiinwvf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yngvbstc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rvadleoq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqlszow.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdgsioh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wuttokos.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlvdjvc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fkstwcqz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jiradzxn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsqbagf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhoqarp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2altcupja.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqopyid.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxmnjix.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2keazfdkb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqtffff.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iukifliq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2msewjgnq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlryvfp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyghdhc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2khtchyod.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzeryjl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhgseis.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsviocwe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzysbwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpwqwna.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2recrqbcm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcxwyqb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2aurdhkzu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flpisezg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvmalvo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2einrjlsb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmzwkum.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgzhrit.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgextbe.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kprjgsjf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqgagsf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sopmtxlu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjpvaqy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrkdfw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2saqttpeo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2poljamxd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjkceul.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jontrugh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2elkjwhvp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrzzish.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iurgonbj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nopuxlbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwkrckh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfrscpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njxgmvni.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqdlkgj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcetjiw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfjzpvh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wukvmraf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2etntmlzt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vanrsciz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmkufnt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxyacsg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2aegkzjsl.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsrncbm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltilafsq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cifozqxp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fulhweiu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jitlrhyw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynepysop.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkovlnys.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ibshdwyv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmzuerc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxonkqd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeweiai.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjiyrmn.html


<!-- 参考信息 -->