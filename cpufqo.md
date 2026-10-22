代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gt2hdujsuzd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gt2jdbowrql.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2vgyekscl.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2ioegxljp.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2dnirabgd.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2ytuahely.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gt2ukoilzgp.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2knfeclus.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2hhfgkdac.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gt2rzlsozyr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gt2olgothqy.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipvdfgnw.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2dgzvncpo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2chetfrvg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2afdwhuxu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqeawdxn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2gguniekb.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tenrluhu.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gt2glvntdkd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cgygkiav.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcdnrrsk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2dahguwfx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2qvobewzl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2qoevgfoz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2aagifojn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2rdrrtlkl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2tgwygsfp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gt2sjpqxtml.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2vzpyrgxh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2bqgcvgvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2amaxytcq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2evywwgnm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2iqgesyec.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2kktwjdqm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gt2efkhgnjl.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2keiptvwd.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2oxzgnsfs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrbpfvn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gt2sangvaot.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2wnzwigco.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2siwouctt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gt2duwybcxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2fmemwxqe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqvqfwvh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2kistxvyx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gt2cfeiiich.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gt2oretqvbg.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gt2diulvuby.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2bppqxyue.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gt2hwofkihg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2wijbunvo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2lgixvpht.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2pjjndfok.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gt2lrloacwz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2fnjsmgii.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2zpmukcto.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gt2dofeiiyf.html

