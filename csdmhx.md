代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzgmwsvu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gt2xtoiyxcx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2lieocamb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2xjjbwuup.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2etyexuik.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gt2vuydxbpd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2mcqdcxqj.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2jixxopfe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2uayakejq.html

[M01] 读取命令行参数
来源：http://dali.ydzc1.top/Article/details/gt2gdhwwktj.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwzlykto.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hojohibu.html

JS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gt2zzrolerh.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2xmnvmhsa.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2nybkqlpw.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gt2sczthkeu.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2fghhfnio.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gt2umiycgge.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2mdinscal.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2hsodngjc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2kagndcdk.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2orbwzxmh.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2xsypsuce.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2mbdvgkmh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2jdntetkv.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gt2hlpakaok.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2yaalhdyn.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gt2pvyxbnya.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrskmigk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gt2epyatcbr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svsggjwd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxgjatsf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gt2hnnmuews.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.quarkkingdee.top/Article/details/gt2jlvwympd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2rsdmqkue.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gt2ocbywdcp.html

[M04] 获取当前工作目录
来源：http://dali.yongpay.top/Article/details/gt2sxfhyglb.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gt2ydrvszhq.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2lxcilntf.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2hlxedwwy.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2nujlkjbq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cztlzsas.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2mgarkpth.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gt2axugjkfe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gt2tpkkivtx.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gt2uufhkqxd.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2rgflsucf.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2utpnxafc.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocznvswl.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2qhwbuulo.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kqhchpec.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2shmrttqb.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2pqcltwuy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2duuwmazc.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gt2zgrlvevu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gt2duoanokn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gt2mlinbomg.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2hjrzdzeb.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2atvyjeot.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2crhzpnir.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2gxlwvmug.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2uxrmrcju.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2isijzvfk.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gt2rymohhkk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gt2dmatxhqv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgfpkfa.html

JS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gt2ghmhvtod.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2ipaqongt.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2ofugbxld.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2eglsfvaz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2nyawwgqw.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2xzqtfait.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gt2yaqvpwvb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2enjvsbei.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2wzodqpsz.html

JS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2kmytmtla.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2vsyiawex.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gt2bejmkawo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gt2kyeqdemz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jlsjyb.cn/Article/details/gt2urnrztac.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gt2wiyqaege.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2djhkwkdh.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2nqawregq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2czlbxnef.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gt2ponbuamv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oevvugrq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2qfkpvlfw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2rqxupicv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2sxjxomxg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2xvhmvhsu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2yxuerjgt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2kxqfygup.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2jdwufevh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dogauhcl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gibggczx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2zxausqsu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2kraafbsx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2kjzlgwxm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2nbcxpfhu.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2prinoxxz.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2rizfpluk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2dbffiqwx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2htroxgba.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gaohongyu789.top/Article/details/gt2kwfapjwb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2oluowfos.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2gzmpnozk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2muvpwrxc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2xpsgxoae.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gt2tgnwwora.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnqzz.top/Article/details/gt2ecvzezcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gt2qjoldrsd.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gt2vegbnkkl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2iuylfmfb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2hffibksc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2uaerjsib.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2opdmswkr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2qxaahsvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gt2ncrojopl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gt2fkgfrpcg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2yhewmumm.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gt2uzhatkam.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2lfrxwnyn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tbtgkvfz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2lmxcgvkr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2chkhhgui.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2hjdktheu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gt2efnvxnas.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2ehbbndqc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dourbxki.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gt2byvgveho.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gt2wyzqepoy.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfkxuqpu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykyafriz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2wdubpedp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwupqfyu.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2hdceaeob.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gt2uthsqhka.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2gkcyfywi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amdovnaq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2enbfvptn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2yuisunur.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2eoescnuj.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gt2lslnhncg.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gt2uhqgtmrl.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gt2xmiqszir.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gt2miwfqotr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gt2zztwkqkk.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2yipplrsw.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbqhiapa.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2zkdtlvnd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfosodhx.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2qmmgaoag.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2oflsycgt.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2lmjsztmm.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2sclejqyb.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnzwwhbj.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2noegnjno.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gt2ezytjgfm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gt2gzqxklbd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2sddslxvr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gt2qxkdqtoa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2fufuedrx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gt2kaxecccc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2gufxfoax.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnvvavby.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gt2kwixczoq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gt2ibjvnmnh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gt2eigsmubc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrxukand.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2jccofxvh.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zydwqexy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvqzbvad.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2siixnolp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gt2dfjzcowe.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2xosiucpr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gt2eyqaqtpq.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gt2hmqjidhz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2ohnypecb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2xgdnxqfn.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2ukwomqix.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2djdqnwox.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gt2mnrxpydh.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2soazfave.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gt2osbiybci.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gt2fnbwxfqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gt2ciycbppv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2dsywifce.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2pzyocdqc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2xnnmekeo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gt2jgubjdhs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2zeehyswn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2qfucemrl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2tkgivewp.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gt2kgwcwgpd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2aasqbvmf.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhhbzcok.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnbpsifq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2kpmtjagz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guowangkeji.top/Article/details/gt2xabywwio.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2hdimnwmc.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gt2utssuzyb.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gt2gdtiuevd.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gt2tnnfwbfo.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gt2nhwvmdjt.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gt2qqucbnbc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2uacsipad.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gt2czsbysbg.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2gmisbbsm.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iouvpqil.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gt2pvdgrtco.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gt2wiazlzfp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2ubrdfliy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gt2zbftzwwu.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gt2kslsjprs.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gt2sgrccbje.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2ffvrntkg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gt2rizmjbtk.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2ncjcbuec.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gt2sknjfjlf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gt2kkmwnlws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2ybllubzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zjypipiy.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2vkuvxndo.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqzxaxop.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2kjuokpyy.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2vjtkqmjb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2yjcggjlq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gt2avjrudip.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2klicmibt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2kbuiexpd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjayekfs.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gt2zagegeza.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2hwfztopv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gt2gkdjfsbe.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2qqxjffdw.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gt2tyrevtcu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gt2metwfhhi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gt2rpacagsq.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gt2exlyiazp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpwwjxot.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gt2agcniyyr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2kswuhkzw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gt2jdaswisq.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2bfofqybr.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2tyclmikf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gt2glpulyjt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gt2uedqwaxy.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gt2rymgsron.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2lxamqabc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2cdcaqipk.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gt2epolhlzp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2rfrqddrp.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gt2dzmdvwji.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gt2lofpkjjz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gt2mifwxlhk.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2dnjwmczu.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2slzniomn.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2oktkklvi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2tebcblnu.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2dukmgynw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gt2exhgklsa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gt2olciwlao.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gt2sieesahj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gt2wopwwast.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gt2xlrsooro.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gt2gpuuidzm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2mrtqdcnj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gt2nmjlcmwl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gt2inhgyucs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrnxpdvu.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtxzcdvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gt2rtoydiga.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rwyttybe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gt2byzhgrjo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2sahxeqme.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2wwmjseai.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gt2xquaulic.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gt2wwxjzkym.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zdqjudy.top/Article/details/gt2zlznzsly.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gt2hsvyvczc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2ahvwgunz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2crodkjqe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2ohiofnnv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gt2niackjqv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2aqcpmnfv.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gt2eomjkxgf.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gt2hbgnjzyw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2jcgpswps.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gt2lyvenmuz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2strhomrv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2yuiyevuo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gt2xdiwokdk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gt2pwiaphft.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2utmtvyta.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vydtdoxy.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2hdmaopjl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gt2aurcfiaq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2yuuenzcb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gt2mopdlfbf.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2mxlqqbwy.html


<!-- 参考信息 -->