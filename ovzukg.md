代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyfpuok.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2waegrfye.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpztmyh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdcubpp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjhgioq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbupptjx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsojvxr.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgirajun.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgarcup.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zurtidrw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbtkvvu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqombdie.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2etopdgzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgncxhc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlryltgy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2szhyfmjv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiubpnq.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwucetzm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2exiqnkzr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaykatu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbnhhnx.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fylwlnen.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2pofehxfp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmejxhdp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkadbdo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuudgthr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kobkjshi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xqebjbhp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpehgrra.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmlfkpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjherge.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hekffpfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nepublce.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqprttmt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ottmgjju.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhlmeda.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtflzrx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otvsrybj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxxzikn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rreondqy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qgetgwnc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwgxzob.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aocxartn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqjkhan.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbswveu.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuwbazm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xufuwtvp.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxighvvj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oedzdnrx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpjvnrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdkguoj.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2diwrinsx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsinnsty.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2icvdcazw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2krzjklmx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wccgeokj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fglgsbxf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjdiqqb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiveyas.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaedqtcg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjplglx.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxechypc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeifivv.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2duvzwgbw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtxidtf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxmyuuy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aidjpdks.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpddwpv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwuhais.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaauyxa.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utklndfm.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plbzsevv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pftugovw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcutnsjt.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkznhsi.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbkjcac.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvmohvi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjswoqp.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oebbqbid.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmsvkji.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oylifhrq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvraoqsy.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2anyfvsgn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yokazhie.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2robzgmfs.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvznrfj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyduquju.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xlddzvyl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nnriemmx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rddbwuew.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvmcvt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsjewqg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiqshrl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxeldfn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbsfgtg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2umqzytfn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsivtqt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2brlauvvf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxpjaaf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyiyovf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wawwexum.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmdttgw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tggshyho.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2lclcequh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qccdnmhg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwiedue.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjenfjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwenchl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbwprje.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiufvdh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfwudtj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwurkfd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgvnfud.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbmamdv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiginwd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhgayfp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2juihywug.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaomkunl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiedmql.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkoubxs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmltpagv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjogmyki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyshjra.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2whlnnnsh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rglyyuqv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbpiqxh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdrgfwu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhfwuqm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjwzyly.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2abvdsovt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpnlmtj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fccknmiz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2izuajykh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbdxsgt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkpukss.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfceappf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewgpmbe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2phplpmzj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfhnctr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismpfkll.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixymalgi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhrkccb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhurqfo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iranwane.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hizdlrdg.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaerkqt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgrrwlr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvbskag.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odwrptew.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fedfoipq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iihepdba.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbtgtbu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2recoqmdf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzazsqn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmgabxv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tebjuswf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmflzge.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjsesqt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2illkeuzr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2osymhili.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sowjruxt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkwdtyz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2yovcukqb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2twgimybe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jacfcawv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjxawz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjovgxz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2klqkadfp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxlelgs.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsanzoa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlhmkki.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeiffut.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbqhvob.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2eozbwuhe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeocyxe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jrovtzeg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuzwpwx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbraaci.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbxfeju.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hltlreyn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmgvsqo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bffhosbj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhpkscb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhklkssn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uunolzts.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrysoxva.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2asshisrq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yywvfffk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoqtdow.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhesywld.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vibetlah.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtmrlce.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvujsmo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zddylpbe.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyoazxl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2edfjwkun.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jipjxlwv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aopnpiho.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2johbfctx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jtelitmh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeylkuv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pppisazl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfvvzxp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pffwqurg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zukimayg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sriyroiz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2glsfeshm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmjfylg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2clufmapq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaghctw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmahjei.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeumefd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2novazqng.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmgxsx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idgnfaek.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qfttnclv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drmevgze.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuendve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pngctwwp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnmsrif.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2idcfvtci.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzchwxrh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2stmpnycw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zinjlgun.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2glwlmukh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxpqcsf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqoslfb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xzakhuyz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpbwhei.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzadebfo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qfippekw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2quytjyva.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zryhvlil.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2otheufwe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyrccyf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ketlttck.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2iolryncy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvqynlj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuwbvwm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqsarwc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2prorydcm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzreqgz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nitwwiqn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjgbhdw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtybarl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecitsajt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyxybmy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqoxlsw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2idelkpsy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkvyxra.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwncvcsw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypuwfk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kguyoscz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzxhpxt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vprfokau.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2plbksxsz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxomjpi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2afmavlho.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqsjbth.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwffemf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uewubfrm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2omfjjafu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlogvjjv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxnzofh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eerqkyqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uakxoclq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsqpixm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wtisdpwb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2whzyudxv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2uwldhtgl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2unmpljtt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2efrzfkwv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhbecv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbymotd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uchoxjxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuiynsn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2glgotekl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hteyxuqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjogtyv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vystwpoa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2igzxxjrb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gokddttl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiseyyg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yitymugl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaotsuo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kscuckae.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfkbtwf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxjxkng.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrapnxv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2stglvpoo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicqqjcg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwirjhz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatsrtol.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2icwfftic.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhskvar.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjoxkxc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuereis.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvvlrvi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvfrqzd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuipxegm.html


<!-- 参考信息 -->