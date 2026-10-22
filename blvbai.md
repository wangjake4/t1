代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfclbcnb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdxryex.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmemgqno.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zikayvdt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncavslhg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2aslrvbnx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2twbhthvz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzzilkv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzenwjy.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2rumwipiu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbxvggq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2adrwtani.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfnodmd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrvyflk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2avogwwwi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2baglpxwm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpjeayc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlosqag.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eloyqtsz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2msnlfvoz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgfnuww.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiusmeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iofwcjdg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lahtihun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdkekjs.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unmmruep.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiupxsd.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzdgrhl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsflhxeh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrdjyun.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhspzmz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyohnmt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mehommom.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpypmaj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cinopvpr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgatpca.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgavcacz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jahajpel.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2msjfyplr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuexsso.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2icqweyjv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyfmlrf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqpagqp.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzsjnwt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxygqpxl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tshuvlmr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhmjfgy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiluhmqv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqoklngb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kupnmjuu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2soxwtuzj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2grvbpvsr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fploamlq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gurghcup.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvzilyq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqnmvdb.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yancnzlh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwreijcy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yceadphz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbcmhph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdstjfm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfznppp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyhmvsl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvqeklz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwvxbzj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2urpfkurl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhioxwcs.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwunhqlb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvkjcxb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoaftsp.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2taodhmip.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwtxdjd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgkjtfn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrrxkgd.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhumujnt.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnkvaoo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbimbsj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlwlfsf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmzsyld.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwtwkcj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2bfllqigp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2emvinohj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bavdjden.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdtdov.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2roysfgbi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2agkygtcm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzhacay.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tivnlhzb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyyfbfj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrigrdnf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kolakejs.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jugotrzy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iflpmuqg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxxfbuc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzovynsn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2givmqymu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxztbwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwaxsio.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmwnasy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbdogdw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmizfjwt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbyhfdz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehbuimk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqijyxv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhgongo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfucvvor.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trszwocj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbilmvvr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuutrzs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2aadbtffn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeqmzjn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiapqve.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuftpqe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hicyvlpp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpjlfis.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmalwkw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdfpdgj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtnmdna.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mchkydzm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoxvdnp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2terdreeb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxbwfhy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2sndgeijy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wggyyqcn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyzxcgf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyhvztc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgfrqbh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jovesums.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixoquxi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brebtuqm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchgdltw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsjlfyv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhwnfgh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtulgsu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2chnpbihl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlgrbyz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2amylchro.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypxysba.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svdzhfeu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaytytwo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxyxxzb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2stxknfwh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvsucrl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2flvdhluc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvadnelg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvfnpkz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbrbrtj.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsjpgim.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrcwsbc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lahatvnt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2grjtoeqs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sutofupa.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2khgdsjdp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrnhcj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrwcdmf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zorrregv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfppxee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dotcwres.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vgajbjli.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2tputjfxf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wcabyeyq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvumbto.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwrlxuj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kexsrrtg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkadfec.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2alfewvlc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyhyzex.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvqdhdc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpcqoct.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cppvrubf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuorxyf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzpospm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaswqvr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2veshnhyw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuuqphw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2riylhspo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhzyxuj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbagnfwb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwzwrsb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdygxwi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvsappa.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2itrmgtbi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2awodjwbu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goiwqzdd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rivioytk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhoxlyq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvthwbyv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pignppjf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzgtccc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdvrncc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2grrbqzey.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxjsjqf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utkeorrf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qbejkvfq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qobgltfo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gucqdrgm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzqxlfe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dirfohdm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzyind.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwtmkcs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eufimnjm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uejrarmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zymzscqp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvxleeu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbltstn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqihjkd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctswcbz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxpnwgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcstuulz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtyjyml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjmixxs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgauyjy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2txlkbcdn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjgqqhu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmxfhwb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfdexdf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jypamprp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjxdmrb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrmvfkn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlqfjcn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlysbxb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2epuwcizo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrgmibe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tahfbmjw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uovvtnhp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbhbomp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2htipszam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvtazpz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhvxeuf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvwcocg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ryodgmmk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sjshnogu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2stdcjtxi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ynubagtr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daugtuen.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyhgiyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atmjijwu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxxmgtk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2khgzeasf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2asvdtwpp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwcheaj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvphiiue.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzevqlqt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2exnnjcev.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2esegzbcx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2anbksowh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2msiunrkt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjsnypz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxzquvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2phvarnti.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2azxegkfu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzcuwjo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2toczxmvp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnysfwok.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wflllrla.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stvushgg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uodxcyds.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiirvqw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjpltee.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwcozbr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qglfaclz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoptlqr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkmokwz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqcxttf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkcidas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iglgtkoy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxfcchd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjxfmfo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2exvstsav.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzsspac.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2slaesdxe.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnskesx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdiwvjjj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfwlivh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuszacf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hshxcrjl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnowdab.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgrffdd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2alguxgce.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lonxcvhp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2muxeuczq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmswuvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2idrgpaff.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2unmnbwxj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tafmddnh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqgaylv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sospavod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2udewdbsc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2prsgscat.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcecofu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzpumxp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcktbvc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2buwailir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2unykdegh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgzhjbx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2muoqoyth.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2olrakliy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqjkkax.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbwhcum.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiegooz.html


<!-- 参考信息 -->