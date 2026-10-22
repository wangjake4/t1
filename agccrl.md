代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjffeys.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2eanyjmmo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdkpgjx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2eramybse.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkuqguj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2kevqipjy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmvgcci.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ccalqjbb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcbykfl.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2uomtjkfz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyofico.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kblhfims.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2thxwwras.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpdziuz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2smgutlet.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuvqlex.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yooelotp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lurtcrcj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcbgltt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tfycbeey.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2imuxjncr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylijvqtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgghegjf.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjjmuzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbqsohy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwnghvx.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqplcep.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2awstupye.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nztilgkx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2egayevzb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2amtypqpa.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bchrhcrn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rbznzvgq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlbhdpd.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzpvpvl.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoaghoe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2izwdnmjd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlnyyna.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwhzguw.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sydsdezi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvadjpjz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqypxppf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhwvpgj.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwhxlkf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tovaglmf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bavchvwn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2smtcvynv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnfwpzj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbaltdq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gohyppet.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwepwgc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqmvxhv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwpeogg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyuxhfn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2llddohsx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkuhqw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cclxxhmc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mprrormu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvbfuni.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2eheuncbb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvyhbmj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2aljionze.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzejktn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ninskcca.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzydrwd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiatejb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsfwfxu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgtpqob.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oiabnpbq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwdreow.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkvduqk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbgweyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2skbiaslp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjafuli.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2atdijtxx.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2obftfzmy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnmgzoj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2odvbfaac.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhgkubf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ezczysyn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkjgruj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvufegu.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcqfwnz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qthrttzo.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhgtqld.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsugzngi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lakrawvc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzsuaad.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2edrpfwdn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2imgaaydd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2liyiwnoc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uyclxqxa.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoeends.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uebqeqzp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlufesxq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rrewsjbx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2elgscyce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxazmoxv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vldulazg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agadwbta.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdmeafe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyhqhfn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlcmtqg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fogakxfx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoesowb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiabgbgm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiiuvye.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpagzkxv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjkkpcj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfrzjls.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2orhhvhca.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiiessq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgybxdk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppocoxgu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzssapl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2giiuwsuc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgjpehe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rteiukea.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmttuudn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2htqhyogw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcncdmf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xciwincu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2loahekhv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwwfflo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ytepaxwq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnrizoy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgmxpqk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnlcqsg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2filkixju.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epyfjnph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulshssji.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfadwfiu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nigukffx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsmlnkb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbfeqqq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2axxoklwu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaouxut.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bynajjtx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imrjxpdz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuojmgmd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2recqxasl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfshvkbm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenphgkk.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qupzfbfj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxvhbvi.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqblakl.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2adinvwlg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xucgrwpg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jckjwyij.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipihxxbo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkuczhf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2egqwohej.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjegfxp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnljyna.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tljxzxdx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2iyotmlmc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tybcmukc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmzuili.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2stqennoy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcrzzer.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2asevskxk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgckmsc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2iflzenmf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2twfasoms.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehenojq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2adcaucdg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kksgdgjy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxnzjio.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvcmavw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2metosjdg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qmecexzi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxwwhrb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcbrsqr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaeffub.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbflrnkg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwanodnz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfxrdvn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2powqblvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqcnjcn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnfqqcc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaewknq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcooqvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtbgbdm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwfyjer.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nezsnxlz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uffzsmxa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnleaups.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlllkjo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qitwinxr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbrmvyh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dgczdxsh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2txorpmfq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2muoahmmn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tviygzff.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bosowfon.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqwoyyr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ggniyjtb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaqfeer.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sowjdxdw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpnozys.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2irjjywud.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2coerssax.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yicazlvk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zksnnsza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eywcrtla.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kemccgmi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsjqwyf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yovbnivs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chbnausa.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mllwtrox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfqnhpe.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2znctzsid.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzuprbo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bokasbjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ksinwyht.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nfemeajn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2djilcryt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2irofkyqf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzvunrr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2oqplokhz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyohpjs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bapulbcq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzzyipp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdojtyyw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2shvkfhws.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfawgbp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nztjwcsp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xsytkuwn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiowkfr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgyzgwz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxubaayg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnsngbb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyiukki.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoolaia.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgyucsd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxwvrrs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzwavvq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxaicv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rchfizdh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgxlxuv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dabmfjjr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dicauifv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enyoxwvi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuygdsh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhriwix.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2aprfvgrt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvekizpm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmlbmpn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eauotjnm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bwobdfjt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtllzeab.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxcskph.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdavqun.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2blzmqkyo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpqonbb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dujqplou.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qeidollc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwgabic.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsufzics.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nnocskky.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2faxpevkb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlisqyi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgbystn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrgxcel.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2khighywp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dghjkrye.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzardxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuzmdnk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvixsyl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vghesjuo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jtydtorx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmnhmtm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkapbvzt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmvirqi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdygkcu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2adjioevq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvggejcg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tpctkxxf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmddspp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwjtytv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gyemfulc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvsjbmk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltxjqgo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2apxhyfri.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhysurmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tiggskmg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrtcvlm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwgizeu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyrtlyx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwmxjly.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfhdlko.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsnivfa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuigvld.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyeqguk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtbpnzz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2irvqvbid.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xheszjjj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrrcobk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnhvbqa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnntplj.html


<!-- 参考信息 -->