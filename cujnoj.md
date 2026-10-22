代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjgbzrk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuoezdx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfozeojy.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnwgiae.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzxumvz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsjdzmj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fggxjtkt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqythmr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrtcfww.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxemevs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2qloauhhl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhmmrlg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnbqoht.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2urvlkuor.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzvnsti.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkwtjqv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gthinqbj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gceevrcr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2judhnapu.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpamfnq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqykwztb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmqgyps.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcvkins.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxnmuva.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jajplrau.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2btpnsuta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvamcxjb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhhgpxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bglxrntb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uukxbkyr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnjtsmi.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgobbit.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsytzjmd.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czhjrkyl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxooyes.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwajgar.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2fdigzmjl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2srxjjxqq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcsvbox.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbfzme.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtngmkdl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2okibskbn.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pvubteow.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqksff.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ontljcgu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xekzqqtp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bonemczr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kxojlpkr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vafmlibu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrchjvxw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltarqnrg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rogjjjyo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oljmypkk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nficfcyt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2liwaeuzo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2skzjdcsg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgizpr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2smqxygel.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfuyzet.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvebudye.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2teufagyd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2paehxezb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbtoksl.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rfibpnxf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjkpxix.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdputel.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhqqcky.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2etstmhdx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoribzcm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2veuuwujt.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucttdwxv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epahatwq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgtmpba.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qdioxibk.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ooemythe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fotfdfka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhckpie.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvhoero.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlyiheo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmglnnoj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aivfyqyn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzafpelh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcpxagz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcizoxb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2szztdvmi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjqtcdb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmaxbfd.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnjpav.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsacziiq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2afeswhmi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwlhvao.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjvjilh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpnpwid.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjawwwsu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpcczcj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhndabn.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnnfhyq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwjrkiw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2srqnkieq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxezutt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcvgnix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpdjspv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiawjyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faxgohqf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wngmfexp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yilgfrhu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlwvafw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaygvgg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazhsyyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhzovfv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2neozxdcf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2algrktfl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwetxyvj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmojkduw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgukkni.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ganylzhg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwuzgjo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrmmqqi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjubdiro.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dttmnaqf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mrknxpee.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2liubbbxo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdngwhel.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qebprain.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwcfrtn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqylybyd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjmhoel.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtjyigs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaummyy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2izrfnuxr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvjjuzr.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vxutmcph.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmnvkll.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmjwrur.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhoegod.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2llkeqxrg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kymhmlkp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrkmkii.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyogpjo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmryump.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2trcgstlt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqxrwlw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vamwqqta.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iakqcvgx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nydimwjr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2erdaqwji.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnmxdks.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafminly.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veqgudcu.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shjyyepb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbonktya.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpmczff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2psufukzj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xasegfpd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxakgdd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aemqtypi.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2crimbhww.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2iviloooz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiikodb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyiftpn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vymbmbtq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkszclma.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqibvxc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sulagfzn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgwzerh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjgpqzq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2emgburdh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhflkds.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drvjdwnp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mokblyfk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxesfap.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czdkfzxn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lziebxyq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2momjwzqk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bsezoyef.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsudfcb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hzskyyge.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxdhuiq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtawfbm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqutttc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rsecwuhk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbkewnh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbfwerc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dccthaaz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlnngfv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjmordi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2eizhluwq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzlubfr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzotfzpb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2blfbpwux.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mceiprck.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fklbdnok.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2oapgidoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbltits.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rylgiysk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrgcgni.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yelnnyfw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewthfbgj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbqxtji.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcaranc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqxmoia.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqekzav.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkvbrtt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdesqsq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2slvhifxy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvebhvf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2symlyezt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2unbkwugp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2flglrvic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlmkjfm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2khawpavw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nntocfoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqrgqxj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zsydeoix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asgwkklr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hufehjby.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhgqhve.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qiezbbmh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kodchuok.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2orbgiloj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxutrwz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2inlkvtng.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iutdxlxn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ayztuyli.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuknnhf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpkwlda.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiimksi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2duwkkgyw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2neffzrgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsblnsrs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zirpshku.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tltlaivr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rsofailx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kevulsft.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hndybhxk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2esxdmruo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwuqcfc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2katlxfjb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrzxodi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeflvyy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugscsph.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxlwqpp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzytift.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2annljouy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zibtcuoc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdlppph.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unlopfyf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuieimr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfjwlzv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rproztcp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imjdzrzq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rihofhiy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2irlremvn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsqlydu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiqcckf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucbqesz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmuzbaa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrltkukz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjqicoq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbpemuu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wonwxtzo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfxyybl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fshlkajr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpvbpwc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaomrmr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrlisah.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vcavzgme.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2oaepahye.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdcgahv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iukdizpv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumekmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aoloomay.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhghxhp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cheurvfn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gomoizcf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctpzxg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iggvcbtz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2auensjwn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjachcn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lsizrntc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxynejl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yuthaaqg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2solblvag.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwewlga.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxlovnw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rirassji.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2znpojfhj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsskhbgv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvopcsuz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2haidywqu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgvbpqp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuuwurv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsrygow.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2idorwqdl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2avcnvhgf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zppimodw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uocuqeum.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjyrydt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lglxeqje.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2woikylzw.html


<!-- 参考信息 -->