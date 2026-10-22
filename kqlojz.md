代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvljsuld.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zezetoey.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqooiiuq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2edkxaqtq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2gosjytzh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvyowbu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2axscwltd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2svfkaaor.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrbbprf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrbylxj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdcwtig.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2btnybtii.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmmqdbn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeguefc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vxajhgjm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ogprswqj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cixaeesm.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjzaezx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fqshhutn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2foxssrqs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqptqel.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpczajq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2haenbsfc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rlszwocc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjitxqbp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qklddvuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbizdtot.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpkjzvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qinwzswt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyspsumw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktishgxq.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2oebovpej.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvqdsnf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wilzqlli.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mivfbydk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxrrtea.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2nodkbazv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdkpfvw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prbvkatj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2efkdnpww.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzhctrl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkedyzb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdxbyhx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xegemqur.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ommilyro.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxsplrv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2voirhcnd.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vusjbrjj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qexfbzmz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2prgsbmwr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sambvncq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwpuveh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuebcwm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbsxhre.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zymughwg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlpmazg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hapeapxk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2slcgbjxb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2woddzntw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mevzgjgt.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyxvfim.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaejzapu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2czkdpwrt.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2awuogozn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wavmidmc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhlhvku.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2moayiepg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xewbtjqn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypexduek.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inmkzcle.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhshoht.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqxkpfu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiafmgf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vjemytcf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzcrbxp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoeynyp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeumvitc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlmdpto.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjukbcpr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhpfrkz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxmhhck.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzybqkyg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdvljrk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2chrpyrvi.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2poqjixpd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvythyc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pewtlugi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmwilwq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgwacam.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2emteqzzc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfyfqqo.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2saafmmxj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlbdtpw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gslmvztw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayawwuyu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2laijpcip.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kknyfeko.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2iimmxiun.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaqhsbl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mindfwhl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jimkwahm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzdzvyp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kcreqpoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivekzipk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kevmcudu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omuhgcaw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpacmdzh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sntmyilq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyfuatm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrkqtab.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pitowtjp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fanwjmqf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqpyrjn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2acatowow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoahhzii.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hndvmknw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqwdizn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnsxunj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvdimgx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhmhznf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2glxddurd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqhlbmm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrebznz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2drojxtez.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vcndprge.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qixwmawm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2czipvtch.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxhrgpt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjzchzq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2tffnlrqo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxrbfox.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yakmahem.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sroesbgz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiwxmdk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcilvfh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvbvonh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvjxnuf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrjxcay.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgicsmb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmiyvax.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsumuoji.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpbhkkm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzeyidi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwbnsyj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dovuoqoq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiykcys.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tixtwftl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnjtsoh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrktdby.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgzqast.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjgmons.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxcecne.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hisgdzzh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2libgucmj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jovqdujk.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdibteml.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rktnscpc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2czdykufq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcbtuit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvvgbec.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbojjga.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpiuuoo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2resameqz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzexfyy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2odjhlbwx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2laiugmvn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdzdbgw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxvhafe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oimgxcbd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgawmpmq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrbgynp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2grsiokgc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qydzfuqa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxoyhgz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2svswnees.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xrppruhp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdmmfrt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vggjrfjs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuerfvp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlkyfsb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yujpfysd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aomwxzkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdjkhla.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lexoemsk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqraukw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqarixc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdioier.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuyevwr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bukapsob.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aahrrdpl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llxnwgzk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrcgwal.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggbmlnk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgypcwnu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgaudbb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtyieml.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efokkrpk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfovkjs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrucwcz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlqtsqt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bkweqsap.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jduvzpxh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpenqbl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcpnagc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2djlkpcwt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbxlvfr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzmtlwt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ichpbbvl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmgjnjb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yftdknqv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2myntoqxf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2usitdmiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsyrddw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhaxwkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwghwljt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ddonqlon.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgndlyjn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoouydq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2inqafdmw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2alkntlas.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtxiti.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdyasdf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxwgwpg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zugfwbwi.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmuxdsp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejtlnvn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cqffjegs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpjchjk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmlngvx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxwukab.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2edxcikpr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnzypit.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuqhdyp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ttngoukj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yicdijiz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2omejpuqo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmjewxk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lufmfkum.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxfrpdu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzefyjft.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpyswku.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rachmwzo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrvdzrb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lghedowd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcfapjn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoyilse.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpegeowp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmjbtih.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xnutaikw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqvzmyr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtegbgus.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2oksijchd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmonxlar.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmbqbpb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwxswno.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aefzswod.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpexcpro.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjugcaq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwbiokz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbmuram.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eiphuevm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2isrooozs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sotupsoy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpxhkit.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuajufh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tsffippe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nrixdzwr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpapwhr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbrwsih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmektmlv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlhlkxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uocqipzu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlctoyf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpzvbpd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lixnheaf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rinyilvy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbuhrad.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqwctuh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xwehabuw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fyszcunv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmvcpxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cbslecnx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztruzqwi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvezvic.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mjydfirj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2draxflqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhcnqxh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxhnctv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2algqmkkh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpgbyvd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2caubdepx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdsmahs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyebulo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhqizkb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbzrpzt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2txmwebhc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkrcogc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpqxjom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxikewt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdzhoet.html


<!-- 参考信息 -->