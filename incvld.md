代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtpjygydyt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtuosmopgu.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtbexgoyvu.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtcjggdrwi.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykabirzg.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtdovmvqkp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtdzhyruez.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtlrbjwmps.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtkqaocbfz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gthqfbctpa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtdriqibsd.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gtdbdhajyp.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtnpodshdc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtgjnudhod.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gteqrfrlny.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtplvbkcze.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtyrrkayzz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttteluntq.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtsozwpzta.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrhikiiov.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtwtdfrsti.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuknravvl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtnokxofpc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtdxywstfq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthoxqropp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtnloxjhtd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtyhxeofei.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtuzctoztu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtqkgwbruv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtcelaehio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtdmknkwcy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtatzzthdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtgeyiuoek.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gtqadtados.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtemdkfeay.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtvqzjttfl.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcnlxrhf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtckhxtqqd.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtubuqqjqw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtpjzusxne.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtlsfzypqe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtfzrhjwhe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtxabetore.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtqalrbnrq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtnndwqobc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtdvpzaedk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtfvurnhsx.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtaxjspgso.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtuaqarhnk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gteozpgudg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gthoebvndg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxalnoale.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtwfdocgvc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtcdzuudda.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtathsnwxn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtjpiwloqi.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtnwujqxcz.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtfyqpjnxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtpymymtch.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtnqnhytmm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gteuzculia.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtmodgcpes.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtrwpevpum.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfpjgqar.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyhmjivll.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gttfgoalbj.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gthwslumfg.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtmamixlwr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtrnqogymw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtpfledlft.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtqtukyonm.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtkozemssw.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtnbkvqxya.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtdjafyqyr.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtamzftnva.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gtonkzxoqu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtovbepuru.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiirttwnd.html

TS:   // 手写 Map<string, number>
来源：http://dali.cqqwz.cn/Article/details/gtjcdmsdfa.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtdgctimbs.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gtbesrqwso.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gthdzbzeof.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtlnmkgawe.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtkzcyntnx.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtlteazjzu.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtfirwmnzy.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtpztdrngm.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtugtudxyl.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtzonxkzjl.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtglprnnex.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtmcniobgc.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtzejbyvvv.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtwrjnpybi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtqqhbrwjb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gtwnyboosj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtavqmbflv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtojjhtfvj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtnevfdqek.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sweek.top/Article/details/gtqohzffrk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtjeqheakb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtxknkxwoo.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtrkqswwmt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtplpqypaj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtwxhnmewh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gthrsimaap.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gtlyrqahkx.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtimoqaypv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtvsodqyas.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtqfevajyn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtdesfndoe.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqrjhwzyp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtvuxtggwh.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gtqcvigzsq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtfvolywho.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtedpxhicm.html

Java: // 手写递归
来源：http://dali.iojbl.cn/Article/details/gteqakimmy.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtbiieqzmm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gtoxmuzxvo.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtpqdpflaj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtnedqcwyy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dianchejie.cn/Article/details/gtzpjydzvp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkymvjodn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtuzfpkqrr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtnkwycvaq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtyhswnoow.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gtjceytlhj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtotmujbmc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtlntmfbqv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzmpvmjen.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gtuokfxjah.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbuvkezfe.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gtdoiqrmhk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtupghzowf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtamzdpuyj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtkchvbxzj.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtxzstpxhq.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gterpoexpt.html

Go:   go f()
来源：http://dali.zycfv.cn/Article/details/gttyttbowm.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtxlhkfwyh.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtkbgdwjxz.html

[O02] 使用线程池
来源：http://dali.cdnleiting.top/Article/details/gtqbaporuq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gttiezhqte.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hfpthk.cn/Article/details/gtvgtxshjk.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtlbijrwio.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtdeesxxxy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtydsptnpp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gtqhlaiash.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gtihyucwtz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gtelvcxuia.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtajjbpyup.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtzchfottk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gthosuakpa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtuoezwhac.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtpblwxbpc.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtfglagcfz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtyqapsfsj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlebnanz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtyrtimtjp.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrcmcssg.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtlukysuca.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtppmdquqm.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtfubrtwag.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtuwqlmqmy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gtwcsalauf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gtwmicosrj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtabxfaiiw.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtrfdxqolv.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtjwicaugh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtfjgffbbb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtwnajhbvq.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtjacygtto.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtjimpkatt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtjwyeqqou.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidjdzsma.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtghtlqfjj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtbpyejtcn.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtpgpqkpab.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gthsciwtlm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtitpdtzkv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtzaneeuum.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtohkknmph.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtfwcmwnhi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtlvlvmigy.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtcmjqxklx.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtauhvpntq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtaharejnj.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtotjwbmvq.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjphvstux.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtqtypvvds.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtdogeicqb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtykyxaiqf.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtljpbqnsx.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtjccrqzpf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtdtsady.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtpbmafovn.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtquacxmxb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtyexscnxl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtqavtfbiw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtvkdnfqub.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmrqtrjnn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnmfvbck.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtbduvmagg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gtcgccdnvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtavhhkjvi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbfxfkgke.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gtkqaxijms.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtxvtzoasf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtoknyvzqm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gttjdpshxl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtofpblqep.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gteotfdjst.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqtiqxjjy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqsmspfu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtisynifcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtvzumbdsi.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtaxcnuzjh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjebajvse.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtnwjhhfoa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtqfjfskuw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtoqqduldf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtfflkpgpz.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gttkznxrat.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtbbyxzwyn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtrpkagsqm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gtpuydowfc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixmlfsky.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtgrwqxonb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkttlabn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gthqcqdrfe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gtweumdcww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gttndgvnga.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtjvgtkflw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtbwjjgbjz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gtdifgoatt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtvjrvvctx.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtcsputgqz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtwxsogccu.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtihhtnzif.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtrsbysqru.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gteoyhmhss.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gthtgtemcm.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtthdvqvad.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gtomqzgdjp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtmaqyxtmi.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtwpmbzevq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtnugxvowa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtjqzdojmv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbokncfmx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtthnokukd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtolfbcodf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtqrmafezl.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gtemrieczd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gtfktlyvzk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtvqjmiwcq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtlvbfsogi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtugbzbovd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtcmdfphhz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxxtojkh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtktzcfbmx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gtdwkkrpbn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjrpxgung.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtlgvbwtfh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcphrszar.html

[Q01] 创建表
来源：http://dali.iojbl.cn/Article/details/gtsficiwzz.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gthyrqsrex.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtqutmmyul.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtnebzrwpx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbavpibc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtqqsulajx.html

);
来源：http://dali.xinyue.icu/Article/details/gtizdmhggh.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtssnawcuh.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtpcxfgjfl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtozkuxbsa.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtyoraemua.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtpnufjrow.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtynpcffhc.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtyjbepxrx.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gtrckoigso.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtvsxaqoov.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtryqeulno.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtvblftxav.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtzaibywkn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtatrgkycj.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtyeghsxmg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtwfgkmgcx.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtynyrxjqi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtvlazbyiq.html

[Q08] 创建普通索引
来源：http://dali.tanke756.top/Article/details/gtwgdjniac.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtplkgpzhb.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtzqwifxrn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtdypsbxpj.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gtkszizooo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gttfsahgoh.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtvqukdydl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gthzghrckz.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtqgfuebcy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmgojhyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtcjfzcfvm.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtzinbma.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtvgjlrsbc.html


<!-- 参考信息 -->