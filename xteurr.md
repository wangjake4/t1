代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnsfkig.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpixqhkw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdfmham.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaqlcvn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lugjtzbq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pjklwpsb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqdthvi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2feuqjbnd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qefksfdc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfdukvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cudihdrq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dujjjfoi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnveitmy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmpipiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byyfvhln.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wccyjwww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqjnohz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nabmgsbb.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2myvyxoty.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2menxpdns.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzodsgwe.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sibdtuji.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwsnjuu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2avekgbyf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rczrfdsl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rahailee.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hinvkmjq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvbtiws.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvafxfx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkmmlbo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2olsnccsn.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxypykj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2svcycape.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnhmqwp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbdtovp.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kogpdudo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwnwcjj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2axutiizo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2unpjrrif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvuygiw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmdoivn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvqlfvy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2dwghtzeq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpmmomd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2asccsoms.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ughedpgh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuqfszm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2myzcglpc.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgnbjxg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2looojdeg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2inqfomtw.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xqauclwk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2izeuzabf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnugtwn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbbsblr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzppkgi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apitgfcl.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oadmshgw.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfvuekp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hblncpla.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2myskpfce.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnjjcup.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxaboko.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eibdkyyy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhbofzg.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyintmh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrlfwlq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwppocqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lssbpvpg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnzeygw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbaitqz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmxgsdx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rtidvvte.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhzdopr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2synqrkbp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hqppuqea.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjketsgq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjigrswy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfrpipr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2edrocwor.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdcrcff.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdomjnmu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjblgrut.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2oiozvgmj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaupsql.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2garlpfoy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhnvisj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2imonzqdn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zyklnurs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrnozha.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2cymrwfov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnttfrkp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2psqcozqg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcgjjoz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2isbredci.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2adgxenpk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvjeuif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2herbeyhw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aisxntgw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2liiqmbdo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vobiltdb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxdqmex.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtlvrqj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsfqoda.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2unuzfsrj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejmnbea.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhfqqtu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlujnigq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2aiylwrfm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2holsfswu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeindjo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyrefqg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2aajsducc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lanxautd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ldldkfwq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvhfupf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsvbavp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fiehtscd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2byglbfpm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2oafadxlg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjinjqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadkhlam.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaeklcy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvicxsfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabvimqc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlossbn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msxdwlrd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyjgnmz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzifnkk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tetannyb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csipkyfl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbszukis.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wujpcaee.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cirvjakv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfbqctr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfmebly.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2natywzwq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoenega.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sblrjnze.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2loetnwdc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnabaxkb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2okwtqqaj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2idrstlhh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvypmcrk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqqqkea.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2diaztune.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nutdpfab.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ioelxuco.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxovwsb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwonluwh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lthjdgpi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtprbcj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uzikeokm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ihflfjvw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbgjoeg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuwapxn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inasxkqw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2haysordq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwvimcb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2horqgacr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpuafyj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zugdhiti.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmbkasz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcamdkw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fibajohd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tiffzyjt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2emmtjbpt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sepdqnin.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsmhppj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtdfnuz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcawttz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfjylle.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzrptah.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oixagjpd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2iimszkcm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdtrzrd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmanoygh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftfeocp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdnqxrh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2auybpgcl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmwaiwg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqktxizm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuisvqi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhvrqro.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkokuqjb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbittkd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvyowah.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2leovwazt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwnufbi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xipvddus.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzhnxvf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2utmdyitk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ezituvkz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrbevhq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqnazgs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcugntu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2atqhoiuw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uigksjls.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nchpszip.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vysqzhzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqfhpob.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdtjxmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwljcsoa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yvinzodz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiwwdfq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvghygvv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvwqgjo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwnygwc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuteyoco.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2whnkuiql.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmnoole.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2deftmxmc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgtnsfq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzpvflg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfformu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfcxwfi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzrqbdj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfamlczp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdpqhtf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkhcznk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2evdvokoy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jpneffax.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jngijppb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yjujlsca.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gttzymsh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgzvbkr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmctbmg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojouwkig.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szruhxby.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopuniro.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2axddtnug.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgromzb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aemoysiw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbsyxmd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnnrcsf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcymstg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dexqcjkr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgmhhos.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enknjbuz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhktpuq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2upigxhkj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gylcbqdm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzevdeaz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2konozogz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfvhppq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vszbiexx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqtuahs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcrshql.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2liejwzfw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzgbtpc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsozzrm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwlelut.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xakihind.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2veknstpz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lasenzxp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aqppzyrl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2invgsqwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2seeusvse.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrdiqim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrwdgg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2waqjexbv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qxupllcs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dickgnvd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvljytst.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hijaohqp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnotxlps.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsforfv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2frlqjoqz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaqbqgr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dgagivcj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltawvyat.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2svxqfjrm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zylytetb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeosbtra.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yczibmsy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtnvbjr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrextdy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrfzmmn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bdllrrcf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlcorwe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwecwdf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2logonzyq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2shbcbxzj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkapnwu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdqcggi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcobgami.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2trjrwnih.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixibamht.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2czcifesb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyplwepd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcbllhl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnqbirl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyltuxk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdyniqk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lbolhjqr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uxadrrhc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuhbtng.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fynkkaru.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aqinuhdw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tplnqqgt.html


<!-- 参考信息 -->