代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gt2hqszkibr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2jksvgvxm.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2wutheybg.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2cflwfnsi.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gt2hztqsidj.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjsnfazh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfpgcgkn.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2rtkdcijc.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gt2ehdspwjo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gt2nusawuyu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2iiioaite.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2xdbvfymt.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2ynrtmgpj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuhxmxan.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2cjihpitw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gt2yeccchhk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqwedzhk.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ptrpabih.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gt2gkdupgzu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2tqgiekmq.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2akbhqjdk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2zcdbzmml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gt2hhklirnw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2avkugtyg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2swkmodii.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2bpjlnmnh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2dosjtpip.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gt2qibmnkuk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2lmykxmrh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2witniwrc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2yvfjpkxr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2eoljegcg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2jewyfgch.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2bmapclmg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2csjnshsu.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2flaxtxfa.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gt2sclprlvx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gt2mppihmqt.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gt2zkkmituq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2nzzaslxc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gt2urjyleen.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2vbfsidqt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2twcxnrgq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gt2slvddlsy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2ynkdeojj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gt2tmdbfguj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2aodymkex.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2lkouhcop.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2fntebbrl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2bdeafgeo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2nlmodidb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2xwvnxcen.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2nuidbnvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2opvxlgdu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2dkjyqswu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2pcqthbyl.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gt2ubczdgmi.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2crrinqgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2zrhcgdiv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2dwlbqjik.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjzupfio.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2glgixbdt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zoncxlfu.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxqwqexs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gt2vpwtprsu.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2nrewlefr.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gt2qsyknjrl.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2msypvehj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2xzrqychu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2evnzuuxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gt2rgtiudvl.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gt2gmflprie.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2ywzlmbwo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2fweuzjhl.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gt2jtdelhzs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gt2ijxhlcji.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2oimtjqwn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlazrfjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2qqzueveo.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gt2sokcrnkw.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258.top/Article/details/gt2jjgcwdsv.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuxzntrw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsyfbsrp.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gt2naysfcgk.html

Py:   itertools.permutations(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2nlhqbooe.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2vdaaggfj.html

JS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2rjfielxp.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2iyseufyb.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2uawznscd.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2gvwrzidn.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gt2tzkdncab.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2vcwhogxs.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2cobdcnvi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gt2nymokurb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2llcpytcp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2nnzqgrai.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2srisrszg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2wkrdavsv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2amuswfgn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2qmksfqxe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gt2azxrurbd.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gt2qayjsjcd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gt2xnxiepua.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gt2lkjtpzhg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2tdmmllqi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gt2ehfzoqfs.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2xlwfoote.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2bchrvxrh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gt2xqchbood.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnyetjqp.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2qpvmivgp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gt2ekcxaahj.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gt2ignctfwy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvszipzs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxqhfvfz.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2agjnrgeu.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2qsqglqix.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gt2tdqyhkkk.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2drwucmml.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gt2nlixawsp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daxiang520.top/Article/details/gt2bkzotrtt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gt2nwsacltn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2wkjsuzan.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2ykxtctbm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2mvpfogpe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gt2qqjvwtzj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gt2mpsjdzwy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gt2hpxofzdm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dpvnghwg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jqklxbci.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yprldakv.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gt2haubaias.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gt2imqazmlb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gt2updpzlpi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2snxgfdzf.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2mrqfrqja.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvmzaomd.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gt2nqbuuexw.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gt2wiuwuuet.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2ikynuarc.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gt2qtdnlhjz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2iubnkusb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gt2zqzemjii.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2vltnxzqx.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2oylhttsu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gt2lwyutmdc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gt2jlxzlaqg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2cmgkrunx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2rjcnqvkd.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2lkespchx.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2cznjlial.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2bquoipfm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gt2mktklnag.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2xggzavzk.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2szyxvcmn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gt2sdnouran.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2shrmxcnb.html

C#:   lock (gate) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2onakwsfx.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2glboiajb.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2kktfduuf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gt2ydaegdpm.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlngdmuq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2qkovnodu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gt2phytooov.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.haohaochexian.top/Article/details/gt2ohkktsra.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2zrxjnimt.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2pjceohwh.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gt2linfjvqd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gt2xnlhxhuc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gt2evxuhxta.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdmwpk.html

TS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2jjjzhiam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2ayebvofz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnnnmfes.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2lejleyaa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gt2uimywrtk.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gt2rhpzyjrm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gt2irwaqjsr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rsmmfulb.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwopcctj.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2lbigrsqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2pueeetxo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gt2vwsmygzn.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gt2rtmoqyar.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gt2wdovdyrb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2owtuqjea.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gt2pppvbmxn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybccszbk.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gt2kosvzzde.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gt2vqtpnpjq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2yrjdmnzt.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2islwmwkh.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2agpaqbqg.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gt2hygczmxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2dxwisrmz.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gt2rcgytgmj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2waigaqvm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gt2vfmlloqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gt2jqbnxoij.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2corvfkqa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gt2wyzifsit.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gt2rtigdjrn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2vxnlsfdn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gt2gppjqgya.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gt2jtrgpesr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mozxzpnx.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxxgigli.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gt2oqpojlqs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gt2deaqlhon.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vetmubwn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gt2kpcrhzfw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2jqjeiknd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gt2dbgubzny.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2gwugimni.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gt2zxjtoviw.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gt2nqbyytak.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gt2srvmflam.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2njgymttw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gt2fqnuuuom.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2lmohnpjt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gt2zpadbkha.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gt2iowmdhmh.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gt2dntklaoh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2ivmipshl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gt2xrpzxuad.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gt2dnnanvfb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwfuadwe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2slvtnfwq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gt2lvinxngq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2jawxfjtb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uaraakcc.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gt2bzyhkngz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gt2uqhallud.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2ukgguegf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2lrxcyqgb.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znogadqr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gt2egkvuyqt.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gt2yusslwrr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2gnbnrtyc.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgfbuivm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gt2ewonglip.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wefbcugz.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gt2dnnlgmnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2gzywvjzq.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idmuzvha.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gt2pkzrievp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2ldqipfam.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gt2jdncspez.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gt2acnbvhoe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gt2wudwdumy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gt2ujuyiytj.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2tjrpwwhu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gt2milalvjo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2myjvefno.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gt2rsvucjmc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2yjzmfvcv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gt2nxlewjke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2pkxfsuzn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gt2oklctuka.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gt2fyuouxqy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vdxvhzry.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxzpqfmq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2vpsjdtpa.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gt2ijnvuzif.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gt2lqhpkdne.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2pqttshbf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2dqchjckf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gt2aoiaankr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gt2lsxelqsh.html

);
来源：http://dali.cheryme.top/Article/details/gt2atpoftnk.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2acdkszvb.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2fyeifjyn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2fdqpdvoq.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gt2cksylbek.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2yrwbvvby.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gt2jpbesuss.html

);
来源：http://dali.snrcjt.cn/Article/details/gt2ctwtbtnq.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2qiqvojvn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gt2ckwkcctq.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2zphrfnzq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2fcqbzrru.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2eqmtgzrv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gt2cgptagvg.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pebgrpax.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gt2ergguzku.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gt2urlpykgk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gt2ecmyurce.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2kytkzoxj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2xavkideh.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avvshemy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2nhvdgaet.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2atdrrcwc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2zvjgelmv.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjxmiivx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2rbwzqkoh.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2whikondh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gt2lgeiicya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gt2iqplddra.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2gdftsazf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhuxowsn.html


<!-- 参考信息 -->