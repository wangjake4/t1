代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zybmimog.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2raybwqql.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzgrodb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrdzzet.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzhxlxt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfamjyxn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eldaraii.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjmdwnj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zujxbamc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2widjnmrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmptnray.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ravjiduf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvasfax.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2udvipmbr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsujlqkp.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvpdjwa.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krgubglu.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sodkupfe.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmwmqay.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcegvga.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bedmmmxq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2burynynl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyhxhdz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2aifftdun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptfnrh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xusbdnzq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvbmva.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxancqtt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtzutoo.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnnddwe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykphdjzc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ewluxydg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricmtfot.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zznglntu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdoycqu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzksjop.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nalxqtqn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gucintzw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqcabuc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yplprwei.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nojyvdxg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlevslvs.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2tutofaer.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jubvvesk.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2owtamekm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2htrbigre.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2thcpnugl.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2blccxawo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmimsbwz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzzxvaz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxzbbdr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2grtgppiv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbjbeae.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmazucu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqmzojq.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epoikujf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhsgmyt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2sexoezjs.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cdscbluh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfakitk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpjkrfu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgvabcc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwdkral.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2umhfnnrt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrrdfwy.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnovyfah.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpvditj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdzubnj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2iumqsvhy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmommxx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bupoyhel.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uedxlots.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhrifnw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmytfgoy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2iuujpjlf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjcfgog.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tvchpsrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnmcnih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlftdvn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2emoglbzd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhvzbxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvluzyr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmyxzkw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxppda.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2azcwmzgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfxyovk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2tekmdiey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lngabixr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gebidltd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyqveno.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tynabxvr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aomobohu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vucebxfo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppymgkqq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkmfxjo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkprjjhk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwlyyin.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2palhfmwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlgirdu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpafvlm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdduhtgh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilovgszy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxllhhh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvncqvj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgykxaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqhsmdc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwatmbb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgahczl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2awcgzaqb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2axrohkem.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2huopeghr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuzujya.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcdnqul.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2crjpdrmc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jgavnslm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2sltuiwzc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otclbjse.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzzdfxh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdfslsn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrogkqy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqpdyzs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaqcxzt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcvvslv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2elpbbgnq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdoxwon.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgvhoeb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpjpdmw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqazlsyw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbdcxkg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnpnkyq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttybquir.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2niyxygpe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2leexltkn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyjqbjg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2irruyymp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyecvvpj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vesksiwi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fihszmaf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hcneymcb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgvvwwj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvlnews.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ushfdjnr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjxykya.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2acbteskr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqwjhce.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vscqenmf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbagzcn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjwjmnb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2apihlhns.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hzanrehq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuesswl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2otdcfktw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmvadir.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rafifmmj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmvmiat.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfsdgyq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxmmnbx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llmrqlmc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fzykigca.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgnyyup.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iveknhqq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxhilxn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2olxhhlce.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrqmgdc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nibelihv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zssqqnlk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zoecbazh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hakxxsjm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hufrqrqc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eeorovfy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2knmlrjrc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcjjmwf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgtrsyv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzkqhly.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mepmmiyu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2koetplmu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cydzpnlo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvgpquh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqgjfcp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhogfub.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkzyzed.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rzseduvh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdzgfau.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ablfuxgv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbligjc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcxcyuk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esymzwqe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxfiuik.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2drjaxvvq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpbeqcr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxrntho.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxsvomg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zreshqto.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjkwixr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqmdnxa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdlhwzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrarwoq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzqowoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiasqco.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhyihdt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtgszwx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rolpnurd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfkdkhb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxvnepx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiwdcyu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjgtdqi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2piohkhzu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2poaokwjl.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nnchzofk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvqhrjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yawkpxcd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cftabcvq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jixqvplt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiwiudp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqnknlb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lotbpuwa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2abuqxbxm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqqvzwe.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqivlxx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmfpjcn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbspctu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkssudg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlardyq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iynipifw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuviaul.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdzkcmf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ithatayl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xadusdcn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ecidjuty.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oidjxfgc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agzfpevu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lonnblfy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vywjlsnm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lrekivgx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atupywhq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hjehaibu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcxfqaj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gondnbyn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlpmaus.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkqvikb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtwkncb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2orwgwdfx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcissng.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzxkabw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbxvvvt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2newbquuz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbpwqyq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2adxzurng.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqfqdks.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zppeecqg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2etjpfuva.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xytisoht.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2weujehjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smhuolkb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjffblk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgptwzs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpifyyy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdlzetd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhiksgh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyfvvyw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqntgwb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfpxvhc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lgprvjpk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dugwcepu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvevfam.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmikuhg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpuxnsx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcnxvrz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgyuyrh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtadibgk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjvwjjq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuefjzrj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxnahqu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlertdwt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzitjlj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2smyluyge.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2guqbnawf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2arahtpdo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzspxgzw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimycbyc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2swtovuxs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqylgtzq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wygstngb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iniatqot.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkziowra.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwduaxq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eujjhfgx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hodcvdap.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqagkihk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowrpedg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdfjwrk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2waeoxscs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmngfiw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aplquvpz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlnzmpp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fxesnfnj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azgjivqs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbjeteg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pggucsfl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwjmigk.html


<!-- 参考信息 -->