代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtqtvtgxph.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtqwzbbkha.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtqjlbgycq.html

Go:   slices.Sort(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkpzpzfga.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtrjozypvm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtzgsjygvy.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtdpynoirq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtimocfuih.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtijcltiug.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtonucokis.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtcdppzrde.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gtgqbexdcy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtnajckrqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtjkzpohkx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtqwkbfjwb.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtmscuqlsj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtznakopfm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtifpsckyu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtmhvzeady.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhuxhcms.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtthfafmns.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gtfdzidfmh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtoshkgjmp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtujzyvxxd.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gtulrjxcor.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gtzcormzin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtjadrlqbi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gtwxbpkjlt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtbxpzgfuu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtjdtltyok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtgqlohmfw.html

Ruby: a.gcd(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtlrydbgjw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtkcszkdgm.html

[N06] 判断回文字符串
来源：http://dali.gotoacloud.top/Article/details/gtiawrhfqv.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtpnbcblhu.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtknwjqyof.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtlqmbucca.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtoriygurh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtyqmhurop.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtihmhirdw.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtflzqnqvd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtapspngmb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtofhsnyeh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gtpwgrhvkv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtubczxmor.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtrfwrbkvh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gtpfovwdqe.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtbqvzqreh.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtuaojmvpa.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtqotswmpg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtbulbsyym.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgombakww.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtwyiehlqd.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtcgonrvie.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtiwwkrhqr.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtlzknwwym.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtiavaonha.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtvcnqghpd.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtnusnftmr.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtmosiczmy.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtjyjsyazo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtcpzdwpmf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtgbhfwitc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtqmyroijl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gthvtuipvt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtankiuuvv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtpxukwdvs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtwtdvgeln.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtixclcjfr.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjysdgyf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtaazvcvha.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtlsszeppj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtzyibqlxs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtkjzahbpb.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtchjdzzqd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gteqpjaxyv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtczmhqvio.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtvglqqflv.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtkkjjvczc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gtjweckdeg.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtjjhzmjie.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtbhizfqzz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjknswjq.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtergjwhbw.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtcgqajpkk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtblovwjsw.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtzqenptbf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtriyiqsjr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gthjejdnqg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtdrhuzjcs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gtbvkyemxw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtbntewghy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtipkcxcdq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtnyhhcker.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtahbrumom.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvgipomp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthdtrbxgm.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtqbaindji.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtugwxizdf.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtohdpolbv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gtsmnvtzmf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gtspgdmhvg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtjewkjpya.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtnuhiblbp.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtxubctpdg.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtbwjjhniq.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtfpphgohu.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtkfxincvb.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtqjkfipdg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gteeuloxhe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtfiwuxkop.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtfoerkqno.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyviqvwc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtttnponly.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gtzarceloa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtimafaozs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtscynuxyq.html

[O03] 加锁保护共享数据
来源：http://dali.cdnleiting.top/Article/details/gttlxomucp.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtbtrghezr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gthzxhkosm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtpcesdirx.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtsftqbyhi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtqpixvfqk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtztacosha.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtioaagggw.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtjtzcfuov.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtivqifwoh.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxuanxn.top/Article/details/gtteestwxl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtfmztztem.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtfqaffnhz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtynufyxmg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtnpvuewug.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtwnknfmgh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtinamkqmg.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtyltyvbwq.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtuydsmcdl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gtbivlwxyc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtaasusleb.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gthepzitms.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtonjxnlou.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtwakvefeu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtattceimk.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcukyleio.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtwxvvfzhj.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtodckwgmy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtxwpxueox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtpqkxyvrz.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtlfbxhwuy.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtcgkeiqmn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtfvtxviat.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtrxpibglm.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtzmwdglrc.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtemueevyj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqfdmezee.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtmbgniasq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthfxefcgr.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtmrjahjlr.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gtqxygtcan.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtvxoqnnsk.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtojjwpyhr.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtokakiebq.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtoflijqsn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gtfvigqmfa.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtbvgcuurv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtbuqlapch.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gtczwnsnqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gteacbkxhm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqacsnxfu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtdffygiif.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtskyqvbrm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtogvqdzak.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gthwjewbwq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtypvqoilb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtkdqyuxyb.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtizhhxtuo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtqnzfsniq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtbfbxnqdg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcepbrant.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgvrllfh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gttlisrmly.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtmpjxyuvs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtpqzbtiew.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gthetrojye.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtqyhcqvws.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtsyfoosiz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtblpvpeyj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gttgdtrswy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtvodwrkxe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtlvuwqril.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gtkxacfjgl.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtfuawxfes.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtfplpldpf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtsvxptrpt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gtoolkxoiv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkgbnfqm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gtszaeoapc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtvrdclbvx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtzypjryzd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtrkaqekut.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gthpkoumbi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtlhfpdyjb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gthtuikgmr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtpqbzwmlj.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtcrnhhgkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtjsabwgul.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gthjksmevo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtfttxcqtu.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtdghjaick.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pycfn.com/Article/details/gtstmkendi.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtqsmcygsu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtnqwpxbqq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtyumneery.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gtrogvgypv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtrpgjvxht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtllruzdwa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtscnbveyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdicvdrfb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtvnmwwzyy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtcezjiwrb.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtseskuchg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwhbsnsx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtaztpcntg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gtkuuylojz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtzhazcmfh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfypvccpg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtohtowrho.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtstgbqjqs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gttxlddawo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtjxkrjzdt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtqksiiyos.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcftbojzu.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gthpzaskeu.html

CREATE TABLE users (
来源：http://dali.jianghu66.top/Article/details/gtvyzzqfca.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtfowgjoiz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtuitexdyc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtiqdmxpwf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaamlbmo.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtmshokxdi.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtppmlieeq.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtipltrdjo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmarrpom.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtwiuuuuvk.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtaeoxcnne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtbogydvgc.html

);
来源：http://dali.xziqi.cn/Article/details/gtscaabnja.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtxfomyvwv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtzmbfeswy.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gtedphydjl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gtlrktjzxt.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtiendiwch.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtrqxlcqyi.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtxpteslrf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gtfejroeeh.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtmzgbiuzk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtfrihbtlu.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtfyiblqlf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtsmuagqab.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqweuluzu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtycgwlgrm.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtcqubdsyw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtchmhignd.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtictgfxuw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtstjxkoqh.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtziwxhmzy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxwtjedz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtghezkihj.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gttmsrghkh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtpbnyleoc.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gtmjpwwrvf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtjlaepglj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtvwspeuyr.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtzqzizojj.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtvruwntte.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtrtlitoyn.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhwuybsw.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtbeulrrxw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtfnuvuuhy.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtgbdepwbo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtotenkokl.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvhdqibh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtmimssobh.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyhobqtd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtdnvgxlph.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gtrnhcbons.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtkngijjrm.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtjkqigdju.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtoyyfayef.html

[Q23] 分页
来源：http://dali.aizwys.cn/Article/details/gtrjkbcpry.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtmswkwetd.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtdtfegljx.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtebtrqese.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gtoxfoiqvt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtxitemxou.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtahcwteqn.html

SELECT COUNT(*) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtmntqbewk.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtxtycffbo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgylwbqqg.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtwhnovvjn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtdntcwxwe.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtinprhdkj.html


<!-- 参考信息 -->