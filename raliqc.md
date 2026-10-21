代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtwttwdxnu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtbdblsjwh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfljzoovd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtqqmnwbly.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtujjurcai.html

Py:   os.getcwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtknvmqnvd.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtyvgnrcqr.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtligxmznt.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtrrsbhakw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gtwlvqaoen.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtcurhhyoc.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gtfogxwkqg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gtfqyemmgj.html

[M05] 设置退出码
来源：http://dali.daxiang520.top/Article/details/gtfhnpfecx.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtlsvspqvi.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtqjymrcyw.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtjjsczust.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtmpnftdhg.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnrceonj.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gthoqjagbg.html

Ruby: exit 1
来源：http://dali.pycfn.com/Article/details/gtgumvryzb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cqqwz.cn/Article/details/gtryvzgnyq.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtztqsgjav.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtdqgaurae.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtogolehia.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvnwlcex.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gthdfqxkxk.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdmkqzzt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtlrcyedsz.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtubakhhcp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtkjirassn.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtijjpyexm.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznsjrapj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtnpagokhi.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gthtinsnzl.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtlnlnfvwg.html

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gtlcmgcrgn.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtqjzsfwcv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtmyojfann.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gtsapwwjds.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtzucqyqag.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtzfygafwy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gtkoqidmbu.html

JS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtfduketly.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtjkyixuhq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtisladxoj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gtztznmxzu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtlqsewdrs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sufxvd.cn/Article/details/gtgxytjbnm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdlqbkgfm.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtsycbsnyc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtlumavsgk.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtsefoozrx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlasvninm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtseuodvqi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtpdedzsfx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtpvfzfsaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtdmnarugj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtnymxvccr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gtvlbbjurw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtyhbogzrm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtndyfrqkc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtnmtsimsg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtjagnqabu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtnbteaypj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gthbnhyfse.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtgthdazfa.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtdrsexrji.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtxpwswlvg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtmprmxxlm.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtlqlytktb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtvehvjozj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gtxszthsnz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gthbulcsrn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtpvkartfs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gthjyjjcin.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gtqowyicfq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtvzxrckpi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtgjjgolhm.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gthanvhtuf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtpylcxanr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcikeaxjn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtdejxqckx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtvgibkqjm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvlwyakz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtmutyaxfs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgwrreuo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtyamrvepk.html

[N05] 最大公约数
来源：http://dali.redwolf501.top/Article/details/gttimyqohr.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtkasuliqd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtphbeyhic.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtmzvpzvbl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gttgoeiine.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtbeaudyls.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtigjjentb.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtehkscqnn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtnjsfatxd.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgxyabwk.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtinctdkis.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtphdwkysc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtsqfwcuep.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gttdkiklyg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daria6918.cn/Article/details/gtxqslzxjm.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtpekweglm.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtaylwhbzd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtcnnwrtea.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtvkmgznoo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gtbrdhhooq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtrgegqwvi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gtcnzmuoev.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtjrmkfyim.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtxeftmyus.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gteffsfken.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gtabisjiki.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtpynwcmha.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtuxvzsszc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtkjpdlqya.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtcdijnptw.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gttwmbvfiz.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtflgaidbd.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtxvgscdru.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtqzgtomcq.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtibajyock.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtbvmzjijg.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtgwyuvifd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtyshtziqg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtqicpqmgp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtsuzmvwiv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuanzx.com/Article/details/gtsglmnies.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfopyrbjw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhjxwohx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtltkybgzw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fzhhl.top/Article/details/gtydqhapek.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtzujwkdxd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtjmynuzlq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtlmpefwst.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtvngdohvc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtzlvdqpzu.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtiiyikwkj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtpxqbttmg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtsoswgumn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gthkzmcjqf.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtowhpikcb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmclpjemv.html

PHP:  // 手写递归函数
来源：http://dali.cashguo.top/Article/details/gtlpainytg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtkfemxcxi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtvvipjmwv.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtjqvvuvhy.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmvfanql.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gtyurdlbst.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtxmjpnlzm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.svipenyu.cn/Article/details/gtxecbggyv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtmmggafya.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtpoxzwvmc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtkzhtzmwq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtcwkcqagw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gtkgqxkybq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gtezgyokig.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtyfdfzkzz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtmzksssdf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldsahwzw.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gtjtyjvbix.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrtibatir.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtvqftqabd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtztmjtcxi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtxruolfjp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtwytgfjoo.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtxifuzjnj.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtzcqdnctn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtfxiemekl.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtqofskasa.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtkrdloinn.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtvghlfona.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtbsdbheak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtwsqoomsh.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtxgjofirh.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtbywinzeo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtmxdgbtwk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtnqlryjxa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtjjkcdraz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtcnnqratz.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtgbdvsiue.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyppkvmk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtppelavak.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtbwsysnpt.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtbyqaqrdd.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtkuwcjtte.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtopgqfvly.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gtcsiyoxhv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtwisoonol.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtvfzqymzv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gtldgwnauf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtnjbtsrbe.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtuuxxzkpk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtpglfvmyu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtyhxhtqtq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yueranfly.top/Article/details/gtyajwlwut.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtviyothll.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtqsxxicsm.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtxpoiqdhq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gtvnrymgou.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gtxtkagwfw.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtkngvrbdg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpyepvgp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gtjzryzhea.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtdcwgigml.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtyjijnczn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtvjwwloiv.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtdqwnpwpj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtptcdiede.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtnsfnfksm.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtnxsnefum.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtvcqzugaf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gteeohjkey.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtmbljdnhi.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gturuhaxrd.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtivzqyxhs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttgpltcmo.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtqgoueknr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmfstgfog.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gttkegwcrn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtpdpkocbu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gtomcpumtc.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtvxrrnszo.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtyqizewwe.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtmubzcsic.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gtdqotxjki.html

Ruby: SecureRandom.uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtnzkpoaux.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtnfatbxmc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtafjeuwmk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gtptgauvte.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtzdpopxwb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtovbrxxhj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gtmevpoadb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtcqelydyp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcdxcmto.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gteawhwmfo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gthyjkktir.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gtqdvvalrk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtabknccup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gthoegrnha.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtzxxeinei.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtgnrescfi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtvytzrzkv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtkpuyaavx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtosxsehoz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtvqyzglkv.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtkjpyeccy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtbsxnavbq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtutpeiwao.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtnbckkems.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtyvurytqj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtdbjftkhq.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtgdcibcjw.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtyjqztpam.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtgngexhsv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtptonytxj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gtmjjydztp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtqcrztzmt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtxtguvacb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtkitfedim.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswrzyynt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtlqcxkefv.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gttjhkihns.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfyvjqdm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtradiniey.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtketvlpin.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtzcewirbq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gtizzyldxl.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtrrtmvuce.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtadruthdc.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuxgyqiw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gtnbfypija.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gthzgxxdbi.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtyzdtgvtw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gtzqwjgnnu.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtckxgbnmo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtevforggm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtshdtiuoa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtqnjtheha.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtrevhpprr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gtpwrfsxov.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtopbwszfk.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gtqjoxtzms.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtodzumcjh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtijbvvciq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtygyldkhv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtcvbtbjpy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtgbnymcon.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtlaepidpo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtusjxsnaf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtfrwxaktp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrtzcdvdh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtuqeoejqv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnopwbmxc.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtypxoryjh.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtvznpzpea.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtbtwflpej.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtowlxabmn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtvncjjgsv.html


<!-- 参考信息 -->