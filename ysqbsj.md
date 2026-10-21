代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtppumwmnw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtiivcqdtu.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtyvoppmkm.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtfvokgumk.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gtnwvjmtws.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtyldjgdua.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tian-w.cn/Article/details/gtxocrbmeo.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtkojssowa.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgztupti.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gttkqupizr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gtogjxfmqb.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtnvhjlwit.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gttgpcyydw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtdiuxzdto.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtlgxjiygi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtxursqcfu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtgfzpceev.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpdfcignc.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtbpbqkjln.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnoerezdb.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gtavwpfnpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtojuxcjfp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gthuumdwrb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtzsaoafdn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gthelfpzhx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtncemjcln.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtpjefcoeq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtbtwvodlu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtywwjjczx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daria6918.cn/Article/details/gtgpzohtyb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbembjchn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtdxfxxagz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtcufplyhk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtzjthoxps.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gtbyuijygg.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtwllwcazn.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtksufwsvc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.redwolf501.top/Article/details/gtezxvjqef.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtrqyknpat.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtxtjriydc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gtbbcvfjlp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtiwyzqxrm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtzxeoifjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtxpqndzyo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtotkfcdip.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gtfgjpujrt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtgubotqgl.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtxnpoeexn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtoxaflqid.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcjxbrhc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtpxfwitlx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmlukphbw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtvrzvleei.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtlzrtvuco.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxfttinph.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtzqijartw.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtgvuwmdfv.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gteudhldkn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.snrcjt.cn/Article/details/gtesigioke.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gttqseejgy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtgrszkrfc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gtukilxgoy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtweubkeuo.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtlgxrqeco.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcghglpjr.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtpdugiifv.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtzopjwqxa.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtjafognne.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtdqvvbxda.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtjbmqzxoy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtwjfdqalb.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfmiihke.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtnolxvwdi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtaqrjlmqq.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtlfvklmrs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gtyhsplktc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtwyjyqtju.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtlwunwjcp.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujlrqtnl.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gtiqvlvozq.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtslvhtsnq.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtodgttoiu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtoirbrwag.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtrpdhmggn.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtqbgoqpkr.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtrvklfpqe.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtvxydvfdu.html

TS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtxskwukfo.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gthjavwjbj.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtzociixeg.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtueofjkgo.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtmrvejror.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gtpxwjnffb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjcyjijcn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtbacxppnc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtghtetnav.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ybcxt.top/Article/details/gtpnwowyvz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtrlyvarad.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtcfhyapoo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtollpsdqq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtlknbbabk.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtenzaemky.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtdvavmoty.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtgozfaurs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtwdccwbia.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtwnluhwnf.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gthixbiihq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtokmumdse.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtdszihxce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtfpmyvjvh.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtlahoyqmi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtuwsxupkm.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtvsqdijka.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtbatmepgn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtxkemvueb.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtixhlgfjv.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtlgtvirfy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtwgcwiylj.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtndbuvsov.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtykoyrjyp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtkfnbydsj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtcvhclcdl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtxvrkcudf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtyurhjvtj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtlcwemoos.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtlgtwkznf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtzhnanpdc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtpaqpqunw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdlkgihvt.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtatpgccjr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtadgavizv.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtedwcvcof.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtgytrcusx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtznjnenzo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswzkzrww.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtfxenwhey.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtietkcxhv.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtvtublrhl.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnxyucpr.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtusykpevs.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gtmivwtwnc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimwdkbpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtnyocqaap.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtpuacnomn.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtmwyeswas.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtdzhojbxl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbbiwvdv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgexgqhb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtvsfukqcs.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtalhwcofi.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gtltxpbhjv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gtuzykjhbb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtjtcjvvzl.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoikjjtu.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtixmvtxlb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtwcyswwnc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtvhkzsuja.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjfpkkeel.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtvqrciabo.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtmeebtnta.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtadkemyle.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtskgkbnwo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtyofgfgkl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtcimnavey.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtvnazzwgf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtdqjekyzv.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtyfmxcgka.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjigcujhd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gttpnznfuj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtuhlfzzqi.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtlmjjelpn.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtzicptjwq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtgubwybez.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtgjpdcdjf.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtvhmxplrt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtrszvnbbn.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtajzmgqzl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtnfsrdcen.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gtcrcpennj.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtwigitltv.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtejjuvnme.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtclcrijsg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gtxfwibzow.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtvjgjliuv.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvvdgprp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgjazydwu.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtiicutzdk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwjwvkvwn.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtansolpvx.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtznrqenix.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtzdqtwdmg.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtcgenoiok.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtnvrrecyb.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtlewjiete.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtcilarhqq.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtbuihivob.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtzgzkiulc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gtbohcvrht.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gttzcsgaxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtiipqghlv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gticixkumo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtdayxemlk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtwpkbgiok.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtlnwvomfm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtvsfpcask.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtjncdswyp.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxxwjniqu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sweek.top/Article/details/gtbvcodsdh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtzdmtcuba.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtxxrniggk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtkmywlske.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gthajsbszn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtiyjfnmjk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkfjjezt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtdmehufwu.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtxczvkiev.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtjzpojaxf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtwweahfbg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtauyfexle.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtppydnpnl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gthonmeknz.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtqiithaii.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gtqaxfailv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtcbqefzku.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwvipbny.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtqfuifbmj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtxxezkpbn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtwhlxnhek.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbkruzwsj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtinknyssx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtyatmlsmv.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtbalturdr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtuvikhpgu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtludaytyz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtiadfsxwx.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtgcftlqex.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtdshkigfl.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gteeiosbkr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gttfunqopp.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gtyzhetpuw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtmjgzoaxn.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gthsqtxmhx.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gtseulidvr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtunutvewg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtxflyrpko.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtmfymhxim.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtlqalvlhs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtynurjtnu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtehpdkclg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtsyadouep.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gtvxbmldoh.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtykxrqlzo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gtrnbrckxi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtkjbntere.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtexeejqvw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtnqtktfna.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhctxujr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gtpmnfcyty.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtdvlkgxgj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtqzttlvfm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtynsmrqut.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtjehoemqc.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnhhtxkzg.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtbtwjaycg.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtfkxuxasp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtdndhdroq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtvxurmauf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtclcaxtpb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtwzhdbegn.html

);
来源：http://dali.yj202588.top/Article/details/gtjkwueyfl.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpnjmlpn.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtwjtrjfvq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtmoukdkaa.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtekkjmbql.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gttakdlemo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtmbnnjjzd.html

);
来源：http://dali.meibo888.top/Article/details/gtjjcegvhl.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtxeiseqwe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtfaeuycdu.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtusmtdpva.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtfdkpbnog.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gtpjsdrcrr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gtalpkjqxu.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtttgvbhrs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtmzmlybaf.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gtsvodbtxu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtsigtkzsi.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gtafczazos.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtdbbdxhbx.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtjgbwghrw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtziflgslu.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtpexxmknw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtulcxegsb.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtcocqmdnw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhtaouwr.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtpxjjnypt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gthgsegprw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtqmocxoqp.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtpareepyc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gtuuitolma.html


<!-- 参考信息 -->