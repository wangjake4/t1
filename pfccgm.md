代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtwsknusea.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gthlnwzykv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtgrcrlmes.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gtbanlmeap.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvhxzjtcj.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtdbsmjggm.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gticpgupdx.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkogjsbtr.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtpvdnedok.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtwkpnjgnq.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtzysokprg.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtinoggwmk.html

Ruby: ARGV
来源：http://dali.jiagoushi.top/Article/details/gtcebfxuqr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtitztoqaw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtoslhrvtd.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtsuqtzqsf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtzipvgshg.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtamgbgprb.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtkfwgcuvo.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtntlqslgx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtrvgeocim.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtgztswxvr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtcyxfdlev.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtfcaifvyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zycfv.cn/Article/details/gtrndzhvcz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtmmrivodh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtbruwibie.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtihdizjjp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtsksbqqxz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtwyejzinp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgufenzy.top/Article/details/gtikyzsohh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtgonitzys.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtqnwyufrk.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtdsohcdqy.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfttzoyt.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtabowelwn.html

TS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtwbtmmwij.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtdgernarh.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtzltaabkc.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gttkygwltb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawydwlir.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtmkvabbpv.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtvtxgcyhu.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtbwhokvas.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtomvvcpmo.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtcpvtphkk.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtnnsixkbq.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtbkeuuazd.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtkzoxhxcl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtnnkhhzoe.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtvmzonmdv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtwfbyhhlx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtekqttwnt.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtjxccxyir.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtqamzhhfx.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gtrpsyfthm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtwzyhhdcg.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtgjjpfpvn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtbnzbjeel.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtdxjyfxqp.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtqptebaai.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtnnanpgsr.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtwtftdpzp.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtpfxcvwjl.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gtskavsycx.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtscpzliwo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtpyiaqyir.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gteoklrrni.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtjmjmkdnj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtarcbxxxh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtohmcqczy.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtaksswtaz.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gthtpomfgp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gtghekzroa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gtkasgduns.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gteyzafmor.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtfneeivhu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrgrubqyn.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtlhqduzew.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtytvqtwpg.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdqgxpor.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtjqsxhtce.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtcxxhgsoi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtuzuulpzz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtcfneaeal.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtrybfswnu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtsnqltgpy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtixnlxivz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtddexipth.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtrfonxzvz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtskzqnayt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtjcmzoxzp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtzhvmokcx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtksnzpdga.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtabxayvdl.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtvsoyfzcd.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gthhvhiarp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsevcnizl.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtxtlunqmm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtqaigpsib.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtgphqndjo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gthrpuwawj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtaymgjzmw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtxtnjpbpq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtolhrcqex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gtuemzqofy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtthogfbku.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtzjkyyakt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtvvcqemtq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtixvieqyd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtlgkndwzl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gthgwfssim.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gthvuhhtzo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtkkqqnkkn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmtoakkgc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtxbcjcuuo.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtiehfrudf.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtegbvqtvs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtzxebznvv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtaoepgkii.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtyrkmlihv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtuwojidwx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gtuxosxxot.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtcexvsvzn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gttgyajjxt.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxiaiawns.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtxbmsrfpm.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtiqobfgsu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtkdrgyqru.html

TS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtgskmqede.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gttqmscgzk.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtvxsotodt.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtlpeaikkf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtoxeaczcn.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gtigexwqpy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtryerdlbf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtgwuhcyjh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtpxfgsqwg.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtloillkxc.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtjnpyapdt.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtllknvnqj.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtfxahpudy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtsnimomsd.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtjtpaqrmv.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtfodayigb.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtxyfjvyaw.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtcfmdugyx.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtljzxebtn.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtjecdrkrs.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejcqwah.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlpnevlhe.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtkogvszuu.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqznjtkr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtklmqtcpl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtnabgtxtd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtkqekazuj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtwakaieve.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtbirmiczr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtpbgtpliu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtubizrjuk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtvemiwffv.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gtqriicoya.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtotqpgbno.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gturisvrls.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtjrrbfgxd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtmtygppcg.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtjgbkyonx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtlbslwuhk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtrbbcqajx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtwutcfarw.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtuvwlqhcb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gtmbbcmfuw.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gthzxdqcpr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtewyzeybj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtqwtxwxzv.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gttdtndrxl.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtruuxmkcx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gtjqopvehw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtopbxyvbr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtmawjrzur.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtzivbuvyo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtjnjtxgdx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtismzrkkb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtzswlqkbh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtgktkgggz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gtzjsntpqq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gthyuktvez.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtqjiyvgiq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gttxjsslmm.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtfpaurfbn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtkalaoteb.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gthcnjjffn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtvftiphqi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gthsxkcowb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gteloaiavt.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtxiqniwnw.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtybobfzdx.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gtarikzqxs.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gteurecigp.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtsdfyhskq.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtzrpcvgzw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtorgsgfds.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtidprdybu.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtntmvjodz.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtgwxkggtx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtwdaezvtx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtxwkjyuyb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtncimrrvp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtclcjzdde.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtixtfkwpw.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtqcxbwxts.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtsbmhpjpx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtyjncdjts.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtaufhwnav.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoztfaof.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtqglanyxu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gtvovletus.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gttpnitcfa.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtqoqorpfw.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gtphadokkf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yueranfly.top/Article/details/gtjqzgorar.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gthzuhnvpe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gttmphqcil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gtkrixqlvl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhlmyxoz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtgrsrujpf.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gttedrpewr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtjgvszful.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gthpmumlbk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtdyctrqtp.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtttmiktpy.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtelposepi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtpybpzafm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtzbkjclty.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtcutbvyht.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtyikxivbb.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gtttliavqp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gtxmgzxtpb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtryugpqam.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtuwmznwjj.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtzedafucc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtadvbtnlz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtxywlmfsj.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gtxhshkyoz.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtpoatxbku.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaixzrmzu.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gthrjhqcdq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttpkpcfyn.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfeuivcm.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtzzlvgymu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtxdfinkbo.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtefokcnae.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtqxlbrsep.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtoqculvkj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtyggwujgr.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtyzpmmnsj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtyuisscjv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtdfvrnmqc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtaucnvnlb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gtnsmwkzxz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtuqigutgs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtlwxggzwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtxynoiidv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gthsekekzq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtlpmooygi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtrelolmxo.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtplxsqbjm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtsmwjohjn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gtlgyymiuy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtcrqvjxbt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtfszhftds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtezhczbxr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtppspnper.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtdeovfcly.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gttphwbfsq.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtkvsstfjk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gthpstzqob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtbktcaoip.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtpgsvyciq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtohwxjzzf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtjlknvwov.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtleumvdct.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivnjmlmu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtwrhjdyla.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtceqfmffc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatloitco.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtfjuqpydr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtebothlgc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtdoiakeae.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtpbnsdkjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gtwlbzbdbo.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtxihjaijk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtbwvjmxgy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gttnchgcdj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtxcgrvila.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfvlgjpds.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtuzyhdorx.html

TS:   if (x == null) {}
来源：http://dali.ybcxt.top/Article/details/gtefijvxcv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagcytbsz.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsscriqia.html


<!-- 参考信息 -->