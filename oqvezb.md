代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnhqyna.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxwwjbt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2skyvmxip.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmeskul.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2apyfenpw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhiqfpd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jayeabqp.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzajaezd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tadkvusn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcsnfof.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywjppok.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqmrpns.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2htifmibf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2omxdgquf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdxvnbh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhcdrwp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2czmtpjsv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrmnfgt.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2epxgzbhw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2rdovclht.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhfmpbo.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmseiwe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2topgjjsq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpimmsj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbuvoqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqxkisz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2srhizwus.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgtarb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2svsttybk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iztlggbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhkxibn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdhnqdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csvbrszk.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2anqlzqfs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsilrah.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mefrrpph.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osrtjdrw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtktoii.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhyvisr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwudskv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2knbqevnk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsqzkzw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrftkpgy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnoulzc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2juygarhx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2juqbxdfw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfhxpjz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wegbmqwu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywngpkqz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnejsjwf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ishyajlt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzzqrlp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2odqookez.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsjlbzh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijniskjh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkplwhxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlirntif.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxbqgat.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhrdlyi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vilrjkyh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvhpmuw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvwgmxh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2spzrwbka.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjqofqa.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeckuhlf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyhptfl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dohmierm.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zfduudyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdellak.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtodqdn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbqslcb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsphljwi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexlctgo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmdbssy.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbdotnj.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2todzewdf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ackfphwt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtvpjgj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqtyowa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyggiabw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsnxljm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrxjcyx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkhhniv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcajwrp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgzquij.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbhmlic.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpqrmyt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fcutefgf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtyhdiv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xqodhttd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmwxosv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrcsysw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2crgwwqvj.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2djbuziyz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2whcfmfpk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2scnmjmig.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzemzaf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fftvlosh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2oeldbpee.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbtlbaw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mluuqgqz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2reufdscj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuajlxhq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaxxugd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtgmocd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwkdirk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgqzmzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkiojji.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2chlbcmok.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkifeks.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuwolnb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sujvpcmp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoydsdg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdkcybf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjfohul.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2swtrvbiv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmhvfva.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaizwed.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2stgmjjrt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2werzsdxb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oypgwwye.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2grpoqvcf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhiblre.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqguxizx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2etykkgre.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbhxfq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsdtnfl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvbrxmg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gawvzdat.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdibuhjk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbgxscr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwtbaqh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nytiamjk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lwieqctq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cigxzrim.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhttpps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhmbkcv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjdtvid.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pscfqvnm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hylvkzwo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aucmuhwq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhvrklz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyvxtsy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2malxwpve.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2djgrijze.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhczqre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkifhryz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhgmnrf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdcdoga.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwvapyk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhybzapp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzyljzh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcbemko.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvwvsaf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfomtob.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhaqtyf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvdwiyz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeldgki.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mpplaanv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lwollpqy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2paaakenk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdpjhof.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdmetwo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgqzcvw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bgveyetq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xouovxhs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oavbaryx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qoypgayd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xydyhlls.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2whqldehd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2letpsxpr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2quulsnnd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnroomm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdufhvxw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtgnlui.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyizdag.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mshkyhua.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgcxkvf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nakgxajg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oqunsbcw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fleyvodz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2loyemhba.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oacfmeoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffybekbs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2guifgykn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkumjyay.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ccustxjz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eywjiopl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfljkqq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbzrfiy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2txqxgiza.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiadnuet.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lorljqvc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznfqqww.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvwuwvl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrpbsvd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jntvwybj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aozwqbdr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaybnmq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwwljcf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdkrkeu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyatnnl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2syjzbfrh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eowbycqf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbyfvjl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hakkublf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgcucnn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mddoistg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdimkwa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mukljriz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcukprpm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2chawfkjo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsnxfzy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltffrdip.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefjdlti.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2caqizdtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrznxiyj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmwfvib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqtwufn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uqegihfc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuotgwf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2znrppofw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rbevsxrf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aszmqvrd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaxpgpl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpagccy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdmesmj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtxflju.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxwxadw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqropfkl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iaserxpf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvfjycj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsyidda.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eozrulbk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2oynfyynb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ubryiygr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2paynmrgh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxrfxqt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqkprzt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lchrvukw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyohesg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ifprvtrd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gizopapl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihigislo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lesoyiom.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbzpbpu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2osglwnas.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcerxwcd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvboykv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmfjgnh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtckocgo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kesdbunn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2anldxmce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fenxtmjd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccowqavz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmetlxq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyghbhdv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkkcxdz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhokqxbc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzcxtan.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2iakvdwbd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpycanv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2akrygwth.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwliatfb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wuufwqfj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2oovcwegl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zftzhlfn.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qoetcazu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uprvbffd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbhsnj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcrtnkx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwhoazb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwegggr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hojfvtpj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiksavb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgomnwx.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmohgcs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2inwfbgjz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cajsusbt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2odkotdny.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2grjvsoxp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aesuwfap.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzgbvyk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2anfobxdv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmhbyin.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tclvgjvq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeyrepv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2drfmwfok.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqzykgi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmnfysy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuzjazb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jconzzhf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gurnyeee.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rryxrqaa.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnpltzr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qourqotr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2goyhveyr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kueigtxq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnntqehz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dotkixop.html


<!-- 参考信息 -->