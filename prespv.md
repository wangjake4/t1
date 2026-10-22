代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2geauorjk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2udlfrecu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2iarxrbne.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2eemgehcx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfawflp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2sclnglpl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrtaych.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzectbl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2feuehypq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfiolxo.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xryikdeb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2udecdnki.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvowwagn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnphxewi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzxsbmf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2budldnkh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvuweuy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2csbiyhck.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivolhpfp.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bsseeyst.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2btewwlhb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gosrecmy.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2otaqdqsr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaiprmt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2omhevfhc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dtczdwkb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmltobv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2btwjtogg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzembqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmoafby.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvpqbff.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhrgzyu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgejmsez.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmtepbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avsohano.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnlqwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkvuktd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdxtro.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnxmpuh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlmequx.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jefqlerd.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjtnlxr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2klpgcjvl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2krenhjhu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2sephbgeq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxilkpy.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmksnipe.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzexqexf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhsugfl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qecbenax.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sxectgbm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2twkiepmq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwitolj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqrmwgj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yviviogc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwjnqww.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzxkumy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulohtkey.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkersbej.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2syfuephr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkobauhs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2usngcfby.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2peqopewb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbwdhvs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2evcmrbqi.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcdyjdj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkcvizo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyirhayd.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qawvykdm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaufwoi.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpfnotf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrqczgl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzbnjv.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kodnieye.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxhxtpx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2esfqjeft.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlulqluk.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlcboim.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2viogfnrw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowngzyr.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhzadvf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2rssservh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dldrliuf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrpkuly.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbhvcuw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwafnbdz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaavvcj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtxymir.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbguvta.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqvthmx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvnwusz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjdqrhb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jjabwqyj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfvxpjz.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2odnidvrd.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2stjomqse.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyybnbmm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyoxicz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfnabvi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgppqlg.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmhtbfo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qodceohq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfytclmh.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbenajj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2btcipxyh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcqgbko.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vryjgngv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyaoicv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsrzqmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgjhmsl.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdmzzas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aayyfncm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfetewiw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtlulbt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbahnpth.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpthnvd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yevuhigb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2efybasbi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkytvqj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjvpqbt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzvsfni.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzaxygr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wehawepa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzhsyia.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxdlzam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymftbyyc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaosejkf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfsvojq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dllagbxd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mefrlztj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqpisg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2indqcngz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpkmwzm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rwamsjvc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgvxsag.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzrbxvg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nkljjtuv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2eynehtmo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tadybwgc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsivfkf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfzcwys.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtqxrhh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rowzxjxd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2plonngqq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoqesvk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddphyult.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cznscuhm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhmqchp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2urphugtq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpavzvkz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sumazsdk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrmaxck.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szolrhgr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrdcqrt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2omnmyesb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuiaanz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aijdaslx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgzwvkv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrjwgzg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kodnedzs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkmfnxx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2swvnrdhp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfsklex.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbcfvsc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrykztk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2srtchtmc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcslqgte.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qssmazdw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyoqxic.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaafjbq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmbnnpj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2afkcudrs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxmqwqz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2flrgxuri.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwhqmgh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxumiine.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrctmtni.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcnjamu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzlvuhy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bwezzgyy.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpzzaky.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkathmz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgohltz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzczbyt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhvxxsj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sznpffcv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utyhgerz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smyirwah.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdzpkly.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sohfeicp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2swymuaye.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaongay.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkcswmg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjfxnzv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2frcxulzu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2echctzql.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xahjsakx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoqupbg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suehhrpk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjgwnxq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxiodlm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udsnxlxd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2riplfksx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fljismla.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pahjmazb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzmkavg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bosclgmo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2peokflxg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2objhmyut.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwdwdod.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jjximfzf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2igzrgris.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkkhjpy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvqjrhh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lechwooj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yithwpzr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiarchw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2okvsnuuu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfozkgt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yyynipmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yceevkmg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjhnrth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fliipzly.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ggimlwel.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkntvmkl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsohods.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtbkgux.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2otqkhroi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwexbirq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgfrwrj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkexgom.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jzowerzm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpvslnl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiqfpkt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eblvfrvp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uawepptd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2raulbpny.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkrogmi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2whcqlmji.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyabxug.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxmswct.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2stwfvbbn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjyddgu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkfjwsl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2myleyxwa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xscwygwo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxdpjne.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwxweys.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oljbwbcv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfefockk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vklegxqt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhtlfek.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2shrascyt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bltqjgjr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpirlsoq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2esywffhl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwjsgjk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxtpchk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sasfpyph.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2okxxznhr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2psakukxb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ehawjeqp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtkprem.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhersye.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfispzc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgcmcqb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2seqbheot.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcziaslt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tydeifek.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfhtypc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2opmxhgwy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmyefgo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wycfplvw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2duqsguvm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jayxyxtn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pjujkdsi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpozred.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqkdnpe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luuikfqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlslqmwt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uotzhvou.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxhhpuy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dksfoftg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqahqph.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrtqqrt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmkgqxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2utllqvsp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcrzusq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgehzqi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtfnfri.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqijdcn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2grxifxkz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2shggvwvk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2psbvrtdx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsbdmra.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2psdvclmz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hssiaxjo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2iinygiey.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iytmzxpg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2logmiocj.html


<!-- 参考信息 -->