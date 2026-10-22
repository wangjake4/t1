代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyplqko.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnunicz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzqjbym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqylcbfc.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2phqscmhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhzuopm.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwmmktv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhytgbs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vzitesvq.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ievirmom.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnlmfdl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2syxughrv.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2inmzkcpa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpbjlgn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncraxbb.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvgsqdn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ntylahwn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsndkmj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmfvfah.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pupodsdt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlnzuey.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2uundvwng.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxanvmww.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2salqudww.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvnfliv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2afpxwrat.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2djbawlmu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcawecf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tqujnuir.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2absaljjp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwydcgak.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2dekrvvlp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkecqsao.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsfadck.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjgtcds.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xutlzvyu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pszyelmd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hnahsrqh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuwsogb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrmxwud.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kexdxhkz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2guueuyxr.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzyvtzr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2gvncuune.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uerthisz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2diqrdpot.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2baiuputc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2uspyfjid.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyrdlmj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbicdam.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbnibil.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rbirexlm.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uljskfbd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqlgzpt.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cssmiwrh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpllysw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sieevrpg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqbkrrw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwfmwnr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2durigrjb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2elrofnni.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwhrdqk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmngjuy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dmviqtms.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ylufchwg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2okhzdphs.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zaprktbl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqpamzm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkwdwek.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2amuwazfq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtayeea.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdmrcxt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxklxoq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtpnfxe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgijcyw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ecortbfq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cplzgcvm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2brbflyiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhgrfqd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnsogss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yowwzuut.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiopdqdt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ayynawxa.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xolcydxe.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoaxgiq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzamycq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eijuyihg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfspluaa.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lqokdnnz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuseddu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyuyknq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwhsnow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2frudwzeo.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnmpsci.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2arwycknp.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mifzgeki.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuzzdcn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2eawizojb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmexqqh.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnbedlw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdrvqcr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgseemoo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wugwaxbn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbbjzib.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rftodysc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2orepvhhv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyrmajb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbxwpwk.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wklvhzvl.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2igirjysp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzrdddb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzqofqz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmxpict.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaymbyk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgthyskr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxoiaug.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qegjpsoq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaqhjkj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrtfwri.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnilimjh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfpmsrx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcgtkzc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpxifce.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chczhvuu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqizsye.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmuuzdq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2izpxrwub.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtnmebc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpnrkck.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbxeoxs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqsyows.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfdzclk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnqinmm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bausvykz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2blzsrdgl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2esdvzjgn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2asucndna.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpgmvwf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fihtgluu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoewsrs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wookknjj.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiztvta.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkipbrt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnflsrz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tctbqooj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbybmxi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2imvnlipv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dftgdzio.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2farvlqut.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiezfbzu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2katefxel.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnurycb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vylfhzvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkpwybi.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2iyonvcin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqjpqlq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfkofjv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cktrmqqc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxpgrsl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcorzmc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sryhjkvw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgmmxmc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuuxdvo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2evhakyby.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfounfmg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuuaigu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtetlbkq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdkdfyn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjnwcjm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuknnao.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrobjok.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxysbxv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2goiyhbpg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvfqamk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2okptdalu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2covamkwl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnunvgo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxayicyf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrgffmn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mtloqojb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzuwfup.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2cabmkevp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lytafxtn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsmexiq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxwkzhs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usjtpmab.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyebvwh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlelqit.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjledvej.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtlkyrj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjbyjya.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyirjfmr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdzbvhy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqfzsou.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roewdfqt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amwyberf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwctyzr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhumomh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwukknv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2opjccgyn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwpwdcf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hywuxkor.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iakcubat.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2folifabd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfcwqqf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aduhqjzj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2brqufizz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyrazqn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfwszpz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2honooomz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nervmgdg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgifgbo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrgbkhc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ustxttun.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dyacnlql.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2yppwcwvb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cwslytbw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsyagys.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2whfdjvma.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2prmbmejj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2deleuxln.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtwxjha.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2otujhriq.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhaqaix.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyebiwm.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfxwcdj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ohirqque.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bscvovqy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2veipvlkn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmajjgfe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlzahph.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tpozywmc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iygtmxlf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gomezezt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lorqqkud.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zygeehio.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvufdmls.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qzemopun.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkvkxrj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcwvvmq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutiwtj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2njwtvohg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoubjqf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyfihtd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pspybrvt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amrugznw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgiyocm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2istqsokz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnzxycs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gunhqfev.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpenfss.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhybogs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xdufymqi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sonurmeo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdppawh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2newhmkrb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jadwezkm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2znvkwtzf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aolqsjkp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrkdlar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wykknghx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsmdjpm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2clkquoob.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2exvvwggu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdicjbd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcntiex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmodibw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mgumqiiu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmifaxz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzwzadr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qucfsaiq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oylocvmu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghudyqca.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kukpsqal.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvelvoxe.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2czjtejph.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2owinupni.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fikopqga.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zylwnpqq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2inxlnjhe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oycplhdc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2czuhicpf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfvsoqe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iddykhfc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzpqxhq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkuhkrz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxcbobz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsllgyo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyzyklw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cifkivoi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvarlsmw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmkhtzn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkacrlqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huiaskjd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yikktznm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoexmfk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvbfime.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euncjvwe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfehylww.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2clpfoyhk.html


<!-- 参考信息 -->