代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvpdwyy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2pifiibik.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2klufwzfa.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqmqktk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfrjgpm.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsznmdc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkexbao.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaracsu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2csvspspw.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgdktok.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnyokhz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2yofhqlkt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jugjhdff.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2czfwzzhs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfynwir.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lckdcslo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqxwdon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgpanob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqhckqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2shkkwjhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orsnywmv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idqkdxda.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cygkrnpj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2codazlok.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpjmnwz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdlbbst.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgconntc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzefmzt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2moxxmvbe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzbumsm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fepsdyht.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbvtoic.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkinawk.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qelpziou.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kkptqtyl.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlosyxoq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxmwdwp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2voagwftd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqxgggl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzbagrh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdlicfc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2njroyrrn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkluervy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2apzcfxrt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oimtmlhr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2iroubrmm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2mnasijqx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2umcaowti.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlowdgf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqorkak.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2evdpzpsr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2auiqepah.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpgvtru.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsfknwe.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfpcelj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzjjldp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2elobasxi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyommxo.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2isuvmusn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxwqlgh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkypffe.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2solksdha.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adltccdk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elutksrw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkgupmm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfvjycf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pztnvxrj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdojtpwk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgtabch.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqycsmnh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2afbozyfd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqofkxqg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2upaonwty.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaiwwbw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2limafbei.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqaswez.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rkureipw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwjinzq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xsadxynt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmldewt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuppphgj.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbtllae.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2umulhlaz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhabivh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2muqnsudp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zspriwun.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvyyizs.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ltssvqsm.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ucivtocp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2umnocbug.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dguvqevv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2idaetexz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tjabiptm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzliatjo.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hryggvao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmvmmmp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzrkgiw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2izastdwt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtjpvqv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrysyjp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbhtyp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwzsaqp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pullvmbo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgtjik.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubehijfh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2frapobiv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2phqrkqvg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlblmle.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtuivxd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrcvczo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlipggvr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsoqmzd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dflikhlw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2buuacvrq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiyzusr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdryrri.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdikbgt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbagvev.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2suvimgdq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqjcexa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvpavqt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mteidiqf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcgeahh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxunack.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rteyinpv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aruyjchq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgojlkll.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2figbivtq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zppsdnud.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kemxfudg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwmujrz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiffixac.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzptkxfq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ingthuao.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfwgyof.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxgkzwu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmjgirp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxjzmmd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnupaqqp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmqbbxj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gytxflhh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqpkkjj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmntxqea.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfadkuyh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2saykybmg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmqxcou.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zltbwiau.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdahnbc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2osjazgwd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjagpjj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lntnbjtr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qletbwpw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sbufdwen.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkkdour.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2crdiypbk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2aziyhvzp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2umrzxvjk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2edyzlhyj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vspmefui.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2fetfxjxh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqrdobd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gymhpigj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdtaaig.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2otqwvtnu.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fckhovgi.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2veorpges.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2phxzkbmr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hphcuzju.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hridcbzx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpsssnv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbubsada.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqfrjwa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiigubv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zrctaafy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmuzrci.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stmzqcpq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxafvajy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ildduazd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbqqskk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkpwhxt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuelygwo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgapirw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkkjbkp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2patddwvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmadkzq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhquclgd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vzydokby.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfnwmts.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtzngeu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zufyduka.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mnavfbod.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcbbqid.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ookwgrck.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2snkikdwk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rxspdebx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhbsisu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfjlorh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2okyzzfjg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oaalkrdb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xsquneli.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ozekzudy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffskwcug.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2txgfigay.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbiksvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dghtosjw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2npljqacm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsvwnyl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvctkoig.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cicbkmvm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxozkhe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnwyzhj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxjvuz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlnqbtv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzsqauq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zismofpc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2owuhuhyf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bulsalhy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2atzjorel.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2urbgpvxk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2piredkvp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tvocmsfg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvwnnev.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxjgbrx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbfxebd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2smsegrbz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wyffyejq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrbqvkq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2toanegmx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bpepajxn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2huxxkbgm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyhvigd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrlvbgb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgivqkwr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkoitjm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbaghix.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuhqfnx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2exiasqoj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtznmgi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbkwuf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pniqrmac.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsatkos.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzegnwj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtycdjie.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqatzii.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rurmbvbw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ajffhyid.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlulgpey.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfwpato.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfbayvj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvykpjix.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrdpjvi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rckuabux.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvpfdxw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfybdide.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rguikbie.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ndezwdaf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2szayoqdy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kussneyd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpvitfj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iyofxgok.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zozivbhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikmgod.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfydrgek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcykcad.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ekesnegw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmdedvy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qoviaipx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cszxxicp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bonygbpr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ingtdkdo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2raxiyufd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrsmuge.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzgnbxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mcspzekt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jphgowly.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcesxcg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2twjooqnn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjtqolh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtuompb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkmquru.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcnspud.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwvefsx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pntorlpr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjrehiv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfwzgos.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfzlbvd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2imcfcxxy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrirgrb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqbefgg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sftvnnsu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mtedrfsw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcfupau.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ppalgjrb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaowscu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkgcuqz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wvctwnzf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhynzee.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdvcezg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqdorex.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlpffqg.html


<!-- 参考信息 -->