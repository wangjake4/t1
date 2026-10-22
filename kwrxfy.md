代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjngiph.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pevnlbzc.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzufjoxl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoovqlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfymkpo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrjumyh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2friluczj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2twbcoavm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsdggzm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwxxfuf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyufosic.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2edltotaw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsojifvx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2epgmtnik.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbdlpfs.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxubqjk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdybkpem.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnboudt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptfwxs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwhallf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvupwki.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjplrrdg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdoranm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kpreytqu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vscswkvo.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvdflog.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmwtmxo.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2rbljgagy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyccqdz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2luaadsmy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2nwovscoy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocebmcgp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbcrwvo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mphsoogd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qzssvoqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeeserw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmiczms.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrrcwwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoiucoy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cgepokzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsljeftt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwehzwd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtkdgk.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qverflyh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2synwduym.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfufdjon.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lufptrpc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjlvixc.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2eblenoqu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmnoaic.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddawhuiy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkyjyiv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvxqira.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2csapoljn.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkgccbi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvxnwul.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlhhmfl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqdufsu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohruvqwa.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yoerfhtg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbcctfs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyqedjt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwcarxr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsktojbd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwobnry.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlisxhoj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzogegp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2acchjakx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwtcfij.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sntrlohk.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dntnmrnl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsehptm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsamsab.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2geimvdju.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvxctyr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2txwxybch.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhsnlzr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdepgdqa.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfulrupd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflqzukm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kahqikvn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfitvir.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfawnmja.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyoiwdk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxixbmen.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvhwpqi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vobhotyb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnadwnk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzeglen.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2csvmyvur.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvypons.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gohphdkk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nctrbuyn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghaavm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyxlztk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2khowkctl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhuatki.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2htmhzmka.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2codgcrxn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmsgqbe.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jogklkvr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqxwdsx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2sytkrdbe.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzsbfcw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jraeqgxg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mknfckbz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaknjfc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2blrlrdwk.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdnnrvg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuwxrhs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvqffbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pewpdinx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2xitydquv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbdknto.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xqugqkpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iahhgjse.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhbgjyo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtjrowx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlnxhmo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sttaetin.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hojygkzd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myfskgcf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uganlpsn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygwbciq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2frtihjhn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjgylav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqqycxk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hywzcxer.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqopqqb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2itpcmmnz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqjcouv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiskgwu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rapgguyw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2szozyukw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lftbryen.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jyaiogvx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzogqde.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvctopz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgtfbtf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhotzd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cebtkyis.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrhxrxf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yxygdmau.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoojrxc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzbzbcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgopytal.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2djldefje.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aitquatr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzevewl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jssimkls.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoefzqj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsurbki.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhekegvu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwcrnkv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfmovpv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhumawiw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xglgaztu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmncbtc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgytvse.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalhsmgy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbadwejm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbptfrh.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2opsygsmc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jskltomk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpyesvn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thkphiyd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsadwgb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgtwsai.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqsejss.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2axfrsrwx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbzorpf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xcooldcv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsbfub.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxxthfa.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsdnlok.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwmtcvj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmhepfl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrmxkms.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fjduudjg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfczxoln.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fonzibdj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvecqbg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmhgfyq.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fltkoxwz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdovcyk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2civiwnlx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbtdupf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ovymbiam.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2meutetlz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lekckjag.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpziynl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dorjjtig.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsnzfdg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2byqwtytk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sclplrfe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkufycd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qefzzovw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zqanwigw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2psszwefc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsljxdfe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iepidwgy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2diflengm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsliyunq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsithsmv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqpfwqm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yddhnkkr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxwuoaz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpqdork.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqaqctm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiuycas.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejikkdhe.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gedfldco.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzalxxq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gauiqrvg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbkvlvq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlrepgt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnlzffu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qepucsli.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2acdpbltb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rudlsaun.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cfybvzqu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtyduox.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpueydna.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhkgexl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dihrtwjp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2earrfuys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eycqclkh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2umwoomuz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxhrade.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgcdrho.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lebfigwh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tabquopf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdatqia.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2srpquzau.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfefmcol.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpdabmm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pqilwktk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhzolhh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmrknnn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwxtmxy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zvujtvno.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aysfssbo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2upvgvofy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hepjjoqq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkalfzq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuktclm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2codfgxtw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vakdwgiu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2euooqkqc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqojevw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyvhzsw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qppdhaol.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trqgrbrv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifagxnrg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2opvphpwh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2llfrygrb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dgngsrod.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwbzkep.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mupdbhcn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dybtcvix.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkboqwf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2outjpuwx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rswyotjw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bpniymop.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhumfuuq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnytxuo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomuhlll.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvjzycr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tazusjpj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoqlpyw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxzqmzu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtsnqwo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2arikgikt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmmwgfl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrclpku.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgzuxfe.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwqqlkt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmaaklg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2swcqyyae.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fiudquma.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgkyrpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spzksysz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxhhehp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstlkhx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjqovjt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dawyvqhh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2airxuwuc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcffvwt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhrgpqz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2daivslpv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdbwjfx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvdsboc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuiaxjf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qoavtuvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlltnsd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhzujnl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwlwjzc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtynfxl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjhnxrk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpuawiq.html


<!-- 参考信息 -->