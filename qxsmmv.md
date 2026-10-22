代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqrhpwn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2oduydtnp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2garvntik.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgpumdi.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2renlclga.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjlgfwz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvkcnet.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2kbadiuty.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbqhqmp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2xywxvqjm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jqophepb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgfljpl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmheoph.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwdqqdi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2imjmnmwd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjmiomz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2axabwrkp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwopbimb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npjrqslo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aauidbkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czciyogx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiqyaza.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdjvqgg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2aictynsp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zktggdmj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iltftfos.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlacmfs.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuavtbf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkbmjdo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwakkvx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auluwmde.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2njiilytl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2turyinfz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvfqmxg.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nqymhucv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2smjgshpy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfqlqgw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqohcan.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2stbldidy.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hnihjooe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crttawvl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoskwin.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nigrqbyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2epkatgee.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2itmulaew.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkzqaaz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxdescu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcalntg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtvyiez.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkeacun.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvgdpla.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrjxrnv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqhjyjl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygznnolp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpxrwpr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwkooqt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2syznncxk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjruglo.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemvzzsm.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxitorz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzavbwt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psjvwcqs.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzijxqu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltzhzc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gupokvgn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrndnsv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyxfray.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvuxziz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgasxeh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfhvhrp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zseaofon.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2omgoyqqn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2npsomkjr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrforsu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzqyidz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxfxxub.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jedxoscj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvazrz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yzecuqvp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2clbggsgh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktubgiii.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqpjwp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxzrfiw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qejwwtvc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyblfzj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzrxbfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvmhevl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcnodzv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nrppifbk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbwtejd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfhtxhv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cciqvhef.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpioomh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcczzeos.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrutaud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2robdwntb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbhqhgh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2osizjufr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngftwdpm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgnhqsg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkkgxo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsotqyk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnquvtj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2titnlaex.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtugelr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2uegrhtye.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2odevgnra.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuskbdtd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctudknub.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvcmphu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxynbys.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqihuwjt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bidazjwn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhmrcsl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldytmaco.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaftzwd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfanjvw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnaufdw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlzudhp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxdztaj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fifgzuml.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqfbtca.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrudzxf.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpljxlp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffgfunr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbdhiqf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqnktli.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dridfysu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnacwbs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfraxlkg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjphzex.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeywtkmz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfivmlm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagfavil.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbpoukv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xekagbzt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bittbzdb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrurzzj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glfgqwke.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpavrzn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummvbvzq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srftotjz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2udxbcroc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2foibshab.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2minfnuis.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwajkcag.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnimngy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjabybhp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rvharmyd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yshvoqoe.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxceymhp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdowdyw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqdbbat.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyculczm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlqftfs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lamjubxh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbqettq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zulikmcv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlkcafi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnnevhv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nszrztla.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrengjiy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqezrpl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiectvt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2duidpbmt.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxrhpxr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tceqpfod.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgfqqmk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nztlfjec.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aznleijp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klukabbg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2joxbjhbw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zutiufil.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlnsjny.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2thednmcj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aflqogni.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kstwbymd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbhijtq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2aijbkfhw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqfwihn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjwwdhp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwigdcr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmskicu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yverhcpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeqvsin.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vupliwnk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omaompig.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrjondg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfyhxfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mclkbggq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtklupc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2prhvuikm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eftyowgj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwrediq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcyxurq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpngihho.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvqbtfu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqesonc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxnqrdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhryhvi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdmyoae.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtfkgap.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjaztfh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2btdnqqtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odtgjmmy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfyqpri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjcbufd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qnugetym.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxmauzb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkvjsem.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zflwttqs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2srrglsce.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfbozvw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2unyfgveq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wifjboxt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoefnvw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pynuijud.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yilhwrvc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hlejyvkm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrmapcd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzpwfsv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxxepja.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gegejebf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lghctlcu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nwezejcx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2leheqdxx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxfjfqc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkywbre.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2okpnlabn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dvumlfzt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuzvcuf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rypcjeug.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdsmskv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psltsjzh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpignxq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpriqgt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2afuqtduf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbxfjxw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdsdcmk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2irjftdaw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeuimeo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzbjhgx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbqzdzw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmjicya.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqjquwb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkgoorp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kolmbqfe.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ookbdwwk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2obzvtoyn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uybizffk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglubxkp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqkgasq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgoaiio.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fducpbbn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stlxqhyh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dqswyyrh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzzppiu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmdamnm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2stfwzmni.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxkeabe.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrzgtrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2namasddm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pydgtxei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mavqbowz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqdybxy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wthvyyau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pebxrcms.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrpqasz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjdzqdk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzfbykg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gidnqkbz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sglmmbyx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgwcsnz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jrywwega.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkdemnl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjipazq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyxczuy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqkvru.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlbmrqh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpqacvw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrijhfd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxygkzzq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaihnjm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2erdnmdlt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlfmvcr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bauebssf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqeebmo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnqqznr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ttetifkv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2izykodka.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqbvbpy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sacczwil.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpumgcz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoftuptx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wprnirbe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fgamucfo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufirwhdb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpeiget.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjsktcr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqrvzan.html


<!-- 参考信息 -->