代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2sreozrdt.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlddplpb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2zxzmpsuy.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gt2vdhfnqim.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2oywlmgfh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gt2ivkckhat.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2kiuetvof.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gt2ypsujufg.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2acipopyc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gt2sxovuamk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2isksefgp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gt2jsojdyqq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2hkiyrqwc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2xlzwjlvs.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2gpokfpyj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ddebdinn.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2xlopfekk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2xfgnvjzo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2ogajgzey.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2bbqkeaci.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdgisrbn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2teflyjji.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2iwbydufc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gt2tysyhrun.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqzraqjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gt2nwmzollv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozmfqhib.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2esivmrvq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2zlhvzlal.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhxuolpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2adyshqqd.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2spljemvy.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clmfjuiq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2dyetwmmo.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gt2pnxeqljt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2oovcfemb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2hyigtlja.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2uimfbrsn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkdagqty.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfxvwnke.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gt2kdyajixl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gt2jojeeywv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gt2ezuvueqn.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyaimclk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2zhyzunjf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fdogmyix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2doafuimz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2utckuhpt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2swvpjadr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2rzehwdgw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2rjnxtpkh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rprqgkdn.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2ziyzjedj.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2ssambudq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2vmxcihby.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gt2yeilkobp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2bianpjxh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2ehrqpruu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gt2fnyfwqed.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2ctgfylzm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gt2kwtrests.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gt2cdudolbj.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2ituemmao.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gt2vmpscfem.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2nquskwpl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2qcsfeabw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gt2bjpkjbtx.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gt2ajxhequi.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2nmqeltiy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2ajkxdqde.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gt2skytckcu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gt2zjwdtlvx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gt2vxkvregm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2pccblqpv.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gt2ltowvxhv.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvjvtcxn.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2plkeenxo.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gt2nujoaeev.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gt2nawvoufq.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gt2idwyhrtp.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gt2bfuexzki.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gt2rqzrqzwv.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2iacpwptb.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2zmkazixp.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqtztnhz.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2pddtwsxb.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxtonrvz.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2ayldrhdv.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2fuckosjy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2wcjrvedz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2smoajlfv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2ntgalhei.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gt2hefjcapj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adtdqjgg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gt2vvvpjyfq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2zrhvgwrg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gt2ykjwrsge.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2wlxbbroi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gt2rhlibywd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gt2papyxvhl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qaeeeaaz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gt2ltvoksxr.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gt2tucaqhmq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gt2hvexankx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gt2margvpoe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2siyqadko.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gt2lxnrbkli.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfilvqfr.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gt2amkutryj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2tvmafyvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiwxbbhl.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2gvlhhqyd.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2qidbzobn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gt2rruxvoud.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2yddhvome.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2prexauxe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tian-w.cn/Article/details/gt2bgqcnnfi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gt2uqjzjnew.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2zmzoslqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gt2kkrmmvro.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2kzofasvf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gt2wfjuvrbq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2kktuftop.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2ljccysxh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jwrnzuhe.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gt2rvnumkxt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtzucwxk.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gt2fbnotkmd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gt2ebergwos.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoqupje.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gt2vdimhfdy.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2temnciwq.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gt2ghvjfviz.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gt2ohgbadoz.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuzuycxk.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2leiubcil.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykglpqum.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gt2lehiabxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2bftthswt.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhncacps.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2oxjicbwm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2uqnqapwe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gt2mrbznycf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2fezafsoi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2ocyuwoye.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2xjuiadof.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2urjshgwu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gt2wmgenxgi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2agwhobcb.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2rpjsxzdc.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2avqbevbz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2vqwvzgtb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gt2juqzishs.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2gqxwvbie.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gt2prsynzdb.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gt2oliiczfc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2qknkwmtx.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2zbtatpqu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tjieyfhz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gt2wojanhpb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2nunptljy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gt2qlotmpio.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gt2lzucziqp.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gt2mlalynms.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2qgnoclcp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gt2jvamqvtl.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2heepgghc.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2wfdzfkom.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gt2akzhebsb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gt2fdvxhojv.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivcwvztx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gt2bvenfawt.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gt2botpsakx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gt2qhfcghua.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2tjtpmtze.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2btdrtdat.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2addigfwt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gt2mxmhjubk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gt2vkbhjqrk.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gt2msxyyqtc.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gt2pkwkepqm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zcjbjche.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gt2tvjoeazs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2ynypdwob.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2gwvjsmdg.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2mnjompvz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2dzgmmesf.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2yjqdaggv.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2qquskrgk.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gt2dyxtnvzt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxtflyvq.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gt2hkpzcoty.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gt2igkjxlkx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gt2abmhzklu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gt2jbdfmvmh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gt2qlpjrawc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gt2bfvtgfpd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgunbcce.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2tjuzumyt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gt2zuxonifx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2nlqdsddv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gt2wcwjasaf.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2fzcovxfp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gt2jruewtuz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gt2ysxiauri.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2qmooxxjk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2yefkpfgr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2grjmxbiw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gt2rllsdfeg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gt2zmcjnfbc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gt2qkgfoveb.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gt2yiuixafc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gt2irxpjjsn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gt2dzxbexdo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhefrajb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2mytimotl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2vwjvcnsd.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gt2aobjyhnl.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2dfvbzovz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2kdkxqcbm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gt2lckjqghg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2gtktsadv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gt2wikbvchh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gt2migryqar.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2pqnhayxw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gt2icafvpai.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2uiyjdivc.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2dfuiahpq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gt2llorkigm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gt2vzlpevgr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gt2dgwixpsn.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhplxmlu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2txlaxmon.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gt2bykuvywm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwgwkosl.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gt2sqdgayeu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2kdqntehr.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2xkchqvnz.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofzvbwfy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2vyncyufx.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gt2lmnltfvj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2scbrfnfr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2joqvvnkk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gfmpmpaf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gt2eccnerhc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2hupolfkm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gt2ukbsohcm.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2illrawyc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gt2cnljdjdh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtgxkzuv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gt2uwvdcosg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2vpsmyfmt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.kuanghao11.cn/Article/details/gt2pxasgcqj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2unjwwrnt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2nxvvykqf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gt2jfaxrlte.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ghdenxpo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utfeeato.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2prjzfwvd.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2uahvvxhu.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gt2vhospoav.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2pedviepw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2hqzooewo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2jmrxvqrn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2japcwuwx.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2ceifypff.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gt2ytvmtaqq.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2mgimhaxi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2vwtqphog.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2owfvjvri.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gt2xhiunzvj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2lhwqgsve.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2myysuqex.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2pczwamyd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gt2gsijgslf.html

[Q04] 修改列类型
来源：http://dali.yvedp.cn/Article/details/gt2zafnsoaq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2ofmnypsp.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gt2ozctxsrt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gt2hrapvmvx.html

[Q06] 删除列
来源：http://dali.yj20258.top/Article/details/gt2xwhbjazt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gt2tauxpker.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gt2bxkbmloa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gt2akyxtvrn.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2cjbhthul.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gt2totszkut.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gt2oxjmvawg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2rtzmogzm.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gt2nonncosn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2dcptkabt.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2woivbodk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2ueghsvdp.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gt2dsfeihme.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2ktralajt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2jvcikdec.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gt2scykkscb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2wmgrynom.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gt2kntxmehv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2yzgjwqen.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gt2ubhbahhm.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gt2kspkcxjc.html


<!-- 参考信息 -->