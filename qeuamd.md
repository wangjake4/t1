代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihibinyg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhpdezy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tigoqhmf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dqocohbz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfbuezi.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbhwmnj.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kylebnvj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nerswhwk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bopwpzgt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfdnsls.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2buifbmpg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzxyoys.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtseixix.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzwjggv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2okbnqyao.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2anbgawfy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sixrhdjv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2icbbduke.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ywofxvyj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjgpjec.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgdvrfs.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdiqfnc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpvhavk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ueygqlgu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2elcgieqm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2thotdwan.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxucbiy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2urqkifeb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvvmaej.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2onpfaylm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdurvvtw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2belcwfbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvhjdd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jisjtuly.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nherlvji.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wufsmrqv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnecez.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsnuiwd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdjcydn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyurgzu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zuptwewr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tojhpnhm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztokmiye.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvessfo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkaqlfs.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zktvlgjf.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvxulnc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rocylzna.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mccbvydr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2giazfizb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbzhggc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzcxohl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2swqyjvfw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yeumfaxe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tscqhyfb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dykmryog.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iljifxpq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxbnbek.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmfohjf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrducre.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2duubasve.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbaavob.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjorzpv.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xckrpybl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2magscmlk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxgjcls.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzntoou.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvvhrfa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvdslgs.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkityysh.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjqohbd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qauqoucf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpibwegj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uktnrrbd.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awtxatkb.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2liyderjx.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyphesaj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtfdiqh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fbazcuqx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2laxukocg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tafjuymd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnzutym.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ancjwzhp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnxvxws.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocflwbsp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjydrgqj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhcklod.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcqqjmz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnszkoh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdvcgqs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxaryfq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuvutsp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2spurwsum.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mohokrhk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2gythwpus.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2njgixlco.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gtprvqjg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zamrirss.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhjwgyk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uaifbgop.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tyulnqpw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwifsask.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoevddu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnzvagq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjnlzxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcrkcsd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcgmowp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfdtkfw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjurswud.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aengajdt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsreesxo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeikish.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmmckmr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoebifo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2giwmvpcb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeykjpqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2orvggjpb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmzlfts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2blgefghk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fogxwezc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjltnyhf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzxrafn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuadszzt.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sznbqudh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ctosmzip.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2khzduxyh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jejvpwbm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkffsnr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlcaezj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjaundj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2riexlcto.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdhbkzb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fvagijww.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtumjle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxmhtas.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkeylpl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphrdxyh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfypqxt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjchcat.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypcrag.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmmntys.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2badybfra.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnqmnkj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgdxbze.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlatejk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpirtsc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiacwcq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkbssbx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oewaezzl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnimljjb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pklpptyh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfrssta.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vksjdnub.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zczafgxg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gljqmwvo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pubjmzfy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2datcjtso.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ervpiujk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcnamwc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2davkebsc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrjqjgy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rqazpatn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqrpxq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gvytnvsx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vscblcxy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nizmecmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oquctyao.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvlfimm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cuslliih.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hylsuodo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2drfmopho.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxwnxdo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phppwxku.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpvgvrg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rwegobsw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwcuvct.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuberdp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2phwlnrbn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmqcoxi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoomocn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsciwok.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrugqer.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdzdttd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpkxsna.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2udkokdze.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvimprcg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqcnvhc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufneavjl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2trrvnnkl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxcgjyz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlprdvdt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hliwhrwh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfppjdx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryinvqjs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgfkgac.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2arvwmkgq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2virssvlb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnvlleo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nitcfnni.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqyyvqr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaamdkw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zezwomgg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2axpxirkb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyptobzl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkuylwt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgubilc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jrljkoqz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oweftzcs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxtramx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghytjivq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2moptjcls.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcvkoza.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnmonvu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzomhjgt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzfowoj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhoatwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrknozga.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpyutjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eogmwiph.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcwthfm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdpcmfc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iulmvwzj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gspjeigd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvyjrxa.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kavzicdu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2boewbyjl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmdumhp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlbtdqf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqkagnw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmljlrmh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyecgzt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2abujhbtt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbalbsv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aljhhloc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyihrls.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvyxclr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xqujytwh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yeucmmyp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxnzubj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyylvpl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgzfvru.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdmjgyb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvuimpw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcciixz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvurimao.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vphzixig.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2efttbfag.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwhmjkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcdjpta.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihzlbem.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwbcqlu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2avtuysyx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2itytqett.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cibnucpe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgobngmn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfetsj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rucrcgcv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vivnfvkh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzhrhri.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjndbphi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyykemue.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwokyhco.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wahlutmo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfrhuup.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jggpnbwc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzpgfij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeifpco.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwvyysa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxooyea.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ulieywpx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aopjzzxt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fknrxvcx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2eymjcuds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nolherdk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfyzany.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcggpib.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjajggn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcqlftz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ucocnycx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2awbyllro.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrandcj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tipuodnh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhpguow.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyellfx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdugqvgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gkduuwnq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bskorcdg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwunkcn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsulbmr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkihnkx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2thgxmikb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaevcmm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uweqdzga.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzglkjsn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mngyivye.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnijtek.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmvxwew.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbnafbw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fogugjud.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2teaiwyef.html


<!-- 参考信息 -->