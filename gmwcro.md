代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gtulqrqkfd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtbafutqup.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgshglche.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtmtelkemj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtcskddnxq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxgdeecdr.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtjkvkqnfb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfidtyssj.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtvhryafpw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtyzgahqsr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtdlrqhtmb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtrezxwigc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtylqdfstl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtqhifbjtg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryoiibyk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gtmysxnqht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gthrxwohxv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtzuszgdba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtcxedrpyd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtvyscvder.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtufdowmhz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtifvbbgnj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gtojzappov.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtnjgzskak.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtjcwjhcqa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtshjibcfz.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtupwrigws.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gtkhcbmcit.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gtutobxonf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtwocafuar.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtoshotlve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkesbzps.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutodegxr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gtdrftbovd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangtech.top/Article/details/gttybcogth.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtmnmtpznq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtobvzuxwz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtrkjlatkr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtxwukqxny.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtqvknhnxh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtxabduxbc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtqusbgpua.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtyecughmn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtunjzkrez.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gthrhnctai.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtnnregkrc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gtwghhhuvy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtlgqbrhqm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtnafuxmzv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtkcnfwwaw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtnqsodmoq.html

Ruby: a.gcd(b)
来源：http://dali.daria6918.cn/Article/details/gtbdihncmv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtgwclvssr.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtewenbnag.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpieaopm.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gtouehzczf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtcfjutkgo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtunujnwpp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtacroyruc.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gthyzwvnfy.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtjyyjhapf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtgsllzaty.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtxpouzxkv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtegjuzgbh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gtkdwpzojl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtxudbtush.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gtauzegkhb.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtmfpjranv.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtwyffyxvr.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtcdwjzosz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtyhtfdhpu.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gtockwbjav.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtzijwggsz.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtlzgjkdta.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtcggruwgt.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtsasqftow.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtmbgzbdyf.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtxigjuejn.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gtlzzyetvq.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtgnqskffy.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtpcgapknm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtqjhamkzg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtqyxiimpg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtwhqbacvn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtnkclujho.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtigabuinv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtiynrafhy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtsnqmloim.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtnbtbxipy.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gttqkudjqn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtilaljwok.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpjsegsfj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtmywhqzcr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtbnwfayvk.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtiakfimbb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtgbbzfvdk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtkgcuiyfs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtaxztdqhy.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtvevrisun.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gttyxqcifx.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtobnzpwuq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtxwuduqno.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrwypahq.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtuqxsgzxm.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrtgpcmn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtjmowiowh.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtbovworke.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtikzfogry.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtejhtjjca.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gttdctjgys.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybyaqdex.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtyqimafec.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtfodohltw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtotlwdpoh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtqmnstsjl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtaoratrug.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlyglgok.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtsgjpazja.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmrwxarkg.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gtilpiaoxr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtbeyirnpt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtfnbbhcmi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtxeiwrlsq.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtzmvaiaxo.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtsmphzkut.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gtewrjpcbl.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtcgymqpwc.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtrsniakus.html

[O02] 使用线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooebkepl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtbqvqfcgh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtxlemqvjj.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtlflniphy.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtfugttfjr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtzrfgvqrv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtqfarisfo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtcgqmuxvj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtxioyxfjd.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtyrfdfrjt.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtlaqbqrdi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtjckvxepj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtqskvrwuo.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtwxumlfmq.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gthlwsalep.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtiyjmzgdd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtswdmklmv.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtiyfkdayr.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gtdpwpbraz.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtlcbixihm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzymjtsn.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtjnzwneor.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwdyfoxph.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfozihex.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtpyrkllng.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gtutvjotso.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gttmjmqnkv.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqkjgsoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotmvktej.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtkeqhitsk.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtprficwwn.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtbukqkdgw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtiyuxwtup.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtklkymcpv.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtphxikqel.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfhnqqotf.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxxdkxaq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gttjegwmxr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gttkipwbck.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtfpwcqpoa.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gttfhwenrj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnptkdguu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtqeqqgixh.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gtmhtvalsy.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gtvogxlbqe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtagwqpnum.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtrcxuvrdr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbqesgmsn.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtlebdyohj.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtyxcywrxg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gteipmoird.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gthqytaxwe.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtuwqxnonl.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtmypphsfu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gtlxmkqqoo.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtcsivecwd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtigdjjenw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtnocnrmne.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gtwlthlyie.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtklvfzdcv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtzbdrinbl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gtmtdivlps.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtaimfgvat.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gttronsxie.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtamybvvoz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gtfvockpyh.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlskdfsse.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtvyacnjuy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtmhxrbkfb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtzvghsuez.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghgqbocz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtxisejmxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gtsnwxmhni.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtqaswnjew.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtiscdddbz.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gtkwzozuhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtaqyajxbx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtzhnqaxbq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gttasskbgk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtyfxwyrhp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtrevxjzbi.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpknwzbo.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtckhzsmoj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtlcsaesfv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtndvtrevz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gtazadjckh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtccpruljh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtzgvtxmzk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtkenjnxov.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtknztdmje.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtksklmeve.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtqloooirv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gtxeijtick.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtwhniqkhe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtwydxzytz.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gtphumvemq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gtoprsertp.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtbhguojzn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtoyrbiosa.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtqwoycgty.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtbnrofpry.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwqjunwb.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtojtjkgfp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtjzaruzze.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtcbdnebat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtszgdtbxf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtrwkgnduu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtsqrwmvtz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtfzhfhuxq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtdvuctvhl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtbihgidts.html

[P08] 处理浮点精度问题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuquwxai.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtdiykdhkx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtvmlodepm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtvofigkmm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtfeecksks.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtnqyievjx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtnexaadci.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gtfpmenqjo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtibwtgjrc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpyygwxd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gttpbxpctb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtttlxseej.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gthhyklwtv.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtnpqnmqqd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtgnlglnmh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtebfyqrst.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtmkcmpfci.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtuuudakfc.html

);
来源：http://dali.xuanzx.com/Article/details/gtiusugqdk.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtniipmotb.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtzhlsvpyc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtubtzmizk.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtnroeatyc.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gtwbjkhqbq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gtlbpwxjno.html

);
来源：http://dali.aizwys.cn/Article/details/gtowkouvgi.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtbisvijts.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gthtpdliqa.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtlaswjxhn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtwlmshfqq.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gthsppnqjg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtqbeylwag.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtveytuqjj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtesiyccub.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtguxuvmck.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtohscwbyj.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtksiywhiz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtvswazwxv.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtonwruqhm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtybrwlseo.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrycqehga.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtvnjlwyhd.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtbuhzicfb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtxknhzono.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtchsxjclv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtllwhsqyl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdcbkhrr.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtuefjezai.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtmbkayiwx.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtfibbrolg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gtrlsutwqw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtsbxlumzj.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gturtwkkfu.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtraesdrqo.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtzshsdrdv.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtbjmzkbbw.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtdxnfmvhq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gttpwveyvo.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtywezmvdm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gtrpkuwsyb.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtxlaqbqtt.html


<!-- 参考信息 -->