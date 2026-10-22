代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzxmapg.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqappmkk.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvypxqa.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwquupb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2uivwayhw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvzacvf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpercuvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gltsnitb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjmbxrd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmpnmuf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbqblhy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2avvprqrh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mafinydg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hspnpida.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuxgxtx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vmclghxx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vlngtxva.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2lplogqaq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhqrxzw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wciwwsno.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcqkdlo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrtaytd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2udejqdoi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjxsmjd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2swewbtfw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2reevsgsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guaijutx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eikxrovd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arvvefea.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmknkva.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmndefl.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jslvnojt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eowamsuv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdfziga.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2iydjbmvd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hulhnymv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyepnxf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmlxkdn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afmyrlij.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyphgyf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnanfye.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2smrthmhr.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlvhgbg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsebexf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpovupfc.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2weqfzrna.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2agqefpgv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xacuyjpl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijarqczr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2btklmdik.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwghvikn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgsdqtq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2seuejvvp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeawqmd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rixcexff.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcytjony.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2isjhhtrr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhaogpg.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsrmyxz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxkfhwd.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgrhvwl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwemjdm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xahdpdav.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fpktebuv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhovreip.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqasuxdy.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rocyjphl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlicexlo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjjamrb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izkpkkfv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esujdfob.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2khidutqw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjwgfz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhidazs.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fvachrzs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmxtvcp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwanmmd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiltyhc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoosqps.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sveccndr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmicgxq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2uddesgqr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pubrirxc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpjkbac.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrmhid.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pirzxnxi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kgclyhix.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vfitdgfq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjtsfqm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpofcwa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2smlbswff.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cebcvrxq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jngldtog.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkizdgf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwciunw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlmhsxl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhyuhko.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgmkqbj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2atvkgscm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2aucudvxe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zaedtfjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukemyrwr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ritjtmsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsllidr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwghwiv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewexett.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgepzlft.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhomfgfw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgevdgvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwionusx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2feddkyjp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpzfqsm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itdjjvfq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcqjrwc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yssqddvm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aybufgnl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqkanlx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rofmkjfd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhdiqiv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2echtjpqh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnmtdxj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxaieqo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fselhstu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjqnbke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhyxrnf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdujgfmh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vymqpjgk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xogazdpp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdvjbei.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwsqwvs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfzqpmh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdigal.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bamtrash.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihautsjq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkajihyp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2duiarndn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgdjgqt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcvoyon.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdokvsnl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nddqexor.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2forjgbfv.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwsemiy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoatlnz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koqvglkb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gssigpan.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aapqrjgb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ampumfsa.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrydnqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtuxrpz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqvpceg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaiqkoe.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrixhbvm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eohcznjw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2akprtibg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfgmei.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvpyggd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqnzjbk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gycvsrhh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfoewge.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjlfesx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyarmqd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svwxzbbh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgitara.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgvqolh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nokxazfd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegjpay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwgeeqq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsihiqta.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eivqjujt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hssrzccv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hzivdabp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtvqiip.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdkyhlx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2decgtdzt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtvcynt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fovuqogk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcipgoyv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2netkhyfh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uipptshv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxvnrvr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdaaixy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjbcivr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfdrtkt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qykddcjb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzsxunl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2taryjzis.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuombnt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgsulud.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtjwvje.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpwimad.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsugkgvk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwkdoz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2epxbxvcs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqdxzyf.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqtunih.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aovgntng.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcvnjpd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2unspungf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqigbsjq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oltavott.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2irxmfppw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhfiljr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2krvmqcoa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lceuzrim.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2usebbnpv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpqctkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqmzrpq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwxbhxh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tfawcupw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2onihfpzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbkecrb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qotmzgsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdkqequ.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2aobfcvbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyplteb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vxykbclf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvwvicm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2athaxwnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vxovjyxa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hpihcubl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoeffob.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tobrwbss.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwaijhu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2shpkeezr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcisipq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkvduhk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfmyjnb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfmxteb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hciygism.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmljzjb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cagglpmr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iazzkuuo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxrblhj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2imimujwa.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fawzhxxm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2naolnxgp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qksgwokz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2anorxhpl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opwnzwwi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcvtvsw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhhrcbk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2racyztdw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzupxqz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxdxawx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2agbryigm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eitgvpov.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pemjvgru.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzbcbxd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kseuidef.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2oggooeck.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dplushif.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeoysmu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyawfvu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hsramepu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoudaixg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsljauyl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzomcqh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2apjanrff.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcbsrwz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deisypkt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kfptenlr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmmewqv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpukxgd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2reicymxe.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uraciacb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyobfrg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ltakwlvj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2baabkbqr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jxczowiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfaohkj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnjfxie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnuxbhd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ostiqgzy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2olcmdfik.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mobzvcui.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uteprnbb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2icfrkrpi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyuczfo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2odfkksyi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkhohfo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gslumatg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbaqxod.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnecqbnn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uezilcdz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2azevyihb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvchtzcf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdivqvo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfouyir.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nolwfwtv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2krzuogzu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkikypjo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcodqsu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvvhrnz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rglqeaid.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yimxxtlb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fckfsfhl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrycycdl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogubeuha.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeetxzl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jswsnvnp.html


<!-- 参考信息 -->