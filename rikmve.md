代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkctvmuf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2doxltdgg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkhjvuc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jatqorjj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2rlznnrce.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwrpvqz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefaqbv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhuuevw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcmlnbv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwikswm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqftcke.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2aakbmbxr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjfdjq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yiylohos.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2fdizmftu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjaiwmo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ustiwzqo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2svftfhyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbladze.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2laimobic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqizdcmj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alldpzcq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzqvnhi.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxyzpzu.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmdwvdo.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksryfead.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwahhtou.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvmvtwi.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2kcooqtdh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2szdpbubh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjrgcrm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgajuws.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2badbjdhs.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2puxulgqp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bowezilm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsocswxd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pplgdcrt.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2qwttgknl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhntamkg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pizqurxe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdreviw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmdjvmg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2odcuwgtl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsznwkk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkalkvv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mufwaxzc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzczdhr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvrsfdj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvyfpjo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lixgiohy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2sswnvdie.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdkmcjn.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yleyapgx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdttzee.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lprhmfzc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmajecm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzeyrzx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2epbwjnjk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdrorzh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkunegzo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2twmibbjv.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbpnzea.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzlrbdv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhwjsce.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdvproh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrsvfmw.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2srawulxp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlbpaly.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfieiyh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sywouqks.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrwvutj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2czdpzphc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2usipuxkb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2htsjbpra.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zukwsenc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzabln.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vybssxem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2klwqyger.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmxsriz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbtorao.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkidecb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzuqbyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tfezvkgt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iihczzhe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fwltpgko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjmdivw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvragxzu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxcckch.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyeobzm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjfwmae.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzobuaqr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfrxlrj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiizkdo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxiejhr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zetbuhgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrpinvp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxburhl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpgxlxc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2atlrjihs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wolyngzs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeusxbx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rikwbxig.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2weebswxd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgrrnif.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbmipbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctudkquv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrjodrm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztujkkib.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nubvkddz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfqdce.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuagooib.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoipovj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmrnieh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2durchdge.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkarpt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvdhtag.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2mvieufwd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvbtqru.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpdnlnj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oirqdfjm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vluklmtm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgckeft.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnodbto.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfjkkeg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2elnwkrsv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgmyyml.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2huiahxdr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpugwddi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvmmedt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwsypqx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzejcvt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pangcmen.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtqcmdn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2relcevej.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qykbutbz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqfawjm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwefxsht.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiwayam.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdsokzy.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzahiguv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgnlsep.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2troxmzpm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2httciinu.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfyvnmz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2elyamwde.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzfumkt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fijypaib.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sljhzxjx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gycnkfwj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsuovsw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2chxjdmvq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxlyquw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjrrwxc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwpgxei.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2grdqbnux.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpjwmcf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eualpcbh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bjafvtfv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjlvgtr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhvghfi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpacudte.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnenbqa.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aypxgnmu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fgltnrzj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqberany.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2reaopnrj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2neumbhhx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjqpnpi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsjyzgw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvibyph.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvivawh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imjeyhst.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pogorqsu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inwkwjsw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkmqwlc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzruocbj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcyevpq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxqbigg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2slildzqd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwtkwyc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2udaxhwoh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkumzog.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdhryzn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2drtipgig.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphzukxe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupcljgo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkqnhan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfjgoyk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuucbeiy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2civdedbn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfjyrey.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfillax.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxddurz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdbdkei.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yynreehc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2brwylsbg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlxpgxf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2odbleakg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wuywqdof.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujutahsm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vdftxcey.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjgbbmh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpykoan.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxffefi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xylzsfit.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2grrrhcsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrmcrzf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rncmcvqr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsvqzlm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fddzwrci.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrglhsp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlnewfv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnewhioc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbexnzy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2htwfgcru.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsjvwhf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rivbcbyj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjtviym.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nqedqchx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnizzxj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjrixts.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2itvwmceb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzzulnk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwesssk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fadktvup.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2djpkfgut.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uggzywba.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2svlhlmis.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sdasnhzk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjxdcrj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsezfazr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qriqpqqj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcvcjol.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slciefiy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuqzsmj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmaxqji.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2trlykbwo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziogtpbh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwdpeiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2izfdtjkf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeblaxa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2eymvrlam.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bezvicxh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbegixb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lybpasmm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2oocvegnx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhcyfnk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvxnhpf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzaltkf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rotnjjoo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxxtdh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsahrlb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgcegqg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zprakwdp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgjyplm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zorwaesp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqsywas.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qappiaiy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrprvpc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2obrxrbco.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuplzlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjutwnn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhtzmmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uupevguy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfyqicy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gegldmhf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tktzxthu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpfgpkm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yojjaaev.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmawnak.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqdzmod.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzqbqkx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrntlhy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yojykpaj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmsdoup.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fenzlyvp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvusuas.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmrcanf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdozvzwd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcsrquo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtyrcad.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijklhgac.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sevradyh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nomgkuwe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlrmyqc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gttzidml.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sckmjjvi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyqcdgi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtefqoe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxqezea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvvkfgu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwocyra.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnwnsgv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2camzoana.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2udldwfyb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kerouhvc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhzxkcf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxwauov.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2imsvigbn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2atfjbzqe.html


<!-- 参考信息 -->