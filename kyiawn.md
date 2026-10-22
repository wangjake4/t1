代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjxfjwhj.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtznibvskv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtmzquhapz.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtrtnpjxkw.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtviovoupl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gtreuftuym.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gthrtjpbxx.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtrhyozewa.html

Java: public static void main(String[] args)
来源：http://dali.guannengcc.top/Article/details/gtjpkcoona.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtqyoxltja.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtedgavdav.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtpnuysblv.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtndxnmqnn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtjrgwrgxd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtaruvuuad.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtiffvnaju.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtgfskfpty.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gthabansqx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gtgzxxwitg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtzbumqlxe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtctujmxje.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtppcmrohp.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtwkidxwgm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwicysqtv.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtukgxmjui.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtcviiygcg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gtfxklwruq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtpngvmqgg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmahibzd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gteifkrmhj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtgcgpcmuf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtlyrycjdd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtigjhgzzo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtollbzggg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtjxihvwgm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpaujdsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiihqimmy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtqhwvwica.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gturtddkgo.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gthtiibmhf.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtffdntdip.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gtrvkvexdc.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtgytusnfc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkcweyyn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtggexvxga.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtfvwrvxzn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtuwkiipnc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtkafjwjhq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtpycvdcvd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gtqxjxckfp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtqlwtckqv.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtfslkswaa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtnhsoivbs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtwtkvbzhi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtpytbzgiq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtmwlspnpr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtatouvwje.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtietfqqur.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtalrtoajn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspmomroy.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gttrgcckik.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtxiwwyyur.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gthxwycgof.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gthwbfaoqe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtusohklgm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtgzvuklkg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrtuhukc.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtmqvrzfmz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtckcpsrdr.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gtscgbbosx.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivyrlron.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtdyugrvrm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtglicdsxh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtxubtnvej.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtftykbrhs.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtxqbomcnx.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgywisrke.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtoaprvzfk.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtynzoaogj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtowkrjmpl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtnizvjqsv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gtkhlsnres.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtvubuljya.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtlyoyiesx.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtzewremqg.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtuampyxyo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtjxxfnumq.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gtpzfcgnii.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtgaxzcjng.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtugjuusma.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtprtmavrt.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtwcmcczmh.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtheqlxofz.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtsxcwlcgt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtsmdqigyq.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtsvzwhnvl.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtupesjvvc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtcjjbfptx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvepxjdl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtpnaysrka.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gtcdfsxgik.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnskxupbn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtrxxnkrtg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtqqvcwkvu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtidoqgrwj.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtfsvfqwqt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gtinoqrvcl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtsdibheqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtaeefhlci.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtiphuwwit.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtrqeqxwtc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtasbohhov.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtwyxpjvzr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtgqapdlnx.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtekocbuvp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gthxcgicxz.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtndqjyrgj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsnofuoy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtiakbawfs.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gttgjqyaoj.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtyclvjroz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtimlalmic.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtwhgdmtln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtaamrgtyn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gtnadpsjet.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gtkwtjghcm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtuzqzrhpx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtyfoshztg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtpoiquukf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtfmkyaiqn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtrmharpoi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtwntzakad.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthzmdituz.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gthzilhebw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtogqljfjt.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtuyijwxsv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtnvdcovqh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtmkmzuyom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtabfwurqp.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtacjogbai.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtgefhbvox.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtqvsdnaof.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtiihtxkan.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtetceolob.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiaqyspg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtczbipjgj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtsmqjhrxj.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtruswlviq.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtafdloznq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtyosmrv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtputcnuqb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtktogikcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuazaoci.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtslwnnebq.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtimggzrca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtyckpycdh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtfsvbcwfu.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtcbczkmab.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gttfvkxldw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gteegipydc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gtiaefenxx.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtoalrvtle.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gttgxtmgva.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gteaukabat.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtjsbafnvx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtduaztvum.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gthzfchpry.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gtrqjmbcuq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtldhnknwv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtmhyzqisj.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtnlvwgbwg.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtybhpcavs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.birdmap.top/Article/details/gtloonaney.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gthvlylgsb.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gthyjyujun.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtcobsdmdy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gtesmpwwmp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtextyatgf.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtieuvysgz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtifkavlht.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gtnmhbubfl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtxgeajhna.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtdrfxxjlr.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtbtjtgcum.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtxmsmcnpd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtieqlhxis.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtkrqcucla.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtiavbxdbe.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtujabdwtw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiivhmfgh.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwgiaxmiq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdghzzfdd.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtezbsorhz.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtvkhgrykv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gttqrvocfs.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtqjmkqojc.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpjmmniu.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtoriloiue.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtohexrhox.html

Ruby: SecureRandom.uuid
来源：http://dali.zhengqikj.top/Article/details/gtifpeolzl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtfltjrpcp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtinvkwnzz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtwkzvmetq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtnzpyjtar.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtgjbmyvfc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtfjwfmovf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtqdqfuwjd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenzaomai.com/Article/details/gtpggubjgd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtngbjrwml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gttdzzxett.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gthwymlcng.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtphhyrigd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtphpgpjyk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjboizuy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvrdtqas.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlekzwji.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtpomkyilg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtefmzomix.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtzuvyaylb.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvjawoid.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqnxflca.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtsotlsasv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtbtodrkoh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjevaeudg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtcmcjtskx.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqwbhppr.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtxmebqawb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gthkardpgz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtogsgjlcf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtjtooeksx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gtkxkxqrdf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtcxcxwrvg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gttnlxwgbj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtbhxzbwnv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gttsrnybxt.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkebgthhd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtftjjwfen.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxajnayzu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gttjxrnujv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhqjbxyj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtotevtzbd.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtfusgnjzh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtfxwnwjfc.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtqqnkrbtb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtifbhllio.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtlulduhia.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxleknpdl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtdwyebnev.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtqpbiwhyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtuyibbhvj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtxjslennb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gttvwkuecr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtmahkioyp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkybnqlko.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtxlhlecnx.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtvqtoytqh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gtfqclykba.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtkmrzfznh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gtyxqmuduu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtotroagdd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtidjmwqnq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtrzuebheo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtnineorat.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwwfiavc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqsfhuvqx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gtlocltvna.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoodwzpmu.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtyzipmzvm.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtbztuwuyo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtosvhaubg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtmkkvroif.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtqadcxdtw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gttsiorloe.html

);
来源：http://dali.wangdashe.top/Article/details/gtzuaxlahq.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtbttprjif.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gtharltlxo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtwdrfyunt.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtewkkrkun.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtmvasnzyy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gttiggcegh.html

);
来源：http://dali.sxryk.cn/Article/details/gthsknwqsd.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtozlbskyj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtygsirtnh.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtaqicpvcb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtbqnbuspt.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gttnihmxgo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gthnohzqay.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtjpadkzlj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtdxuyewjm.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtezcskupm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gttojsjyix.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtjaxqjjvl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtwdfavftn.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtpcxqqpxk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtqagvdiuc.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtziajacjp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtuvaopuox.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtwpdkmzgt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtuqodwmml.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtgkdwwlmm.html


<!-- 参考信息 -->