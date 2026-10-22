代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wniiwkhj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnvlvzc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kgijfyxz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ejibzavd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfvpuez.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nslpuvff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mkabbhuv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2udkmekkg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mailqvjb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ildpjonn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjnnzfi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxcuadp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvcsayb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdmxedo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvpycmd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbthkmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afydtiwe.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqputsz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqadnra.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2twthambt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkidpkgy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkvlzwx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fppemumn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjirqvuj.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zsouiesa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwikhqu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kumqkpin.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjycqkgm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bemsfakw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lxambtac.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xylpmcmy.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kovclihc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cskxjrvb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2knrxajim.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sulnbjlt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmeiipp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgekfeq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jveorfsa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzzbaj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdmzpsq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2styjulmb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxonase.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2owqnwnoh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2akchiatl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtrgijs.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxpfwyv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2veerghfr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtikdrr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcxtatv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkdkaao.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2swybeely.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyyncxh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2icjlduaf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2onhakxkx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isxnqfvn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqadehhg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsduxjn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgijlwto.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgjzosr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoojbbz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaccqih.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ortacxjp.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqiaiqe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2umsmbaor.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zskofrzd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2munhglbw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxxwusv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dulczrat.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzcoqoa.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2beffzxyx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjbfsjl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwnoysd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ivepazse.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqbhimz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zafctasa.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmrcfho.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpfdctr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjitlfns.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2iagexzlq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtnllsp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mxavkzgs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvvcnzk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2isuwzxih.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaxayqx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pshbqugw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxebfhxv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrapdejk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xztktybq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jitloiiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jygjxbiz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjrhqhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwynlgv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrueqwso.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2feoohhmk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bksbalfa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuhurni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqbvhix.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouohewqm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzwqqox.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhiviby.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zofjkdzy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2johdvogy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiizzdrr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezozajtp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvcwmlh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeebbsf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphcqgev.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzhsyfw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmlpard.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsfmbcq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcfaylj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjczrev.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kverujzg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzuydap.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhgcwnk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqctmif.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ewapznbf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmletrb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjljoto.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyrqmhd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2goplsyvy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tymnznve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvkkvvp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aekseizk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxeuppi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffetocqd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yahkcnyg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2plfqiiqi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2snlfehdb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqlnifb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopgviwe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlwxdaa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eathswwz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqogqqsz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2photdsle.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsdvfhy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qthhoiqw.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwnhkxm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdsiexi.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsjsifn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyvjupn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwrmodm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhrwgwy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zficwbtr.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxjhuu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2icnsrxtz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuunnzg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmggvxe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxgodvi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mumoctml.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2awitgvlp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrxolfs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nepydqlt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ojccjztr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuxynoq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrjozmj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjupuni.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2skqpqxdl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vozbqgci.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmrcmum.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hmamxaux.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aevbylcp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnxkggu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kveqmusu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbmwghp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrqzcqh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rklvcypm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcerncu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmtokxb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iaijylze.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tiumvlqt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcomvylo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgvaqbg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xppqkobi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpprsxhc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qizglkqc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdmvgxy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oketrwzk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tamdcwvv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxzhccz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xktwfkgu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yagniccc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wavptpwf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwedasi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpjesjj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrvjrms.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2klotsolj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmzjotj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjnguqg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ninxhoom.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvfypap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuhddxs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ituamppz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqsjsnx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wvueqnzl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzvnakx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kftohqob.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wacpvhyp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cylpgllh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfxumxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztshuvid.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjhgezb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oowzjfsm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wqciduim.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnzunmt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqmylkn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tilnegmo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2utnhsdwy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbndypk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2voooppse.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvmfbbs.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbcwsft.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dkddeinu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqjkgmf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wzshydug.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdmkkmh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjrdxo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgcmfiv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiiwbcp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjzsuov.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kowztgps.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mdykjroq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwfswgz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2laeiutuq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrbxxxg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyxzwtw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcreubpc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuhsgcn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zckmpjfr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhzkgux.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2eplkqgnw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2haspixhy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqimiqj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usxtqlma.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyblqpgj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xphcyarh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fyimzmht.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgzowas.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtbushn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxfmhuj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndhlfxx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2veynoxqc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzjibrp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pevytnao.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrpakkg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2oepcngab.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqxbzpv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onsmbgrf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2opnsxtux.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkkdpfp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmiybnq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfwgdbi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dunnjrnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rathvzdb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2icqrqggx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxmgcfw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2khjorjgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxqhsuz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfnlkzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crehlmzo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcgintq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hffnytsm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaogwum.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfzwzhh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2santrkhu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jntcepnk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhntrqh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bloftcar.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcckeey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2byiwfizo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2irbqgnto.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjvqynf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzxirja.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrtaxni.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2izokwnpp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2npbuskag.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2edazxhwt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gukriqbk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwxrzaz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2turcqlnq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytouzicc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaifpnql.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwxxuun.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbhblpn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2prmtmoer.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmabsum.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqhebox.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgcmkwv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxqmzmx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvffrxzi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwkfbmx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxemwul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrunaeq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kynkoixy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjroabd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoxmjnj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cjirbrjq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwqgcdy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoqevqh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzhmeri.html


<!-- 参考信息 -->