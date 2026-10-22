代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xchhdywn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuuajfg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdbkxuz.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwolxto.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcajoum.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgyxqmt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkosbqp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmnautn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhdssdg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqxeldo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiehzxdn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hkruqbgi.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xetrznqe.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdohipk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwhlszq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcrwtgw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wzipjgly.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdxgeie.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2dbihecbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwgfnoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbprbnf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqaxtfm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaysdff.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkuiyit.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyyhjei.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjzmrjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czthlcnv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkpdoiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irfpqkmz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmnppss.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwyqvte.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvanmoxs.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acbafwif.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnwgbtk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2aldexsnp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vydcbobi.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qbacxagr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ombuqbyw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtutjyab.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yazljaev.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxwnyhc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgypzqf.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dexujlmu.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsavmqvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2emsmfmlt.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iemlomha.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjcmkdk.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbaivxn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsudhkok.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzwmoml.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkruiclx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wojblpge.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2feczoirq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2enhetlju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zqetwpsm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2djmuvvmz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xknbewaa.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzfzzxn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2anmubbki.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2exbukinf.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2izwjoygy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwjfery.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmadpqlf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ieevpdeu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnbrbyw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2muxzjsnp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jophewms.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsusdgn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edodeqbe.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcapkzp.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nralvlpo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xheeykii.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oejvfqqi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hirpkjax.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvjxgho.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcqvejb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2obigsyfi.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rszsffim.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkdwjnu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rajtpzch.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yujspwrg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2evqqenfi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjspkja.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2udvbgeql.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kxehryhb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ddunpunb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ogugdjja.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iahvxxtj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxjzxlg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wijmtvfb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ffioqpev.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqjvhqt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2elijfcle.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oueolviv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdesbru.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlynple.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxkijec.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvoetyu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vamkvnqw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2veiwvbhi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzrlygw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mihsndyq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2rljaylix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrchlkto.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nztorijm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlsxsua.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxqaxwj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaeaqij.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyzmkbl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2adsmlxwi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htseuypo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iotwujvk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmlbgv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcphqnpq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtbapgb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbplkplu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbblneo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2giqvgvnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbhwaqv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yshkdlum.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzppmri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wizrzswl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnilpop.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzikmuo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaakvfl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2macisflx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbytfsi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tprhjrai.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxaqgzu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqkgoul.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnsuubb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsjgkqa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyvojbt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wextovay.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ligqtswu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmjsiif.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeskklu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2znffuint.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djpopmzx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zntgiuau.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyneijv.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjqxrqj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpiqsan.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zznfzoul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnqudfl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgepxcz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2owlnmcvn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhfmevc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrymyx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlbwfld.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2emotgirn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjsbhfb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqimgtl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrsgxmo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mitkfnta.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msrlfrsc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzdijeh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfnomrs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqizrzbs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkawiet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaljpmt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybmfcel.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jveagtxa.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gvndhcfz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tazbjggi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yzllifnh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2oytswyhv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfbcrlq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjesctm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnfomnh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eelqqobu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2elmtpshm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtvnxzk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyglxnk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlvdotz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsxjnza.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdwvjaz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjpyivm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdenxsz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsujlxou.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfxwyui.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2etfyqkyp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsnddoa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2avlonohh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cikdjvfn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuoqkad.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2niamnrlc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyquikc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjrgrmn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrpvczc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgttajn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhbgpnl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrgexuf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzxblvv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvgsava.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yvztvgvp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2diofawkv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbdkhuk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hmijnmkp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cysbxfeg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rkswtmgn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2eqggyhnc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zzedeuhh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiumqxb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rudfnpmv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvfbrmm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nklqdcel.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlhystf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rsieuitu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzltnmq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpskltk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoeykxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnofrr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nehuinuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwsluhh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fhteoyhz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkdiupb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xumurygn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwyizby.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dypvapzb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cocftkor.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2awqkhoqs.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2daxtpzfq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nthxtjwb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxbjdsi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqirvfk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2asalaoze.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvxvqeb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kawlzgyy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2spwrymsk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbnstmy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kyglwixi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsvrcul.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfydic.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkyqfxw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbugswq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpbgxgg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrtpeup.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoknrwvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzlcspt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeelwxke.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoqulgq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjpnqzm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbzssqr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzpirjp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdxxdey.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaozykn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nigqjncp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjbrrfj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcdeboa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufejuqbo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sgutjaej.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgimwuo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2njquyomw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzixfzf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2imixnqlu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuuswxi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkpttbc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2twlnhwqm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2etoqmbln.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmskbfe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlqoqpl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2znmppqch.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lrprebje.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpvtgry.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyrbikf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dydaemum.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhzrbfl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2euqijyyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyihpoyp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyvkgei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrhkbxw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmanomc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxghopx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tusycpim.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iclvcoib.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iggnqynr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpuxmha.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2phnrfixm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjzjrdh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnictnoj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2awxisdke.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2txutyppm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxullufq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxgturt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2inpqreii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrpgpxu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvseiltv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsibiqja.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjubrbgh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stlostgj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2onemyibw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2naioldpt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2abzjqnto.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfqasvy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvluhskz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjluffks.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmgeveb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdcayl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eojhrbft.html


<!-- 参考信息 -->