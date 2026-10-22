代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2enlmxmoc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiejywd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwavlos.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eaomfvwo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkbqhuh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tagzdmon.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tlliacfc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlyfjbf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2odrwosdh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyxwwjg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2xalibxyn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2eduxlxxa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2llpkrjiw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iaplccmv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ngljvfmn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2paibtqsv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdotuyc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2piojnmvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfpqjht.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsvokhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdtqkio.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zltcotat.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpdannv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnejgluo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzmfxew.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksetqnam.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqndgug.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aabxsjfw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2frmthqzl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqbfjka.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpuquwb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2czlcvtsq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfrbpiv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2afqrlfxa.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsbzcpa.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzmfxix.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqunbci.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwehofm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljdaktq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aeowrvzw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjkcewf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdspvhw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2otnoytqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvdsyet.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqohxzqz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nowyxghc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgjlpzp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfnavzg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhuztuq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbijcdu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2knwvbmlq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsqzxib.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qikxpphn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcnzuyk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkwvnqp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2imvrgrer.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfarzcep.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2idxpskbu.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwksvuts.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpkkbjw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxtivcj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhybltd.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkwtnui.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcymvxvr.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxtrhlp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxtdqsj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2echjruct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmfgkxp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkwzsns.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kflsyerk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdfyci.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqocjin.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqhpinj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2npmsmyjw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdunglpr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrazqxz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkcmzxu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qszsqeki.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtmaisq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzjasgo.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgditmbx.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2smgmixfj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2mixjlkeu.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bicsmvnj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyjxvgb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xefuojxg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqirohl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhhuywi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cttyldac.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgkcyhn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbvqgvd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cfejeweo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvhvjrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlcyjee.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2aiazdcew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvtqvyf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hknjlnrt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gujkcvyf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfegkcey.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqdhmjs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopfelev.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxntypva.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2usozarez.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlnpnuz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2liafdoon.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2adatlfdm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2auwdhate.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbunpwxj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sunmqqih.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sslszaew.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tduwdpil.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpwzlyk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwlbcza.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkafhqes.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyusidme.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhqebri.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbrnxyx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2puqvfwpu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdbjbdp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2upiouwhp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bitselru.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vnynmwik.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbzejph.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgyxjqa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyxcrac.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uloctcng.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvzoija.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzrchmz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsztuing.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbwjxvn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swcycjai.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xznmgbxo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcsoxeu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjrpllp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2areychac.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfwlcfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeeydxa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxlyxfe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwiyipx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpukssrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtkfkym.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dxckfija.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnmahwd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2osjuriti.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngobqjvo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lunbngbj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lesizuhz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqxpwmi.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkhfiua.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jreflvjc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgitmof.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2apehvatc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2awhfcxaw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrdifoy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2iligphoo.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgoezca.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvrovsl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kqirmkfh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxrqslu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdtdexa.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfybzbsl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwtadkc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcspbjd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmwqphv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dsffusok.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cabdhpul.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2eylfzvbm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoklbmy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlpfpwx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2crxgbqyp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kckwrexf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyobjrmj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtixqhd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2djugyhjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnrqsbt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlstmgtd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2agnwxfcf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcnvhfh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nncamfsj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qluaacmk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjctbwzd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxisgdvp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prlinwzy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2abkdthwl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbssltje.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cppmhhmr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhvalig.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqoudnq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvebafd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkcbzwb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oifiunzy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzbjrbe.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbwfxae.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wijpnyep.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrembzo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfpgpp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcntpmx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfzzpow.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsihcwp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wripghaj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mqijhvte.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgwympv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqaikkh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tgurlgzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phiozaag.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2klzhfheg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvwxlwf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lkemccbq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbpthtu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgykrmo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lyehvprj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gadpbtqa.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhyhhpu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmsrkfk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2stgdrweq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kikoriuw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2idhyshuz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xflgzkaf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mjndakqz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2evdmilop.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxlkdal.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsxxfxi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhrzppo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgefnlx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeeqkfi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjrnrf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fetyndlw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gikaervc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyghapv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzqdduy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwazjuu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2knbexgba.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pduodsdo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtsrqpz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2njmqtmrm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoubklw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2phtffqfh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbdfufo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoajhboo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsakere.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvnxcsj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2poudcthi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlesurc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxrfaxd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypynsdtk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aphxxdji.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2prunyxfl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpmfity.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvekeww.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqzgfze.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkqjpox.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqwsgar.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aonvqtkc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnupinp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkowymby.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2egsnvalf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzldprxu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfpduag.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2euxbqgwk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjdosjc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsbqvtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uojjdmem.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngewgnkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgwcksp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2prptrtxt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gsanuymn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmrorih.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqarlgm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2axcrkvtb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fviktmje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmyehig.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vyijdpnf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hovathca.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpasphz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2aptcmtzk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcudjjgi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwnmkfr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxuuofz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmhuykk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wynidyow.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snaynwnd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2klprmmio.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfagjrsf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwovzfub.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnalszfa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcncimd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bipfuvpi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoelvgg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsuitpf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqrtxkv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrtewxh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2udkkhznq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbhquaj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2azlfdixq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrcfefx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2scpemrvh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhijthl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2byxpwuds.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zedngfms.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfdjtmp.html


<!-- 参考信息 -->