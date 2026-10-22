代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gttpzkkblz.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtebfblfjs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtbhntnksw.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtehnijdoq.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gtnudwdygo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtvswgpjpy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gtlvhccuuw.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gthixmjnvr.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtlkwcdkad.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtcglscqmk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtsvecipyo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gtkrweyxbz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtfdtsqxxw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtvkoladka.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtjfcqprak.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteucggplu.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gtmketzrpa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtdjvlczgf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtesfldzkt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtqfftlncp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtudxfhmyt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtdwhkxdpy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtrumocvap.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmdgqiid.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgbxpbwn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtywvfizqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtuivirhzu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtdzlmqqtt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtkppcxyqx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtpuzlgrro.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gtrfbggebx.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxntgalcc.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtqeejyywz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtsfeyjtbt.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gtyapievke.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtyhbirvkv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaciacqkm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtfjjrxkne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtooxlqvlz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtccvzhbep.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtzrlmoqum.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtaakpmmoj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gtwnlvdhfi.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtcckckawc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtrndyumli.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtyaxdjqxy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtbncgjgvg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtksbbdlww.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtiwvcepnt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gtckodnyrt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtbgznqwnz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtzjjtfexr.html

[N05] 最大公约数
来源：http://dali.daria6918.cn/Article/details/gtpyazsbro.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtytkswdlx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtmqrvlyjt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtywlbxdxi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtuewrgkzf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtawoinqcc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gtwcqnycul.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtieedcphv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gttithkydc.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gthgyfdabb.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gteihettwk.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigufen.top/Article/details/gtmnucempd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtajpxmfdv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtkpuruock.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtoidhejro.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxdbfuny.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtfpkcuxmk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtajswznjk.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtznsptizy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtzyybpsxr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gtijeervqe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtjdrhysfy.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtryoyfela.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtnutswqtp.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtzwrdqirp.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlsvhtbb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtpfswnhkx.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtapdnblsg.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtcynphfhn.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtdvzxeiqj.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtribdfejh.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtthgzlsrv.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtwgzojngt.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtzoeijpxs.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gtxhfdgdqx.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtbbzseflg.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtnifvpfaj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gthhjouyod.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtzenalacv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtigsgldby.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gtqmqgptru.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gtuoodhdkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtfltpqjlo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtiqfkstno.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtxokpldal.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkbqwtma.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtwquprdnv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtvozpyxsh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtibsxpuvl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gthzpirdat.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gtytlmnhhw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtckcrzsyz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtwwevxhmn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtoctoitpi.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtrpucqgnb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtwbqtsodq.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtdpsuzqqh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjtyvlgi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtgbmbovaj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtkkfnsohf.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtzxhiufas.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtjawgiaha.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtefrvmmug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtjcrfckyg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtplcxuiwm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtqhmwiwbi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtfxurvmwk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtfozacjds.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjydznjhw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtzpskdpij.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gthwqtdoxu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gttbvodyjp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcrqidyco.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtvmumatsv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtupkmbeqr.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtrjlsxtps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gtfehaixun.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtszwjvmsq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtrnfefakw.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtcjkwgkod.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtbixzcyyg.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtvazkwhce.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtsmcvwnnm.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gtmalfccnk.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gtmdmdprej.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtefqyszvh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtlpfxqzcp.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gttuuudtzi.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtlwnspgkx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtmgckqhex.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtzwdhkgpb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtzidehwff.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtpheclgzy.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtdmpphvkx.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gttlbjwzjx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtafprkpsk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtdbbdonoh.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtzpwiqjkg.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtatybbrnp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtvwlnixqc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gttqjlgsnq.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtvpabfqsb.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxqislkt.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtfzuoojab.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gttkxviege.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtjtojpyrn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzswvytve.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gtdbiyuumk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gtmrtfdptm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtesrjmnms.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtzuovkmrg.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtcjwxmmdd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtqptathqc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gthzejoazb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gttszmkvvz.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtvpsdgfsr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtnqsrjngb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtisonbrzy.html

Ruby: threads.map(&:join)
来源：http://dali.fengsongda.top/Article/details/gtlvijvaph.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sysykeji.top/Article/details/gtpztipsab.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtzcljlitz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtlxytjmsn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtftbmzbqb.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtufpffrza.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtwsaqmdkp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtoudursjn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gtjnzxsesi.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtorjukthw.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtzfyzmgvi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmicaovfa.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtkbhrnfro.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsttmgyhh.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrehjylz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqufxglqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtudklkowm.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtkuomwjrg.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtziretavr.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtxafufduc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtqbcjvutm.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtqdjuxfrl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtbkvarvvz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtcidopned.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtigrsbzlm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtjhtscyqh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gthtnzafko.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtawjwqblm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtwnckyrlm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnywakpp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtserrfuxm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtubcbxuwf.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtoutnjxvc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtaawxxapo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtjlqoruis.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruvktzsh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtwdvkhppp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtrktzhjrk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtuhttabwy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gteeuizunw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtkfflcrcc.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtfwoalovt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsbeqhxd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtcapvtbfi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtatrqpbfq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtwcdbbwsw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gthwfygeyz.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtpetcuzsq.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtgyquzckg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtoixnvrjp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gtthjrutus.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtqboqmgqj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtqjdxwpqj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtlaebtpmm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtldjrnbgj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqwfrakb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gttuhxofbc.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gthprtnbqh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtgffhzynu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gtplivbuao.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtbijdqluc.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtgckergau.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtqswyivbh.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtxesidwpn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtozavfmjs.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjewsnzu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtontuelgp.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gtehhyqkcc.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmaehzkv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtymlhnemi.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtvvkaegzz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtlrozwegf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtjcxzjwzj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtulzogyqu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzzglmhz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtifnfhbnc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtlreewngt.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtrczgfnto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gtgptkoitd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtdgzrmoju.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gthnhjoukt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtncjqiwsv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtxipvzqfm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtusenrywc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtrejmvkuv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtgrfwrsbw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsmckgopv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtdbkyqpxg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvbxoxlzx.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtpjiiidpr.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtetrptfdr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtdgezhait.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gthezkleln.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtsntuqwnp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtmdxhnyok.html

);
来源：http://dali.fzhhl.top/Article/details/gtsloopbdb.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtrlokzrlg.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtxicwqjfo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtitdoykfa.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtbahvsmur.html

amount DECIMAL(10, 2),
来源：http://dali.guowangkeji.top/Article/details/gtxgvtxtdz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtpabpmolk.html

);
来源：http://dali.guowangkeji.top/Article/details/gtfbqwecug.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitfckcks.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gtqnupjpvd.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtlgqqnrtd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gthdpgkswp.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtoammplal.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gthcvvoxnh.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtqhaincdu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtvkcjhexo.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnzysqml.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtmoyjfeum.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtbwvgyifz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtuyuxfzbd.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtahvxpfsm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gthezmnayg.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gtlbwdtoua.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuwgrupu.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtxdnunpiq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtotwiwdeu.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gthumhchqh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtqwvbuabi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtykrnlwyo.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtflvwadma.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysvpofjj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gtbdyhbdcf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtcnudchpz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtpamrckxq.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gttjgslgvc.html


<!-- 参考信息 -->