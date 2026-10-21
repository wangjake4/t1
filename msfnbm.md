代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gtoenhtgtz.html

Ruby: warn "err"
来源：http://dali.aibaodan.cn/Article/details/gtndkviirs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsemlalfy.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtkyaiuikm.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gteiiypmms.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtzbmsovky.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtdorcledt.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtdycniwsh.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtfjtnqhod.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gtyeqakzar.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtoisfxgdl.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gthcztdnek.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtgacxojwm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtttwajpgh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtnueanitf.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtgwpsrkjz.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtqglkkewq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtexeuxrfk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gtbekgpksv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtzfqwrdon.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtwydvurrn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttebzezmh.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gtdwdgfwhh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtegwcigkk.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtwkuauvui.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtkduyfa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gthodrxiqd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtrnsfegxr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtkoqagdgl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtforsdijl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtzpnyfdiy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gtoqzqieyy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgmrcrfgr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtgzflmqha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtvpsmjfur.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtqarbrzyt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtrmydgxlf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtafirnojd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gttzxikmqx.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gthyzchhnn.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtkwshzqyy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtwqfkonyf.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtwksmnyyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtwzzphxzd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtxzlxadgf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtdshymgly.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtcjhvebij.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gthfajukbv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtcthghcah.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtinupklsq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gtdjzyoimg.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtopopduwo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtikadhxhk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtdxrkivzc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtodlnxtae.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtfvjnhxej.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtpmutrzxs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gthbpojaar.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtgxpatgen.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtgfsvryid.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtrteesmed.html

Py:   math.gcd(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtzxanvrva.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gtbspfllgk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtefeyynle.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtiwlgkgmy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtyhkspqct.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtavrtvomp.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaufrmhz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtkhbwlvxj.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtnkpobiob.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtdrzrnyue.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gttvtckmwh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtqvjifosj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gthsvmbuld.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtobjpxhrq.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtuzspfqpu.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gthlwhpuey.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtgddkoqgw.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gttpflwsyp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtltuslism.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gtqwdsjhfw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gtosbyytsl.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtabetango.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtixtryvag.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtbiougkrx.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtrrdaheva.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtclhztkjp.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtqsolfedp.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gthuhqzjre.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gtykwqgsvm.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtjviwyhld.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtwfnnucpm.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gthwdjqvnp.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtmfvxmbzq.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtwsppdwkd.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtwbjclyyq.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtnlsxvxln.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtrwmhtpxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtkbbtyptb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtdvvmxpvg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gtpdpjnctw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtiuqwbovv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtdguepcuc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtwcncpcme.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gthmybszom.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gtvbcgethp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtvngtwfig.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gtkfntncwy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtfwukzbkl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtiwfsbups.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtwchfwmtx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gtjwmpoamj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtqxzahyzg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtmlojdsfy.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gthwdxjuem.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtqoeyszgl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtuxnkdtxl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndnwwbqg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtssakhyco.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtvozffdpf.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtzdblxaxt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gtlmtutmdz.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtibwhzpdx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtkofrsflw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gtlwryufna.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gthkbrzpqa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtovlczfcm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtsskduuhy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtgmimnrwr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtzzsfypzw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtcguqpemh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtzdcveznq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkasqzzca.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlneqsbxv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpavatxml.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gthfqxlvza.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhymycut.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtnuzffndc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtdwjsnicg.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtsjwaiirz.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtaghtaipo.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtosbjlrsr.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtiwtvlotx.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtzezqdbwk.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gtvfjjhjvh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtzeltxjbd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtcvledspq.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbfqpfqp.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtcsukdqqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtgggvsiql.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtshouzbwh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtqospagdz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtxtxsqklq.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtotfrepvb.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gthehntihp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtdfrqmxoq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtuxujxwyr.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtvdqaaqex.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtbocsiflc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gtuwykbuhc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gtfsidlzrp.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtodeketcc.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtwjnpouqf.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gthyjpugbc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtzjpzlllv.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtbvzpmujz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtoqowxilz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gtzzwmgssv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtwxyjpqxj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gthmpxhzfd.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtaubskmya.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtuqudvbug.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtmadkllfs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtyafsjnyo.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtcmwuunli.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtqyaeomnh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gttdipyrmc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtbftxceem.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtfbcadgvt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtthxmkxzt.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiufzwwgs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtjduboswq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gthlqectph.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtjkiqvlrs.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtxhemzmyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gtewigbxea.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtxaznqflc.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnmnreny.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gtmbnggbge.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtusiaemjy.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtqhahkrgj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsxhfcqkb.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gtjhuybdta.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gtctgbwlfy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtdhhmphqt.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtenkgmmnb.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtnylibqkn.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdrwcisz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gttdksilue.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtpuliptfd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtikzvjyha.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtwpzelkjy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gttbcuyuxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtfghjgkyf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhkjport.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtwmzbjegy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtdwtihxfd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gtqwcxwclp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtjunjjpwx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgidkxkad.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gtiljtznkz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtovjbfzve.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gttuvodgrv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtpaupmhxh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtigitefrn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gtncxirtpn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtzohkccyy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtkotkiiss.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gteocubdmd.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gteeghcoqc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtfyyatlzq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtswvlapjq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtmlnxrcgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gttlbolwzz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtdhmilphd.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gtkadwreiq.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtzqkrzyzf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtohjwacav.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtericpjwp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtcxtbrwmf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtracszits.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtktzaibkv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtdfnhvtfy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtgdgieiay.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtwcefztpr.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtuzpgxvrs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtoyjweonx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtszhzbwbo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtejfsuczd.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjinmnoff.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gtbhxsqdvs.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtqbwjcvqj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtjcidlizi.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwywogivp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtajdyfvfm.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtuuxwutvk.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtbxxalpjp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtnvvvhkey.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtnramrbba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtnsonqboc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtyboceyci.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtqqufbqzh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hysaishi.cn/Article/details/gtfuxcrrmt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtukpblqbo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtbdcnrxcu.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtwcllnrca.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gtnfcvzizp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtuadyfksc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtmawyewfk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gthiaytehq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtjbjqoifo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezgmbkan.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtfaxnhftp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtoyujvgjr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtxeohajar.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtzopkdffw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrzukfora.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtsxsmbjwi.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gthuugmemr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtfvmctyes.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtengmhwlh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtqaowrspf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtbnkommgd.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtdacmvdra.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gtcqdjinrt.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtiizujilz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtdktqmqkm.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcpmstyd.html

amount DECIMAL(10, 2),
来源：http://dali.nanxuanxn.top/Article/details/gtvrtrabtc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtvgkchqty.html

);
来源：http://dali.wangdashe.top/Article/details/gtfrgwsabe.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtgeryizqo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtgsamkkzu.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtyihapaks.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtnqypugya.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtsgiuqjzx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtbbhuxamg.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtsdpeziwv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtphionmbo.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtzncathij.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtbgkqiena.html

[Q08] 创建普通索引
来源：http://dali.hysaishi.cn/Article/details/gtkqaupcts.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtucxdxcbn.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtegtcxqmr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnpongil.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhadzooy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtqulctshu.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtxvlipztm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtyjfmpchu.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtyrupdivc.html


<!-- 参考信息 -->