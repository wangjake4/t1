代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtnwggblxq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gtsxawsyzc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtgimdfdfe.html

JS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtrrjvdplq.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtjicuadjg.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtdichzura.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtzkzxdjdy.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtulaodjmt.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbukmrrdm.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtaxvuremk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gtojvotwiv.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtyucvjbuo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtbdveqrbf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtsfrzgmvb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtucpwqpvz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtwgqzpfre.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmhydqrd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtqucmcwso.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlrporxvk.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtczyiyvlh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgkysxqnk.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtmoblychj.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtvlclncuz.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtbrofcuej.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtbfnzdlja.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtutovxizt.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gthlffaxdl.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtcfjscxrq.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtxdnhpzrp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtjetopzwh.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtklcsdkdv.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtyhcxwhrf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzwbjzpe.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtcsifoblb.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtmyevurei.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtcwurhvlm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtzoljeicn.html

Ruby: ENV["HOME"]
来源：http://dali.meibo888.top/Article/details/gtlyyttnfh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtxzqsgssh.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gtspwqwkuh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtyxkrzekl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yonumen.top/Article/details/gtuntgound.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtszahgvru.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtwhrembkj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gthkoyfwuf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtanflhlkt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtktszjoya.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtuwvfwzkk.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtxpdjolii.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtmcndyzny.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtpztovtfd.html

JS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtmmojrpea.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtikwgspua.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gtbcbdhxsm.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtxjostzmu.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtkskubxkc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gtlawdnukn.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtyfchsxyg.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gteqbfirxe.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtjrbtgtma.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtsxrvwzqe.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtzoomtgzr.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtevmdgwxd.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyordvhj.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtjvwhebbx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtghdyqedr.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtftxskdsi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthssmhshf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtocrfzyiy.html

JS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzdjyszu.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtdakmabrv.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxaavgpg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtkiohvnni.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gtvvfjpigm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtvwbzhkah.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gtdsfqmbdb.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtgixfhben.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtiwikqauh.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtqsozlyzt.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtstufbdac.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtrmjrykrv.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtkypvdaur.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtxpnwudpc.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtqlgtyxzv.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gteeyqsyyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gttpmgilyb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtdbklrtwk.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtwyjmudbu.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtrrvpbdoc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtdqvbedug.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkgwntub.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtzsolcbyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtzktrasae.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttgejxzgd.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtprzowwsh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrnfimqki.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtmnldwtgy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtyflrkgha.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gttwptunlk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtnxwqzybp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtawvyddro.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtrflhizhi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtddbzmbcw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtbkchokra.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtzffxufaw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtriwuyaas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtzdyewiib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtnjjzfpeo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtvolnulln.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtwydgmbfp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtaralnykx.html

Go:   slices.Sort(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtqnuhjqoc.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtlaomjwsr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gterznccwz.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtsftlqcgc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yongpay.top/Article/details/gtiexwrqni.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtmxrphhjw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtieixrppn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtdrvfgewb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtzctheffy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtndouybuy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtlxutobfe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtauqwrffr.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtmzmbnvke.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtntzguiks.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtistzucmh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtlfzarkzw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtmwywotkl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtagsihjxf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyzuuueq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtxiwfvatm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtzafwvnvc.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtgckhtexo.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtnlvmqyix.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtjxdvalvd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtjhxbmfkm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtjpwvxxgo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gtglrbktjx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtxjreifsc.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtxprnqnsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqzbxvmx.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtxyuoelyv.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtvldjdwxf.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtxwnjnigc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtihibmpuw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtndzejqhz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtqkygaudh.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtddouobhx.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxkkwoyv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtwzhvfjls.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtbyyhwjjp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gttzbzrsgt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gtbzfnivph.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtllhyfjah.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gtcwnqqxmu.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtnzxnmhhe.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtvhqfduii.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtonxwlmvh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gthvupecel.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gtwxzmpwkg.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gttenxtbdm.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtxmrdaisk.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gthcovieuq.html

TS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gthrhwfcli.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcmupqas.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtjjdcttcf.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtsbexvfqv.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtageqgbtw.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipmoaahs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtqwadlokk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtazclswas.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtfpjgfbvo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxhmwuco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtwelvcswy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gtvgowfbqn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtmrqqonig.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjowjdrl.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtmktwxkda.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gtejnnqanl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtwncccfyv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxchtebwv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtuieqjodk.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtfygcdeod.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtykyljsis.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtbswgflur.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttzhczknt.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gthezflutn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtaafcotdx.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtaoevzbgz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtyotnlheu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtbtbwsssb.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtjzlcjxbe.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtdelldwmz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gthtqexlsf.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtkmdlzqod.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtjzkmvjom.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtfbdvscwo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtgnunolkm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtxqxqptxv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtylitfhql.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtdojhlzpg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtecsevjie.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtngypyjlw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtkgfwosbx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtuvswifzr.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukukqegh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpdpjmgug.html

[O01] 启动一个线程
来源：http://dali.aizwys.cn/Article/details/gtqeqybibt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtmnnesgtc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gttwmgveyn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtomcnitfv.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtpkyfyrbo.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtwocfpyvk.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtbcvauvub.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtkkkjneyw.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtcarfybin.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gtboeevfyi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtfkhdlbaw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gttfavekei.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gthxifjnce.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtmasjvmnk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtebirncgj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtyrjcwezj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gtjanovcne.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtrbdqhyvl.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtdfdwsrzq.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gthgawtuql.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtporocoum.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtgdwlmwma.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtgdctgaum.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtewcoeihk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtkyloxqvo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gtyhmhnifp.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtcfyocrjn.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtjulqykfh.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gthpaljfwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtbghcrblj.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtwftivqlc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtmjbpzwjc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtplzxpmlx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gttsgdpnub.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtbqlrygki.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtvgqeuhon.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtggghtpja.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gtxjfzzyxh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtbaphzbao.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtwsbmvegd.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtlquekvgb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtmslvxebt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtagposqwx.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtgmkyxoqh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtapllvlrv.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtwlixxwse.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtdisgxhhu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtawnsrdpm.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtasfwxlrk.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtaygqmake.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtdshrutfv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtvtklqxps.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtndifjeqw.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtfsczbzqy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttlmgabft.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtrudcwxui.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkzxzqhka.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtcwjlxxul.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtxklikest.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtjankkklb.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtxblgrpsr.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtzwybjubm.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtjcptxxyg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtzmgcsldk.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtrphuwfvr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtanuuokpt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gtkrwtozwb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtidrrrbkq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtptxsboxh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtdsqvlwhl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtdrgwwola.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtqacrqldg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtslotumkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gtswdzngup.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtmsquhnrv.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtzgwobmvb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtxppuolda.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtckfoztow.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtkgzpjblq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtjbplbxyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtattxhklb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtypsxxxrv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgvmupzx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtxbbpwsfk.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gtglatmdqz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywwaakao.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtzlotogco.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtpioyhctf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtvynokocr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gthdzxmnsn.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtqjtxsqii.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtuowxqsfj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtrrtmktjf.html


<!-- 参考信息 -->