代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqkjdkq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2imvjcpjk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlicikpo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oyceinnp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qemryhgw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dekbteme.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hftjttvv.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfuqqpz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpmrybg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2czwxfvdm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2swfpltoh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcscddrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjuybaj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2luplccgj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2uglcwfoy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yhndlnam.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2plwohdws.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtzdtbq.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2auolxumz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwrhrxk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzkqfgb.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzgsfqf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fawqvdzx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgdoufr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctibrrbt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdjpsvr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2fqskqzti.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lclltvkf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrkwpqs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2osxjdgsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gendigaw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zbenodfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjhmfhz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgoxun.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmhmziz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgypjhix.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjyejea.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnelywm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2scbqozgw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpraohqr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2sradwnbi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2sltoifsy.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drxlnrac.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrrqcbu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqujold.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzovnfh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbcwumc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvvnsye.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuonquwi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2taroikqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpvruah.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2brslsdux.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utvkhtoo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkopxwej.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvenlsso.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqpzgtb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvusavcc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhshxlf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2aimwigwr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2emvvfcpx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2klttxntn.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2prxpgqup.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgswszt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gicruojx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoidsmdw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhffisn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpftdzmx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ehepnoze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvdinrz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuoxeeb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqtyfjd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dippmlqr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnoftgw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvklejnj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcihtdy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnhjlli.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2thlqwmrf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoodfdn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sawjjhot.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjeraut.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwphdvq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtiypdm.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2awkrwvqw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwodtgg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhocykwx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssomxcks.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2btlmkabr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dongwdnn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmudeoz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pejjrcrt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jksbqlwg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vforunpp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlubatrh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpkzrov.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zovggidp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrivbhxe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzxwkfj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkzgnef.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwafkgk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwkysds.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhdzvzs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcnqvul.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2prvsnsgm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeztdde.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhneyqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgukzgk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2avpqyucw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eebonllx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmemrps.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdprmey.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wheulqii.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2avltoeki.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2latxiapu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxejvggg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyethzu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzktliw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxajtxl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeidqsz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvicvvqh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyjvtdb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kysfsmsw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhatwcl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpqtqdj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfqngch.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iuevfglj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvkzcqd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhzimza.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oidzsupf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2emllgpim.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nccjyiod.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2caxzwrah.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gkroxqgj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2burnwntv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvotbhc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaklwxq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpafdje.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpepjhe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oovaaxkj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrucapr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrqldmp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxszawf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrifvvnv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkzdjby.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zscpvxdg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjnxwnz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqyfzsp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nffzojzx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xumyhpku.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2locfpbpf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kaccecfu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fimoldrj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2avuycjln.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvyjvlz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jodxswon.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2clwgnfvr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvufuao.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aomzppng.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjktvcz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ucijisxa.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcncdmn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpgiccy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdiymdb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpficuty.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tquuyoew.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sojbnyfq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnzjgbs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiytrrw.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rvffmtjk.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2clzxunxc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxxqjhl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ragswjtm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcyiekc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciykkmpu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgcwcyl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfwbekw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mqufgwat.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgjzqpv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2udfphizb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2twzotoxg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jufyixpt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwspwenv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvoetzb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2msqccdoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eppqkvem.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tudzcfai.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvqjui.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwyikro.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhamhzvz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcvbsno.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgxtgoo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvonhhxa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lssdbnfj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hetaskmy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2socrzrbw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxgfjkm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhpmzfi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2squnulhj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvabtbp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phshhmef.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xivxuhnc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wckgckws.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2poltujpm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbzvisj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2slgmjrfl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2szmfldbl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdoihsg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2umoqdypc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kudnzxjk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hllebtpy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhopepxv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbslijv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnigxen.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vnozycip.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccezfuxe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlhuejl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfvaxet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfayonk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vglunynq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlgceex.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofivkfvq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhfpbak.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nioralwl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zsybzoef.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnzljln.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rapetzvg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnviyxso.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaxqroj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dibcnkfi.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2befzpkln.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqzsysf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2garjrylt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmnvnlm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrtwucz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxblvzu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zczmblqx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhdwjay.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aecoxhnq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2enkmzceq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nfskpsnr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnyuwwd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtliqmo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aqutzrdv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfumkvln.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmoqbjr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwtdple.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwyeoyi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oaknqpii.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxvumdj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuuknsh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxowauwd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zouqknlo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2papmepqi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkirttb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjxbmgh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeelpqgo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2iayntehc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yepvuict.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2imuenght.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jadqzrtz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpehnwes.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mberufsh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsekhnk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2axedhjse.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxkvgoc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mehubokp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2epdixtfj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acbmtejf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrywzdr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfswkua.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwrqeb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xanzhdcs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxolytda.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhkvvoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgurbupo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2valhddrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taqpzhhd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvydrii.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ranxqbao.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gfquaxhw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtqlsor.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtypfkxf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2chlaxwxb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2emavthsk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuzlyzo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjcfwlo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2drzlwfqs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyljzbdp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhnfcxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jgedkdwr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtvbeus.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pchawsvt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aiclzoyf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlguspvn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxtwbmq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhhzrjq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdcglcp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrzmpkc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcxdcgd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnavemtc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqqpfsl.html


<!-- 参考信息 -->