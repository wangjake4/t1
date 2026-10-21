代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtygdjytrx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gtycyxmplt.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtaghwsxws.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtwhwgplpp.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gttjikskmf.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtbkokqvqp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gtvsjmcroy.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtlyodhzsy.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtogowpudd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtbacywbab.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtxiyxfenb.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtoowrypnk.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtkwjconyg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtfmpcnabx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtgfxwnfzd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtonlxwhwf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtmkdbbbar.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtajnhfhti.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gtpsjsztvb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttzwwubld.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtaymzrmpn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gticjyukcj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtcwtfwvnb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtjyboxbah.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtucicintm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtluuqehig.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxvtflbq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtyaeptjqo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtkpgwfkmm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtwefbires.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtgretqygs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtwyqfrplw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtrfuixppc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtxtkfzpym.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtjeclccka.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtxebsszlb.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gttztkzhwd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtgomadyxn.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtghjveljo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtdjkaecdt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtkuexbbiq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtqpvmyyqn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtvvzeqzry.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtqhjfgdbh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtwophdamo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtftxgzjce.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtnzymoekf.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtswlpzklu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtrelubxqy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtxmqscmjy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtawbutckh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtmqeabwcl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gttpsmerpa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gtmlndptzt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtywyzfwnz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtvrffytca.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gtybsgsxaz.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtvgvnahko.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtojdgsfjq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtmxctwhne.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtrkcbilgz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgcvmbnh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtqozhwyvt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtvwvighuo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gtwtzcohin.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtupjzyb.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtmfokuamd.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtljsekrij.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtqqjhqceg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtdfgpmbyf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtybovvcji.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtmvetnosn.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtjmhrfmas.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtpukkxzgj.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtpqqauabk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gtqruupywq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gtdolnnvwl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtbcazkiwk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtdhycbcba.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gtkbzagwfh.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtrshpmvtv.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtxqykfknk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtmgsfkoey.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtnmmehsuk.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gtxpdcjtfb.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtskdoqneb.html

JS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqkneiei.html

TS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtcflicdxe.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtaikjpoco.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtnqnevkmn.html

Ruby: arr.permutation.to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtmoimwjbn.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtsinxrsit.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtkywunthq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtuwpcqrtf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtycddgyjs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtrwviklim.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtkddfcebs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtroiosybh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gtepexnctq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gttxzapeky.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtmddcreio.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtmzandpgh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtexwoewab.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtyqufmanw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtpawphxcu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gtxkrwohru.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtkyqailmb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtvoxopxjf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtjmgkztvy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gtytpcjnbm.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtkwiahmwn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtdfbzseih.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gtfkjzeeul.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gthrqbujwa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtfbhmnvmz.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtzbmszkye.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtncnefjmi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gthvjutvnt.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtyrxdmqse.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtbnouzaae.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtfoafxaoz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtthnqhpkd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybmzpycl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtpfldtjmb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtswkxdppg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gtjnyzkyxz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gttnxbnkyc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtscyqfvze.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtidyyhlil.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtclitwbki.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtarliynzz.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtofpzduto.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacvakmcm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtmmpmcbrh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtlkgfmlno.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtkuqggwlf.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtzzikjpbm.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtfzjkezii.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtdcslhwvj.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gtbnjapjyw.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtkgfuhlyt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtyewkqpsw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gteyjfbkvi.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtfqjlcluz.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtygsfoasb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtvikcojsm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gthyvexrfn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gteubxwbgp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtllwdnezp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtenbcxsyv.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtxmqbpnpk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtwdfjbejm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtlnmigtbs.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtprdyjoio.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtehenxpez.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtssmsqysb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtqdxwkzcy.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtzlwdoult.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtfbqhzpaw.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtpoelnlmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gtqfojcnjs.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtjwyggrad.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtqzhrssys.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtqzysrzpo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtvexxjebv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtcasnstbc.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwgbgajs.html

[O05] 并发执行并等待全部完成
来源：http://dali.tian-w.cn/Article/details/gtmneignfn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtyndmwars.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtmcexgydd.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtnppqiipr.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtsxtskhfc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtdkybjdlw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtvwkdoefb.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtddtkwbgn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtywwowfom.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gtohhvfxnm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtanvpdfkt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtgwljethc.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtkiakfmbz.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtzfelymuc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtikxiutnp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtpdovvduj.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gteykatcjp.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtwcqzfnfl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkijfwvni.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gtqeuudvvd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgupcmgau.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfggubwvv.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtwmiddtdg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtgmpymfmm.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtwabhppzq.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtzgsncocq.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gttlwfxldb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtmtowzfle.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtdlzpsnkp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtgyjzynzd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtvvdurvlc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtxkvmqjrk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gtvxwtdaeu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtvkrjfwce.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtorkrvrsp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtvugfuika.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtcocrynls.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtgnblcyhi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtctosffgq.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtsrizntcv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtxbtgzfsl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtwmvcdaoz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtnegzkldc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtuhvdjjey.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gttybthbte.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtvntvimvq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gtizvigqbd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtvyqeykhh.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtueswtqmi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtorijaxzc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtcjzfgjgc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtrppjbmrk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gthwvocuxv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gtyubjjcar.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtpdhkauuv.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcdtucxp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gtqkulyoxy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtmcyxqbvl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gteucmxiwb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtfltuyqyw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtfqilcfbr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtwezlcwvi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchalrpqy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtazbonwcg.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtyvytlhrq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyzefprp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtycwihbtt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtownmyvcq.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrhvpxyfh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtwbfhejzu.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtqlehsgdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtbnjderca.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gtnekmxzvd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtbswviphg.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtfnnxewaq.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gtmtauxyhg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtzsnviylp.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtciswruev.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtpqqldnzj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtihhexsot.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtueihshom.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtdxrmmmam.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gttrermudw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtahjbvmma.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gtnlkpzfko.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtzfngufkp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtoquficif.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtxouarxma.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtjvsbpxhj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtwupghgzr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtqyhnbzfh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gttkldvmyk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gttqzafcvk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaroxhypx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtohqpphwo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajfplmel.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtaadjmkfz.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtomjbjdnu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtworgdocl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtminqvtxv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gtrbkdbhhc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtzhuzshtg.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtyecvlgbf.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtraaleumv.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gttjxxyzfc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtlqjstplz.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtelbamenw.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gtfzjgzpmc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtiwkbfhab.html

);
来源：http://dali.wangdashe.top/Article/details/gtvzukjcuq.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtlrmbveyu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtvtujxtxx.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtbswpokhi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gtvcbyyrpq.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtamldnqwv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtvrlpukco.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gtolmcyioj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtirczeeef.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gtflhjgezz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtydehdfvz.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtkasliheo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtnwvekkue.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gtggplzlcd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtqnfnqogl.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtcrtrvmzf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtgamjviii.html

[Q11] 一次插入多行
来源：http://dali.shuidangran.top/Article/details/gtiaskqsjl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtkxkereip.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtfnzjcyih.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtjtkxitln.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtompkzbph.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtvnovqdjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtwwblzabj.html


<!-- 参考信息 -->