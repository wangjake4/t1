代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2satbxjhm.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtomgck.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2edhfumlz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xsztlhwn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmklbyu.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnlxbev.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2batmvmip.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2svovercm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ricmggdj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwblhavh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2mppnwhoo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hkukrcbd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmbswyh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfphdwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kslpvffy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdrqzbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjnbxay.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnzxbs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeqnuqt.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlbcznt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iexwejxt.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwpslnx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqjvuwf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2czapngjr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2tdozwbsq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmzqbmk.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcvkan.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmusbxbn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqlbext.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdcexxi.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xwptnhzv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nowhvtqm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2szryshnn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxufzcl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2utbcsalm.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nalewlnt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfyadvr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uopocwwj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2knbpcacr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksczxizv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhphesv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ongxlybv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qbduiquz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ctowstza.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2denqdzir.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nralgrgn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2alaqhgmd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzrpamg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfokrdx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2meaeegfn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xswycptd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2guifxxhk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvtxgrg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrkopar.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwybqzo.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdftyqy.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrkvome.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzwjgqa.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxicfqbv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axcsiasf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2klrgjnqw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2toporrbh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyakrnuj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvirrdob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqgcfxh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2suqlcrpa.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jstypbrm.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeyzgcc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iokdkfgk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2msipdfwa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeuwtzf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmdfcck.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqtfnfc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ngclnica.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yimxcpmr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nparzmgt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfadhrx.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeedlmi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2elgfoqxp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsousey.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zixhxlbc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkugvac.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsthzqkv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vggyortp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrfdmip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cubroftf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgfwitj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zanafmyc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxungxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kndmsdgu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gpamrvzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyauark.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmkwich.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuolnbc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oremovyx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rctxnuav.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvlvpet.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozpqerd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spgkzyiw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jguwvgmq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcpucxr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yajnyhid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvxuqjs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlirqvff.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cspgotgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aijofwiz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpfmmpz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbwfaqr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfewmfp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bijtfxfy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkqohtl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2eencsrjl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdqhosh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrwlgrr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cqipzxaz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtvhnnf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fothkphd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiodppe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhnfdma.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2cteiwkal.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwyjfku.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjogrnxk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiivgof.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xreecxrx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsqjlli.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdhsrxs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwdceri.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdupbsxs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfpyajq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usdkjlyi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmksejyv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bppzswma.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhfkjdu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkjgqwm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoljrvjy.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtkvyym.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uctraxvk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xllgtkrr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvivema.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzclyvkl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogidkztp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffimtrif.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qcctlutq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkwdlfu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlqkyoc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ocreaebu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2clgwqzmv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2evvawawu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsisvfc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2depnauff.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvvpoxm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kagntidr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ziirhsjt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgidqcj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnqaeuu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yanzpulb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mawbrecb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yuttpufi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbyxexw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgdkcno.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnbaecz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxqyfum.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2aegjwpzg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwvaiyh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htbpxyvf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pacbxlwt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzunsewx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvfxzno.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2glcprgca.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pufzvxzy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2saqmozxp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2duyzfnbl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsoyyxi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bsceynnu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2twromrdg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsmditz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hviernws.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2owanaqci.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjpeuxn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2swtogiqk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2leictvix.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkoqzli.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbmhxqb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2syvjwqcm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkxaqly.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iisaoygk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2stmgptaa.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnpzukc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaxmjyw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sldxqeld.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2imffqzfk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiututr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkdehjc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgebipfx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmesmml.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdjpavx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2egudbyws.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcqfuag.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhgxytm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhlmbfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzyaack.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lejlveij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnkxboz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwztzbc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqxwsth.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cugsvhly.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkzgnot.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwrtqpq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2heqpukec.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2krpdrpmc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktetyjvt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdwitwh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hptgccfe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzthxqs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcqohgu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjratt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epocpdxt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhenujg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2casyvfsq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2csvbapji.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kdikubjo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2olqrtmaa.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbhnjlo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uevqyjhq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dewptrho.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtjwpse.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgrelwl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnfcqei.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hepcqfrg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxvdyku.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2todbaqpa.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxumiceb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2niwbtfkx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfqrfvl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnxiqnb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zowgzbvu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdqtmny.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrotwbm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjyoarj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaannhd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgrbzqo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeophdv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsizeyq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbvyvjd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvzrorv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2flbobdpj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qproetrv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aogzvrxb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ncisildr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgugyb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2budpvkjl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2smftwsfq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nypujhgf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfjyzyt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwpatha.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2meuyoaua.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2spqxqbbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrbdcdi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sascyuum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwskfkjc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2imhkjqrl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2scrtddjd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhwoktc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2notahato.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhguijf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvalqfam.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2inavfbyj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2giwnisnk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtspkwwb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyftiim.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzvpmov.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwdcxdj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2thpiyvkc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsgbhug.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtguwftl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtizjtm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2macwpfzd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnmtmhu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kusquxmq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ephittnb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfizttrl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahypznsn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuepjwy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2peetjiug.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rayxykcm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbibuhgp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvujkkg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxonibs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cdixquqi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtcpaqh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jdquycbw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxpbljo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaxixqh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygattwov.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ewirvvqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rekiiqsp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrlrauo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2amlfmamr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aqknredp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2babczsrl.html


<!-- 参考信息 -->