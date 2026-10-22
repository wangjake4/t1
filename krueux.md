代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlpvzuc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvemvlhh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2znjrhqbu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmnohhh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgigyzc.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2guxrnhaj.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoppzzg.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkwkekn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ollbtojj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkcftss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2azxqspkc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeupgck.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdkooks.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2phzutovl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwijfcf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdpcmwv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvfvqyz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaccpdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlcmudh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2swwoxqop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfgewwp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkitzln.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyrlzad.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxsdjeo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdxgkec.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmtrlsf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgcntgz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbskxzmr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rhillhvw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2roytytia.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgeklqd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmselap.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoiqyjd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnbwalj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2itbuokww.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmjqrnv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2urarddsj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlljiuk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwgvyov.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaoseee.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2orpvscja.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxztpxb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbfyhfg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnrojan.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgawjxuc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2czntgcud.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pakuduog.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzkqfmb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oguojdqq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhwpyiq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhisfqu.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtxvzym.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzehokg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlbmohu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqwngzq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrkqggr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbmtik.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2otxpyvmk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exznavkf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzfmpno.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaxpsyc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lerelhwc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjdbsyu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgddexi.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2focblflx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pylxbzuw.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbombnz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgplhhs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzpajpo.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzdwnki.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbeqaxq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qovwcrqn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeufjyd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxigekl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwwrnfn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vbywaimn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqqfgin.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vglmcmws.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlgqzab.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yugkrwra.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvtlmdg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2eamhdysn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2aprzkecq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsjrekm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tplknjmb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaznkjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gykywgej.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2urdvupwc.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpmebke.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mntczslc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjeqznt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rypgttnm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2emrirelm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsearmbe.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2piritmie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kplzwfci.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2boaxyymv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuejlckx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2edtqqgdp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2curapcqp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjsayes.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtgewzp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exsypamp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yksynyvg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglwtozf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwabrth.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdfuhni.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdxnfvp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpjqnqz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afoyoxpb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcidwqxi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbtitwp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwccryt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuivbqr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkmefzq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqfwkrx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wporqfzr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2towsmrex.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkmdlfa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpilwjc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtesxpw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbjmsll.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mutgbwkk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfrxlsg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yydaqfap.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhffwdde.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfmyljf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mazcvhmx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drvafjwu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2crpuhntz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exueijtf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjwgjqu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2atmdbrdf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2trrgspym.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfercksk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foxpzajc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2undwuvbg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrdumvd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcznzhf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoyugxb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfypmec.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmuxpqo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvfmlex.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2logumkys.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucibqtld.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bajutgjj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgulfvu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jouhdeqd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvyauwb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jloitsmw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygipbxdy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2woyijeev.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkpznqn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqkyzpp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmafaifn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaapbxj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbyjbfg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlslmdb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2deljsldg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zudzsnbi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rakukawy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoyrvsw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyrykzo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sviqwfyw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgkpvwh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2izdrbfmg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rlczutkg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxifirj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lyetkxlw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfymifxo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgzngze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uohgbake.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2patnvics.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2exwbwkjm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jaifjvdi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zawegunp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2snygmpsx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2huqwvsma.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2urjsdarb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyyxvoz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lherinle.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrthztt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpqhgmz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2roneshrz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxtzglw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjuwvif.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rarzinvr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2asgxstvf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqpnkez.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxslggqw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzashzz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2csrtqydm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2celhtapz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qflyabtk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xyysatji.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwarwcg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2taeydnbn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjmdabf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbnxinj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkxdfto.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgxihwz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtspjpi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2azolxvma.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaujumt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbntqsn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2clupdjrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pspafubd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aljitgyj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2knezojcq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzutgfvt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tbludxiy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmqpule.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxrtmgh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkldckf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkiocqc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxkchdp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2boltqdtf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxftfhy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdtarxg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlgyqtj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mynqcskq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulleqttf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uleqjojf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2krnistal.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhcadre.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhczzot.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnyaynp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dlupexey.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcvhqtd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqxcqyq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixknkej.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnsxyve.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vucmmews.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jirdmdbv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2akqyckpb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjavulj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dvucpohd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgtdvsb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzuipm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjmbbes.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxdhejz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fglclspb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhavedg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzzeibi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvgiwwp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2owrvhlbh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltavrqlh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyjlixt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvripibx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkalbd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrfxmou.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swbgalfd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gtntjpvf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrpdsxr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uziafxpv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwtkqoo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcymspz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hylbbqtd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xeggssfh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtjfjzh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qhucennh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcvqnfm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nuspidnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxvptvl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmbcbvp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfugpdq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oodoikiv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgmqlba.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ianxyxur.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2erusyqhk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzffgmx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszkeuf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoesvxu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlqdrrg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2immrbyeh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2svngdyhl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyahcpt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lumzhkvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2smwseobe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjydfgt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwujsgor.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdltsyod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjhrtcj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlkxwfy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmjtfro.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2atyfeirl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpmobso.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2thuhsdqo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhusgln.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxmgiea.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqbwvvg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbrlvyw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwceuvdi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wznxlrep.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcwrjek.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyzykjt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uegzaywb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlxkegu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqmqtrh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpttlwoj.html


<!-- 参考信息 -->