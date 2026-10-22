代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cugdkicl.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxouboe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaalnhky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vywhcfqy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjudrlz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qepfrpdo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxcpezv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsyqfcc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkcgwvo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2axkqhtmd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2njjkqdsl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqezgch.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rggscqai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrigiku.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2elogsmvu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wouleggy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjidgvaj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxnrcqm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dclsyske.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qtblbhbo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzpyff.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjhnzgp.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2eevomobi.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeqigue.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmwuiyn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tihrurbt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2aisjlbsa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnalumne.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjqcoeh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ingcxmox.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvgtpju.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvqazfb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyfbavw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2almudyxq.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrqnbii.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2wrducpuy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvzfnhb.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsuymiz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2esrfiyej.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohupjmjt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwyxckq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiwcqoc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nlihdjwg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwzsjgp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaihezbj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2blhdhnae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdvjxxt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrozuyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iropprcw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uetmhkbf.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrhbfpw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlweynih.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwdnvsj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoinpqz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2amblivyl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vlexzmpy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkplsrv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyknhcuf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcotshbj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhrtgvj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzsebjj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkjpdli.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxlqkdb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpilsskt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbfchwq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2czlcdvru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ormrlrpi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wihkuotu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnfhtot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzydolga.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2khjvfqbr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbmsnky.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqkdcgj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hixvjvkx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyuehhk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwbarjt.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2btvxlboi.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkncwang.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqzkmei.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzewytie.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwayxnu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2klckcnjb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpxjghy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjxucou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2egspuqdx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tociucta.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzvyelz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtccntn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsjlzsr.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2drixatal.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoawlsao.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2euylysvk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2khtplukq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbpaklc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdwkmmo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoizcuql.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2btxdjofd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoyydos.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrybuxs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eddkuqdx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2amxqnvjq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cthytzha.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvxldjo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvwhcon.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ycstsbrs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zotyepdb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2avvazwsu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2whmobnip.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zphpyknb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkkaqwm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrklrvd.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpbobma.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wirvydgb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vitsxauk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqeihmo.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2piaywbgf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzqjagd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwpmdqd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzalzyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mysqlpvr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjyboza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeiwfpa.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hublmgwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxomfl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjacfyw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmzkfjx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjipefs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkydpxdj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaofyim.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfjnyrj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zogickkj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjnmdch.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcuxpif.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsckuro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpysqhd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2npuqsbax.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clevxpzh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smhpbmak.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfahaqo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvdgxcv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwcnkwd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyyzcns.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfwbdzp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmlonls.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkazdmi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcwkzyb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2irbknofx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjxtscz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lotldkzh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcicuwf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yvueiake.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofckwojb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqevfgtm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njbpmtsb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gifhubpr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrfptdt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zatyarfy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzaftiy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdryulpc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sogpkcuy.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpqjhka.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbcxwiz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gafniank.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkhdsxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsroxmj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoyrnmq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzanggxp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrztgrs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjqcdmc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ocswxsma.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sajcyqto.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kguogmlf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jefpsdyb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eulkmmyk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2padyudfl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aybvrguf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yopcdgan.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ccodipnv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpdbivk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2blpixndk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrzralm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmlwgak.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2trfyilqm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2azvwmelt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2txknmffp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xeklaeot.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwjuhsy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2drdqqcle.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfqriqb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2maquqquy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2usqvtvac.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtuybpm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2insdtaje.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zoabsrhi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxgcmkh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqfxooz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpapdsp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaajqrv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqhqnzu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiskhga.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jonxwfoj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmuhkij.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cgivhujr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvvlsyn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zosspnoq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgyzcno.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyyyqas.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdajfhrp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fblopvnn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhciisgo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utxpdbla.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixunqeyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2idaputpx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxkxjou.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hyftvbkk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nemkhrec.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aefoqqbu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmwumqy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkrcdqk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrbesxm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sxspgync.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2resgqiqe.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzhenkw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxnpsji.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnkijli.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2virxtjzm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnisfmmw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sdghvujx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2csgenpxw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2akywgpra.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uivxwurc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xefpglxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrttuyb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2etutgwul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmkjfme.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ryccdowk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsfwxbm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbwzagi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqtjqrl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqwpupt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzoxwbd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvbgkdt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2utlzpska.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bbskhbcz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtjlyjj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnyojks.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmnnbig.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkfnagv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2upwrtbqn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsepeluw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2crdluuft.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuwminz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aoypscyo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tzywxews.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gehwdumc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hhklopmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pravsvtn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gczrsarb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnthowkt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2adxalfkz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvxjpzn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naagoiva.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbbsuk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbyvqwv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnzyxni.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qevcapzw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfepuyby.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2amxpktps.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhibzrt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dezirwwp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkwnyhf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpayowo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2prazzftn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnghmiu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqfnokx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2keyrenng.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzjyfaw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwurgwsm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtquysgn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcrmhoz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsozgos.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmjmwvr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruirdfnx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdojyfe.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjuwfi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkrnhet.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oralrjbu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtfdrmo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2iqavcixf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brbachwm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xauuewgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dofoohee.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vajigmqj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2itkyksrc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kiacswgb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsfnwsd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzglfpst.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoaudne.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmtykan.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvbeexk.html


<!-- 参考信息 -->