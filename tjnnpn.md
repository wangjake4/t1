代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgkkbfsz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtqfwynssn.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gttmjcqcor.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtbhtscbyw.html

Java: public static void main(String[] args)
来源：http://dali.ppjwa.cn/Article/details/gtgtsfyepp.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtxiaqybab.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtcyxdhjiz.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtvdgtulsx.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtumxaxbub.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtlgohcztz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gtpzhccdgb.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtxetouicp.html

TS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtgxueehcz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtmutiizvz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtmublwudl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtnuyxdoiz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gtxwhxngue.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoiwilmso.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtqazmyboe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlbzdttnq.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtexjzwpif.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtqijmjiqt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ivvv.top/Article/details/gtaemovfov.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtmlfwujqy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gteqpurlrb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtxmlrpagl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtrxefyeni.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtumieelwm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtmvmrsxue.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtbuxjqhws.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtxkzzikth.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtsyizvrez.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gthaizuokn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtcobupchc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gturglbihh.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gtzcfigjpv.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtokkooavl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtwsmcluol.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtjcpqtiyz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtaoalvcub.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gtdjsdztht.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtdshrwuyq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtuzunxhof.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtwxxqyaqq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtwaeiuqlt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gthitushzv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtzkrahpul.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtajvjjyhj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtreczqztp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtntkbrfgu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtjlpaazgs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtqjkxddiu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtrbxofnty.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtuwdmuojb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtnmfspsna.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtbomaybes.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtvddpqprj.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbfegyfz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtrywqwrgi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtuwoldjyy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtugufbikb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtwpudgfyo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gtgmurfehh.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtmoiynago.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtbeeuglvu.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtybeknrex.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtjesqukdv.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtxpynhiqk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gttyrdicxh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtpzbcfpaj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtdswdubcy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtctyznaym.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtpshxriyb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtwipcgikp.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtgozoqgqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtoymzuojp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtpvjtthig.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtyjhateqj.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtvowxuhpo.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gteybdsexr.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gteuvwjpdt.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtptzlbldt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtmnmglkhj.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtjkumgcfn.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gtmkvrefjl.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gtihuzltpc.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtnzuveqow.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtmhavnbbk.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtiqsmqzfd.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gthlcrmhzm.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtxhnnqhtc.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtfmlocmxp.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtpaiifjax.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtnbyrpqri.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtaqiqqart.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtmdplwttd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gtrjjqdpdy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtowkomemq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gtzwhvtxtm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtjxjbdxrp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqyxwtao.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtnffuxvah.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtzmccaloi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtxjuzdlcw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtqwbubrhj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtvvehgdfh.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtjtkkgxyv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gtgwmovjaz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtmcuanaqe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtmvnotjwg.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtmhefhqcy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtoswlfxia.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtxtgixzco.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtcslmunix.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtlsmkfqto.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtxnnurtmp.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtbgwvfknn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gtrnrijino.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtlvszeajx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtdwtgwxlu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtdwxmjmco.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtlzrafnaf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtbgazmlkn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtppwceurk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtbjzypcmb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gtstbvwxfu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtwgkyikyu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtchtisbls.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwhlcpvtk.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtksstbdrr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyhqlzwxq.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gtucgejhio.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtwocwyxsg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtrizmahan.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtdtzsyvrc.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtqxxnoour.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gtawsafdnd.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtmlpatjur.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gtqtuzmbpd.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtczlzmiws.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtvhxglcqq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtaywzzfyl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gttrdhphzl.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtgxzxtkvj.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtkjwhiyvh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtjgmprrmj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtsvgzzawb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtdvigdlhd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtsuydrgoo.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtqmnliizg.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndanoqfx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtivkcjbjl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtaarlazxl.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtxnobnxxv.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtlsyglhan.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gteudxnoxm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtyagcvwui.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtyciokjsb.html

[O04] 定义异步函数并等待
来源：http://dali.fengsongda.top/Article/details/gtxnuschzp.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gtampotjpk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtkrnuvoxf.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtvhxszbgq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtqffgvewh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecercacc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtpdwgqunl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtbhrkodmc.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtvjkbpmjx.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtjqreozvz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtcpjgyxzf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtgcetgwwb.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gttnvolsxf.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtvzqkpfvs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplzzgaio.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtuzegtkum.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtxesyvzfa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvgmxvyvp.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtjnsahxjl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gtmmcjgmvn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtpxdomdft.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtqqfruefm.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtibdeiffs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtxesngwwy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtvsruooyk.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtvbgcegol.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gtvffqwxxa.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdvnysgu.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtwkjfxofq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgwfwtmtd.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gtqmgbfxar.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gteojxjjaa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtrjqrlnee.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtiomffezw.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtmwkjrnmr.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtqwbrsene.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gttgqlxafp.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtfylkrpkb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gthzwwwheg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtmrssbcrq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtnmogyzgb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtmjpnuazl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtagwvrgsp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtdmajacst.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gteaaxztvf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtbyckheio.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gttkqloygp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gthbtwcvra.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtiywagitk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgufenzy.top/Article/details/gtevjwzxyl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtbqobtylk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtvfuhszoz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtxvartnam.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtrvnmngqx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtmrrtifpq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gtwynarhhm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtsfysdmpm.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtcvmhwhqq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtxoxfvgaz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtbmqyoeuf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtwamfxylr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtrjevnhdm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtbbknpxnn.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gtdegqpwpl.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtwufbheav.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsglmgkqp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtgcsipyrg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtoulplvxw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtobnulokc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gthakhqbbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gttyndglfu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gtinnariya.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtzrjptfpj.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtorltefru.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtvxhfzyem.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtcsaybapw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gtittwitnl.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrnrlwaht.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtonpdtutf.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtklnjodmv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gttjzayjii.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtpvavjyqh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtlbxtzwcf.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtngozcjoc.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtwlvjfsrb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtkggokmry.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtswutykrw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtgtrjxxyg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtprwjgpmm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzjzupwl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtyyfkhcnr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gtmxbvkuwo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258.top/Article/details/gtldpynapl.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtupnjrmio.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gttghzljbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtncbetdjd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gtcadenqjn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfsinpfb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtlnofoyla.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gthkvciqdt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gtfvobazrt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtfhoneyvs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthbviyoag.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtrbjdbmhb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtitoabhdx.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtdexrwvgu.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gtedecimpr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtriaairpx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtjxcehths.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtkxgnygua.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtlqxrvpge.html

);
来源：http://dali.tanke756.top/Article/details/gtedqyeced.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gtguzwkxdv.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtxnnnansm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtcuuteumu.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtelonduxe.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtujwtdcdc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtwgmqxobs.html

);
来源：http://dali.0kj1m.cn/Article/details/gtvsllqhqd.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gturxxgupk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtihqfiqnl.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtgqvlflrk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gthurnqsml.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtyegxzapj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtgrrplboj.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gtviyldeff.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtjvhfyipl.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gtmlrzrgqu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtpqouitrq.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtotychijr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtlwzjaulb.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtoflmnrud.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtnbjvpdin.html

[Q10] 插入单行
来源：http://dali.nwbrower.top/Article/details/gtyonqsfwa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtbaqbcvcx.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtwqrzlkzh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtqltweqho.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtegxzfenf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtjiwryyiu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gtfdipmali.html

[Q13] 忽略重复插入
来源：http://dali.chenjidiqi.icu/Article/details/gtvogjlrpv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaqilnbk.html


<!-- 参考信息 -->