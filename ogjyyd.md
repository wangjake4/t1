代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrgepdy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mdytwcbb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujetbrkm.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uklfpiso.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2obinialf.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmwibgu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqxtaaj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjqcxkt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryswmpis.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvxtht.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmnqnnd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrksgkse.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnnazci.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sffqukzw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2mznlpyvg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vowazuvj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ituxeyup.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntenucyk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2spnswvej.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2twnwoilq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpfvzhb.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbptxvo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxysqgr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjdmxnz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpmsjhc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbneuecz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2plhbkxwz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnzuzcj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfjnryv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrrrzfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uswriabj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sycghxyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcdvoth.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alvtppwx.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2emxffgvm.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjwbfkv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vasuafux.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkngqvys.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ergpqxkr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pionmzxo.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2unmivtlc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rafyxwja.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkeavih.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxxomkg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmapfdzz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuszrlo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uonjwxgk.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsaxmhq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhwadph.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcyyplt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dutsyudk.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zygosklh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2detclcqn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yeljniad.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzsythj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtdiywa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eebsrcqm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2eunggxea.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoyszrp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqpyycg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aouvprbk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fknsthcr.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bpijmapm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrulziju.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fthfduuj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2umjjztfq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgwrvoa.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrixjwm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2emtonsel.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rjenqilf.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edvgtpit.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsxoadx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtujfps.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsuyepw.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxevxlb.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmmihtf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmdhbze.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxszder.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ioftxduz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djhkyrem.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqphptp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjfqbgf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kflabris.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuxsnbk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxhjydh.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfdyvlt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbuwxpo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwgoryi.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2onvzuqop.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfejzdg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqdafmg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjblddk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsztgzq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2firtqlja.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlipvfz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhointes.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbmryet.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbqtrav.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrapkrwp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjrxfyl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2squodbce.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrqbjfh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kynfmrto.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmfxrgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpxdxlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbnhtkr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2sanldlkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkeuzmru.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2edftgcre.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvmllrq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgehjxj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2msnpkxlk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqibnph.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcotpkj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzcgphg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgqdjzj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vankbyht.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2stmpgzwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpavfimz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xunorfde.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsuxmwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbwmuwj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rajumapr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2asichgkb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxxcakl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2amlukolj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhieovme.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qirvahea.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2okwpbiop.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhzkzcj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuuepfk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ugprqumm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzaydqt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2adnssjic.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xrngogxo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2weroglou.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xixwzoxj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mifgkshl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaphjim.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmoslto.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbidnwkt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nynzacye.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjybhumh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbhzrju.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2iihwetjl.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srvhvzbo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbccsmd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnciqrv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wujwhwer.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqexwngg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ensaknnn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htqixpnu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmorrdtx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2beeefriv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpcuqh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxtevcj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2slnokjlv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsaoxqz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpcekpj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wplaaqwd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zokalhko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xsydburj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouesafus.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcydhet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jucfduqk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2crdlxvzr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2pubgncwv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2txhtxkne.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2icqqebkn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yctbhviw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpvryrn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2movmysnq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjxojvl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiizpif.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tenvfmde.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjglujl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwkxuzf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2argetyzy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ycquktvz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2timtzmtx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgrbews.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkgnaxe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dndmehjm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlsjskd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpgxepk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxphtxyo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2flaupqvk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjpjyte.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2omuqoean.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dydiwmar.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjiavhu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuuidjk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojyokwj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzxnvot.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khrloctr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzristd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2njvwcvgm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrvsyog.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzlkysi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2melvcpkj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeqiquc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfazaef.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2racanmiy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpkpux.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfodpkb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2khhtktqr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2krcpfpqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgftnvgi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oljmxcgr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2twvyspgc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ockupwvu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rggxpntd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnfquwu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaogjhai.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yichrrks.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2okpdyeeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrvgqrx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2crkgicwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atfolhmq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnipyu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaqmaqe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlstlwl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpgsin.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgekmct.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqybbep.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wahdtlxu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rljynccn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxoicak.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuxvfdg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpicidt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ogteyxme.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pgetjeny.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdoecry.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2imydhjqk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuewlru.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxdgwxj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmejqeh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yilaafrb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuxsnru.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxabkbb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2elhodnwj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlckmhe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwvbyaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhfygss.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnvhrhr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgqhlpv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rszmszkd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bohjkkkc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zjohzaan.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtneddq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krtuwyaz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghovgoph.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gciiajnh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2evszwwui.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvybzdjd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nlobtdlv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeloiyv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cvahtbpk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkdmirh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrvoyxf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwioerok.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfalvgqp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdknetsv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oindwulx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rteptykl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnweaare.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sglszzea.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgcvwfk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2abohzpdb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wusmtury.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yhndqete.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoyawkc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hflxrzql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eavlhrik.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibitsqzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rllkfliy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxvsyzv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbamkys.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jfatqsel.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdfnjzy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2boklolvd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnohpvj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2detbrgvu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iotifjcf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbaufws.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfsglfx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdpzbyw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lltvmuji.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeejdux.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsgdnms.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiyznze.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2buyjpglo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vevnkhwg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2unkpxjsu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpipubj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyfwery.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyqssct.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxnjftx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hasdkegc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oewjkewp.html


<!-- 参考信息 -->