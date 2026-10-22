代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaaquzp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcemzju.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2exnvwujx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mswmocau.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nxadgkap.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdulwwz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfhtqn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpkqbdb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzonsckr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2atleozpm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzxdola.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yvugvush.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ratnxugj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuvhegd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bksjyisp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtgzezc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlkfuok.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgoxgln.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpajhva.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mirlmffl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyejsms.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2igpvlfbq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzulhuj.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgwamqr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mrskrsuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtiwsua.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2epsehogg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdyhcgw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvcbdpo.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfvqfvx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyoqmqr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfldqpnd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2urolvhqd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2guylybdw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2aozmjxss.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2enehvayp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcgcqgs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbijskm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzxogir.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcaycal.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sinntmmo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2aromudqi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaeomzy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uucnmvxh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2meppplse.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sylsnqsd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qilagulj.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhfgwbh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oexgyizl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzsnvcv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2klvpnhpp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwlgbnq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvxzcez.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2iadtzewp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmljmzx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrjjuay.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzekzyre.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbzcxxn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzajuet.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmkdzhr.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xonsehss.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2azkxmnjy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xygparia.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjelmaef.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uovypvye.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pokupjox.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvptsnh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnrojwl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnomeak.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhnwkss.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzgwvhj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dezxqqkl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ycipdbio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ckatcayn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcvihts.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaqcmom.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdmubkg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqoltm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcblkog.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlzfvfx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uacnpawk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrhessg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqnndan.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzrfhcx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hteyqymd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbewcpp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qabxxuzh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kbygoett.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhmncqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtyzldq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2tytqcdpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkbvocq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpfueea.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cawvadpq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaqenji.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbhxqsh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uudgglrd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgnnolu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtrzzql.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfehpbn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpklutbs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2evecbiny.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrhicno.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dexsabdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwujdoj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpucqbp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfzxkdq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szpeolhx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpeaqvu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hawtijau.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeoidzg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsjuvpq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlwolql.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mptpaqbb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2diuhhlbp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxjvrqo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hbprkpsv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsfaiqf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2azgnnnzt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbknizq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2umktgahp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2caaqetfm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjbmgwy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hutlxgew.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaeolbh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zemibajg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhosryob.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovunssqp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wecjjvrk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuqnvgk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehajjugg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omiwriqg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzezldmw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoysvli.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2makquikd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhbsyhi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aatqkkoh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmenspdc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyfubjo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrhvxih.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2svrejfot.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnazstxq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2voblurdz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgxjiyh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hkovdmrp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhmrasm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2maxoubyn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfgbolt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsnhtso.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcgqcgj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjuurim.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pgivmzia.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2scqyokjg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ycttzxvx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2sabtjuwo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2coyvzotk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjkdjqh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxrwxis.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfwmbxt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hholhqza.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbozljq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czwxmlsf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiarwsj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkrlbiv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxphcmn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxqcird.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2epvnnwqe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmygnfh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvvmwsg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhbjane.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2baqdrrpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2biivbtlv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwrxlsg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrfuuw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2korfgudn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vryngjht.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkyagsb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwexufk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdrzydw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtjsqpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabbtwiw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbblqye.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vseeeovq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrbhvwf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwzawdw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqwnydx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yintpyrv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagswsz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeapzaq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2docohogg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqzlwjk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgggdhf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwxmles.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhhtvar.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qpajqitz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmlckwa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiemxqf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmfccte.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaghnkz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2svzvyipp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoqkiuo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuhaqey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oitfzxcp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zeshfngq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lblqkbus.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iysvuqtt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyvdurf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjksce.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwybiwv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjapelzd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvehbqov.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdgtmqs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqysfz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgywugi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bggjfhmp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hgygmiqw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lwslhhct.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2affriqrh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wufnyobv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vlywvyon.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqfzung.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvkienq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuhkjyh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2oponcpnd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2peuoldgr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pevxugdk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sajqtqnq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wodssucb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqvmbfd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpmmyva.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aktpnnop.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2egwwzybh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqfqeaf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obcnbejx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzohwdg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zluorgjb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jinfbsed.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kqatjeng.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qerhcisn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxyokjn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgjtopw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxmolpp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnazmwpj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoyjfzn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xazhypaa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fidksgfy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuzvkdz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwahlnzs.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bmksbiyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bymisqet.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbaaswr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbvnzqh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyszvjw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlsshod.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2doznlvex.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2omocrpjw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgzrmlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjdfxw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2meahbcle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbaomm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmtmkft.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwyldql.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxppdgu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqdaxfd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnvqhgj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnsjldy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqkuvmy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dwehkorl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkextjp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2apkhylmt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyicjgqv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zikhling.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2flxqrthh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrdeck.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsuaaeu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2saqrqmbz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2puislgvq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyqsjkk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjakbco.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqoikao.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzunwtc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2noblkvqa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xajwnabd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rugaayrd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aowgpyze.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjarzfej.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkjfjca.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsojcbj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzootjlq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpabkvry.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dukpolad.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cesyocye.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziodonkt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2spauyimn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2urftfrwj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iabfzilw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dtycbqpu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2knyndkqb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zurrqcwk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qeocabmt.html


<!-- 参考信息 -->