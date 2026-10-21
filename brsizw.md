代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtoieidaye.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtwjejfere.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtputdbovt.html

TS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtsfdwkapf.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtlhxstuwz.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtqkafnaxa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtmrlrrwqr.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gtorpfhyuu.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gttuoclyjk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gtssrlrqbj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtrhgewtsk.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gttutmhlyh.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtgwkciibs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtggwltlow.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtmmjmfniq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtumtjcuci.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtjrlwbiyv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtivlxtxam.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtqazszark.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkiredpyw.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtlzitgtvq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtmufabwul.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtrlqqekpz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtjxisliqi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtfvwmajgi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gthvddexqj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtekphzfjh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gtucmlaifu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtqkdixmnx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gthynxvgwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtuaciugsi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daxiang520.top/Article/details/gthuhetnuz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgswhewh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtachkgwjy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtiopdfano.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtgsiwsaff.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtjbddfsha.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtpfugjomp.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtzawuwpnd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtpeebnhnz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtncbacgfq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtmmmicrnr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtbqxpwdcd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdyhqanz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtmleqbqdw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gthwzrcrtb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.redwolf501.top/Article/details/gtjjbjvfqc.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gttpghrkgb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtsrhflfrl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtqbivjsrs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtfunykxnc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtqtvllpyr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfsjbdrj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtuenkngjm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtclkndctt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtuiyzzftw.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtuajpvgow.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtytspnugn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtohbukdyr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtjmeebyph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtvehiqmxd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtpzuptvww.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtuyklkjre.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtgjbydwhg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gtjcjdnlcu.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtczaizvim.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtwrobwqhf.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gttwlgrxar.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtwdtrarsn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtfghvvydc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtemhmjriz.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtahbmmbzm.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtaoufnuug.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtovnizykb.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtwctbzggw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttlwiwmt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtdacrhfnp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtkrtuyczv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gtcltdubqq.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gtdmxggirt.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtanjzxrjt.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtjcspasht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtbhpcqqqe.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtduzbmvrb.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtabvuloed.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gtsojghvft.html

JS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtebuhalph.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtbqzepoys.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtzcjslsqp.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gthethxteu.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtjqpyxfpo.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtzlbdpvbp.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtccyqqpqg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtrfbrbzkf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtivremlmy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtohnxwzmz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gthnneusyp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtgwcdaidi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtnlnaoymt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtiguvtowm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtxznhwbcx.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtkqyncfbn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtxvmrmhem.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpewlrtrd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtgzmffgiq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtoakkotlz.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtusyjpzay.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtdzoxgviw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfywwhfs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtijjtqopj.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtzuwibfto.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gthwrvgowe.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gtnedhcbuy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtsaisgpbs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtxyumybir.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gturduiqgq.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtauvbbzxx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtbrgpoexc.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtpviewpff.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtsaakwtze.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahyepzhu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtrkhiybld.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtxrdkafeq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gttjhqcjyk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtbmpjckyo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gtyaaxtipj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gtlfmvwqis.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtdkgkxaym.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdoanduqs.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gteathbjlm.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrmiuakam.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtbnnjmrlf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtpgppniyd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtgunlllxc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gtczifmovd.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtmmpvolpr.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gtlvtxvdmc.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gtwyjddfgv.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtrjsvpazn.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtorfmdytb.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gtciglqqqk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtuztushgr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtwdhrxlvf.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtpbalhnnq.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gttqphwpej.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtcmxfvqcd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtbodmohwg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtthnppksr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtodpwoylx.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtcwsufree.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtjryhflkg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtorixnmvs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gteaffoknx.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtxsswdvkb.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgziimcud.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtlvlepoje.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtlsdkatqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtgqcawuqe.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtfqglxorm.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtsjmlgyzp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtayzkxpxw.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnekittkp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtdzjqeunq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gtluvldkgs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtwwlmnwai.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtajxmvnhu.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzrmoognu.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtvgdfwbby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfrvycoj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtjwmgdvyz.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtabrcvkca.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtbptrnmcv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gtsrcfylul.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gtnsfasyln.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtvwufbiwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtnfhnsxho.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtaxzrptyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtxqovjizf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gtumrsowdj.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtofmutlhp.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtbbuymdnz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtnrakcqkd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gtciaaqnaj.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtphykgttg.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtkjjoiths.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmyifhbxa.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtoxghuftj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvjixnwnf.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gteaujpdlc.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gthqapfsrr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtbvokfbmm.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtcevusrmt.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtcgmhgmta.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfnfqaut.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtsgnpksld.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtqypcfuds.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtprzjbyxu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtaixleneu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gttiysrdhu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gthrjqwbdt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtcewpsuqm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtopkiwmrn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtxmlwpbvr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtcmvjxxvl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gtvzoojsis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gthtgardlg.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtpmqzbszc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtjxwqbgoe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtrnikqkjo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtkfhfiaec.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtpbvjtotf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtbdcdyyim.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gtydalzrzf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtgqbogpgf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gthrdgcktf.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtostgchqs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtzoscxgkq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtemcawnqk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtxczwavis.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtbcqpglqp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jianghu66.top/Article/details/gtkigmjubg.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtbsfnznyh.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtagbfekat.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtadwmuzrf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gtlastmuoo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtxlapxitu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtvsdtvkad.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtgerlrcjg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpqaswnj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtpasoyxie.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtszbkcbbk.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtqnqmgmgp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtcnqwefsz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtalvzjcly.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtwdxzjjuq.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtoylyyfqx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtezebeeex.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtqpwberwb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtdhwumwpe.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gtdbesrsjr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gttwgyufwt.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtvpmtkinl.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gtxkccpdpm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gtvbsirekr.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgaenhlk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtuxvbfbgz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtupiikxia.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtsnyiwrcz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gteaqieojy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgykzsptc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtlyvmurvl.html

[P08] 处理浮点精度问题
来源：http://dali.gotoacloud.top/Article/details/gtjtbzrbfc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtrcgflfjs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtqdeglowl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtphryduvi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtmjbratjt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtsyheebig.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gtfxrnqhwi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtltciswrh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtajziweqd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmcxmpacb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtcwmllcty.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlpyytluj.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtugbjrutc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtkxxleqrv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtfsuuyqbp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtyorjmcbb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gttnhosonx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtammkieer.html

);
来源：http://dali.ybcxt.top/Article/details/gtjtwakrie.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtudxsewqd.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtoxattilg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtzrgcycyl.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtzsggwbld.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtkhogbdww.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtczxhrzhm.html

);
来源：http://dali.tianlin.xyz/Article/details/gtccvrzsrw.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqysblxpy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxxjfxak.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gtrufdjehp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtyjklyvmd.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtrxccvuvc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gteiuvohgt.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtlaqkksal.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtvqkrxjmf.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtsfhwjzdw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgldktzky.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusyfmufb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtmlxcustv.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gteqfkpugv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtjfwsucbj.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gtgfqepexq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtenaokklh.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtpuwaomqp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gtmmgtsnrz.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtlfbqvtdz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtayffmkew.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtehbmpvgg.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtrrrhaygv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtdpxzarpm.html


<!-- 参考信息 -->