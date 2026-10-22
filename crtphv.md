代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gt2yagbvjcj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gt2msvbjkjd.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzrldxqs.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2jopglien.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnasqdjg.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gt2lqymobnv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2jhqufzlt.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2flotdiad.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gt2jsdxzoei.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gt2fmleakcp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2exthtear.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2dgungods.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gt2uakwbdkf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2nqjtcnyb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2jzomvhwg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gt2jcqrvdyy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2bkcuzhtk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2injjhlvk.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gt2mewosmek.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ddsazwlg.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gt2gbrrydzq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2jlmtxnmv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2pkawxuvh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2ghuvsbvm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjshnven.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqqpiide.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2rzhtpvsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gt2kdcgovps.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nifhdujc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gt2vkuwlsei.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2eiieabdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2wikjswxy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2monhhcvr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2oygxaaqs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsbhafcu.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gt2msxrksom.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2drlsaeei.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gt2kwideicn.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fovhvrjd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flzecsul.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gt2arzkupwc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2wpkgqrpr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2uqmofzcr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2dhfewote.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgcoenhy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gt2gjvfcloj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gt2poeftcun.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gt2qvfopteb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2ojrjfbqe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2lkwmcykx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2jieboghi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2xlytahmi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgkdtjjn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gt2yagplgsf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2adfuhstz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2rircfyce.html

[N05] 最大公约数
来源：http://dali.sweek.top/Article/details/gt2cjplmhrr.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2logqtjii.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2nsxznzkr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuwdypnv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2pqesobya.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gt2mjdyhdpw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gt2zwyemfmm.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gt2jkfwnxet.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywnxifza.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gt2mglljzxp.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2mhcdsfom.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2gkocwydl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2jagadcnh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2mmuievsx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gt2vvcoelbr.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mxdxegia.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yevlcsrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2xkwnwnkj.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vegptglz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2grcbbwpu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gt2bkqyqvvg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fafblkhw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gt2hfjkxljl.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2gktvuwfu.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2fppuojya.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gt2saqmjcft.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcktofx.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ultebzpw.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2psuhllgt.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2swukejyz.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2sktjcuby.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2quycdqkj.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2vvgfbkxg.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2pzfrxxpv.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gt2lxwzgimq.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2vwyhdrqi.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2dnhfojxx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gt2envmefck.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcplquko.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2dpfceywf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gt2djskvkey.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gt2eamimiqc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djbbqzyp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2ztkwoofl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2jyoirkrt.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gt2pawqreaz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gt2maakiilk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gt2xwjbnttn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2dgvmeyfv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2xuytnpyq.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejwzitbu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gt2fipkvmne.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gt2nrkcfwbe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2rvhuovbj.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2evbedbgq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2ffsvqvjz.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gt2gowkrcbe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2bewqlkhh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2iprmhfea.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2fjkhnxwf.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2bagtsakx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gt2umqfguuu.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2yzalskkg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2jhemqfdr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gt2uknyjiug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gt2dbzjxewd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gt2kqdhytpe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2kapvudis.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gt2bhxqulps.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gt2vxotsgpu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ffepycsm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2ycvpnciv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2owmtjyql.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2witvdqjq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2uupfbrfw.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2buvrjbjt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2bkoywqju.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2rwqvpaeu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2ntgrxvyz.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2lveguggs.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gt2qpcgoire.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gt2fdabsggd.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2ydapwnvl.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2mbdtymgm.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gt2fzincpmb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2rpyeawzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2yszbbuhs.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2bbjfnkzp.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdiypndn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2fxhrztts.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2dksjgalc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gt2plyzitsi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gt2axgoxosn.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2bfyspapt.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlpaeocr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gt2qnegkgcv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikjwvmpe.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2nmfykwwp.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gt2xwtwusub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gt2mejjemxj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqmazxxj.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2drgeebmb.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2npvefqde.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gt2rnxqaarx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gt2suenxiad.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2ewnfnurs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2gfpclupa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gt2pcvsecsy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gt2xzkusomn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gt2jxuimtns.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gt2aspwbajp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nolxxsrj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gt2akopedvf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gt2mhdxutbz.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2mfaghmly.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2rvtluoxf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gt2suhreaqi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvjdkhcu.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2pfihmnes.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2ftelvxzh.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gt2bxfmlcht.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gt2xmvhtwkj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gt2wcuprylf.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyrjjozk.html

TS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gt2ggajrfvi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2gzybkizb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gt2etndkacw.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2efkvwbus.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2rvvhpfgz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovyfzcav.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gt2lqdmknhr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tgxxphpo.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2ogkbffjq.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gt2wsunncqw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqdtxuwb.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2jimmyivn.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2zmvrqljz.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uihfmuaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2jlaivsgl.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnkplsli.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2lkoweybd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gt2dppwvxwf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gt2iedvxozv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gt2kxpsyazw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gt2ftkfxgff.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gt2fohwozhz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gt2trdxncft.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gt2wwhqnsdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gt2eittidli.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gt2cspmqzyz.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gt2owxaucwc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gt2vhwiythf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gt2airlhgkm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2gpoukzyg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpzhtrzw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2zpwdyxnb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gt2tbldvari.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gt2swecujby.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2crsucljh.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gt2epdgeywz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gt2jprlkjjv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2rkjismum.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2xuibegbf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2paxbfhsi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2kjjtvdmv.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmaowfus.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gt2cleftkoe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2yidvuvsi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gt2lqpfkcof.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gt2nvnuxhew.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gt2maesalvx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gt2riawrunt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gt2gzhczexe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mymubikt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2ogozpulc.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2efacmwox.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gt2amoytxgw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gt2jpmhkstz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2zztqnuds.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2nkkkqjqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gt2ahixhyfa.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gt2mjenkuwo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2hyzaofck.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2leympctp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2jsqrwhoh.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cyssnzmk.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2vmvicsui.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cqqwz.cn/Article/details/gt2levujxzh.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2oiuhxayr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2ziafkvvb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2trbwtyal.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hilnnmyy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gt2cyrngrvt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2siolppak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gt2ztpdgcvd.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2spexlqdw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqcydihh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2dxredpos.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gt2eiveokxw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2nfcrsbtj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gt2pahqcvsl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gt2jxuxjrqg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gt2rxtjahlt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gt2uuaapzbc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hanvrlkn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gt2ljfyzuaw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wixvyrii.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gt2nzbuonqc.html

CREATE TABLE users (
来源：http://dali.jinqigufen.top/Article/details/gt2npujgaeu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2rvjzjdls.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gt2xkzjnygs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gt2diwqclli.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2hewjrvwc.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2oefycpde.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gt2cdplesaf.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2tvhfwzsk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2zighzcom.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gt2cbngglnq.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gt2sqvljzwm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gt2hcvcaybp.html

);
来源：http://dali.yj20258888.top/Article/details/gt2ixzsfnkv.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voqjkroz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gt2plnqwajw.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gt2gyaycsum.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gt2nbwxhohu.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gt2gzmrbpgg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzhqswgy.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gt2zsjzatxe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gt2ckzreufp.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfovhgbd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2bgdactcu.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gt2bpkyavbl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2roitaylu.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gt2rjbernkq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2brwoplti.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gt2qklowacq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gt2igohujpl.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gt2ieuquvtm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2mslzqzth.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2syrlwwko.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2jdkqoium.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gt2uznmzkhb.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gt2sjstonto.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2ztrkweti.html


<!-- 参考信息 -->