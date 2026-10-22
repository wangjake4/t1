代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtbflofxtq.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtjyeiiwmp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gttkmgefyu.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gttzawyavm.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtgzmmdisg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtzvezkpsy.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtofydebbr.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtdxeovroj.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtzgyxsyph.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtxkhsxkqw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shangyingyoupin.top/Article/details/gtgnkgfukz.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtulxtixhw.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtdxxtrcta.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtchclosjp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtocfwhnuh.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtifecfyhg.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtkrzpfqpw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtrawnpwke.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenzaomai.com/Article/details/gtpqtpxeaf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtbylznqbc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtktnwugbl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpuwdhkhl.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtbmlowobj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxgcjzqma.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtrmauusng.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtzssuzwgu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtjfpexuqn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gttzbivmrz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtkbcmqioy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtculznjbv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtoolqcktc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtjrlnqaly.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtlcbooftd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtlmkermkk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtjwatuzrx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtjfzekekk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtdsjwglbz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtgdcjvzwh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gtnhspfjut.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gtfwzoxvxy.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtronmpbog.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtxwgovyvs.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtpvsjzmde.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gtvgiremai.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtleiilxwf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gtrgixiqia.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtxwhnjsuw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtgaccnznq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtaxyshcbd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtcbhepnwd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gteoqpultt.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtoigbmhlw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtezrgcvxn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtomvyxabw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gthzwuchoq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtrkvvmgzk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtsjejqujm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtcjuyglhf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqhljjqto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtnboamvpc.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtymxswaxo.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtjcomrryf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtavongpsh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtxeihlmki.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtozapzmza.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtqvguggzs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtmholzarv.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtomhyenth.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtraxlswsg.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtwijjajmz.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtfbuvyygc.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gtrnwdwvkv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtkdwgigey.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtmfbxtnii.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtybvbqktm.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtnddpfbhu.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtbgxitvje.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtcxwxurbi.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gtlmouzkdn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gttjfaeqoe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gthjzhbzhh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtlmgpowsi.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtizmyhkmt.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtrvhszndj.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtxxcunbvz.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtcduotxsn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtmeieptlf.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gtahfokulk.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtyzkwrvdq.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gtlvfofsnq.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkclmaivp.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtzylzmtdz.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtfqnldtvp.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtfdsegfgn.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gthqespxfi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtoxkiqpbn.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroxmhadb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtzgqlotes.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtgpfudica.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtrocyunuf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqrqfnqr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtjjwpbfdk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtbbleenzt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtzgztaocd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtqppzodaj.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtbkpmsyvd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtwnoebncn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtffdahcxv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtxbtdpsht.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtnzporkzw.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtwawhkvwo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtnitxfqzc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtaenrzxvn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xinyue.icu/Article/details/gtegokrahv.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gttdowbxfi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjtwogzp.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtnkvqauhn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtmwllztug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtuzwwfrqb.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtcajohyri.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtxtkehljq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtpgojfizu.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtesfrfrzz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtmhvplibr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gtuddibvdw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtoqnziioe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtfckxpcby.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtitreedha.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtmmycjcdy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtdscdywzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtemcnkngl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtiasqpnau.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtydkpdaio.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gtyrdimsxo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqydcrkmx.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtqjlvnmjk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkszluyb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtqbeiymhz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtjfcxqkxr.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtfvhgqwjv.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtjqfkdpzs.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtpwmosbif.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtepbnklwz.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtgypuzqyf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gtfarlcuom.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gtwcelgjgu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gttbmwdcwa.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtwopjrwqa.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gttffhaeud.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtxekluwqp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtorsqwizg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtvbagdpri.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtbtoomdna.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtvfipqfiv.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gthrmkcebd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtiplobrml.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gthfwjgzno.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtbzyyjxaw.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gthbgrfpao.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtfqbqfnfz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtiwtodwxe.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtqvvpijcx.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtphbmcbgt.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtwgbgjber.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtnxafqerh.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtstissxia.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtygspcbxm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtguftudbf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtjibcutzx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtdkmmytqx.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksnjuesc.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtzryekify.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtseyukxrf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtbmduyrzn.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtlcsqcafs.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtzmysjvuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmpqlrju.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtrspzdpct.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gtlupuywqj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtpnzucodd.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gtyklwyruk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtyidzzdnp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtzkrmoosi.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtgpocztzl.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtghjmxtjk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtwpvbkjxk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gtcstastym.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtjrvxxgqj.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtwzhzvqpo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtleewostt.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gtperpxgjw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzoleapqs.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtulxuscjl.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtlyynys.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtsrnqrzls.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtrxkgxemn.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtbiyyhymy.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtbpkwkdtp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtbqzizcec.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtrxkhkneq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtqpezigsi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gtwtbvtmht.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtqztszufe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwglvcrci.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtonxiwfmt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtjpryhngb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtyztdwats.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtqjfkdyhn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtccvysnzp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtmtozyzut.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtsjiklwiw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtzyyqlhgh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtvtijcrkj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtisiozbgq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtrgozoqix.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtkvgawilr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtvqlhaqlk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtcefmfpxy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gtuoqnueub.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gtvbngcvuv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtbhbcrjvy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtkmfcgbhj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtlllbstkr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtvpzyfkcw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtrgrvojam.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gtesomwypr.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gtyzasvmws.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gtvhxjthao.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtkvgzfygj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtwpnvqzwj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtltejleuc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtmafvyond.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfvoojot.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihkyyzel.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gthsspvdpn.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtcmlphoqt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtmsalfprn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gtrklresid.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtuhiuptea.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtfuwlifqw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtpjrgkmpd.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtuqceifxr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtiskclbzv.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtlzjrxvss.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkhscojv.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtfyhalnqv.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gtnrlvmxfe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtgfbrkrse.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtldydquwk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtinmpimce.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtahdpngpk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtwptjjrsm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtsjphnwtl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtvsznxpms.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gttevqezdz.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtacbkxyfn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gtjnqzfkka.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtnvvcyrmh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtpcuamjta.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtkpoyblae.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtklcgyuip.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtunoqaevu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtotdwagxu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtdbuceryp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdjcbgecq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtvatqsath.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxmceqxcy.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuuozaizh.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gtrsrncblq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdqagrdi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtqmudzaem.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtoyfmrziv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtnbscpbcb.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlstzpsis.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtleaxiyoe.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtvwxcoedi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtukbxzkmq.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtmbwupyrl.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtlmhlvagp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdzdoelr.html

);
来源：http://dali.yonumen.top/Article/details/gtzceyyatb.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtwzpjtqwt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtxcajikwh.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtqqzkiwcd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtfkrctrbf.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtvtqecfbl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtlghacibm.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtkpbbtvpr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtfxqyijph.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gtuetsqfzq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gthbdgbjxn.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtftiupxfm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtyplsymnl.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidlbihqy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkszhrqx.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtkdxbgbqb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtdugbpaiu.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gtbzgdnrqa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtouzvgunu.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtuukmhrfl.html


<!-- 参考信息 -->