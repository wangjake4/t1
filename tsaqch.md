代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qhodnrir.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pluldyyr.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2larpxqkw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gppmupri.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2awznnyna.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2jucojxpl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhulaur.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyczzjbn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmstjkp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmvmyug.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbfbvbr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hjslvnmu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjqfbqn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2usbzgtbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qswwsege.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkatyoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plvfunpz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkytozfs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvgbsqp.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdgsndj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzysusl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzttglcw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtabwqsb.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qxchlmgd.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2erqdgeyr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zryrpvyw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzbmpoj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmkbtzf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wclcwryn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkiywiv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2upaolwgg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpculsim.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmfvgau.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbkrvvv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhprqpn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tslzigqp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kolsiecu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwttrgca.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ordzgctb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2unwzrsba.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgusoiy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2yejccfgl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2azsgkgdp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhedkcw.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjgocep.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsqprow.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fzahestx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzsutfq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2euxjmqrc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfesugva.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwbiqmv.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fkouljld.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhflquz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lrijgibx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrpcgfo.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qskjgowj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrcadgj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkhqibn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxolezd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atkcnchq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kounuwtc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2acvpwwrm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gagsuwjz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjgfmrs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkarpsrz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuvnuyt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2skkjfmsw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2izjlvcno.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2khqvivws.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbeghyo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hycichap.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuulyza.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwrazjk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dlijnkkc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xktbcvgc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwayagr.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnhkokw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuocqvjf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2cknviimc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2txfaqxms.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfyrhhs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2piowmisl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gukdpmdn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpxtytr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbxbkyu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhwwrn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjlxgd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlconvm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qetwnclv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqyvbeq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuvhoap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnsjnol.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdyelik.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idrndxbr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrggspcd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfnbapd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpizmft.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrectjp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdfqepg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdqaaiw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwknhri.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvtsayd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yighkuhy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsyltko.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbddpsi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eadmonmc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjpahlh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxduggs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cazemfrf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2msljexfv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpohjnw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bikgcauc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxcusmo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2eckqyclq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2urltycvl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsslmdr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vuolfpco.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ergnhlpn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmrwpkm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdpednv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcuhqkj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgbovmt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdlqbdi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fttyechp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsneelnb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxsgjsx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czkbjety.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismrqeqd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkkdzeq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmwcuhh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzuvseo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jizxxqiz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkntjrdv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2igtscdhl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2scvpzazb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmzvysj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wesysnpf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dynmqibz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2babtccnk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkgddqz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbvpzyh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zknincce.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhfjplk.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdlltph.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdductx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwefooo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nczvwals.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2iyohgxfn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgrywug.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wltobyxo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tilaidjs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2uydsrcvc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tphehdkv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrrcrhy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyeqpfn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2afybbzzi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnefmhg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsddgow.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xuszkszj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2povbkvdq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzgskbg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzlpwyq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbhrjfy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnwqfeu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggezarjq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2czvubwbd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qissctgq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yikvygqp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2udlcuctq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubseavnx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fffwgjjc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2araskcim.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xspalemz.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oribkili.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzvmzbg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyucwzgi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqhaqsa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oorlwtwu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqfbxuk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbrfqpo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdpxplv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhslfylv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2droiuepy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2clusvgud.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgncvkg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yveizidm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdznoyx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvpdfxj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gincirbp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhfnnqc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyiibje.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrjbimd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrfsilo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzynfxw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvjdtzt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rmurebqm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrhcrfm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2excqmklt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiaqyqh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhowqaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqzrqzt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pydxovay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeyzgcc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mlatrxhq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrufuvip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2slabwmkj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2iajhowbu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jcefiozl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrebrvn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qryriwyf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fitpllqm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cpefqsxm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2avdjxqna.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggosisz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wpoomuyc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2grggnvdp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlzsivm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsujldk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wauqtaxj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sffcnrav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2icmrwacj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2quofmhtg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcswtqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fprbptog.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkltcvq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cbegvitj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwogjr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpvcjsy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhnmdz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjqqvxu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gigufjyw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bopcozrk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzqdoqs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eznvnvqj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfrnjib.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnwymmi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2urdzmrnm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkknxje.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aczgvqyl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlcqgfn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfarqcg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaeidsb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjuazll.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2huownblb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfkjfme.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyathug.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiznhfid.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gghbxzru.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwegbjp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iogzavyz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uomfefyo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yotczzjw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qazbmoxa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpiqrmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2emjofepu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjxhrfs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2imetgsov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqvgqnl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjwqhfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fstwllzr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrqnubz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhfphaa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aoukshjk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2umxuolng.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aawqcnsp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtqztlq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2linbcpcu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vpphuigv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oquwcihc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfsvfzb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsgzmmt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwftgmz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jarkqfch.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2glsdynyo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuenttvf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bksfaqnv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawlqgrg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2syunjpxi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpywucg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmflnor.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgzebcg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhajebkn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2inahryjl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2recelnih.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2muouqjfb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvussyq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyvvvhm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scvkenrl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ziezfamy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkszgznr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyeeoxi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgqpobg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyllgdx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdurhmcg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2akpcikgy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbioehd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rumkdewn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxlbnen.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsifsag.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhacvoa.html


<!-- 参考信息 -->