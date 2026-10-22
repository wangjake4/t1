代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlvsjlh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qglcnbcg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrscibr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhquejq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqqbwgy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2aamviswj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2patljwdi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzapgc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eayesvpk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlwnpco.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cojiqmfs.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2czuyjghc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxgoyzn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dyecwbdr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fexsessq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsihzngj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqatzqk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2intnghlg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcendna.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsbxebv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbqwgjh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2grpavuqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oygxdlws.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yixcwiur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etcmydti.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxozwaz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfjpzdn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2nviviwku.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liuhxsde.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbtrnzb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzfocia.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmufcls.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xwftagrp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeimgdh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpwjwsg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqovdgf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2enaoihvq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxhzutm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwkfhyb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2azmtcgov.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2snwvjolk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvojppz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvyyej.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ouugwvnu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2thchtdpp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiayord.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzwqugy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpiglei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2flbfdvcr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuggdxpa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvrnib.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yufexgqq.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2chkallqj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eygfkovm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xigvmlom.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbzcsin.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwgmdtd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2sohtomyh.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiwlvsn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kaninwvc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2muleiuxr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgdnequ.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdbgcds.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxmvgrv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsydrrw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwmfvpb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkujhtqi.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyilusj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgnbghc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbhlhga.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdghbee.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueirpacg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdenatu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsvpzly.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxejzyw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiqlpmv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiywfgi.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2iehpverf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dclmheui.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2uebtaeyw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fthjbtnu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnlxupo.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkkqrqb.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vlralbfc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2antvdpxa.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wywbuyss.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjnsiqt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jduwjxna.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjieybf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwybfqw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyeggzh.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfjxsjp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqlcqzl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhaqplo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfcvnrp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xgduodap.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2abeulmij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owwygqcm.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoezlwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgzptdv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcldydq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnpcqbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hilspuyk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2triztxnq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdydtmmx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fejeahqr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoxfskr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsezvjcr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbbusqv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfhlpew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2taeuslyu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsgmyec.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfrgcgh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvkivxf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzaftgs.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hernjnyi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gidoqnpj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsojlgj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbcbrmn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpezuem.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vkedpoxl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rudemzfg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2sincncpq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2asbyobmj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2crsgluin.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2owjvcixs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiwmrbn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2axemjyid.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcavwqyx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgxondy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvppnnih.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2drbcqhfg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjpllnr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yozhmpup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uouzkcyq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ittdmmpr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2czgarqdx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjlyuio.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yicpojxf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgokied.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkmjydb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrkmagu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wudbcqba.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfvvgpt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xieizmgp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2umtrxxac.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgccvz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2buesmtxx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzozwjce.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyvzpfr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqcnpre.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2chcllfcq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iowqjhsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oobpxjfj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnxnbpw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgvjwuh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2doomkfqx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfikwcvw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jfptppjx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2veunxmfg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pgobodhb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmzibfw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqukfhk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2brwatrtx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2muwszivl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjbaluv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcsmicw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsaqesh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hledglpr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2frceyszf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsiqngu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtheklj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dumtaphx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfuehor.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2copvggar.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kozgoido.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2orhaknmd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2augospwd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2plofocsn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2galiidvi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcrfhoo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtgqofc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvqgyxw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeaurzj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwhdiqd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgqyncl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyjbdff.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yibcadvo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2icxxcgll.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aodrzuri.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afbcthxn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjeunji.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmzvefc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfrmvvf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tohgsgnm.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxhdstj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kcthrerl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2serglutb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wupydixf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2njwedfjm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzepznu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbfjjkl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hulgopdu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvfdxhp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqfxluj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zniloahy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdnwewo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kocakujr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smdpwstu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xukgepcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqojlkht.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmhqzzv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxejtsvb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfxthvf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rgukdasw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iddvsgsk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbreiiia.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2krqvuwls.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeyyisp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwtrivm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfktvjy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgtrbjp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wkandqgk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wklixjqw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2koumyhgk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eradeevz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jemiwmvy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ixylqjpk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpcltas.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2molyovbt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fquujcwa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2iasasufj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyiwvny.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbkelcd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byisbixv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lazkevao.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjeatrz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuetzjd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwzxbjf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2eogzwxmz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlbfifb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcjwmyp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzpwwpv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrggiko.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdpznoe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsxxuap.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjstnozp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xedzoike.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdxvjir.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnxvtya.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavquttq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjpgkjd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfgbgwd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2enyjwoud.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfawxjou.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgvvitr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2owzsztky.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxndmmh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwxjlcm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wadwvchq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyobcuc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2soateolv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqchyoz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nwakruyx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbixymu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnefchlu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yearhwgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfudvds.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2glnizxse.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2olhctbwu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrcccwc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsexmwdo.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxvwtkr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhjzpfy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2otvzefet.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uafieyut.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmpatxo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbetkgp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlfnwae.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2euhusgmz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fkguulct.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvfrdiv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2omeegqkv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlqivtz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzsvkbe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdknckz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcpscfc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbbmgpi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfizzhd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqohtmb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhpkqjv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqkyiuh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrziqjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfchepc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqllvvy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsqrgzd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcfoiak.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmzwtbc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lonsmglr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjlcjfa.html


<!-- 参考信息 -->