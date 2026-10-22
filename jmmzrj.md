代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wojhvkbs.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoidjbo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoujfdra.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxhzyid.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnuhywo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xajqrokn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkatcngo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2itmkzzxr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzgtyqb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzcafjv.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmkxmid.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2entrdtjl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oayradpx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtgbdsi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwnonun.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgzjsdg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zddjsszi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xgghmlso.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdnzrvc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yimgbypi.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkxzcvd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzhqzpt.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kocuvmxw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqqhfoa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jukdklll.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2psutyxwz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcemjsl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxsfpin.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yklibtaj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdtukld.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrcrugy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xabzfipz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dmujgmlx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjecqziv.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnqgwcx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhwgfer.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzexstl.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkpqgb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbbspvt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsibhpo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbxpmde.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2stnxgfkq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdbbsfq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ueanuhlc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdcyhdf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcwoeiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvotfpc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnlhcrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yflavxis.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmriqjfm.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjwskqt.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2itccybig.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnscqjn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qypzosgk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pruvwajn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcfpobe.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxsradm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfipqto.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpafmuhf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2olqivbqs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2phutaudj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkazlzl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrdkkwz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmirysku.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnpttru.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwesmcu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcjxjuz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfwndpv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xznjboss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzgqgxo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbsyofh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfugnrmc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2axhclybw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdjxof.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2calqodgn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2msvdvhsf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbrmols.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvjslzo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhfeebk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zymnpqvo.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2duzgpsdb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2srjigwos.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhgsyrg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2aysoncko.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgtbgwj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfapezpx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iflbbiia.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nebbecwk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgmjluu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxflhfby.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfvuumu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfavtfcs.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgxeosl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmssfuq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhrogfn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yohfzwhs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwuyeph.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtcamuy.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwanhsj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2grmwcbwy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2evvhwslz.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bozmsfbf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuoxorm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgycszx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lepzlvit.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afuefwmn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlkbfyi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhadwmg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2twyniohm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgddbck.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2oygvjyqo.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2thgvsdpm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2owwcefqk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrghkexe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfiasx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyoqwey.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zppldznj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hydmsypa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tckwcpvi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbfglxb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2eortnsuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcgxovd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2oseuzglf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkaqzbb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoigyhku.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyqmwbc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lignwnjo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnutfal.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsarpdyt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mguaqfuf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olsjzrny.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhhbtde.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgffoopp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2krdzwxii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2obynyjia.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhevbtty.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmslcdr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuwkeil.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yevlgnjg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdqwtqi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjsvhdg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnklqpkd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2truywizc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqmlzvs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ufouehvg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2imahepif.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtmfrzu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwcxuvo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2svvmeifm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2okhrfjnw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiubimx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwwnikw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsdoyde.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnngfnbp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqskkgrp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmjzeum.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsojeen.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xczijcdd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2koqyoovq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2axrqzqcs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ustrvnbj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhstsiu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxigirv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyrwdns.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxiewzm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgupjvn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oisfrwav.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2weifnkko.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uspmrteo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwcgqkn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqotaqly.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrqymxc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yamcwrmj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxisnwml.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2febxexnn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2furvxzjl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qlptozir.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjhcygv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdigtpao.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hgktobms.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqzqmfs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrwugws.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ykivknhm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrwcfyk.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmmbyrd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgyieeh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hesntzia.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdktmxzp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfscivd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ithxofek.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uefailsw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkeliyd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yifpsexs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkzskau.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wqutjeji.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiwvscx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbptxpe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oouolojb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxmdtiv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsicihgd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhgifbn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjkfzn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2taphqimf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mougswjr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfguvzoi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxexpbo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2geuaskex.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chceudvr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfxftty.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpsvyjc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omgrhakd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyelaoa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrddhgmk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxjptos.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kreygitn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2igvqdsdk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmlalsg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmggwzhn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fspdhjjs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pohscxrx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ceebedpx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjmoamv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ysguzlrc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhvoezw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrvfepy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnqcijy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oispepld.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbkegle.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2drrbvoya.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgteedxa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2popnhpff.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qreivune.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhcptxj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2abrfkjww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qczbrign.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2giienqwg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhpbhfe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjzhfuq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2umwznmgf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdkdgdx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pszvjdxe.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2iivvorge.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibakwrit.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2unbmjalb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnfyqfo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cstacqnp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2htrgmfsl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ajblcwhc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbprhrd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxtytog.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuulmzzw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrisapd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jxykbjmj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2onqkumcl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxfqcrm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yxomedfm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfhbtwu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uthhrrux.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyecpbzm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgflbiuh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhciioec.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoikbdw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fihdsfgy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oimbohhk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrkyenu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfokigaf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oacogjpw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmdkxey.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2noehqkgb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2okovshkq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gliekepm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jgktokml.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iorurnpr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hphsshmo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxhssly.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiehuxt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2omqirhpi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrfpypn.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdqwvxc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2soplyhwh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qazqdcnz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2atjimdry.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2irldhfhd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2diiwekow.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tsintkdm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hvimiwrn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsxcywz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyxvdzn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrmnalh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdjyvtg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkznpen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnnfvdy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvlhclk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2biuzyojx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqtahaj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqcjeeu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkhfiqi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uknccjxu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ytckcdni.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2accyfwmi.html


<!-- 参考信息 -->