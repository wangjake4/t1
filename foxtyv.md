代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbzsthk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2zptzgkco.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpffziv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahigvovy.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2auuuukvk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiwlqcf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjlebwh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rirwouyf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqoodeb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnvoqor.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdwhyos.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2lktlpiyq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcuitgk.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ekybunzl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2whczyaxn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gegruzuq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wumxoaec.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2midjkaiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrwnqjy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2aaghjsfc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsscgxl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ainlkbgq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgzzhkg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiozbec.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbvtvbp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2voxvqpxn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrohzdt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2anghvvwl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjzrurh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnjgouo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqmxasu.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaahbba.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vchfrarx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbkptuf.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mianpsci.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2owoqlyyf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxjfopc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbnjaxw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcxlbwy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tehvmpow.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuqdoaa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2irdmmbio.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zakxejrc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpdpthm.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkkdqfy.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfmzuhb.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwaqfgw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxznvgk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfycgcy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrulnxu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2maivdhib.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpakdafb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eudyvbtq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxvpddm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgjtanh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrpsvtj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeocnaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrrphsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clunibnm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2otjzskcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwpuqcw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfofiaqw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlcvvsr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtlllrp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwvfrka.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjbzvyo.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtyubxg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuqcmfe.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkdiudw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2frdavjxv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjddaghu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2poprfztg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqehhvp.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnrxngz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfhavlv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwwkdoy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgsekxd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaqotxu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwgivrz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgwzoqt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifmobby.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiaweey.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilceicxu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bncvvtex.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvjmdqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxsrhvm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rottbcvr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiplfnm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qqijewhu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vopyoflw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtvfpuo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2baqqrhpv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqctfxp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcrjqmd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdnqekc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfvvqxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzrrbre.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmbvoyn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrumyzb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nndseitt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xazovqvq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elxlowdu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzismelu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkuqbdj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mydukwdf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwdbplu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxjutqf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxojjlxb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzssrvv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbguhxat.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsulmxgi.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgjcswo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgmzqzz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcsvxwp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eslffojl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nknpzbwj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqgupnz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgdavca.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dadjuejq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrjvrgg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlkayrk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwijklw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2igrjdlpz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqzbvye.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2olczqjyi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2baoivhkc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xangjsrn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvbqqvs.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsphnis.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdjzywr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yprbrnhg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2oydjejpe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qijvunwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqykbxyp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdzwdrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkxhkeh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lskcsfuh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpghajtp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iagoahmm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2etyxjoae.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxebcwr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivjudjb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevyoert.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqfclrl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqurwhc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2trxespsw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjqykgd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zujreqmd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufclgdeu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2niawsnze.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oucbdlcs.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemqwpnw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqdmrde.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwicmrth.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdsgcbt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhdcrrq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfekcmt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgczcsbs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuatepb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbdmkjd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2juntooth.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqqxxhc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhgxgdk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2eponkzwz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2havdmbpp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzshpnlf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtwdgld.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdlubxh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbasyex.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktatmvmo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btjruhsd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzudqmae.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2synvekuk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhzlaji.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxtxsgd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpgfiwt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snzaccqp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrnrojj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntopildx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2awxaosnx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orhvunjp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jeucccep.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2awjouofj.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mncuqleq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2paoqrpvo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2negfptim.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtovxgk.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdfnmzi.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aikbuzdg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2acdwvyhc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjcncqr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdffojr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zriwnrqs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfywqsvh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfiwbbx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjiamkw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzfxfmv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2usjazweu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzuuhlk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xujcproh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oinffcqy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyllqsq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pvprffsf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmmykec.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwrmbce.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnioecg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyvavwm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2txkhmrra.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcdmwmi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqodcksx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pezxnurw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzreiol.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nilsmrpa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2liljccbx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlsexmg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mysoryrw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlfhdzh.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhnognm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2woladsde.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfzzpwu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxspigfj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbdeeay.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knxzmgjk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bljjdqkk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzadhbgx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jajwtktv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2slqagpls.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fyokzybf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqupsmy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgkkhba.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2auhqbmaw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcudmgs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaackku.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyzwkgc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhhadji.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpwxnmm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqsniyf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpismok.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oskqezdm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2agfsdyyq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdybtiod.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjmwhln.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivfrawv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixcbxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtocoan.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bszhystg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulakungu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnslada.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxrqaud.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqkfapd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgkuwiz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2alsldjwr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkjtvhn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqhehzy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqyddfe.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kiivsvpc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2szpqqety.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkpewpl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zggibtun.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyvyryo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uweqqnmj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxkquld.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xczigiwe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiqjtht.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgzrkxr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2egqdsmsu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwfytnu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjcsnlf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tbatrpkm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoneaij.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zprzcgoc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2osdpljuc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kampsgrl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznfawhs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzloddm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2krwzyrvu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhvvzcz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stkdiyzx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mixdycrn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxxucbr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmrircv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fliqicgr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ladiqopo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2waoopyba.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiuwnyq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbtabfp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwafuait.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijuisvh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbintkwd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqmbjhf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmeuilk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxisfat.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gnywgvpa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2eacjmlxz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjthnvju.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zaekhttg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaxrowa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tzygnpwp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvmtyxq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbguzqp.html


<!-- 参考信息 -->