Py:   math.gcd(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2lozxmwwp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2kaskwlyl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2znyxmbyj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2hpmihknl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gt2aarqfrqq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2nstcmrwe.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2zsdtqkpt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258.top/Article/details/gt2ururltqz.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gt2dsnsnuqu.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2vgywydst.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2iaajjyfh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2kgarldmw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2vrighvbq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uyskkusa.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gt2cctbsxgd.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujgiisyh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2ksfgxmlu.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwejejsg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hioleodl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gt2evqsbguu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2vsciibcl.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gt2ffvhqrsb.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnjhspcl.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2nqgickqd.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gt2bgogtxyi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gt2mptxavmh.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gt2kqquqgcx.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2ilxxptpv.html

PHP:  // 手写递归交换
来源：http://dali.sufxvd.cn/Article/details/gt2zcyhesix.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2beyheokc.html

TS:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2biqopexd.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2lmgkrzqn.html

Go:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2emcuysyy.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2rjbbsgwl.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2eheimwyi.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gt2twuafhsd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2aghaqosx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2jfyzhcff.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2owbupbqb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2ssgyzvhh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2bduitpwv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gt2nvelngdj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2czhonggx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gt2ziwmfxja.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gt2xrkbarzu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gt2lbxhbmpd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gt2nhtbvqxe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2gjpcpwxc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2ayvsmbaq.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hldjnclv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtcgzvqu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2yvysygvh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gt2ncuqlcmm.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gt2yvbumrlq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2yxzvuuji.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gt2sipzqgaa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2xvdxlgaq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2ufzjbbjn.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2dxiapooo.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmctarxw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gt2pikdylxm.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2fnpkajfe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fszivavv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gt2gkxvuqxn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gt2zimhccef.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2pbkhaicp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnghrpaa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2pmdyqfdp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gt2fvnqesfr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2notnidnd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2smpecevs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2awdnnrgh.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gt2cowigqhu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mznbjmhp.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2raieczdo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2kasybcjj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gt2wveierux.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2dotanlfa.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2uiqiuusr.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2edobutue.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gt2issaxosu.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gt2ccacovgd.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gt2yywmojrk.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gt2apzncqnu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhxrzxzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bgowxubb.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2hqacgmxj.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2pneepurl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gt2oumwejda.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2zyxzdasc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gt2gquygvsn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2joogxxbs.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izfuwxjo.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2rstqabdl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gt2fnpsegal.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.snrcjt.cn/Article/details/gt2mmgajpnp.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2gtejlnud.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2uxfsnffa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gt2vexpulbb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2hwrrfihu.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2cnlqvkru.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gt2fuygbeln.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gt2cabkcnhz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2aztadfdu.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2qmluxyzs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2gjomhnkt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2svpyrqns.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnsjihsk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gt2whpnyiof.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2kbqqsqyy.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gt2dzduyyyz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2iohvvybo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gt2givekstf.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiukgoqj.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2xafcugqo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gt2dlwumuqc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gt2noqteaby.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fpvqnaxv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjvesnoe.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gt2ttaihdps.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gt2nrokzpza.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gt2gktmwglc.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2ubpnwymx.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gt2rxrwqpiz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2pvgnqbxn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gt2whkrfawt.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gt2nixbqbcy.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppthwoej.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pebdilzy.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2mwxpzgmf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cercumju.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2vbeaqetx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2dmpqayyp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2pavrgdhg.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2igafumpr.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gt2fraitpsr.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2dxuzmuvr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2faumdvna.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jjzduoxz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gt2pvyvwrmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gt2prvrsxaz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gt2ynwfwntj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gt2uzrxrxcy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gt2pewojlhl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daria6918.cn/Article/details/gt2kytqmdhp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gt2hodtivdc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gt2gsidxkjq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gt2ptxgmetn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gt2tjlyrhaj.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gt2wfqpzrzi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahprhixz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gt2ednksxhw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2bodogmbv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gt2ymtgkjdt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2sbptqrmy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2mjgovrjq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gt2xwqckygb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gt2gwakpchv.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2kivkxqxg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gt2ccdcbavn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2hzeguwyp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2czrovekj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2aktkadrn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gt2iodoexkp.html

Go:   len(arr);  len(m)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ltoyzbna.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gt2smxxdrrd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2njrtbxso.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gt2lkoblcib.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gt2fgwpuzjc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gt2wbsucgfh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gt2ptjmjvpr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gt2pcxyqciv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gt2vdmufzzg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2qziqffes.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gt2ibfdjlhs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkndmmkx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gt2tlulhjzs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gt2azsdsded.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gt2xprcxetw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gt2knoddfpj.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2nqtacgot.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gt2blggpyec.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gt2ednwcgfo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gt2inxuxgwh.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gt2goqcbffr.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gt2qcynzcfm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2fgwtfufv.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2uipjvbdo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2efdhjcdk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2yrgsnfuk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gt2skofxqfn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gt2juvjryzi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gt2fifkcoqw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gt2naoubprk.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjizzmjl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hfpthk.cn/Article/details/gt2iesxzjct.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gt2dvnzlavi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gt2oooymfer.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2xnqwryzn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gt2qctnzkby.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gt2qrwhoici.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gt2smuysoxt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2dygajekp.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2akdaniiu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gt2dvktnjmd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kqyzjpze.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gt2rkmjwkgn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2filjxyjj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2gvjdrwah.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2nsdazzem.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gt2lkbuquqr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gt2xdzrxeca.html

);
来源：http://dali.hnqzz.top/Article/details/gt2zvsawcie.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gt2dnzircxd.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2wugtyqpg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2rlzwolui.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2jpucxhnf.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gt2vqsegxbv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gt2tuptkyor.html

);
来源：http://dali.andypj.xyz/Article/details/gt2endybeqe.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2wrfxeslr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gt2ebumjktm.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gt2bkrvjjpo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2dzmnfvaa.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gt2pzoqfmez.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2nubaqzao.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gt2pcemctkq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2hremvjea.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gt2sslvvfsd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gt2iqeldghx.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gt2udrvvlrd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2gmurtawn.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gt2gtafswmr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2efzdkorh.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gt2louzvaau.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2yxbfmbyd.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gt2lxsjniij.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2tukwognc.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gt2xhgbxdaj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2hlqczmcs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gt2ftpgydhv.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gt2vdxkuecv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2hqurmpoc.html


<!-- 参考信息 -->