代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpafvbzl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbwthpz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rytbwjay.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2onvwqyvb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2atbhlupo.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtdzkbi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgbrhma.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjluwgn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwydows.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2akihlmxo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhelqtrq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfxcvf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ovylfrpz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyusnhq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyhreql.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhozgil.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyeibnv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnmstbu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpssxbu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnanwtv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmhlpmb.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcumtwg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gntitasa.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2siglsgzw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqqvwxt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgotojw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2buhckbfd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wtugkuzg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqrjpzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfpegzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nilbnprs.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nffuaqxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyzmoym.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkviseyh.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxzbkwv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdopfpqr.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gofhamjk.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerbtzlt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bknlaqys.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjmalnh.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvxhyct.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpahekxb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrkaamu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hufkbxon.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjcngjk.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uecfspku.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwflbnr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzermeoh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxplbbw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iumitusj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkqsrtn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdmsasg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyupcyep.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jparokoj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxnjerf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrkdmuf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuktqact.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqakoup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaqnzhf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sykvmokn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2enbauuwa.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlepbwv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvyzrje.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzsytdt.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwymfeql.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2juspvsqn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqpcadh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaryfsa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcdlxtj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2theehquc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeyuuuz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2catotndb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujtdoco.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixloqipm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqsmbk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2twfzfgpw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrfilon.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2peyalklx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjnhpzz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopskmaq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjexsjl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhupdocu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvgygtp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2caisktoj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrjgftv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqsoybc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xysztwta.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzahjpr.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2skgpusls.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sabgiwgp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hppmlgmv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qytxhzcs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvvshzh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tedpznta.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuybwtm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqtmass.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2whhuosxg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsjijdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhatnvoj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyieleo.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxynimr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvryrilx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfospkgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rutrahmh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfogcqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwcvbsk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoxrqwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgjqlnu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mozudiky.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pysjvzuc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2scptyucz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxndfhh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhmrsch.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvslpgk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ketiblqf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2obyuxdvp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hirxjakb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2usrbgqst.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lurhpyny.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2feisrkld.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozghzqls.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxkvkkl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoijzhh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgkhine.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhgqfkg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zisgurrk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuddayr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwkmlet.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeapooy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2maddzbwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbtukqd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2khuhzdny.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vcexdvah.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxjbzhu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnzjauo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfwkirz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtfdsq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clbanlwb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aynoiueh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2alaneykl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vynxtesa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vogxlclt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzwcoqc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqqzayv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsgczqd.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnujoozl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrpsbtk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgvreda.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqudtfl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qifzmozs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiektrz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpwnyyd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjgdcdm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sljxairj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jsieawhl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mllymgdp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzlrtg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwuqhct.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yraeofsd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2riqbchtv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uzesynhh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkoloei.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfkvedr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2evtopoqa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvnicpv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlfaymv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jmytewyh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rguoxohv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hdydwuox.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pcduipap.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pdquddmc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qadlkrxu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifufmbuc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbexlbrw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2npdkzajf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqvqahp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wwawojrd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnulbws.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nkohbock.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2upsxyzuo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2owgbnwyz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2doegdvar.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cotmfojo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkygrrj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzwmsah.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krclmvrg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cabxapqx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2chojhjaf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftefvrca.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpmxzov.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyiehxf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhlxhzf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bklsradi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2conlmvgd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzawhlzn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgmnycm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmelcwrg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmalrxmd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkcrwsu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2asdyiiap.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yflyqdud.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrkyqrw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2czqltket.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bedcsrfn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mikblsnz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2epauirpd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hffuoslp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyopmwc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaitmcg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dajaajdx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgooicm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ykreqpwp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwprpga.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixribshe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbdcsxz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgdiswu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcikicl.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2etpcuzad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zieazpip.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvhredo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fciscjof.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnijpho.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xtswjzwa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgetfkc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxtexcv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfgcobe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwxabqo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwglweq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2atasdzcs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fngcdopa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2euqrxtsw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dkctbvho.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2objxcejz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpprfub.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2luouttbi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxbmwaf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zlifgcta.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lfedexnl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oimxdvsb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2otyhmqsq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkiajnt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgfrxbm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqltjttk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pclhtidg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mokygjhd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzoaagl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2heksbzhs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqghvbc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcijcqq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lotocubl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydizwygd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2njzbfqai.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vzthfqhu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcnsiog.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbkzagq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2onusewik.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxygvdcq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dogsjvcr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2egxaxewi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2smpbipwc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppefwwgy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfddqnqs.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuvqyjl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmsximf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pushhbyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpyitbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvbxfeq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2npryasqa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nmglzrmh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfxbtkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkvewco.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bxacnngg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dskqrjjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mestdkzn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gujjfupa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aayatsxh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qqayvfwd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvchxuui.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvldjis.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxnwagl.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjlogtz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxctijdl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkckmqd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqioguj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2casadhqk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrfovqn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cblxgmbu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aocguhlz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtwffvy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2twjpzaph.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tprscufs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2scjohpie.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtydcwlm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjqvimz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuoztss.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjsyloy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqjyrwc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbhfqtk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2irsqkebl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixheigkk.html


<!-- 参考信息 -->