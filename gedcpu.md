代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbqrtvs.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkvdjkm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zabhyrth.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wottwxhu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2funqwpgu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2krieuodm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoavykc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lomwsmsp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnpqdnv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnbslqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syeooksn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhkvvgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbubqni.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2otdnxilk.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvqgnzi.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaghqrn.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqwclky.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxwisoz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcbzgjg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcabafo.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkysyrz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgmbbks.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpvfhva.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbrzgdv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpfcgau.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uyybfjfk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbbbysm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvxkiiq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ashefosv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqspdose.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhetdkyg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uksspwzv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iemjrjfu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kczpdntq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2togvjthh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqdsech.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbcwiqh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2feqbumza.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2srqrqmfg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2onufdves.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2axnhbykp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qihycssm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjciomu.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeqiqbp.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xixhkjat.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2axbobuya.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2edbxtoae.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqsprg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yddbxmlm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2acthygty.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqqjqsw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2giwacktf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyupndwg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhcpceh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snnjyotd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbmosko.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgrvpyf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2awkarzqs.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqgmcxm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxjzmmf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2unukkuom.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxibdeom.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtlceaz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2owigyglz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjkjzzq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqtbnoz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcukkgzm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyjosja.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kijrwuaf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dznlhtvc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbmecx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzclmve.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbgtvho.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tozppwer.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqjvvhp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbzambx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2slqcqmvg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqzivds.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdpxbdw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcvqigz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoyrqzi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2csslybos.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkumyvmy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2flhdsjly.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsexipc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdstaxu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvtxxzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sadeoamq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvixiwk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lunegzla.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudnnrl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2agdrxwsk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqukrnh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfcmvkh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cogdtqhv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnwjslj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vutsvddb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2egzzajkl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgfrmeq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhnksur.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnrnktc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoonsrdi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdqnwqg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmjeovf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2agzasowx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhuntdi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzxvibw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovprsg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvpoklf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyizcken.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdstmzk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yszzyllv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2amhgodku.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmiryny.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kqywkzxd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2swksbghr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dihiifyo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfvhnsu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvhndma.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdovhzuk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwpgtji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqgdyxw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxrmjgo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdhiurs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctojewsa.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdtxuqf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagvnwmg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafdwrut.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbflgwp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnjtfwo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sehookjs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcewnrui.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpzryae.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2abxxwqvx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgrcfbw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkpgqga.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqieuxql.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhovjxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2agibidcr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uselksjx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qeouwqsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrotssiv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2icvsqnbg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjjynn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rukfrhep.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmdlrub.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyfmfze.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2okvmqgng.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tesfxjqf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoupnqk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vguotofy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmnnxte.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpequp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbtjxab.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2checuhdk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgqtrmr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeweulb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vycofmcx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2apzdcfcg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzpqyhr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sadslzik.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgtvtqu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsmudvu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrlmrgx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2prllqanp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tummpqaj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hpukradn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtczfcj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmnfvwv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthxteq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqqpqib.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwkqbom.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvsdjuk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahygbsuk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwjgfuu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2obkacest.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwbegql.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaukjjly.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjblazmk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfcojgt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwjxiap.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2asqwxxty.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2exhyhtot.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2emumgwhg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2akuxvvft.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxcdqiq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ughyyohq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nunrdcja.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tddchgzk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2olzqlnhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oylgpehm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lakilfcr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2siczhize.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fviavxpe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtbtty.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxwynzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbqpicd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzcaysz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtvkitc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tgloihqx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjjbdye.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drclnjul.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ydamjzyt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvhmggw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdodctp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvlwjyp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqeslin.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2egrkokze.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ckustiuz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdepnlu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2khlozpxd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xnupowes.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhyqzkr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqjahvn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuqqwkq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ytniulud.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ishgyeqq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxjonnv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyshtco.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vuldijoc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kjewgibi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2abwtzzbp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbxhzop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jczzfchn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afltybuz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvcxtin.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhalpie.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kndzidkz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hemevgaz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxxdopw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuamzeuu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyadsgy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxasinz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gatasfoi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psxtdfgt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtypugh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywogabje.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmneaex.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuadrxk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcfhaix.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnekdfax.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2aguhtefh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2arussmpg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oljogloj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwdhyvc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2anmjstxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdywowwh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vchrzduq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cijfumus.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2musgsiqf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2leokfccl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyicpqz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pwttstfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqptbst.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjsdvim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzcmlsb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgjfijx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbduuly.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2unfjiwgo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cttlhkjy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aivduvje.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpguxxg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uiabcfyk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oflxeguf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxfnpvb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2njjbopio.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tymxvxkv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrgvltu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgdsfif.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoxwqok.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pewlawow.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zallsmxp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yezmnxon.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcotyqzq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjktdbj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoraeea.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2axztmjhf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkktoqq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciulwvuh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgsnukb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2akokwnip.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjwqxl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pzynmrsg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ilduluym.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nljulmoc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dztgrsjq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cuirpnzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cqszqbvo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxzyltj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2emdybuza.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xetauhuc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpqquay.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2btdzfoqj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnmoxkh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjgymku.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qjufvzdg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzcmlmy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhejjfk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvnnwvz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2scyrgfvp.html


<!-- 参考信息 -->