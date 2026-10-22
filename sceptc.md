代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jaahvtfj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2aducrceu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmwotls.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2auafxoaw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mriulyih.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkyhuun.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2smsvukua.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2etllvuoz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvtdapk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxxmevo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdnphim.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrdlswq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2prleibzq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2crjwxwyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ravzkwab.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhdwldk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfwkeun.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrkxolw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjoikax.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbobqvy.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqoelhp.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eudoiclf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpefuvb.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fxikznjg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qijjnkrw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdzehtj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxnnffn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpshqcnq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijzahtf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgizthk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeanskw.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbahrpq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkfaukv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlleojz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpkacus.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjylqtf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2meuyzkcm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafjguo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2upliteil.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpylknqk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmterca.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwkuudb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcjobbi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgecebb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ienszslt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywranost.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yyafgsdy.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyzrykj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hojegmkw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2htljpfin.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrkyfwc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2utrxpkwv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2eglmpnlo.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaqviyi.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otjuflhg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpnljky.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzeuzgm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sayjbddd.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhafvde.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvkdgxk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqccpix.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2rljwhtwr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2trdalupv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iacmfjbj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2amxnqpfw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhbqueh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zygtlnix.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhgfosw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2accssjwr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtkpoyj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxtihjz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cicbwvjv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2avefhzfo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqdgcfj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqaiobq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hxglbzbs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrvkcby.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfapumc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhbrowm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbjxsqo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2srhipzvn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbkxrve.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyidhas.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqtakcy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqnwvkd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfmgtov.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfgfckd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwyeexm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rquxdpaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qflfpyqd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzkmero.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yumfneiw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxzuqkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2peqyzrba.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2feyxygde.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2opetqljx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aacfdyro.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgagoxac.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzpetab.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2apnjzpmn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brlceung.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzovocui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qenhqeet.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yefkmcnr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphzfazz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvlgbfv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfilxgzz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwqqcte.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uoenoyrc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmttgkdj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyqztli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fhelowxn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvdwhkp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kahrlgoy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmisdfd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwuzwb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bxurcoxf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2iuujarkk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fpztffxm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaeyxid.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhdboej.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbvnqwq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yifbljhr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaltqctl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzinybw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvadeeqv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrrhybq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqhgdat.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2pymqahpn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcjeayo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlnderl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktqcbuo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpkbtyt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2stfnjgbv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzglxnt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohislia.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elkwjyxz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrmqcrv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eltwcrji.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gadbbhjq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lasyzfap.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaotlbc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeucfah.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtqvuod.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2powjrfjq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrmhwxr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aftacshs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2skndhtos.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gtelylgt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dumxhorx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tqacbxgo.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2emcralap.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mbskvnae.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ouacscnp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gimwubqs.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pelqbiwi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxadgwll.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfolvzs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdlvft.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrljypt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgwkmxo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pejgbjrt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqltxgm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqssxuz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuprgvft.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytggdszi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aortcpbn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyreijlg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ludjzehq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwltyyr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oprlxvqp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnjqpdm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqbrtvp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2poitnclr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpmsual.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cstgnjxz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2inyiplmc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxragzn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utuqbxkh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2grcxubvy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzbcalb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcctnwkk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aukgrskn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2osknynva.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icijyibo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2etadhmfb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiiroys.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zeahkzkj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjijovw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqpzqfr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zovhwrps.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqevqway.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkdmdml.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvljtqi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbdlnaw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyzcvnj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdzvapr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzndpwv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtitahd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ssczqyys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsggpoip.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqewzsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sovempxp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzsvbqk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2thngcpig.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqikfbn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nznryuao.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqclktp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxkctre.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcxsoaq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uydljspd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvwbmgo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmvhnyo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsxaktn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2akdfmctq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hcezidbr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxkllnn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxelryc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtetyfxd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fbevjpzl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2swhqyqcr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2gabplqtg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fypdurpo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uvenpdpc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpatiuy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iigqhwkq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjvqmle.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajanvada.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2clsvxcpj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvrcryc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhyhoup.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsznqak.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bzquzuhc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thkwfqts.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymewjoo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hiimycpn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzcatqq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2emdifddp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2druuxyhy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhzkxrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmrvesu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvmyqoy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiertmra.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zngpmaqb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2arlsyquw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvkmchk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrrzvvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izwilotl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wieqbdrh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2sptxctmr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuvcqmx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nalfddtp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrmterl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2alitdbpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnryduz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nuifehyj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cxratlcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxakglvc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvaximp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oclesjks.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxwnkm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jglwtaff.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lilwpqzf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzzdptt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjrpeaw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aputbeiu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmqwlkr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zgapgkwg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwuvnmjb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkpelma.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqnjcvi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sajlmdmo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2boomysnk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mduhkhzb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2isfyignu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gekpmlhc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2asuvwcgy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbyzflo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2saaqsquw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxcuukj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qslcdcbr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvblcggc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnllarf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeyjmxs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jggrxzjt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaoznsi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gpszuvhl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2amkhamdx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uczntqxv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2slzxvclt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2krawdpig.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqispte.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqnfsto.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvepalfd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaubnvd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzazsnea.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vghxvnuz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqryrjv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mxivmymq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoyowqf.html


<!-- 参考信息 -->