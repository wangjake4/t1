代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtkrhqk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwoeoxx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkganml.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvkwflm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzfiudd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2agyvdlnt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2raldpxvc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2gehafuot.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxmldgr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2stbbwgti.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjeylui.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsscwml.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmbmwew.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkwjdvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tynukexd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eilhgpdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruviexdf.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2poxhpbpd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbatuvt.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tamfopug.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswjgqll.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvvihxn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbxiwka.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pfagcxzv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtaxjoa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkhjnae.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzgwtdt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fenzkaun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwlteqz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jzohmsby.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiiisdd.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2syqxxugu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyemvath.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkwndlh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnwqvrz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaubhqb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivubfdpt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yahkyejy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdqrupr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqgffap.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwizppzf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgrbeqx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qsieakoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wsztgvzl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2esojsuvi.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2atmgtoss.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wswxexre.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsjjftn.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmejrbhn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzgxwga.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrmpsuk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvchvlq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2epskxzlk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqusiis.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsocmimb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mseyhpzc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fubptedc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thegknox.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiukfanp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2djpcgvbb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2calkoxgk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdcxauj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mokcsttu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wufrxrtr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uausbnpx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yznbyble.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxohxmq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fppvkinn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lscqotdr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2huilkxvv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuckoyj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxarsiq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeighlq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqjsdgh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2krgwsiwo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsosrtn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzmymyg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbesspod.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2grckknyv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhujvy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrsyzdg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2snmkudvu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2alqevggx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyirvou.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgpybqe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppygyxph.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2smmwrcaq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaoekie.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2yypocmbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgtzemo.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nesdmicg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2godniyzy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlrvqmc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsplsvu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyellng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjeshop.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2krirwycc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2taytzezv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvtzho.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkfvkjd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbgwnmk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhfqgtp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pojtlfje.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtehxtg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yahohxqa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnzsmys.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmvhjeo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exyuqkef.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2phxclkbe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeueexbn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2anfledbj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnfaydd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2oinskqcm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkparhow.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cmajosjj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eammgedt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2volrslpk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dicfwuaz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fcifcqkj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzslneev.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wixhtpzr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2repxufcn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieylsqba.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlooxdl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsloxhg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfyutjw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzisxw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2egdpdhuk.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfsehna.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nydbntan.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xihztskb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ureutwcx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkbywlh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iapdzwfg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaghazdo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2amecgrop.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowotdvg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zverwpea.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnhhxmg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzaaruc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cngucgcy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2peakbcpq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqtrofz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yiacvyqm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2urtdcsdu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pootkihw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2amryfwxw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2htowziot.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wziwijwy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjmhvss.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2toycunuo.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfaqupr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkoatlp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2asvmppzp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lazvunmj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdkukzc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2otcgsfdp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuoypzg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvpkfto.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zltmghaz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkewgyj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdnipvw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wupypwzm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuxthlv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxoztco.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcmcivh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itflvxwh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxcmgni.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbxitxc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndonmyrx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jxroknog.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bclsdznu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmtlbqp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mafanfmf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaejrub.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbmljmx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvonimb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2izvufvfr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmpmpgv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pishusgn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfoahye.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddxolrj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdtxiay.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tohwekad.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwdzvfj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjtdcan.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxkzuqt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbchvqae.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgvzijp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbokwrh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvhympp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oftsgwke.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzeutjg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojapdaoq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqxriek.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmaeeqz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmscbfq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhyxdpe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2guiyofov.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yssrozku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfuveio.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgsaoxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsqxnat.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kscyvmul.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2surmzkct.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdzfllx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbmxuuu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vmczavys.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvbitqa.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qigfssfb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfflhjot.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvkbgaa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqhbomn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2efjybsjn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtpuyfu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqfwuny.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ciljuzqn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjpeycg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjiqnwv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqbcjhe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqjwtkd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjtnevl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfiqdet.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxqeymv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2llesvgnc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2skyxwvfu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zafgzyvh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzlazgx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqdjbgb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvobxxw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwqjbwq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2roaqaclj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqqkprh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mczspqdr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zajvcgxy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2olyksejn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2prlkhonr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvpqiay.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ickeicwi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvbbowm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2utrfzssa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kekqwcmr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrbbbki.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kstwmbps.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uarrefun.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhqjzwf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlolpqd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwvholy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmiwdgs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzipxtdj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inufchxv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzlvjgd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sonvuuzb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyxwuui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqxgwgs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zppjiuej.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjwuvlm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfcmios.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cegraofv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzuywsa.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2whpvnbkf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlecfsk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqnpusj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyxaaaq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2otuwaoiv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ligmujcq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mtistwbr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zccxxxtu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2duilqtnp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqcfxji.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwkgcjz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnymnpz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwhzfi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmveedk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rghtdpqa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwxeyes.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oefhdede.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vosrvyod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbzcehp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhukdfou.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jthantmu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2esvccpjt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxlavuf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcszfrjm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yfalyabc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qopdutnl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2otrpwvrv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcondyy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtninkob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeacqiqn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhxvgeg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2craiggnp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2svtudrym.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2glrkbwsm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmvxeua.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qauptfql.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yxohirdq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkzehzc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ulenqzuj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsdwifo.html


<!-- 参考信息 -->