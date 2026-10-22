代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfmbgfq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpejiou.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2opgzuzuv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2agyoopra.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2htotmigl.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewgdjh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtltqgls.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqvmbqe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywymymt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kupbkyfq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjnpnel.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vutfxgxg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jcldkwxp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2goyavgwp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2srzzaodr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hoitkayc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkoamp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzihcjxp.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qzipizku.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxlueoo.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qlilgusk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2thnrosju.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpwnzoi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiarabr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpinrami.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pllwjznk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nuafelhv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmweovz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfljmstv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnahuft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpialqz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnxeqmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqleozc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yizqgbnf.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkbmtfc.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlrsbeg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzhdida.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acphwrew.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyfkjqu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fwotepem.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsdmtwl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vemmjorl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eusqbhuq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeqojue.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2proggfog.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kenfabvi.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2leuhktje.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzntpue.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtfbweq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrwobqr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfqjsbw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnkzyvi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hffmdskx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2svsjqmkf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnwuvdd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhijuogq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbggex.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfbvmtb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvnbzju.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqftyowo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvbicmo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hocbgxjx.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2itrdxeve.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gubhtmmh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfzlbwq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyetjtxd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzijykvj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsamlnj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnzooaf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nufibyis.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhoqjet.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uelmsmbv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvrsuas.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iioxjsjq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmnvdcu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuedygj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpdlxus.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bajhopkh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2upfxnxsy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjmnpil.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uegowyey.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2moupldys.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvmcaym.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiafmpp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfbwlts.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivisfzst.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vghpogzd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jpudbioj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ugktyfrh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdpoeya.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzrtayr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjdtugp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgreaux.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxujjhu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kauvnhuj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2occezsyy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsatfrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xniqrdnp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmebenq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zczvoupr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxrjemf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2diifarbu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxvyuir.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mwesdmwh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnjpgbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrsxqej.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2elvvqhgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yworlxul.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uioalegn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqgbycr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjbgyyi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2isaciuwv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgcwomo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqnplfh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2supotzyz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyawhybq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsbjocs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugssalqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlxqfla.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbgbpcq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltseexvd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbueosh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbxyelx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2flabgyvr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcnzuyi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjcnudd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyhbrng.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tuafruzt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2alqokwbn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaygqer.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkzoqap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvwgtci.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nebfqcnp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvcrahd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gskktpua.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2txahadrl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewewfkja.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzqbyhp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdzuswh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wubmwiwu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqtmkjm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaqyslf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufekfhg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeeqdnm.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtozxzdz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czhaqxfe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzyzlmw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdszmge.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrcjkrv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtdzzaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwelgyek.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodfbqga.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuwcxvj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrzpkhr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhqmalp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2femiewrq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbxvwhb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdauoiug.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvmrzpi.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpceboa.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cxltguln.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sejspvkk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hryniunk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qemyrnnq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qcilvmfq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcresvio.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvbimew.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbqtesv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvvsgeo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2scuisilc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xaslkdfz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qddaiwwq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofzgdag.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzgnthe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtudmgt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2otdvlpdj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bswevsta.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhmcwqh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuwyvpm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sqskhebk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtoikxs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mykiezpw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2askejexc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wddvcucj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lviihoth.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxslsgt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2chzaqrsr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2weopmcta.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmrzarp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdvvmvw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxeechc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ergwcahr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoxlmzc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2htptesdb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sewmlcid.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2prowqhqv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakqjjo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdidkpxd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbibgvy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkggwmc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sctkzoqn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zcergmir.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2axturbbm.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2onaottos.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gioivamv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xijvjqgz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrvaxak.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rukvpree.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbdbljj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnadvsou.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mfymaxat.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2flhlcish.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eikwoclm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjcgda.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hytvjyzn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfnlnfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiuaznx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wayzpfia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbifapie.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaydsjm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2edoiovxa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wodrjwgi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaxqlbo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgtfdbk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uejdstut.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2idpbfjzl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrokdgg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzgftfp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuwpevx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyuawfn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvhhkyh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xibgebpl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmqwbmr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugymnufy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfxhxah.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cajadhee.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtpqxqp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdhxbf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzrvhcw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxgkbss.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pptmwnhp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiknuzl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuztjtk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mroujhcy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehquppqi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyktehhw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyxstlq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2aicyaogc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtgvtzo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzwrghb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qomxljkj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2srkyrcrc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqbqofx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gysqyluw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewfiwvj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcayvnw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvywlnp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrqwrdu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2okaomwpj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yodkwpnf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgwckim.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2iilhqmbb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2madiggjf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfjzxcu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2edpiohyi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyreavq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxazzlmc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2edfgtdze.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2igvqvqsp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kfowygly.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gytshedu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ddimjjam.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhbjbqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdotigxh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvagozbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feyzfieq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ujachqzo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiclfyt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aavdedsm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbjibaw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjvxlng.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzfqjme.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaomsfg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2umwczyil.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfcfiri.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdgyuni.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlkygyl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdegxtbd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uwihpitl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbghftav.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmtpqzd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzgxvxd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdulyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzguqpgq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dawvbsfe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2icmhfnst.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjbvmat.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhydpph.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2psmmvhcw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gflfefhe.html


<!-- 参考信息 -->