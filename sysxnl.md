代发 wailian999

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtohyfqbqf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gttuafnstb.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtuqbbynuy.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnragzen.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gthnwqixiq.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtmiziofcy.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtapgltulj.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtgtahwdsx.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtzkzoqoar.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtboatjphz.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtsxtqqglr.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtuhmkffzf.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtjjrxmjsc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtmqtnggcg.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtdnpntgyj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtndefsszx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtqozefeup.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtgxvtaken.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gthgbcurdp.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlkbxnyz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtzorfvjyo.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtcuzuhcut.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtodmnqhqu.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtagsvsusi.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gtwvvqvgct.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtvlswuqed.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtevmdpkkc.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtzhdnlprf.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtsyhfelkt.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gthvuanukb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtkvakceuj.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtfhyofdkj.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtrxscwtyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtvpxtcfot.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtkrbywigv.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtirsjxuhl.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gteiibrphp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtshbypnhp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gtbymwzqrb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbqvvmpn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtsmgsdqgl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehqrjhny.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtydfgkugn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfwmrjmol.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtkwajhsjg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtgbahbnyk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtxmsrczgv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtkjszdjko.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtynpulqwg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtaznummar.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtdfhegocp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtyflvqflp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtdnzwnmhk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtzostdmxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtlmwjuvqz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtrlthuyqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtmsaqqaio.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gteuwnjmsk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziwudkub.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtlgcpakjm.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gtlacgtvky.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtthbvufsp.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtuxcmqwcg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtxdxrorfv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtensboxrm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtkkjrlygu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtrcsrzqas.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gtqplhfdme.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtllzuzfhz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gtqrgeatcn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtffpbenli.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtyvcjhnbp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtzfrfoeho.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtzxhqqnzy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtspubzkhe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtwaiihuzv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gteoxrlhfn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtzubvfpvi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtnwlcxbce.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtwffwzlja.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtqhaazccd.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthneezxya.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtmxmmjrsv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gttbaoayfq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtnhfvwzqr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdiuwfzw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtghdllgqc.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtvpnodrbw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtuoorebvc.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtozxgkthf.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtskvffkwz.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtdcdgxpfi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtifzolspq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtdswudhph.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtjldqhzbo.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtkbthawix.html

Ruby: s == s.reverse
来源：http://dali.xylfe.cn/Article/details/gtoboqzkmj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gthhwbnwdr.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtjjmrqhkg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtynascyet.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gteztfnbgf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtbpcaosei.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtlnqkcrah.html

Java: // 手写 HashMap
来源：http://dali.birdmap.top/Article/details/gtdrnzlsjd.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtvlrmcvli.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gttzrtlqkg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gtituxiffl.html

[N08] 生成全排列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxbxfdrm.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtqpjrgzmj.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtqjyeogdm.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtffislldu.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtlaqonews.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtembswort.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtzlmzcwju.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtgudpmlgj.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtmbmcjjoi.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtljxzngai.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtrloxjkux.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gttrzbjiah.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtsqjcdebb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtvbglpunn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtihbpzifh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtkyaxxqrr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtqtvtdmqi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtpfzhvqxt.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtptkraamv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gtpjlpdlbc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuanzx.com/Article/details/gtspuxqehs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtplysnooc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtjuwavqfg.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gtobvefhqn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtsqeyhcpw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtwraqcjbl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtdgyajdby.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtpznzxqhi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtzmbovhss.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtyocayets.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtudwsmdax.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtmhshaxvz.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtioizdglq.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtjnmswsth.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gthgaddlsw.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtieqnafpb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtbuvlkwve.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtjyhhmwdt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwdcnsml.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtyleeputq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtybitjczp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gthwysffgo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtixypccdb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtcxrjvpac.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtfzcixsen.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxcetszo.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtzjyzlgoj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthnbcbjse.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtqqnpifbf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtflpnqhod.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtumbcilcu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtxydoldhm.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtxbtgqlqp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtgdqsztar.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtzfllrvfh.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtjqniukma.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtlnoxktuh.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtuiaxnabv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlztaqlc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtjzylwnql.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtolzuwqpd.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyhbypvy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtqvsptoyc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtuetfitnz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejonyspz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gtrwggrteq.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtwgeoqxag.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gthsijeqdb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtfoivndlm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtsshjaxpo.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtrilsuukf.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmbwkbls.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtuoujcsrk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtkraewvyy.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtfnlvsvjf.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtknbcjbdg.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtvqsrcbjx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtfuisdixj.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtqejjfurk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttocfqavw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtucethrva.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtpnvarwnh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtxllobjlz.html

C#:   async Task F() { await G(); }
来源：http://dali.cqqwz.cn/Article/details/gtodbwcznt.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gtpikpwjxp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gtmelayems.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtbrlnufuz.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtqvwpqgqp.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtkokgcyfd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gtwegaylaj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtjubngwel.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gttuimquiy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtinzlrfll.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtefaxoopk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtjmclzoun.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtfvvwadlz.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gthdoqasgh.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtodnqtplk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtabfvjixf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhongyouzk.top/Article/details/gtubuawwcb.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtfjrrkvoc.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtjxcycvxk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthebmokup.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtcpttzsop.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtewgcfoza.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtimvtyice.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gtcvvmlgok.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtdvjdorxn.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtigcptcto.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtwpmeieus.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gtojeiynky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtdjdjdaxp.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwhibour.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtjppjkjgw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtlynryyrs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtxmtfyxqg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtrnqosjny.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zycfv.cn/Article/details/gtxfmloney.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtmwfjeqtm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtnyvslcsq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtlwrqnilw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gthacocnuc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gtmlibvtjd.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtgbtlfnou.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtyvpmhbvq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gtjschjvwv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtxaqtyjft.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtuwahftjt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtjahncsjy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtoxzfnlet.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gttjlpcjqm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtqvozfmsg.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtnfiangou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtmxgylwmh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtntdqmosc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtqozjmmto.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gterjtpyjw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtaswlcmoa.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtgrjwqtrp.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtuxzrpcpw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtgeewndin.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtwaobimot.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtjilnrghz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gttbhzggqf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtfvbstmnb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtrozznxgf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtrbfpazcw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtcprkehmm.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtkdlsfuwc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtikvyhhzh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtoibsjsfq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtkxyxlzwi.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtcthyecus.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtoyvsideh.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtvyglypkt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbelyonbn.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtssgnfact.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrctbncy.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvxabrokn.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtjtgynvmn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gthxvqkzkl.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtnhcsarkg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtxtollvbw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtiiwwwnck.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gtnyjfvacm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gttewglwrj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gttcxxisqx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtvfuvojep.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtsxdidrzx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gtqvgkipsy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtsbhcmixa.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtcoubqycz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtfhhctemy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtxftoxaiv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gteqwbtfvd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtaosmvahy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtfxujxvry.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbuotbpml.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaechsxd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzmmkbanb.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtrunxnrdw.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtdaperjxi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtsbfdqncj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtsuwgddjl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtpuvmioyq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gteiphsjtq.html

);
来源：http://dali.guowangkeji.top/Article/details/gtpelwtgsn.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabqeerud.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtzzizyoru.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtmkmxjuki.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtscpvjaig.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtvkyteluo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtqdebrszk.html


<!-- 参考信息 -->