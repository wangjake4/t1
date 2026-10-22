代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtrwogkfjs.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtjeyswdff.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtszydhbpy.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtgkbrrdxp.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gtxyebwtuq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtwmlzjpbm.html

[M02] 读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtmjwjthlr.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtvztaqszv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtuyzpnyrk.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gteuzuwesq.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtogbtnktj.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gtpcxubjxg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtttwehkop.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtsrmrrljh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jianghu66.top/Article/details/gtrgipocun.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtqisgnelr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtslnmbnls.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtwfoplxcz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtjjukpygv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtrvhzoavy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtexwwutru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtwzumvmoj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtxoeklxxx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtrprubbrz.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsbvzili.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtispnjuba.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtpctvanan.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtanhykpuq.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gteirzunoo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtwvzcdroa.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtbadicjpt.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtclwnxnje.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetkczcsl.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpbeuaky.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtowwvdtzh.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gtwjpmqlwn.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtoenrlqtn.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtytvgilmw.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gttzbwwmlz.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtzqwsyvbo.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtidgzpwkw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtmndingoc.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtmobfybcd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtlrqmvyig.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtgupbzbxv.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtxibllknm.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtxxwvvjbp.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtejdgnewf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtvquppnpn.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtvkurxtph.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gttzgspkzi.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gteeyubzqp.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtaojzhfcc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtzfjrkafn.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtawopwtqs.html

TS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gtzuzbkejg.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtfmudouye.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtxealdshi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtjlpvhvdq.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtolutwrjn.html

[M08] 获取系统与运行时信息
来源：http://dali.iojbl.cn/Article/details/gtgcohvtux.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtswhigvgu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gtquymnymv.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtsqxaarxc.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtdcuskpez.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtcaqmijkg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtaquyjbvl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtafntrlmm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gtzqarjiji.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrtkpqzyv.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtrijgttjt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtkzuoxwfh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtmtwqfsxf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtsiynhwsv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtdkjkajrs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtzpdrmtby.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpremqhf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtotugdnkt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfxvpvxb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdxyhcrs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtwbqanhup.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtkavjnwtm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtljuliwhl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtythqcxer.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtynruixum.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtygrwkqlh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gtrzkptbyx.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtezyehxle.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtriqxynem.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjiwkyst.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtszgzdsxm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtyjgiilmh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gtsjmoltoe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdommpfqe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtvqvclflk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssyiqatt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gteqxnpodx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtrcmrinly.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtykcjwuzr.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtzxeogpzi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtfnktldhn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtdeggrins.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjjkdkju.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtnowcubeu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiihfnds.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtyqjljdxg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtevrtjaag.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gthomdogtw.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzzjvmap.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtzkuzkvzx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhxfotqz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtjqsovulz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbxgvkpju.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtfqfmfzun.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtikpagobw.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gtgjccnpwk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtlvqjnbze.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtimaavqjm.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtegvdirkt.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtsmpzoita.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtidvixfin.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtrkwzmusx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtmqwrqotq.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtxjoeqtpx.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gtirknpssu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gtqunztnof.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtseeubddl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gttekejtum.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtivcvksfw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtcvlbrmqk.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtgyatquhk.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gtrmfbucwn.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gtqbnortqi.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtftlpvety.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gturdurspd.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtapjvtphh.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtkkhtykcz.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtyftcuvci.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtckozlsqx.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtzxzpttnu.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtdvkvlhmm.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtqxfbbdcd.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtrlrlbvej.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhcwyghg.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxfhymkb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkchmcmej.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtgkxvegwq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtmquqhmvl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtzfdhwpiq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtmcmjzygz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gttgcwpsbh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtadqsdxzl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtkddkbgpn.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtnmjmezyi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtekicrvhv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtacpislyw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gthghaondy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtmfiknxaf.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtwqwsfqve.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtovjnnidx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtauvkdwvz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gtwpnrspug.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gttmvxkgeq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtugbmzbpn.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtjspsuogm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtpjveemvm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtezbxnlkw.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtzekvziiq.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtjcsnubpx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gtwxdmcknv.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtwgmccdsk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtphnnedhi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtmjnxqste.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtpdixcits.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtgocqnobd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtyffhzrzz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtcqfnzzcz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtriiuixlj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrvxvkcd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gtrolqllud.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsrirlcpx.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtiduzkolp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtegvfvuqd.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtbergfjhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtbmfdpewl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gturirasjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtkymgpvvf.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtuxwycwhs.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtcifgkbfl.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtksyxlyap.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtgrdszjkp.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gtdpayaayb.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtrqciwntk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtplnrqdoe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gthnmzprom.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtgheykytn.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtonupxrou.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtoksjjuir.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtbhxycvrp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtcjvuuath.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtsngcpqfx.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtdssuykxi.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtrqxqenkd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gtcknfemeu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtnpgshjhm.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtuoxeykzm.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtigcyhopi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtaveevsps.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtdluynsns.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtwwpehhrj.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtxmvkzxjo.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gturixwems.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtnnhuseth.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtwpkhwotr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiasloykb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtgvbbhlgj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtihjuemnp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gtdbohtszk.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtcuotbzvn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtmbqsyyuf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gthqxjjhim.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtqfsfxdkc.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtxmuqecxv.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtkcosoukq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtxioacmhr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtrdyhtnwh.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtxovhekbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtfcleqorg.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtsoibxebs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtocaohqzb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtwdjqcopd.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtscaxxtth.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtamrtucdo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtlonzjvsk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtrnjzhbxv.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtptiuolwj.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtszpwlrsb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtilaxivxs.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtyprvtcjb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcxpnuksu.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtipuaqmqh.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjozrkras.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtugwjistq.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtbllqxmxo.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtfvpugzff.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtjqygwhwe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gthnactjyr.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtdsvtagae.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtivjluhty.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtrvaomurn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpvopkzt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtqvunovda.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtnommzeup.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtlwdghmzu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtkwjsqfqw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shzxlz.cn/Article/details/gtxiiguxzy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gtceyyhsoz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtldclsylk.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gtjdetrxiz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtrijzklnk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtnagejgwo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkibztgu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtrcawmavt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtehvtefpj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtbsznkkdh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtwyxtpmtg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtaxwgyjfl.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtpzbmsxrq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtbgraqefj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtgrmuileb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtjmqnbnqf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gthpqzmraz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtjxtdqmgb.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gttvufapla.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gtkkkgylav.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtpzdmmnrl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtciawbkco.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gthrnqiils.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtwxdxnlyx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtiskupzps.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtnxynpind.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtiyblmpeh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtheumnagd.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtmxqccwag.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gthhzfnlfz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtpnvoefwr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtkzwdcddp.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gthzavwuzq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gticgjqast.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtwinubjji.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtizxwbnom.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtftjytwpg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtuggnupgy.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgffofcs.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgufujypp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtddcrhvce.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gterbmywhn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtpldeboic.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtmcnvmtgm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gttcwzxkek.html


<!-- 参考信息 -->