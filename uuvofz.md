代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyicjyf.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kukgsczw.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2oovvdxug.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yymfhulg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsztcay.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuuzasg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfondzfs.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qnujhpbl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwqwgly.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzuclyd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdksddk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2shacnhms.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuahtno.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2vljmsgdn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjddcvs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owkiggeu.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjhyykz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhconaw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjudeaw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2utyvrsdn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2byhidnpc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hryxujbf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiqawvy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2yymbokak.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpysxreh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2xqweplix.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqphawjx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqzukyg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sphiilwl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2puvejpxc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpthzjgt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tahmbxew.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwwljvu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2okjshxge.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzijnthx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vxetapfu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxttfk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2waunxtnv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2oxecssin.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2tvycqdrx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgveyepe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlnbzmf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fabpjnwh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qbladtgs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2svubvcwl.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhbmguv.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozusbuow.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2heoqchsm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwxdlkz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpilkth.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnovbrxx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2znkgixyc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxvjcot.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvyckvp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqtkqqt.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zztsxure.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gxowzuoa.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kubobbij.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvglfxy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwatcox.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rusfwvum.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxahjrb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyowzlq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgwinau.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2petluzmc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdtmmvf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgynel.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2sxccvcpv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlgbkdu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2axtxltwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzckulms.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lgebfghg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsimjud.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agbvpjqn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkeljkz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2axrqjnhv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krmvwymt.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmluzsuj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtdiehs.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2byxpokwr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2kzszhoeg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2urdnrpkw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqcmfax.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjcyidx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdpnexf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2binsvfdx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bidriwxb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2binriebi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwwfhgw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tujisaap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoelftz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2giqoicyw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsxgnwx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnftogg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaptfdr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucveffle.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnguqyoe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzopajgf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pglmguml.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2meqhvtdl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2haktwhrp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2werbkbak.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2icznzxpa.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcfabfd.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfrying.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpciojxk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqbtuav.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zesjkbgq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuikqhm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeacxep.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhqtjay.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgmkdbh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dirpfuvb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrnlkpr.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xylhiokv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcpdvxk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtohxvn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmzhktu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mesugqho.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsjpkct.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyfvcgj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2flgjrhic.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaceycy.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtdwszq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2llkfsold.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2witebiul.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbeftsy.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpesybu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nkudydyg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2awgnpfdl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xmurpnjs.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mkewusmo.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvdgvpc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmsbkhy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsyxwvf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsidclrr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mociepth.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2natpesjj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2caciovtb.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwsixdm.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mijxtulf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgxrwus.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uclztcwv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrvjtnt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhayeef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtuqgvb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvrzudl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmilnyz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2joowshua.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwthycna.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2spcuxddq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uphdgtyz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2whzqsqfu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfxshdj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urgrmmpr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwuwxzb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2keyjeoha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujleviuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mukynuue.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kosvwqvg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bycwbdhr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gslxpxyq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoejrqyy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgctvey.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnmaqyr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudrazk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdfztpf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2plancygh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhygrkl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xvenalwx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqslvyq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbzkexc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvmwbha.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lhevshmd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxhowgk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeqqhyq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlmqwtt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nylnexzh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qviewiai.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yplnswhy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhgnent.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcdicii.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2doecqsch.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2khffnlan.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yszcbgji.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopyivbw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkybcla.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwcpkde.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wolzcktk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhyrxxe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcrchgt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnpgesa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnntgpnh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyygoqb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2deoqyyxw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfylqbb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpmtcub.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpynhwfk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzmkpdp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwhuvhe.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdxrirc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuvvuzt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnzjkro.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgaaxco.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jtljuine.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwxlraq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsbdeeh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtvjdvr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2emrtmmks.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2avvknjlv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpdrfvd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjuctkh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiswzxji.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkjvhuf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgvpczb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2imkiiyfb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwkgikc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfcwtyz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkytpfa.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrvgcyt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mihwtinq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jswevvuv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmdrvzx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbioqgmg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dytyvqef.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqlxovz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxgtujw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyjfkik.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfwlrff.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oogkryhk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaowepp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtkrkux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2banbrbsq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqjpttb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrimykjh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqhmjsg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhplgbz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpbdvbh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmehixx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2npmqdjkm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okhfnrzn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqeuevn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpwubso.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zigpurev.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwyjiaf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeroran.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2televwla.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2swirhczc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsodlzr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2imwqoxsk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vjddzrma.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2deeglbtl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpmyjvl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxykcvhr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hheweolz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlpxlyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lssjhwno.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcvewzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sthnpoel.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uosidiuh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkiaaxy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bujoggct.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwptktf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwqtbmj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhhtxjd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtgdjqw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqiqmzz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrpdvqt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zalnjqrb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzlzzmu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdzmktu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnhpltx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xkczbdxe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzmnyog.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gamuhmaa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgzpgps.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvesbvf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ptamekai.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2thpngtxn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrxwupy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2otqunvzn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjnowih.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnjxgan.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsbrgmo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2videdras.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtqgecy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2evxlsbyn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2metixakw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyhhmrl.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbgmaoj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ranqujrl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwrbrzn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoimriy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcxzcjg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gazmwzfh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjjwgoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iibyalmd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nywozyjf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuqahhz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrzrqgr.html


<!-- 参考信息 -->