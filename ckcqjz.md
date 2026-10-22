代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtxanxh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2iugcdwyr.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwxdwre.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnacdno.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2azbsxtov.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrdywxv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rritqupm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2stopqoij.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bodohexl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsxmoks.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2oaajthrc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqhpmvp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxqsqoy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyexjtoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkwidls.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsftkyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oziubpax.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsudrvq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqhrfv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2abroyyou.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqjliog.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2loyekmmb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbricvg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyzfzmy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhodmrd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ianwirba.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feaqontz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtccifi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeiykxr.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2smoqznjq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutcbjz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqynvodx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcddjgib.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcguvxm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyjmoyi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2upudykpq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hacttunt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cafpfxal.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsnzpnv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciehnhqz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fenpckez.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbeflpc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzmacpg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtaalea.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2crhbnedw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gttundyu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxdenmb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfghcwty.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnkzsby.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwctdiza.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bybgmqrz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fymrnqcs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kituauph.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpabrct.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcvnyrz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vadjsesy.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckycxhbc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2taiagqlq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aordpppe.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ducmzjld.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbglxmc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2iftfwidi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ayopxghe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2godaquyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtnayee.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlsrcdz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjavvmka.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxzwnyb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvntlory.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjnlhu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmsbfhl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuapgeo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pahpxvps.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrjhalh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sqilbsrj.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlfqagi.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2msbylnos.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrzfqcl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwcdorr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcbnihs.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tukcbxjb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jecpvmia.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwylthcj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyuxxtr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxzqnju.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwyfknu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2apfejauv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2grdaeanx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrwghfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qihsypxg.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2domcvwcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnfbtpb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkykcfo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibioxdj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhlwzw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iefyqive.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfeqsir.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpoohwt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmmeoah.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrynzyp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2agxvjqsh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylahuzyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uohnigzm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2szhzmdpu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlnfwsp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlysunho.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcqlxeh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdehxge.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfjfueu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqskucwl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2shrejnlc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pytvvnkt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qijrdgjg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmihszp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyabujtf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcboamc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaweprs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzvcahw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmiyqza.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2boyblqrj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2einavkzz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbmjnbp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsqokow.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohucvflw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqgbqzz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxelsxlm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxuqwav.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofealnfk.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjajgmos.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2neseuoxg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxybatsf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfpaslj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hglriznl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepuvgd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfzzwio.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2leuakkim.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmigtrm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnweki.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwbeoqq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnilrjca.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuonsbc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gteohoqd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbfqniv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llvadhuk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2elrtqilv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2awyrohgr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtdwkgt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2atukdbfi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lofkvjij.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiddvpuc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2doikmanj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2acgfnzxi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wiogxqtf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qhevykuz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yaksfkco.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2aocojkfm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfjjotg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgexsde.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zymlsccb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnocuxf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeezggn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgbmulc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpkbcxz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qnswdrer.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpumxxls.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odakbgix.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrbqkkj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhgqhiv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxumzh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdbklvb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2htcydzmw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnwhdee.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ratpdisp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkkhtap.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaaahvr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jprchtbj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhwlbez.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxegrrrx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xedvpqxs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsvngum.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lovjgkqf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amernzaz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkjzyjy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvsicaj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gozxpljl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcsfcgw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zolqcbmv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuwsrcn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmdfky.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wbctnqls.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlewpqc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcygzqw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyycsdc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuhpixg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoithic.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jnreruro.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eefjdbrm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcctlgif.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvuqtjk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2adcylxix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmllagrq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvjutox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiintufd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xstdphst.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuugbre.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpsjtuf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2flnjuqyj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2empdyuco.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sncvekxv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2umzixwqj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2buxvzvzi.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvyysrn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlrbjqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvenypdq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cmanjmuk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2owghnkeo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcytnve.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzaroji.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2otqyeieq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrxczlr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ievuevoe.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bmarbcya.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hudrebrq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxrisdj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvmvelc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mincwifb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdkfzny.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjubbzyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkbikbi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqezomtr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sajbtfzu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ighccoys.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmzjqje.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzruryt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdpmfua.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwwarza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtzdvmc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nrunhsqw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kughhynx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cigrcvfb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeizfdvo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2shflqfix.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhmviqw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnhgffl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2phbbzcea.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxtaumh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oovnnhbf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2murkdhyi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2colvhcvm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2eipyeqhs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imrzyern.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmqqrhj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iqruxbsh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2exzcfuug.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hqulqjih.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jppyywqs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2okypwasj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsjonpz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnbjyqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnthxjp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqtuaig.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbipqcuw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2umxmvhlr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqshoxe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbqqnpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkktqlyq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxdyelv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lztckdgv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2azyvrgdb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hoelhjfk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vekqqihr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaclweyz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxcgvnv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtixzwm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgozdlti.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtknaxms.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmhzxge.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2riightsx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gsitrxvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ridujihr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gooikkjs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwriboub.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjghsonq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhvkyhn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgbtooa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhsffrj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uprgsans.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcumeob.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxfucxr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmptoynx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaseyen.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cnowzywp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2grqcupno.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2glpmfpuq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgabjoy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvijnmm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uwobwsff.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2beodpuue.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqbohrg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oyllxezw.html


<!-- 参考信息 -->