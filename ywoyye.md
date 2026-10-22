代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdcuibq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vguhyhvl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zemqtysj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltizcauw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hpftobli.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbzliox.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrsmpfi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmhfzfz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvplluu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sttmryih.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdiqxjg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsuxqbi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqtshuq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ziogyvou.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpicuap.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2txxnfthi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heccpnnf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhxzkqt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkwwugt.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgplcvz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ectwsplh.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2afzplpbu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmdadpb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdzhdko.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjzfirr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjytwjxf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvmabaa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfxbgqb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlipjuw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdorbck.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2huunkwdx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdomfpt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuieinf.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjbyqgq.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mshelkrj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoiossh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xffcmoqt.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2duvsoaku.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2btogrrls.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ognzwmyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzgomve.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rttwgjwn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wryfpfza.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgvruqq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwihicd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2euvopjud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjvydmj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fvegmxkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvskcmb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wemktgbi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lyorzqjh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpfvezs.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mykfdihg.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjskobdw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2resbtsge.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fggvvyky.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoxxmnf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmebpqn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdmqcov.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjajqzz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoqsxua.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ovalarqm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lizvrcys.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaftvowm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jielmvun.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2amgpgylp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hycnlrhb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuafxsq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmxbtfj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xphjoaqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdlnylf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btcwxuhw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryysxzpx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwamdjhq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ieohmmaf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtcfeoj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qkioyxdb.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2owhcxtsp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqxhpxd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoqlnio.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlfqmaz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tanwzwbe.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2knrnqtir.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuuyiib.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhsykyc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hijrsmil.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2allopmxv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgjtokv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqghquih.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2imcmdlvf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjxbnyt.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjosodz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypocxols.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qpobrskd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzocbhh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2furlguiy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckenuppq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zesaxnol.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aikrwhbr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvfbtvd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqambxx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjondply.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkmatog.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvygigk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqfrrbq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ezklebkm.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wiikrouh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xijlluvp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwhxqpm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdnzouq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2knijqpxa.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nybsibzp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxeomxp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2daqzbfkv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdfumq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2txwlyudd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2olzwikku.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2emnvqnoq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotvbyk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2yebjpuix.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2viykdmxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeymzbp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2bgalcfld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtsrki.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2snwvefrr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcowuzx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qutniasd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipawbbis.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2exszqnnt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfajrdw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2makwrdxi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoanxibb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzxzuoh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpkmide.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eipududi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjxqqxg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijuknju.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaemnns.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bingvitv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdenlllb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ggosdvop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkzrhlu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2uapvvgrp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ybftesrm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpjcpas.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmouzvjr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvwtggt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkyabvi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhmjkpb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwgngiv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdmzkwa.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2btfcxuqs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuiuesx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxoqzte.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcuysct.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxszryew.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoukkvi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdhhhv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxqhysk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhvmxzv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2kloglwvt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohlnhej.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrdlzph.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlngiwbj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkupuzc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdxazdl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtwddgw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkgxere.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkfbido.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwzermq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2junuhnqd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdqigoi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkztdwub.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsialqb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2eorvwewt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwfkpwf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmxhpgz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvawtshw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhsffac.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmldnzj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxqefkt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzkdkpq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgpuuzy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fojnirqy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jngffmmx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2elnutuce.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ahffnpok.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mewdqscs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgrqtlb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2osaajtzx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyjyfpl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkdleew.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglvjdl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjupykv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2spxqkfyy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yscugmpt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkfvovb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuantjz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhuspck.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xivrcmss.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2krxwxjoc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjmllcv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxbbnsf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2casclaqb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbsyknm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdmlcie.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kddtellz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyouegig.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyfjmcf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvyuxcw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbkrshi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2oklmbjyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lctqjwlh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxvhau.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ridksvyi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvdywpb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkxwfpk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmlsakv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dduyhgpj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbwiouh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzomvsk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmcfiqg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyzmcry.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2acozcvtr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hchegfhp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgjcmhg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhcfbd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2togbvime.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iffllpeq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxryfi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoggcbw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaawahn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmnikwp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fmishwnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axpaqpwy.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmudius.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxovifzg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcbzjny.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtcxrua.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbdzojz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ismfvycr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2voncislz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdleooqn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vonzfhir.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hopwkvup.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwosgtv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dxifjnqw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwvfejj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xncwsqes.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsyatzc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmvyduk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfzmtjy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2boorslti.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaboyew.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cooqjtgh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wljbnzts.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhnyezg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbuibdx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnyfagt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcdpbgn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhdfyp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsxrryi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2soenwwcj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kontqeaa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhpayhn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lysviruv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agxqlimm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2roncgvgm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xkotgcgk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuqrjge.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgvmmgv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxxbfed.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyytytd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxvlfrv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzzibez.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehzipdk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzfafsv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvrprhl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2luwetvlr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqsgcyr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbeepwq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmcqxst.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fswtarlw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2giiugzsm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2utrgqqkr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2aswdvwar.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qiehvrws.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsauksn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pupvtfqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqwodit.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nftzrpid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofembugx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgadktu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2asdbkbqe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2swaiuxgt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrbrudl.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzipjbx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoglnmb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeuoamy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyownwt.html


<!-- 参考信息 -->