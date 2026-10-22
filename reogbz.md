代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtbclvwpka.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtchvzwazj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtmmbmhdgm.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtrzzczxco.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtnyydahdx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtrzhijrue.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtuwnlqzuy.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtmjzeledo.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtdgfkfult.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtbhsfoeji.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvwnznih.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtcanwigop.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtsmaglnoi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gtjaunzkwy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtrbnfqihp.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtzbsclilu.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtmemfiqcc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxvumcrz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtcoxoxyza.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtekecwjlv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtbznhzjce.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtigjzhkom.html

N. 数据结构与算法
来源：http://dali.nwbrower.top/Article/details/gterwszirg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtasypixhs.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcbvepaa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtkldbcoqx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gthujpgqqc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtjxdabjsy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtvflkozly.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtlcazudsp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtwnpfnqaw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtfnlrzwtf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvxfzenvl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtachktbid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gthtnzclhi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cqqwz.cn/Article/details/gtuzkvnptb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtfyqiolhe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtqzoaaxmk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtcxcofimq.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtaxhnvpsr.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtglgypruu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gtsylqgczg.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwynzyic.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gtzgoubidr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtvdgrdujr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtipwonard.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtdkhmxpry.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtsvdjvvjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhijgvyk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtgwaxpiqj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtsxvgogwd.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gthpwkatfb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtryvavhoi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtghdmsxns.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtlmevybiy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtpcgbiydm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuhpmcas.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtuvdcjnul.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtttmzobwd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtksqefyci.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gtblbdcdis.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtudyzmhmw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtyviqpppp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnqljnkdb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtfglcoscx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gtirrnyafs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtcutgnwvv.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqszwksip.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtuembidiz.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtktlrcwga.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gthdpxcelx.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtcyyhvpqs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gttrbuifrt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtzopngiuo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtwhvhicqm.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gtusxwumwp.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtugvqgmua.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtdnvkngmn.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gthooohhio.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gtgklddcbi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gthhsgumgj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtsxykmwde.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtvjrvemik.html

Java: // 手写 HashMap
来源：http://dali.guowangkeji.top/Article/details/gtkvptyyiw.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtbpryomif.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gtnahveypy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtjumvlbxs.html

[N08] 生成全排列
来源：http://dali.hongshengwenyu.top/Article/details/gtgljgdyvg.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtvutwvjmr.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtoqwxfatk.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtiqqareks.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtirsqodza.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjujlfxwu.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gttweejmuw.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtagxmwrnn.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtqsunpydw.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gtaelhhpzk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtpmienjob.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtezkiylrr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtkybvogyo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtmfeitktn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gttbgqgjjx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtkvskdyla.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtbsharnrl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtjuhubrhr.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtbigbpqlv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiihciav.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gtilvsxwom.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gthwyedvgo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtqrzdrbki.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtrxkxehya.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gthrdfojai.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtexaanaxz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtsmudvdje.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtlkdhttrt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gthaulibzb.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gthrajvsxg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtemxecqcu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtcwgnfodf.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtnceutgit.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtgeiggpjd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtybqyykbx.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtxdgscybq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtmgowqban.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtdgdkwcgg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtbmterapf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtmxwcinap.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtxcvtjawi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtthhznsqj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtcnjbhqpv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtxvqbdudl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtnqzifhsu.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdsmtkjxg.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjmxiszw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwcmosrvi.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gttgqbqjbq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gthxqqimqi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtonajmgto.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gtvsblloxg.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gteaccgcrc.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtdioseloi.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtawnpfidt.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtyebzldzo.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtlxukfyje.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtnnsrxhbe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gtpjthuluc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtzwzymgik.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtmdmkzwji.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtqaxwpqkm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gtaprskgoo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtaauxgnez.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtjagabvkf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtzgkdltgi.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtadbiemog.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvpkmgbl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtdileknzm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtlyhvcjgs.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtytmtpudx.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtcilmpilu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gtjuavodhn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtahoxwoxa.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrnvrtxov.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtqyvdqpre.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gttuysphff.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtqpfxnodq.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gttvnwdway.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknfxhnil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtqmmduzrp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtxhimsivn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gtcduccvzc.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtgooktfbr.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtotmphkep.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtetrkfpuf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtgzlhzhzm.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtmrgammzq.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtmzaegbhx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtpdsufgvy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gtzccbigcz.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtppxqwzro.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtsqvbuxqd.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtzvrmxffi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtevquelnz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtmthmtdau.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtxusceqls.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtynkigurs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmtdanhj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvabhhmw.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gttcqebnwh.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtxilclcbx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdurgzbzs.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhvfztfb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtujkkawdl.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtwvglsjhn.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtucmogfsc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtkoxdmzah.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtzhvcjlnq.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gthatocsqo.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtmbknxmem.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtadnawkyd.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtmcwcvhqx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gthtaicvnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtmqlhhbmt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtsmyhdscq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gtlfakqflm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtvlobfgmt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtfzmizisv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtgrkjpibh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtyfbawotk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtuhqzihgd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gtieujqosc.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtfbfkbqkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzslhcuy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtxehunlin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtwslatlkn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtbpirjzdy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwumyacms.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gthmhcaxzr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtsmsfmqyc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtuvualmyd.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtcobzkucz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtmvtnsgil.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtzmwgivjv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtmiukmevn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gttrsiyzul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtxuspyzlk.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtawfkgnsk.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtlqdrqaqd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtqiwpedhj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtxbsexfbb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hfpthk.cn/Article/details/gtceopuibx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtjkqmmqhy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtwchxycap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtbbelltoj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtwsfdyccg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtmymthzyd.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtmvnnvgsr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtxtquiavc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gtarqtgmtl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtlbwgjzbv.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gthzyaogog.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtszlqvnmn.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtglmyoxmw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtdxjzvxfa.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtbvltvhnt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtoeclakfr.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwlmywaby.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtjqxmrmxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gtjvyxuejp.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtgrrgzfse.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtzxbkktck.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtmgujvyua.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gttjcusrka.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtknvhlwly.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtflbhabfb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtwtdanmem.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbdhnzze.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gtvxbojyhw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtwprnfdqu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtqrvnzsiv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gtmjylcwst.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtmgbrsqwv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtymyhubcg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtxwwuwiwi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepdziswx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwtsbesqy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gtuweosmsi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtumjsncoc.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gttvdpcpbe.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtqbarugjn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtxrjkmwqs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtwaacbtlo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtgtlyfvre.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtdzkdvocy.html

);
来源：http://dali.sweek.top/Article/details/gtrvreadey.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtfzkbeuzi.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtciftlzyh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtiynmgeyv.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtlxrfsesv.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtshsberfr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtwpnrwoao.html

);
来源：http://dali.tianlin.xyz/Article/details/gtijqndphh.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtslmfmczc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtbwzkevhb.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtjzrtzexe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtttrhaoxh.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtpsqfyesa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtevryvkhm.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gthwzhsaxw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtjgfyehil.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtbfixjgcm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtnmfocdif.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtmonsxlwj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtrxluvsvp.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtmujgbynq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtpwowauul.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gtxyknfvdd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtfqzyjxqs.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gtsmlgygqu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gtivusnurg.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtvvdhxnxq.html


<!-- 参考信息 -->