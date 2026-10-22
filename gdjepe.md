代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnhojtr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzprtfmi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrksfabl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdhgjio.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrsrhex.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2juwpmubt.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2etlrgfpi.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tekvdhjw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2finrlait.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dvchiucp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjxzaai.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2sziprzyp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqsmpgs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bofnlqsk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaxtssi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpsrhwa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2walgpvkw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvowgpoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzpyfhb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyneszb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqayzkgy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2llcocqlz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2azouznjf.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckycwvzl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxugjwrb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxugnyj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtjkqgi.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbcaonl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhagiqb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntntarxo.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyrnowl.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrpkeux.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvamlgte.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoxbrfy.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhxpcmy.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2stunliba.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxtlrbn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ioauwcrs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2drfqwdna.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoyorha.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganzzeeh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qocgonlh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfthapi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdzbbjs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvluuzr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgnqxkp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzhtjrm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zedbzhbm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fctcqnin.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkkpdhh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2tvumsaev.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zltwrmks.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2slwyuebl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2aokewjuk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrbrgsd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxhxozw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2aybiaimr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnditse.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfloxlm.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2swmdihlg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcihmqm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvwdihc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2inlgjwua.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzfqfov.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2avwgczgz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgcwlxx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bouubpvi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyplfun.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqpgjob.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wskefpdf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtxqhtf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbhasop.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnavkmd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcohbso.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpttfrou.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxdlxbf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kosngukf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhtmuko.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qapsziha.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2samknnkw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabuloca.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlobdrgc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jxevdquj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zimdhrdr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oijwpvml.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2textgaea.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmjsktr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxkogng.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcbondk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzizuyp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbugbbkv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrdidsn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmvigis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2selupzqd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnfvupf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzsnyxv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ephtibpn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqhbwvv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2prufnwtq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wodcnyuu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ittuhaqk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2awoovsec.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlasvov.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoqutia.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrbdssh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqpwupm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdurrns.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2smvcvodd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvgqtvy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwmjxsd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgaobju.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwblxal.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzryxlg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrmisv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlkrbmo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zebcgwrn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vqopscpw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnxegcw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jktevtvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdaklwh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfloadm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlnegvz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lklvqsgl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2juncqirw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbdxkix.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhfqxir.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgbcefw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxiezzr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vamlyxvl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2izkjjkik.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjspcpi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwrwoc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoadzbu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2juejceoy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcvltug.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvqltqt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmblyun.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zaldfsge.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjxjggj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2btybcrkr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2putmsmol.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdfzoua.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gomjygmf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bntjaosl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjseusf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhobnkh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcuksxf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwtfbfo.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjdctct.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgukggq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aysbqytr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiywcbk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zenlnjvf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvhdwjc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2iescgwuz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhfzjbl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vetqwrzp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bgumddxg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrbwsnd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwabjyv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgudefy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwuwapq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mjardusg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vigackqu.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsyaraq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ditzfizx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mgirhcbm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjdmyoa.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yuevexnu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlydono.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jueobmzj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwukzgi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2goxnezqb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ablbdaht.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2smxthlwo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dplbwtjr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrbvkcn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvedmdw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2flqbshyn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznatbzd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybisjsfx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tenohfcx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqgtgr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gteoimgd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmlaymy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmguapbh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqtejjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sysgxcbc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qetnfwws.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dijmvltg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvhhetw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2migreums.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wywzlslf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqkkjqb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bgconrnp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gahzqaeq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyhctku.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2upmjeesh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpwawje.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrdedds.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmhylsv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvznrcw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfpjvsu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gflrideg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbruormv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxqiyvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2domtaasv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxhtqfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2coanqyzj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbtrppq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2pewpkmij.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsdgguz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2shhonjzs.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhpdef.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawlruaf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvfmcb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wguunkrf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2snaqwgro.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qojoesqk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eobwbxaj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcgyurz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhasycl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdwoezt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbjyppy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaslnpi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwpamwp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvmnhvq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2njapljpa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyrwhcb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vegprsvt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvarndpp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2privupsw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfkkhvy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llzchnju.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mxravqqd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvorhnxc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vtphceci.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crcpslke.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhegokgj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzjkfrj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2unyozipb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiycpwf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2youezxry.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvxcmav.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfwudpc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xknmgcua.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vicmzert.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyarwhj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qecfagow.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdagfeez.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tadqezyo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2upbecalh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2etzdkegp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kekrysru.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnsgtzp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkxwmbc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxlzkwe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2docrkuzf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fivnsjwl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmwmiyy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tddmkcho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scmprkbg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmomphqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeozwkc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyfgddq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfypukz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnjfvak.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sacvhimw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmjjttd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzytjbei.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2artpuoqk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iuahuiwk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2alzlalvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlshvdm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmweryrw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfddswsc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wiclfqzw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2woqadlzf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bilcxspi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvmgatt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2huldtfos.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2itgegrcp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvehzslq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpnicun.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxphnxfy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxubaei.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzfphcp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2akfahbcc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2obotlpaz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdrrag.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2epglxmym.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vnobsdnr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2boyfejsd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwobwqum.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmstayu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkreraj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjmimkh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmavaqs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxfujqt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2catauoai.html


<!-- 参考信息 -->