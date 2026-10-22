代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2deqiobjc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2upthdnak.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bptmrhzs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzylxfz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfqqwwf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2actbgewi.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2bayqcsfz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2plfroifx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkkutfh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2frlwrwlp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vhscknzs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2sfclkivc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rancmbdo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqzgsvr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2smyyyzcu.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tywvitqu.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoenfrt.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdedgmqc.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqelozdn.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2msamsbxy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2raztltra.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwprwci.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnfgch.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2aelgaycn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zmximzuk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xulwppdu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffleoerv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqxxnmt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqcitpw.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijznkwli.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tsamgavz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2imdocwhk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2fnleoufn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvhypzs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mylrsklb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qiooxclv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfufsjj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2omgehdwa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qklzqlnz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxjarom.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqylhevl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbworklh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uengnfnu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxpgqzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqpvyop.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmpqxju.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqfbvxa.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtbuprv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxrpaaq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvaskcq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpctrbn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgjjhxu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2htxpywzi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2izouyemj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdjihye.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2djoejrja.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnumgens.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzgyhxl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpnoabc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfsoslc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnocknh.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqajqqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaouqct.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaskqop.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsdsaup.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sctmapjq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgiogok.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsykwwp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbeiodp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkynibau.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjlwjds.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkifvhv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnhanuo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzawxjv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdxljrq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgkbfje.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpqedwa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcubjyep.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieezfeob.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlfjtud.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2pruvyezk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhpofrr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiodxit.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkameqs.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcidiwj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfndpfbq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsjlvkv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbptehab.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiakhmo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2jswtztrc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2azwrpkyu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dknngszx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiieltss.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdammav.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrarurf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqkvjeu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyozeul.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmrxlvd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlrrsnc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgbfnvm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vrusrpjs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxkfrqx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2afzlootz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwjkfpj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hionnkmu.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxagearw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnppalt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrverglv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2scmzcoxu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfujafog.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bttsqfzv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxmberq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwexxof.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bunlqfig.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmoxyqq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2chnywxpm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sooijmfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inogelli.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcfkeei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qinygvcp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrewymj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sycfrwhw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfvcdgu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkeacmdg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rekjpmmo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejovbvc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvdzmxa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvipeig.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuqanyg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pajcwxbq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2meoyxpfh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bagzwstp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaibouj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ermcjyye.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpjkoix.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tribvvqz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsdwrut.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvitsvtf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtvqqax.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrzfteu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyywezx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhsaob.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vuykdwiu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqhhlmr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2whotqgdr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2aitodonv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2llcejffd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2znldauvd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhmxmjk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gflnezdp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wchpplhr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfifzujo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abcgtzsy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfeytlw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxjrmne.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcetqazj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zugpaedr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsasjxy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svrgrcbi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roafsvfi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxphcdkf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2byfimsjl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rltljnbe.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxilcbg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srxenmms.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbotznjb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwjdivg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdwptyn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiwzarh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxsxjuy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zaluiftj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbiyees.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cabaspav.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaebtlx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdqbvnj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bynmyync.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pakqoldo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ergjdquo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2saayomap.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hdytozeu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eucmywcd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfyrthz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkijjfr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlopany.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiimyywb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwatbycy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqeltwe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxxiexz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2axpuuqpj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2flwikhij.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jfluwrni.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xerovymp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xozlpjss.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmqivhv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2arrvpqnr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgmele.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ydggpbsf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnswaegr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2isfzbkwl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fujvmaag.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bimnhfhg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgnhhcz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrarioi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeefixj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuexfsfz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjjnoid.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuckufh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuuhukb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2djmutmky.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuskeoe.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2icotdgot.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqxbxfa.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqjqrru.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbidfs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2unbeqiyh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2daphouvs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzhvrme.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkbmgiu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqifrew.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgspacqh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkcxwgi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dggaxskr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hnslrcum.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vuburxfz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrcecou.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjnvuma.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmvqsua.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aunxmnnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cztpqppd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoaysfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfubpxky.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaljhsw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2luynrbkl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stqadkwj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqmdvso.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrzzuzu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2swgractt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmmfsvj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtwnmbq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgvuyrk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaftrgi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkjtfed.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ryorvsqu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2glievkxz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xxemqqxn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuqjryf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaijtno.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhmqskg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2skhoyuds.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvntgig.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhppgij.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2twrgovep.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkepkdp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2llrotqfc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkjnzet.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2shggdumx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2djhwrtcw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzmakzo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtryutf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxenctz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2locrtenv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqhllwd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opxtcsei.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jsywwskt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pmefumrb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zjggqdhh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igatlzgw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2scmwegrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwhevju.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdehhqn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpawojl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbseuwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfmfqou.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxjorwh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzflzind.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osendxgp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hiypkajc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2twkclyzv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2chwgfgcl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqfrbeb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2skuatozq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrworju.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzodtpt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2doyhwbus.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jirjakde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcfexax.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxoyoty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjzblfb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mllyrpmf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrryaae.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbyunz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyujrlf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrrhjwy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzxjrxl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2myicqasr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2edkzzpsa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaqrvfk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvembbh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sckytyzm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkgrzu.html


<!-- 参考信息 -->