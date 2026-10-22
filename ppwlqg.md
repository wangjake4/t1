代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2miglclem.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2csoukrdv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jaekmake.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zprfyqpx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnzkddm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpnrjnf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfitpot.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2qcinypok.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrelezci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkwusqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdavaizy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2btlwbaci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgruvvsm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uavdeuxs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcwpdvz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2roekduyu.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szroolze.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurdcign.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zecutoci.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvsbmok.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2buxlhjkl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2albxziqf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjjrmml.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxjojgb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2miiitrev.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuhaquu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iksajkup.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvqeegb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2khgbbidc.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzukvvkh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvrshta.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhlkudd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2taddznbc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2izwkgsol.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkandet.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahquaisn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvqtbka.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxsgjgz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uirdshmf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2glotlcro.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fxluyngr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rexyqihb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhsnjpw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgmvkqr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuyoqtr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gluiijnw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eapiifwg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2msnnfhml.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdfhpw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjwlpoc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohjxejt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdseswao.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lewytidt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfhicmc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2skeeqkme.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiheplc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nuafmwfa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwzvjte.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2liypnaob.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uharzbzn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqqdvog.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxyeoac.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaemrkea.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tervlqoz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcgsvvf.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vabymvef.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlxwixr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2anlkwtkc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmcbuwb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmlvaht.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmxafou.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpneobs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjnrqgo.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwzybsu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bniqvilc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vipphnsj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsxptsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlghapb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwzjauy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmkxfrw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjkydei.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2igkgynym.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqwmvvc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjvpqbp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxhgaxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gavobevy.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwtkgik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpzwnob.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqyeacz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hscxqgvi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzyqssc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptproyxm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfnfass.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkenuik.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urczqavr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbabxcep.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoillvm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2sosalpxg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghciqfbi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gimrrecq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpozzdtd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifjkmpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gblzcpkh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aevsvugs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dorpfddy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlrzztg.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeflvzhv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqbknde.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvzeqmn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjllguq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbiybfj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrsdjri.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnfdkej.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2venewrqv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsefufk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttikvokp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdeejxu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpqgbmr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2udcjrmvt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayacnqax.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxevtakj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxuytub.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhtzyvo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyshsaca.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlnesuj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozublcle.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtaywsx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmcjaau.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oacvqejv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkqlwly.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kftoasqj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtwxnzo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwvxlbd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fgemafph.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2njtfqgiq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2glyyhtfc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoihnld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2blurejmb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2uefvdyjn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2drxoetpd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdsiepj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvbkizh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbilwpoy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvbvyln.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zniaykpj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnajey.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hjelfbuz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2stcovghw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvzdrkx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjhqqrd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuhcaem.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxqujcx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsdkccg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbegbemk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrjjkeu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnxzidj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uenbrkaz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2exxbilfi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fexlhmmz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azgdsoxp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ageisfus.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2shdwaxhy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2enghyspl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2okhgdlgu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gslwaall.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkyvdqz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxayptj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2popqgqmw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoeuxuo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2frwagyvx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiivfqe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qirsdmca.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpgithe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nydocdil.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smydsusi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcvmaej.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2whmxmzqb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmixprbw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gerfyxqp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfihyix.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pktwasvn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcioofmx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2psnoennw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaulhgg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyajfny.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuldqop.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqzzupx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyjvabv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjygzxfg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bswfhztd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xnalhtxa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dymjgsgn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2prrtjjjn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lotzbepj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mctmdneq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2axznacva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hruieygw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2epakwoao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imzwctmr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2grtmgqni.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvytvjo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmrlhlf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgdclxi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvgrdti.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdolwetb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xehigbnt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvviwdn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjhhjou.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhdumnn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpppazk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2egahyjdm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxyfkgq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fsumutcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbcrbgp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdanpvxg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lsragiip.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsubiwx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zbewyrfc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kstqqdrt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwxtgli.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ousydzeu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wgawooeg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpzpdql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2atujmijp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukprfhqq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbabsgd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxagzrn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwmwadw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuphikn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lookuyde.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpqeknv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tibuwiwt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgidfdp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lnreejar.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuulncog.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ilifrbgn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzicrmwo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ultqhdut.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnishqfp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohvhxuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2boqmcgdm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmxhean.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eawmyyzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isitaxpm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wvetfcgb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgppkcl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kawttmti.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pynepkza.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dflrgrns.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoyaokw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cammroxm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dchtzqzx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvyikfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxltqah.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieviotxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmrkldg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtxgivb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2moubxoke.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfhrmxg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezqcxn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxwqdmg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgmumdh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyzkyne.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbzssbp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mspxctog.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ctctangb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2invnggua.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmdxyuf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrhqapo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2upqjrswb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaqoive.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jagczxlc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuvhrvl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2axhwfesq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pujbikpw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrijbgqd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrvutvd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvxqobn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykorqlib.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrzdqum.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvwwvjk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mudyzzof.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yswjoscz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsplnup.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2owmujgqt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxfwysh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxdzsyf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrwotqi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzwhsxl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipotajzm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rioawbxd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2omqtwflv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfaufmm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnjlxsq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwqtwvf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdovcjn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2edfgipkn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ikomflfy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrsyowa.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxrgeoq.html


<!-- 参考信息 -->