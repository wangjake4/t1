代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2aivshqwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyrzciq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgylruh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlnipte.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgvsqse.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2orqyckaq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfjkmmk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dsygieiz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoxvvfa.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdavvbr.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqgkxrx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zokjbopf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuwzrkz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyzqiqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2tujzcbbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2aijkyxcx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvrlvv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdmveii.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qgafwbmd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2khclffsa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpwughh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2havgjloi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eelokcix.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjmljue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imwgrmbl.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2grovxgtz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxdjzty.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2iquxwtsl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrrczej.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sducexul.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2owlwndxb.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2llnybfkf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzxwthe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzxepep.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2shyrajgl.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2azcnlino.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvzlatn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wgftivmd.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2srssddvc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uccikzfz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2twuhuaos.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2duegnfex.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfpdzqr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlgjldf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyyaooi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcegqtkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzdaqku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2venapesk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2skisxaub.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mofoykbc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2twndyxrv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gekdtuqs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2svxhqwsy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnbgpka.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jksxqgmo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfodzun.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqctvbkl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvlqsgw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2utpadssy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2pvktyght.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtskaek.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2djkoerph.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avacemdw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnormqp.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvqacbj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqczjsh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqoijwx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2citfvyhs.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2emkmdvtd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fmisirus.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iauvapmy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfpypwe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyqxkwj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxrohck.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2emjuoaqv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiougqm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiindht.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2eryeojif.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnjcokd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpceusn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzmbpfc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqjqjfr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqqadco.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2moxbtooj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihifrggr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyxdstu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2svbxyvsy.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wihkkuom.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2czkxhthr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjsiovy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxmhjtz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwxdlej.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gtojikrd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2skvjxuzj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcnhtwu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zusaspra.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhkfihs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfrzpej.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qlftogyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwbbhtn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uijnrghk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyueuls.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmzzrzt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikffphhu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrvbarm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2juwdpyjg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2svnykqfv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yokkgdbz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibnyfvd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcitvtkf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsvfkei.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzexsrl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkmxihe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhncuhor.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyglegf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rilisgft.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqtmvko.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2llekvvmh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtendjjh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2axkjwndc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnhauto.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dguxscdh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbacuce.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2isxepxxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pnimufgl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoufanr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2giqgbzxh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtdqzqu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqphgtu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzcxess.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxokxegm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffhstp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazrtqx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeqdkhh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hioqmuds.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqhvvpq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlozedu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdovmubl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvymjoqm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aemcrirn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjdcxuj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfyfarr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zebvpooi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2veovlejd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miuqfzwz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkikghb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsyvhrg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnabdqsx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tteqbsmo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2chnfqmil.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hzludtzw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjanwji.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqpyvtu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2plzfaztu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoxrjds.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2weapephd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2avchcllq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bagekamn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvebays.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2khwjhpot.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhurcmx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsdsntn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cefohnlp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ranjsqgj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvfhxoz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhgwbkw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxqtcxp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2svbfzvct.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsewdyh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpogqbd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbjmczk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ygndawwm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvumzrb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2elquxtmz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuqbjnb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vweidfmr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bytvxapb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiafmkhj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwbdprk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eihohfvu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzeuccv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjkodvo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmjtvky.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebivloj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2paomgcva.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsredyt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejmaqxp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxntnjwg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwayiky.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikobntjz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjzvvvn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2buuuhojg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaqfjtf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvqrary.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrxqltp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2boxzkbkz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwejkqw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uihziimo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmkmrap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwetiumi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvkgxhn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmvnnod.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2utrornhq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvyypwz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pyryobgw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytesunxz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxegqbir.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpenkou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvraljal.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrqjaqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aewmoxsf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jaalyixe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwfayvc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stgnxouv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hqthufxy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdynpoh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2efccrdlt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nanwbodk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllmhpdq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpwjnnc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2woeztgqe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeladjd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2navqsetb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzktocw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qcldqznn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpxuhec.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2icexkufp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2viwhhmkw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gunjlehp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2orzgvkst.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgxhzsi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sihjhpvx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqpcocr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xkugjqts.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pksrsalg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2sewhpofc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2isfngpxf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaahpkr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxnkgqg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppavtslt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gahwwfjh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sraapsdp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdphemul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2smlcitji.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvufeso.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwvkjwf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwobnjy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2djhxylop.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtnionx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2somyuejs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxobjcr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2euzutoge.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2stsiaswd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjxmhwa.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oecrvaux.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtsjkfz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mznjtsaw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2edixycww.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxhyyxq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkcanfr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zulcjlgh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ckupmvcd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbfgjoq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2isfctofa.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaesxbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbipsgap.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2faajodsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlwzqik.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqdzzvi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xeicfqfy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkpzwaj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihajwgwa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2thghikqh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2matzwvig.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rznexvpg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2espsfsmk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgsjbis.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgimwox.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ligskubc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uachiymq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhnoelb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xljfklyn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2egoyafce.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvibpvx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmhdbff.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2usmvjefj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpjbfgl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwvbniy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2znemfwmj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhidpev.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dninidjd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutbktuw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgditqd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2harghxpu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcfzhqk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsrjgvy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2llownfgl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewprcbnk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtyzrwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnizqul.html


<!-- 参考信息 -->