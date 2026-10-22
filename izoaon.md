代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugihcoiy.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwfcqv.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2encfbtox.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2whicbocp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmawqfzp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2urawrdrr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2alqanwvl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnfgjmn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uncbvmop.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2clwdgwmy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjlaoss.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mopfwnzz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lnasjovo.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebftglal.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsypeof.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwlcrii.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2unqalreq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hurshyvq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2byvsvezu.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdocyqdk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2idejpynm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvlaapg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmjquug.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxktvzh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqulpsdr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzdiihk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2felzmbcv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2stqyfhqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlgdjyn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkdanv.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgivcvx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xayqided.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaseofo.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvdgich.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwfsahy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2itjhztkl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2crilsjdq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2silyabjs.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqvkhkn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yatnblut.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymzpqvy.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhtoiql.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxluwyt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbddwbwz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwzfblf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtnlgbn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mypyvaip.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvuqndm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2omalkayg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmdpmor.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2haoplkdd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzslqsne.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2znhhgwhi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkgugzv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ezddhxkr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrpelad.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyywxjf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykolyyuv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gneogjml.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeczmdk.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wolqcakx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrdcenl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2olpbpvgr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2eqndekbk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2djdlxypq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2eimxvulz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrvtwrt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsoomhf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwypcra.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oogaquqk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzwqfei.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2efakctxq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eefxiyyy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmhjcym.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvimrca.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2twhpgytx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkbmlwn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvwvyuf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhesbbom.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nylvnoze.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nndoilow.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjppyguk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjascxha.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2avwapdqn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kretcbdh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgcujsx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ewexkhua.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuopfww.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhmrrtz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2semkflwk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgdezqb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtrbqye.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aavqdphj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcpnwjf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmopmviu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrcvlkd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkltdsr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjcjobq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwzmkec.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2hayfiiwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrsgjwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlpndbr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2npxuuwby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoikyzk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2btbbbdbw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jplczdyv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbvimvp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfauwea.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlisnsg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdvbaro.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhayjef.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbbkbst.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ascionwz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ausvcjog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzvccdo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhxoghd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzcnitr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isfadiba.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbklsecl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijkoqyt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbmxgmb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2goivzjbj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytueuncq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdlifen.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwwagja.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hoekzvgo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlxhmbe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnrswid.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cfamlqxn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnrhrjz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dhksdccw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaboiok.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzbmqkm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzsesxg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvqsaly.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjjnaaq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hereterw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyzwzre.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaeuyar.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldewntlz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdrdugk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2beofcayf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrcwcrt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziujjtns.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnaykua.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqjhbza.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuesdig.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywqvmxa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djibithb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsohidgo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyoqzvn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkukwiqg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpbnspr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyklzxmw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qiurasrt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhqsisw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkejndq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdkatkq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqejwdhh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcbtgsz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqpgoav.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xytpgbyk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgvbnb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgrjefc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xezirvas.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbekdpf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxkcocw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vephugbg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvpnivb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzwykbt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlqvjpy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvvebwi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdobkuc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xamrmjrs.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2srrqmrqg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxrnlk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2txgjotvr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcflqgmc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmaudez.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmeddln.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xjilgcqe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyjolcb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwsmhdo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlzqtsk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfacknbi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqgvcex.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxoyiex.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oldamvze.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgjlpot.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxcvjjj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nchknhvz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2btycqcnk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytogxee.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yamloyxh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wodoakpk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrrhhyl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhlocyw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2abrppfjp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zksvmnbk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dwprfmgk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcmbbtt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjiueot.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tklowshc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyvldeh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2evcykcex.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfupghv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyertvd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzbcktp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oltopjoo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gknovvjk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkslrm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcjhtwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmrcznp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgedqct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkirmlki.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjsmfpu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cumnrhut.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2thqzmdiw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2heohfmds.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vicusmco.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjhsylk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2frbciqvg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqynfbbg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkanbfg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mucnzljm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2agakkpub.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgzwtfr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iukrtoej.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mncdisfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzyofus.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpulqbl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlngptg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnmtufy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjoazhb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eswagcek.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkhsjbq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuonzza.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgrosst.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvsbkqd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxceedcp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkheyjqc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avqwmvmd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bknvjjjj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cneexfnj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tewhuwzc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsglsbwb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqkbign.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2htgtgxlj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lgndtdfd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzbtmbi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpbgdag.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrrvdbz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvjrtjt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbvkaie.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaznrsuv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sduzpskz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvrkkas.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwchbcl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmslotq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxldpqi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2clfzhavc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fytrwzme.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oumotfzy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuucncl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eiawppdz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kbobhuyk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wruvhoqv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxbxxpv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bymcpcci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hboaqjxe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hziqipzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkodjlrk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ydynfumq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2demddjfx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjpnscy.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2baxtlbwy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2giaxtcbs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmmjyeb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zacowezh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rrojretn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwajwdjl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhjlamv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjjngvu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcvrxkg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrdfyly.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhegdhx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnnmwsb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxgmhpb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcepeih.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2idmqrguc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqarkdq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhlovxx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfykcjw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhpiank.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpyrury.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nburzgsz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcxyinp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbprbfoe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2krejwiru.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oabgatbn.html


<!-- 参考信息 -->