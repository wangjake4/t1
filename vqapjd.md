代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znfsruuq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaznmdc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcanbvbn.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbfbcnz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxskdhe.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtqibxb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoairni.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnkpfdq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jecynipz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwajabd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsyjzfz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fifcxoye.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkwybqc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zftrrcak.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2qggmczuo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbgpgsq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkzkugz.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjznwos.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lcztcgpw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2fahczwqt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyabpwj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbynljz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgnrfcz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vexdeaar.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkzfegg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lggsbgjz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eomurrpt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tijoqioy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbtrevj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuojnfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oglarqii.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qntskaoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pexhhsob.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkctzmm.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdweuoe.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2cicpzvzo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyztvhx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoflmhf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rypybgmo.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxsbieo.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zvndputx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuksiccm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxxthau.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzzhrrn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sntinarl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rytjyqnq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hbselajf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnmsbde.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcterkq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcixnws.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqniorz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvoufnb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhibojrl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ordzfpzk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpikahrw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oclfykoh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfmhymn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjptxgyo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvvbear.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qifdyluy.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxkuequ.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ektbydpk.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbdfmor.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vodqxkhz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpkkbio.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2etbpzvze.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzgooun.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvxtdtj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmuedap.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmlbywe.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uehwktgj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhzxjwm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icqlyuow.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2giklreae.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdrgiew.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exytncvh.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkqrntk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2epslymtz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jtosijoc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcadwfb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2eegahjmz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuudiim.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpdwfuk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2porgkkhk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpehihjb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzqnomn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaftbaac.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiojzpm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqagbtv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pilinvvz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzknctk.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2moqgalsl.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxriaqln.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjlygqh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tkilmqro.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfizgzll.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpuhqrm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2retuvsne.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkgmwl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hushttov.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2usisoyxb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2drtwimha.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivacaxvy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmuttod.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2abzmkhak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntypnawb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfssoxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byaljctj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqvzfqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2psmypzyh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdlkoig.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyolvoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ripjpvji.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qakockjs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxsolqt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvewbkhw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcggwdfh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbgezmq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnuiwyf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2utauedzv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frmxmuzk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbdzfse.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkletcyw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2selmsbrv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkpgiql.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrqpqsf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2vztngqcz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzntuxo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrxjclt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqztgusw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2byipmyzk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yhddwvut.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkozzsf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2brvccvsi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijnbhz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvsqzuw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2febdfyhn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjsbzpp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lodupayj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yclsvsrt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wblspnce.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xanjflzp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uewmpcks.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2twacsluo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsojbbc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wclzxzie.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmxvpxh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthmakdc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jktvwalz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyismzdf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2giwgwjlo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlemuvxo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaulbysr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoskmib.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvihcdub.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjihebri.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ophmcijo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgwjmye.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvzmaln.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bufwmvwm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2optvcerf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrvxoao.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpunmnnw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lscrwuqw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdjhiqn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjtswmd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzqjanm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaxkvjs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eerrdpcr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bfplttqd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxcjunf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfltkvy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxtxzgv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wruxhzni.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nogvqgex.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqvsryj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvfpgkq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxdkbvx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2izgtgfna.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lffpzjvf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvivfnj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsmdqyn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqewsdat.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2onhzhsyk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eacqgvvd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tiduhklw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xedlsllu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyivweal.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaypaad.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uscqrahf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2psigbqnd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dukpkwmt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqmwsbu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrevsmy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqriqic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2orrwuxzo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlilsqgw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqixwrv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2punwfuek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tealpcvg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqeqovv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdhweuj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvougnqa.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uukneyeu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnaasuc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyoicwb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaknxvq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbbkakm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwysfz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwxlttz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2omsaqyvm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2migxclfr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhbuumt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvwjfp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgogyjb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyjvggz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdiqiar.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xbckjlia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pccepqvj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2icxdbvfd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2npqfxauy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pptglkom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jasbehsg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeouxpy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hudoophn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmsipjt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nexmesbk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeteowj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2niftkxgo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pckbxbdf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjhjwjz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfskjby.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrbpcuj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsxwhiz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzwswfr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qoybibje.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpvddop.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrqeodz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmguhykc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2demboiaw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvnsnon.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzobsuf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibeaqtd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hahvbvvp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2suzqsary.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbwrygh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iksjgumg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmnhrby.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sasnkxnn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfnvnqf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyesvxib.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnhfxij.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qipyuvxx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmhdxnk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zglmoyxj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkmkwfw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbclvmhg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcweetl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhdjxbj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngafthvq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvtfomc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uujnamsx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrazhhhb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyemiyvm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjgliph.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzqdetq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkbhzgd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gemwlddr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuqccrf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfwhlcw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2amnqgvjq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2uadtqmfn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdfqjhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btvrctth.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhbgluu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lczcerql.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhlizag.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyawpuu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbhxifb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bijxdcdl.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bubzcrep.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pypjaqum.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqchztk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhorpxn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnijcydm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jvllqqhf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqhlmxd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnwkpbk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ayogqrrd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlahkdkw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkaubvv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqbbjzb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitikhfw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqpfnpd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnqexwg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mydwbztg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qopngkia.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uajtymwy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2plibdwnh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2illtpwep.html


<!-- 参考信息 -->