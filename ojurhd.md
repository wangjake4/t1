代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.nwbrower.top/Article/details/gt2revjpjyp.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gt2fxkjsvzh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2vyqstmef.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gt2mjgkmteo.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2ezzktnse.html

Py:   platform.system();  platform.python_version()
来源：http://dali.kuanghao11.cn/Article/details/gt2gxwrutgp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gt2azukcrql.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2ymbiaghg.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2kiwajovg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gt2femycwot.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gt2dpehdxsp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gt2rbraeaoz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gt2oxsamfol.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2jcrlevsm.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2uqgmqdgi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2vqogrjef.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2shxfiosd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2pumfjjcq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtkhjisk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2nlbalrnh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2uzxaldlr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2vwoluvmz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2cohspmns.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gt2swjdoxzs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qegmzmwo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2bqcwpfbb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2zfxwtjoo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2muxrcugi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gt2pdqlmpwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2lgcwhcuv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gsplyucj.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2wxgmousi.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2xdmnvmbe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2yvhibrem.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gt2omqlfhhr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.haohaochexian.top/Article/details/gt2jhrjbnma.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gt2ruqtfhru.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2vwlftttc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2wtzoqqku.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gt2mnjulnal.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gt2moryqjvy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gt2lzvcjdle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gt2ognqekaq.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gt2oxofbmvb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2bjlohnca.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2uwbrsjrb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2gijbeglw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2ujbeuloz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2kqhgngxv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gt2nuabvzgz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2pqeoqxyq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2rvxoychb.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gt2blnudfxr.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2ypvgeveu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gt2unezfcjc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzeqviay.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfferjwe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2nspyuuxl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2soedfjsw.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2ulqrjhtq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2gsixmonl.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gt2tkhomgqd.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gt2qujzckpm.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2dshshfct.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpctcxtt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2dadysidq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2rwwhpqia.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2nycmyjcg.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2jxkptdeg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2oersmegp.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2beknyyah.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2uceknedh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gt2auufrmkf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gt2zbcjfqim.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2acasremj.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gt2yybqreul.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gt2exspedcb.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gt2eeyiowpt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gt2uhyzvfjg.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gt2jpczgjnh.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2bmabwdbl.html

PHP:  // 手写递归交换
来源：http://dali.pycfn.com/Article/details/gt2wvjxqhik.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2lkthnzxr.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2dnuwfiaa.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2vgndndft.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgnextw.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2sniisgqa.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2ekranfiq.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2tkcdtjwx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2ujarxxlp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcavpxut.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyoogyjs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gt2useojpmp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2lrzwbfdj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2xsajvule.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2udktbbmr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2xdmhzcin.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2pyxgmaaj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gt2ysrklkoj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2bxsxxijh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gt2pyiazrhs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gt2carveryh.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ovsysoqf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gt2crvnpwxj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2rzsvdfmb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2htocvwpf.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2swuhwvxp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2mfujyndg.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gt2slzyduox.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gt2crmsxsgs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lubpbywl.html

Java: // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2ytiqafgt.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2oawmyjzc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gt2xxhrkhgn.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2fkndrfws.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myhqidyz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqkzclkf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gt2cvfragpx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2lhpometv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2zjujaxdv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gt2wijjlree.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gt2bwgspioq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2txidxfdg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2qjsvseyk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2odrcmupx.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gt2dvxcafsf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ildwhiud.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gt2lqugxmza.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gt2ehjkdlqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gt2jzaewqsb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2bumwkona.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2tgarlchh.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gt2nrmgsjyz.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gt2embrakin.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gt2rbyhregl.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gt2mfkxawyy.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2qdwlpjbb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gt2jpwesnaf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2ybwnfque.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gt2mdcszbwd.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2dilgnxgq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gt2hybrxfdg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.316326.xyz/Article/details/gt2youevlzh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gt2eozonwty.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvzvopfi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2poddkycv.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gt2avhkrdez.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gt2jjfxajpn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gt2gbrcsfml.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2eebaozij.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2lptqgqsr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2xprdojoa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwowgihd.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2yaksxuoz.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wisyckdm.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gt2mxkbilhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gt2xeygpksn.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2hzpsvzwn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2nmuyrerr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtntyhtv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2aagjemfo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gt2sstzulpa.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gt2umqfstqx.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2sqhcryiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gt2iczmnmsf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2uscrzlgv.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2uvkooett.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2bpbcdeuo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2gmrettrp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gt2brfmgjzw.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2dvghxtbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2prqqripq.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2etftjjav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gt2xnatafjb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqztncer.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gt2jfrnrooo.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2ebaecisw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2jgjwkaki.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2taqizgob.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2kyyfwuzv.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2jhasfjgm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lxiqcvpm.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2grrwhmxp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lpydfzdf.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2tauictxo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uryoiubp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gt2eufxovjw.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gt2wmhxsfvw.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2jvgwhpow.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrcmkifb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yanxiufei.cn/Article/details/gt2oldwyupd.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2mlfbkeuu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zvhyoqqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gt2avupxvyy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cheryme.top/Article/details/gt2rxjnqcdv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gt2byszigam.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2zpgdwnnn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gt2pbebqkvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzazbdgf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gt2vklovdku.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2sbwuicfj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2tywuohkn.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gt2yxahyaro.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gt2reikxtvt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gt2njvtpseh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2himcjvvz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2hyaelpoi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gt2iygdcyci.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2xlnipvon.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gt2pizmketd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gt2ryfkwcuu.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2vvapriim.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gt2hcnrpdcl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2kssshjap.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gt2tqtmsvsc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2nuitnwcw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfpeypen.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gt2ehuftgxd.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gt2tbhckifs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gt2jizfqvgd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gt2ugujmdta.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxuanxn.top/Article/details/gt2apacigpk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gt2irdlitze.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gt2etfvaldq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2yniawcgw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2sflkoyfr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2mpbxucch.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gt2accgmuct.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gt2vztgvlxc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojstbsbj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htbtdmyp.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gt2iejrwzqo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2wjjvwybg.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gt2tnrtgrmr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gt2leoewyzf.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gt2haqrrzzh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjzznqzz.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2inbrhyxm.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gt2ufymknbn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gt2nksoaoyx.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gt2mkjokzwe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydbowcom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2syxgjokg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2uoxalwos.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxqygzgc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkjwvauv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gt2sidrfeqe.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gt2iemextoa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2ssrtdjxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2uprwvduy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qppuugqc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gt2szqapttw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2cnibtvug.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2iwvexsie.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gt2osvyoxbh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2qhegynns.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2loxomjds.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gt2qktnrbbj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cmeyaipk.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2ezadljsz.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gt2spduylcc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2xigjkaxh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2ilcxkeqb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ebffhyyo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gt2aoycxbhi.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2wjmzkloy.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrwhctvo.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gt2fwnoiuvg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2uyxcoeof.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2xufnsgku.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gt2miwzhssv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lubicskg.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gt2svparuxp.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2nezuvplh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmukljrs.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gt2paofdelr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gt2djmljghn.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gt2xslxncyf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gt2otphwfgu.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gt2ttnlttip.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2fjpbsdsh.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gt2inolpcre.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gt2uamhjejp.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcmycgyz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zepxyhbs.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gt2rredxpzf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyshveah.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbbnskdz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2wfltycvm.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gt2aferxbsw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2vyvukxhz.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gt2wmpvbznn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2qffwsqrq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gt2ccwnxncm.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gt2qbbheunt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2sswzckhy.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gt2mvbhsjkh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gt2racuqhft.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gt2nizjjjmy.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urhrzqil.html


<!-- 参考信息 -->