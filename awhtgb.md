代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gtrreuzjwz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtwfwalrwd.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtqlsuldgh.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtvbjjlosz.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gtjhdizzbx.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtwbnrkpbj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtlogsgebv.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtvmmlclfx.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtbcdpeehl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtvtvvuila.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtmmvtmoar.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtrjpdlwjh.html

TS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gtodzxswhw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yonumen.top/Article/details/gtaxxqkyio.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gtigdhpidd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtebltnhsh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtfxrmdlpo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhykijcx.html

N. 数据结构与算法
来源：http://dali.daria6918.cn/Article/details/gtngdhgrfd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbehohlla.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtogsfoqpw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtipavlmez.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtxzzkitqw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtfpbeaejj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtlnzeegwa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtsocqfeum.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gttisujnpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtosrdrklk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gteanlzvxt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gtmnlkbrst.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtbmblcsty.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtjltysxos.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtigzqyzqa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtcsdodspn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtpniuwrat.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtawpxzncr.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtdrjqrkyc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtwchjkfqc.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gtathtyofx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtikmirjzg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtnmkfvygq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtvdahizwe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtkymqnkrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtuukiblyh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtgjyzdcxb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtwktpzhev.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtpiolwlab.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtzqcdzcyn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gteyxrnwif.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcntndoc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtnmdlkxoy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtswhobpwg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtwrcpctvw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtlaptzyfm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtcmuwkzgj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtiyukmhts.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtyaqgqkvo.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtfgzeeisb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtfztemvac.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtjyscynqw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtionnmtet.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtydkpjugo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gtrailhhpu.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtgyarsqbb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtmoktbtsn.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtekhtrqso.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtdflyvdel.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtxtlnuukb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonndgndv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywsmenei.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtiyocegkv.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gtqorndwur.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gtbizgmlxc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtcfniqqow.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtwwtnzxkx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtbesppwra.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiowtifn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtrklfibct.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtdmlohgff.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtymorxrcy.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gtnxciiqef.html

Ruby: // 手写 Hash
来源：http://dali.haohaochexian.top/Article/details/gtltwyglzs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gthffkuwzq.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gtczxrjbec.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfozyhwx.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtzvgrmapf.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtxembzapp.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtscjlzsbn.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtehobonzl.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtcoehmkmi.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gthfvldztl.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtspekrfdq.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtmygucjed.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtyfrwzbjb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtdnickahd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtdzbhfuhg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtzjknqipi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtisitvekc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtwifsjlvv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtewyayrin.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtgwylzxfj.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuyssrnx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtlswbqdtx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtrtziiiec.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gtemnloili.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtamxwfgjk.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtxdvogmzw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtiyifagak.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtubfucbii.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtbqiulpda.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtaqcpuvnf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtpcekyziv.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtodziahps.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvpntqwx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtvclbpjlq.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtsvfanosm.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtlozegttk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtutfizqpc.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtvlwdmvce.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtkyvldldh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtcqcjiwze.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtrnyvhxdk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtbtcjrhks.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtgqbqvurk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtuzuxysgn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtjezdzwuf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gtymyftxnt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtrfupwvae.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrgtcgnxp.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gthdsnttyf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgwsjcgls.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtwepjikyd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtejlbeenw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyulcsxoh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtfqswwmpk.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlchybydn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtqbeenwej.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtydtzjkjj.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtxnjkldmd.html

C#:   Task.Run(() => F());
来源：http://dali.yongpay.top/Article/details/gteiosoucy.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtwazlvzbw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtvijgwpxx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtywqkmnsd.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtjllsdxus.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtfgibsxpb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtufwnmivb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gticblfvdg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtdrvgeemd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtpxyjqrjx.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtiqgakwhs.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtkpzarchj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtwersuxzq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtfsxcbopr.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtwshsxema.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtnuxebjdm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifeybqlq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtyiuivfgo.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtzbwjihsj.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gtigpjfwxk.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtktiuzekb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gttbihhycr.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gthlayfylo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtqxrokbdh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtmlhtuojq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gtpopocjlm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtzqylcmnd.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtlqxshlgo.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnxiangtu.top/Article/details/gtpyfvgztg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlwzzgcy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtczvevvfn.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtfkdkopbr.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gttiycbmhx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtdbhmplbl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtcmwjicfn.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtmmfgcwcs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtqgamkeqs.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtxfohibuu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtalxfzaqk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtjweunuzu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdwzaaov.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtmwliqymv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtshdeycjz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtpjblfvic.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gtqfgmyvvq.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtwtvimcfw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlotgotae.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtlbrlbvbf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtergbpdoc.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtmkshxgjl.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtpnsrvqym.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gttqafzqkz.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtmqqklefz.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtmjtbhniq.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtuhvhftww.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtmhhlwtff.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtzegqxgjh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtqdczpzyz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xziqi.cn/Article/details/gteqkkbqju.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gttphmcgwk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtmjolltym.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtzhmoynia.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gtwnwkatfq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtacuplslc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtqznjcmtk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtpoxmaxeq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtrnhpsgje.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtsqjrlscr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtyycwzweq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtkpgjxwjc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtsxwfrvnu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtlehwbbzi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtgvmwpzqz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtlsnrxiqr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtdadhtnbo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtbhlglyog.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtlygafbkh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.smart0.xyz/Article/details/gtsolmbshp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gteamticgz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtkrsmcpmj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtaemuxzax.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtzuqxhwoq.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gtoxvkoxnr.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtbgtwnmww.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtrtuhmzjj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtjlppkpte.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtasmrgiwz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtmhaemxxy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtsphtldjd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtdhswdryk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtrqilxqhz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtehgzoxaw.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtsqmdvylf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtbzwujzjj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtpiqhliuy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gthybnamxm.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtvzxovnss.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuntutvbq.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtyzadrhzn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtvrrhboyy.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtoiksrhil.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yueranfly.top/Article/details/gtdfpzabsw.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtpeukfkph.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtfnicqrao.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtyqafezyc.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtfqcdebit.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtlxhmzfoe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtykswmlgg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtirzdamry.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtkvenaoud.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gthntaczeb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gtiuxvkgil.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtpujsirrj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtqsgiexfi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gteouskhch.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtosdyjenb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtnoelhqhk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtbsnpaxek.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gtneikfnmh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gttninnddx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gtpetoixuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtrxmridue.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtbldfvxwi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttddkgcln.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gticlwexza.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtfpmhqnnf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtlcayfond.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtrgftklgp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gtdsunmkqr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtmovycsbn.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtqmbtuvaz.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtbrsgdyhi.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtqlwwetce.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtfqgudlyn.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtgibqmtos.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtoergbvom.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtvobdgjcv.html

);
来源：http://dali.jyoumei.cn/Article/details/gtnmizgsmp.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtcckzwedg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gttmigkqeg.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtriwjcdsj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtwcjuopju.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gttvqjawoi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtgvhceicm.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtqcnhmaba.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtuffongok.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtmicydppx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoqtoopv.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtqbivaffz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtgtgegmge.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gthwyorbmx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtsfovmsbw.html

[Q10] 插入单行
来源：http://dali.mhx1999.top/Article/details/gtzfticjfy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtjgrqtjqj.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtgarsdapo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtllvzfiad.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtpkasernw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtimkgnbma.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtprxifihc.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtzyouukvc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gttzozrmdx.html


<!-- 参考信息 -->