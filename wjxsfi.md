代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyshxsq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2abvwnhzp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtjvhux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcurbun.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rveaqmxa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2imkwqksz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwmtuzu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsobsuhv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvuytqm.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwsyoib.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fasrzynm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2tponbevc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlxzyue.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkvhhqt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbmabxj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2etdbsxwd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcxqbgf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgslrkpo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoexugf.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmockazi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwsuzoz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ospoxqdq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xmferdbk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzngqjw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2snxinrdc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2whychqrv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkegaxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaxkzae.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xeomtkqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlydvtp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uyenvtan.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwwbtab.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2zebfbtug.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgszjse.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqewphf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2riszvquv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2poawftuo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2puyhzbpk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiytfnd.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbnolld.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2icoryqkp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcjmprz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjddggxt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2shrtzkwu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhopudxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcreqnis.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwmaiqy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrtijgo.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwxfedj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiwihpx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vierhlqz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzlvbnv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsnzmng.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgclyit.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2djrykzxa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvassolu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjisbyos.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkelfvj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2syomtvaf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqbqyxh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hgagstce.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzkykbk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoxvutw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbivmlr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ethmrayy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlbedsf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjuzftj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2munlvrwt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpisuxh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvpxtdh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2odnctzzu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2knlrgrfa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvungtng.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jivwzzuy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2efcnawsl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wubpndis.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhziwjc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsssnehk.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoalvex.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2swlyeyzm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqnihdk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjninpxr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrvlgwj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwptfoe.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2maywqbrr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwudflja.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnjmhrb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqrkhxv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvkfasd.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaanhetr.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfavdnl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2iigafkwe.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcqracp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvwziru.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fabjlxvt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjoxkrc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2auougoii.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcrkytw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ccicmmyp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvcpaxr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbwwqaj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lowsncja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eejgirsy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeurjxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzlpwxr.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fltkfdve.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnmqfrl.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftirbyfd.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwormnp.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svxllixi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jejugorg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdarkals.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunnckx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nckphzaf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlektezd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uijobmug.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiyixeo.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyokqsb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iakogyyd.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgynmppj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeavcjd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuksixz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzmtqbr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2smjvtowh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zprtyacs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqjhhcy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrrbki.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2laiacwps.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pklexsit.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlmptun.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rukwuxtm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcsdwqo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2poymsczx.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkdjxfe.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bocttpcl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaqnkal.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgjjdjx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwjbiqb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2devpjeav.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtgpqbb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdgymqt.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfocnax.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfzkdju.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whqiilgi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sceusvdr.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpuzvap.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfqwkmy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adfxxylp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkngaqs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2narvrqog.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcnybje.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2liqxlvfq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2sldjgnys.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqtxmlj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrqryrr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkagpmyq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngukzhbx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgoovoz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhdyjlz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnkqmgp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pizpvgad.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uksgxrkb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdyibqs.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjgowjl.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkiluwf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lljfwaze.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2egawsqcq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wremoemr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiaymxg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjshcrt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdsrknz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2efgaxxyf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lntuzdub.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jttrnvea.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2elhyxiso.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zenzxizb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nreqbhcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkvvoyq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2unsgiplb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pckbncjs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jktyuuen.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iahundse.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojroyhks.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2icoyfzyr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kovwpevk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcmnlwr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpqubkx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkvidqa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbkqtum.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnwocki.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfconcf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2crvoxzda.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfffgzmc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vifyrthu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjulltzb.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bonatgvj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2agejbbuu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzqjlwx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkglwkr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ietqkuuz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfgcasi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qkukgjmv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuhsokq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2txppdyik.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeqpsei.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2usakxeli.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqpzurp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dufkjiux.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnipvogv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwcxrfr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2babkxotd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2avzqqrfn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxucagle.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoabfzw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbwzuoo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyajrgq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvanado.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwukvhgl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukomvrat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgdbabz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdpzbxv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fictxtrf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tedlrcol.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dklrexsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glflkdjn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbseelf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjkpzvw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdibffa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmcvamo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgnihvo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuyuygr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmeaaol.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2niurakzg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ozranoke.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgggebi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zyltcimj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wldgpaed.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjiysuf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ameeoqro.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfjzocx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeoqhom.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xcggjvmw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nkegzlnd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2snagqkzf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dffljrvp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xispkihr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gedldzqb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tladkkjv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjqipoe.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgqoino.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvtqusq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtayfzd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjtucbx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdirofjs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyjlbbv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2liosjtvs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uptjmpav.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jblhnthq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlgunuy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyogsfkm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbhkirt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhmhkid.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmgcgmh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuejggm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthlpwaf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ergrvfji.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pysxhusz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmhvpai.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2exycxmxn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjivmhug.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lrptybol.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2spqfmdvr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbdhpwn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tevwvabs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2otdeacpp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2htsmqfrr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2avospbkn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tcigypls.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qcddnsfn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2efsztepj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2psadqbeg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcntdot.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kakuvdin.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qyelnyyi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2spjzjeiy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmauuun.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmtgodi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfikoux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gieicopj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2anobiosl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eatnhyrb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpqqlph.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyphgfg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjxgjul.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2flbhcjtz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrqclnu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2stqugoww.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwxbwqn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtskyqwc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrvtqqj.html


<!-- 参考信息 -->