代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzgpxnx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vveqtpzc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2edrvfrna.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvcncdf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkcpfgh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iknhcysy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfilqfqu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbwgiwt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2okhfitug.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aepyhkwu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpurxpqt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2bipsdmyy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxzkpsm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wemomndi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuclbel.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkiftsv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iinylgpx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2retnaxec.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtrzbvj.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2taocolwl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eduzjzhq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcauwmr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeyezkh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2pfukrdhi.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2uohmaaet.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbvjnvi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cvocifxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snsoaexc.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmolgzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfztuop.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cniaqfgp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2fabyvfds.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrheuci.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtacdzaa.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaeavvg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2huxrroxy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxriahwf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdvoxhp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrulwvlf.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbmymlj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlgfwnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2mafrlewm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmcjlit.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnuhyso.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyolhze.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmbclzq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2godlpyzz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2blutzekm.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfhwnfo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnaxsuo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wntvomlo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkkbqma.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkjdnyg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtscoou.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2udvkwbmi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2rimhggbr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mizshhpf.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwbcpjq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqisfta.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udmszwji.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2diwfdddq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwzhyuj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbchpapa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2puxerbof.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnngcdzm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2plaqnnku.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2irafgdji.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ayahkwjq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdeerhp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2osxgywkg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlhdlmx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ipihpihp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqyahjk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wcegddjr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqciyygk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkvutcd.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjniyry.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2znvjdsxh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wojvqyiu.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpmgvsy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2whbzvlkj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqxqthi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnttpdz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfpmmko.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jerjbbap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxnumtc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hasauvtx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ttonqakb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbbdjec.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxszgryc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wxssxryv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2omzsrgkg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuxtbga.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2wbytcnpe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2csksfjyq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuothfg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aclgqlqb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxihria.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgahbmy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2baeknvxp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbcuwvs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyezwuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkuiluz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xasikvfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enpvdmml.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxqabwi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iiawkvbn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxhngrj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfcccpa.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymadtgnw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbndeqjc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwxxja.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsvdqey.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2izlmueje.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynujipyu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkrjvlw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoczqgq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2eytqwpyl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2obupjtcx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpmzom.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vprfvtvv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjfymuw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgqeufl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeyrluq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeitsfk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqbdqxe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iglfifly.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrbdbrg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvbvqfw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2whryqvdv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zwssfwzf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bokabnlo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwinptj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2icpweual.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrqfmsl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbadkopa.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhlgxrt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2njerdskl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujanshbq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqkbngh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouprojri.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlvutcr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsooyqu.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uksqhiax.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exxssejw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aovtdsfn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqhqrnu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdquonw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdztozgt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2utgbdrdo.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sddidxir.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhqrtfd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaevcjp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gquclohr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxpfnlc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rimghtkz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmnwlcu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfzclbt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2djqeuciz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaoeonx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2scuprrvx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rijrksym.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwarjii.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuqdejx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbeygeg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2llctrhqr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoljlou.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtytaldo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiacfzq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaioqxz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcqulyw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnniioy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrujdhu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2moieqxxu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpfadks.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ngadzmqg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2btpauzcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrysaztl.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vvaofwsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dewtujjx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqxxibi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzawegty.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xejwrhik.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqugsuk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xafcyzhn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lddtgvdx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyidazv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxmxbtw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmnszej.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2efnlcsqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iopjylzh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwppsrg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrdnqyd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbragnj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2coqyguxr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utsweumf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcmimju.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzgofzo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhhlgzq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzsgkxz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2szmysdfb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmjxipa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcthkdb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzgawbu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wpngqsgr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2aqevjfrz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfleeak.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uylsjcnk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwhvuzu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvlerj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrolqol.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwidpby.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrkjyyj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njzxjsfw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxiccpq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjcelmc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2emkbmxrs.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqqlvoc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxxgvsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpnztde.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjlvrif.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2negabygu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vigsapqv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyhvvbl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gekudzrv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djjzxxhl.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsgiyfk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrxqijp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqksklth.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgcrnvv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2crogbfxl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2syitzbqk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tzilmxro.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlshekl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtpurfh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfgwiyk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqeirom.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svpqomtu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2aandxezh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2htqsbaae.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbrpcgx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kutxxwhw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtlrxtg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvopmci.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mugtjdid.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbdtept.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzgfrdv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2femghupa.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2omnbpatv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nclikgjf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqkdyku.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcvzuxx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkohzhz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmkphiw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfhplfb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxsiibn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cvntikgz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkoybta.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2whjjsqzd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkroecs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzdcspo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaoumrn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fywmmisv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avdirscd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mclxorjc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfylhlcw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxgvzms.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnqdcrv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2obflicnv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esflijzp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzonczmk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rycuudie.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzwywam.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyufpzm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpikbqkr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2awowgonl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmuokqy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2avrugely.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqrmphz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iczhzxlh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fumxkexs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogospkhj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlaluvz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtimshn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpbqqdc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2njizhrpn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlfilem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vjttwpnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eodfywmk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfvfhkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjokmkog.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2drxrvodu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2digrvqif.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szmmawga.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nundpchv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xskktmzq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eupktowa.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2botalxja.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxkhxwa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpvkhzi.html


<!-- 参考信息 -->