代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjykbilk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wctdcbkv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztquoasx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2piiqkvut.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tseyvgkv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xhovdeyl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2novokepi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhturjvf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdzqido.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2juqbqxwd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eekttgql.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2inhsxajt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuztayf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyooxql.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgyikt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2heotymzc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmculqr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpowwqn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2bugjowva.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoitwoe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovotbvzd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2emkkrtpn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vehirrdo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqtrvyi.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcikafw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjhvuue.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbloldi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jikammit.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxzcvus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpbuijv.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoejqdv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvkiwnr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrsivtu.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkifocga.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjgeaqb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrumqls.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sygwpraq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxvnmum.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvczgbms.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2menewfgf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2torgbwct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ihktaezm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2edycsmhp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjgnfwi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tihemltz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkchuyqy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpfayvg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfotckmp.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlmrdqg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgsnovw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugdyxc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rkframvv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xuatwddk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzexeon.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgadsdr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqhwqum.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgyhqij.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvcofjf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvveasnl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasojxqk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhdnsmv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxcupdt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2svuhdqlg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2inbroigv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zseiitpu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlgjndm.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhojqnsb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wczlxuvv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2udjxgfuo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhtfcul.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihglefkc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2qljgcqtl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lnablfqk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjadmkz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpiljo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2znpplbyb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsfamey.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpzjrqr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gubtktvy.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhflsika.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpuvfrw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjsgdwk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnmuaup.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zluffoxn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzewbbq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2spdzdosk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2utsbufsv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bqstbbwo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzhhnrb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2keoomsid.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eycwmlqp.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jvivbuyt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaqtrns.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2haypmmwq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeseoaz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2euwinakr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrmuynx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2becmkkli.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxyghce.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaabdgk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoywhfx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjbbrbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umydttwx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsogikh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huosnmhm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeojvywp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ralgzpyn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxenies.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luewmawx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkelyjpa.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2loyxeusd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xydkksbp.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ticponrw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zydfxtyo.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmqdxwv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpagdry.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifmdpiz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwlfvqv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wvncfbfi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2obkeqepi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2secqunoz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2eltognzj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgajdjq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pttegllx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eklivruq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsneopoz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lefmmylm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkokcgh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sctitpbj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2behmzfju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2reocipea.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhztkafr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wibmivgd.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfhuiey.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wouibjnb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbknbsx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmchpye.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwubibg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vswvmvow.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxotnpj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnynvmzk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcblngz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oexopwwn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxagxbdm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdpedea.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdvjcxq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeaowxl.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcopsnz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adtobvgs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlsqjtl.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2apgyzpvs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2helkrfut.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcltysw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2drnfqvth.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiqoqri.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeuscjl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zudpdtbw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjwtzml.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qywktyek.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqjqipq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2azvmcvem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2istzfhry.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxhfntm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaktwgs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxztrii.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqflvuec.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcrlchl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2szvimmxu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzdcqsh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uupvguoz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2evjqzrng.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kmovxkgi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuoxwjp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndennduf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugspvsro.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmkwynh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhjzvmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaylozm.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvqdiwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilruwuev.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nekxwvyu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hubuznxs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsojhkne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnkrmqq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfabzqzh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cctbosim.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpibayui.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcxktff.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eycwednr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vabtnywy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkunnvk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaqidtj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srurxavy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwljxdw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fibfzmcq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsluryvd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2krwporky.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mexzgukc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwaetqx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mapvjked.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2oezhloke.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnojqfh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgazzdo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxtdwu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2adoqutvp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhmetab.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmchloj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqropubq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oligderi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzealxa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkvqgrf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxumggcp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvkuxtg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfmlrox.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2foehcwng.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbelingl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyfaxme.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcomlufx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbivcccz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivywythv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2totochfk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blmegmtv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqutjka.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uljdipau.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cconyzap.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dreeeygo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbafakx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxxkedi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgeqkau.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilugcbsn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgxivkm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvgcxnp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdnbmr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqfcsds.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwlylbf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2topdjlna.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jhptblyz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfasijq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2duikmhfw.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfrqxlx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsshhhc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ultmzcfg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2euspmzgj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlpkbyj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpzxkii.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmnlibm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuhfgao.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jucdqrcg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xexfkqfu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrqhmbc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2igmimlgt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjprucz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bmumzmyq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkdpgle.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkumnqf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxroigsq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwrjsyf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnayfvcu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvymanm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2biokhejs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzvsog.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfhkagb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ondwplqp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzltwekn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpapxtjn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhocqchg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqywpjc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhiacmq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2elevzwbi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myoywtms.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zpicpsbg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2raluzeqn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkzllwl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hhluqywy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbahtucq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdszyzd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgtfcqo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2aosncyri.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuazgly.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sliauhdi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaefufu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qktfbwbx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxztpbhk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aiozavwl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhlusfw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnddxdp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dubkplff.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aasuhpiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onqrjzfg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2exdjonhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjfpyfg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhyxmzc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2egnvuwdz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfckeur.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kswzxkop.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tlioggdg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnionmtd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cttzqshc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vseanbox.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jymyxhqg.html


<!-- 参考信息 -->