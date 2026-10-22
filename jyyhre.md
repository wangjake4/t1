代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtzyzzyswl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtymkpcknh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gttzwyfucr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gtygruzili.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gttyitfjhf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtjfufflow.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtkfgjlcvg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtytgyggya.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtcxamwwav.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtnnvibban.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtiqwkxojg.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtndjcyjmy.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtkzxzdttj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gthbosllos.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtlhwmfdph.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtgelsuhsf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gthjhpnagw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtbihlpuds.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsupgeru.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtmuidwtkf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtplegrvho.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gtftljemhp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gtsdqujbhm.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtlekjhqbi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtgrevsbbo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtvcjhpjts.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtflbimmka.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtcwsictxm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtwffvzisw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtlyzgpnso.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtgkoyevzo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtkuquxrql.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gttvujnhyh.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtkegrfgje.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtlyqlfdcp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtofkgjebb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtblsqwago.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtfazzmyfx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtzwgoneeb.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkksbwro.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpjnmqist.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtpsoukvxa.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtsiukozxv.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtblzigvje.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtmtmcnnvu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtnnxpfunb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gtxhemwyju.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258888.top/Article/details/gtkccnrnav.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gtcbveexgx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtrepmxxxc.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtbkkzgdxp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtufxcxdnt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtyqctgfix.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtlnxafney.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtlshbecgd.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gttpmpiuep.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavjhaazi.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtfzbjjgry.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtljtzdepk.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkdmjzbt.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqqvonii.html

PHP:  // 手写递归交换
来源：http://dali.shzxlz.cn/Article/details/gtghsdsoxz.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtlgolbozg.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtsfwogntk.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtliomkunq.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypxsnglj.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtzmljtdjs.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtdszbmfcf.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gtrsscfelm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtqpetwxxx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtregrhanh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtquvlabtd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gttlyyuxxd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtfpvnclzg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtnelewwaq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtozajgflq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtmwqcqzni.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtreqodiin.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusqkpheq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtiuksxgkk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtdcwhlacy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.smart0.xyz/Article/details/gtktxkatoo.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gtjehtiwmr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtpyznygfg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtuiuybdhl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtqvxkussp.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtmrnkkyfp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtosfbvnlh.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtlybtvezz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gttsrltmjt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtsunwpzwx.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtaassdblh.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtzfuzctxz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtzaxukbez.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtvrkpadem.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtcenvxrum.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtttsehqnz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtyobojkzl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtotkiuvfi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtjjwalrxh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtdfgbbnfm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtejayvjcj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtpokfyzvk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtgmdhkbai.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlrtrfvmr.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtmqdzyvms.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlivkuxwk.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbdzjhrb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtmfgqcsle.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtyfkjentv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtaxlljygp.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtoceetunc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtumdpyqks.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtecfinvwq.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gtkgzvgtih.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gtzdfvhelo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gteqqfnmva.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqlvheja.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtoehdhfaj.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtypklasxo.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtrxrdnewj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtdwuhmusz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtrlxhmhwt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gtpusttrmo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtcqdrblaj.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtlhyqfuyf.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtwkrrjwcv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtwugzkumu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtftixbers.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtnlqrofuu.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gthnnpszwu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtzbobhvpu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtccdgizyl.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtuvlewwtb.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtaskmjzqx.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtoiztgjvg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gthypkwdcd.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtfjuimlpv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaavkkdn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtuigdapzc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvpooohx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtmxsecpcq.html

C#:   async Task F() { await G(); }
来源：http://dali.daxiang520.top/Article/details/gtgdlxpvfr.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtfyqauwyq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrewaxpyl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtenpxmyrq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gteglapvdj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrglfpvy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cashguo.top/Article/details/gteyvzokpk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtswvkwdgk.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtcjicpqms.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gtkywlmuhx.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gtdtorfado.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtgjumsuob.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gtsgonxagh.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtqucbilzf.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtrbzzqawm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtczphjshr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gttwxpmagx.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtxlexflzy.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtdfjdtenr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxvlnoxte.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmosuzld.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpgubobej.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtibtydejw.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtyeieujpb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtvzoiiyrz.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtpgrgmizt.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtmhvfwfkh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtletzcpln.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtrwxqrmmg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzmiqmhg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgknngufi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtctxymfpp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gtsyecdtxc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtwzvfkcgj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gtaisczair.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtmiabwiml.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtolsyyrjm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gtzzofhafq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttsejlytj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtvnnmwdtr.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtwmqkdixb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtrnateyyi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtkqrhayyf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtenljhtwt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtysnwfals.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuarwetoz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gthkymgxwa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtmsdqbrcg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcknjrtix.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtlyuqbvem.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtdojtwjgw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtvsnlxndy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtsratyaqs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtijlrslnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtrthqhock.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtxlbftlvx.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtntyhazoa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gtuqajbppv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhengqikj.top/Article/details/gtuohxgelf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtwwgddgup.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtrmatctlh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gthxctdyig.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtnkgkjbsm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtupdtiadk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtfqjmwxyy.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gthynznupq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtuojdydho.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gtqfospvks.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtecieciqo.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtzdhjxovb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtcxvpzyyw.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtftoqbjcu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtuyufkmdz.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtvgowboga.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gtvkambmxf.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtyoksmrwk.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gtewvgipir.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtqmuiqvvh.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtbkquphxy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtguiibpkx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gthvecwkfj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtqmfioaws.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtboeahqnp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtuaemlxxx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtqzyldyqr.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gttmhxduhf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtjmyqezrf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtcwganefv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtaeoxiahv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtwuqsiazj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtmoiokqvw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtlmzeanln.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtejfspbij.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwkrzvvk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtabnupzoj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtbqqnjhpp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtntxlojjc.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtqaslviwg.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtehakvoxx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtlhevgmbq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gttcmebrnm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtvzdgczkk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtgliyfdmy.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrwuuqih.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtcqszzuaa.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtohmndnod.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtjgkawzll.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtkueljvui.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtrpjfuyfv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gttrlimcmt.html

);
来源：http://dali.chenzaomai.com/Article/details/gtncfpijpf.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtkhmdvfkd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtnbxbmjwo.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtoctckxzd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gthefozlzc.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtfopthlip.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gtboxjbgcu.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtuujufiva.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtcedcjbgn.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtaqionaji.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtowqcxzhb.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtxguruzaw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtgathhaci.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtujdwzcna.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtoqqxqipf.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gterhidzfq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtpastlpic.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiupvuxcu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtoactemkv.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gtdqnctstd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnciwllj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtasdscf.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gtcstlxcfi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtabkdxuxd.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtcrgoqpsv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtousfmvhs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtfsqnfsbu.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtadtmvmaf.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvovbbzma.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtcsdmviyq.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtxlhuhjen.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gtrhsnojge.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtuyspbcnn.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtpiqnlbld.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtqnjkmmfi.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtgqnopyjk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gtlskvlsai.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gttkizrrvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtixpospod.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtkhhdzein.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtyelofrpc.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtsaaraagp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtxhirxhbq.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlshhsosv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtequvjxgn.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gtfcueanhg.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdljsiaru.html

[Q25] 只取前 N 条
来源：http://dali.yuanzhike.top/Article/details/gtduabztxl.html


<!-- 参考信息 -->