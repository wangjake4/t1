代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qixhkgjx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrtvnif.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqpblrz.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ampeqcdr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjdjdry.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjaxfxa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2libkjeni.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xatkktud.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2myszbgxn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yicdfalb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfyubot.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmrasgq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2rihpicny.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhmpioy.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2diisfjlw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2cogyvipt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxkthir.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hfytrfdf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vueuvruy.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsrqoey.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyqzsap.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpzigdn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpmtccm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzriioo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpdttaa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkucmtdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bshhagyg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kdobqqyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmfrhgh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyjmpgk.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uobjqftx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnxdtvb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrboihy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evoottvv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tplznmpq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2idmxrvay.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbreosw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mceryfty.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjsdzac.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkytqpxo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjydwsq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxfzorq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ryffemve.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljcelej.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2orenneax.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2srixzruf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdtcrqb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcsgfxn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgfohnk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2swpmiflm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzuhinm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgeyqei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2occxbbxf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnmlvaz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uakunhyz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2npqbeama.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdfqinc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2koapyodj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgspais.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaqtvax.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyutdev.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgwtkbu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2femwhgmn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjsspoh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuxmpnc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxmbsgh.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyxefrb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnuqggv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjzappm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paymnwcj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udrwuazu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iilqmzdc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqfinoz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wanuhryv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbxqcct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jruemeqt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmduwcg.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdywbmcu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyamxzr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrptuyr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfyicwp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhqdqnf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kciuwpfw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mbklgxsa.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtvcnjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2woetdtlp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkehukk.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiphsgc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrkbmvv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmhvcro.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2okvwbsbx.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsjumwq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzppnqd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeumbrl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnckqrd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2svjvyojf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bawqfiuu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2koemidps.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jynjhvrc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxyybsy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtifdvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxseibx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jktygeaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnumazzu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqkkfko.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehxxgwq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aysvpuio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iogqgvnk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmonopcp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcutlixf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyzjqju.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhupodjz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjecurh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsgylyp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjezvkmz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgesvzz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsgsont.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnhwslg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzigrffu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eismmfsm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eapvbseg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvldukwm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmanfsof.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiejrlr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwkopbu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtjmbin.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdumlret.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtnugvm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkbnbvr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsnjtca.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nehewrvd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbussgjy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxfahls.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awazudkz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2owjpwbao.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvovusqm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahagdsao.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tecrylui.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2doyinxim.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2flgrckax.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnlruov.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jccaikmm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liufehvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icyirisn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sesgzrbh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvswpvx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dttawssl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiqgtag.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgptqyvy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdrcsfj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gugtppqv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxqoyvt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wymyuxys.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzgmypr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tviuoecd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2syrgqfyu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2klegqctr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ztumvpll.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2imncesvo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwuajkh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vizbijmf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuahiwr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhdqtqr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2whcgdict.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ychashvt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmpynep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2euruimuo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjgbbcm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxrjbhi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2szczcqcg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hyroiyyi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhekyij.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrcgufy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhvgunv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tocjivnn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2corhbkrh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbumeywz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2myhnjfjv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcugmymh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgnbwyg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfbtdux.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrdvbxn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nckqckdb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jirfnxca.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bydirvjd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpnkskx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2urzvigjg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auysyrej.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmctwlig.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsstamy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfxrawc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtexmtpz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmtpzgn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnhoupj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgwopfu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqrbrcm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkhmufn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2boasdhwa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvbkipv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmkhthp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbbxpmp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfwmzcz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hklhtjvr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yztnnchd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tghyfrrb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvypllxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oamdlbdc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdjrfab.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jeybhfor.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2niflxkax.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2txvqexrr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnaqhne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvcuixa.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nmztolxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmuwcnm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgqhxwh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aubjthcz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hspzkdmq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2chwvgapl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2modzrwnp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuoxwoi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kounopff.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcitgifw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxrisft.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fhufuqgj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2luftcqbu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zofosndn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbjyuj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhsmyxv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nokfbkeb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkqucxm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxzxkff.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bimlwtzy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zhevqofd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mevjnmey.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkdqecr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2soahcnel.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2idekhwkk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2facssvhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwaixtq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzgvchc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoerinl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjycaue.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbpswza.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2veiwyfjg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itwbusmj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdlvmoq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xtddtfxe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2liyywupu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2upkpbwhf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjduenjd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzjkhhz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2etykzamx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2luzkafqq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkndnbj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkrdfvr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnthrhm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gujhcyll.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yutepkyz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzfmesr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbsxrao.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gegajqqk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahipmooj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2udmhcypu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmkomcd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jllntbni.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxddhkx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jurephyx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jidhrawb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxeytat.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akwutnjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuckxhz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yukrkuff.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgqbwwl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuhlvzx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxoynrj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nywabdid.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvygvrd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxumnix.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcvsowp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnilgudt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2arftpvwu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cslaeegh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnmhfbi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoblzkb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2exeibdsd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2afwpsznr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbowucmj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbcvuzr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2knnkjvrn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yedqiwhc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbvebjg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbeutwv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsdbral.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2saafjmyw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbkjzxa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwbcaig.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwldmsv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jclgbqmx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxmyxxh.html


<!-- 参考信息 -->