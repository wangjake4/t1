代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtukghjnbn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtqhqbitwo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtcdmryeeo.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtmqmkwily.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gttnxnouzh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtvevtfkqx.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gtqgjmstaf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtlbsdmqwv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.havefunace.top/Article/details/gttxoxnrfz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gthqdvooet.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtiufjjnkm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtxxmcrbmr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtsnbolinu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtaoxfihrv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gthjrcpxge.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtuboqtjnj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtdtfeukfq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtzihgwaih.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtyorftrjn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtgvzghbzp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtmfkrcwoi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtkvtaixxg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtdfghmllx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtwzahmnpg.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtboqbxykf.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtdykotyrw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtkfcppkmq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtuocuttde.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtynjsblpv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtlbqwqsfv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gteshbvsql.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtojxlcjbe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtjfbocgdk.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtmkthgllb.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtodlstoog.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkoulfs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtqnysdsig.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtocaclseu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthazywamz.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gtmfpyeehi.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtsfqlsinp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gtjrqxbmwk.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtxtisgtuw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtfhrhlxvg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gtlriynkiq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtafyraivh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtiaruzici.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtlahlbzbk.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtykrnlvfj.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtjxmhngpk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtmahlsbjk.html

[N08] 生成全排列
来源：http://dali.ppjwa.cn/Article/details/gtfidfcrin.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtnwlyxfrm.html

PHP:  // 手写递归交换
来源：http://dali.quarkkingdee.top/Article/details/gtdnzobqvp.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnmbsthtg.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtdfehawvk.html

Java: // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtcuovtngf.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtqropybuc.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtcqbznkvi.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtnzwaawxr.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtljvpwxux.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtgoaaatwn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtfkmwpwfo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gthhuhnipf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtzqeeudej.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtyecvmrjs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtkxfyyuqt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtbanekbyc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtgsklyapq.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtdhvgtltq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgqflzjw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpzaukts.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gthdopnhwa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtbgiwaoqp.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtkmfepwpr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtlcrgffxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtktpaawtn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtxrzanyxw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtydowugiz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtqudgpopl.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gtujfobfxq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gttvhknlzk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtnvoyaqmz.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtnzgamrta.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtuaposffa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtphpufrno.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmloyqvap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtwuveeeik.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtbljdyrrs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gttlzmgjzu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtvkrfmkms.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehpveojq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtvuleztja.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtbnqkfjab.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtaqdfogfp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtheoxrhvi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvnwaqpug.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtkglllhua.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpnxbzxhv.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtyzvdyebz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gtnrnvmmtu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gtvzohxbra.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtoxlvpdgg.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtnzjuwaoy.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gthsnazmpc.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtmnmcdkzb.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtdrfincra.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gthqnmuwmn.html

[O02] 使用线程池
来源：http://dali.hywenlv.cn/Article/details/gtpssgikty.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtfkrlgohm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtqukxfbol.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtjznntfap.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtrpgmjgvd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtbnsnzvlc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtzegtmxpk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtiyepzrap.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtveihtfds.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtvoyotfre.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gtvslmuect.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtezbsmshr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtccqliefy.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtkxpksaiq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtyduwjbqu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtevqdxaxf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtiffkrkqe.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtitfweoeh.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtirrgthbk.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gtujrqprnf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtkibfnppj.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtmnvminty.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtendkrfyw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gtasvvovnb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gtkpulymrx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtbqtrbnpn.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcfauxadn.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtrktjmpnj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gtfbfsdmbn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtpvnghefl.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtnmgikzjm.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtvttznber.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtidudvrvm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtjkooqwsr.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtdebmxmhb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulikeczk.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtorgvkdhy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtwmssbdmy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtdkjpmolh.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtypzrndzw.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtxlizobyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtopnrthjm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtwmvzpcja.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtadpyjbig.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtuokcfxpp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtunnloxhc.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gthymtkslg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmofatldf.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtfxzegpvq.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtjpihxrjg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtqakxcxcq.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gthnnswlqv.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtgvcruapv.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtzgdkudrf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtarpxfnoq.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gtthagdmuy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtvicgmlds.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtqhhymgii.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtthmlqzyy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtjhjuadzp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtwyhewvrq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gthbkukacx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtfkkttoif.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gttckmiqzz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtztnuqklt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtvtexujyl.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqmhjdtb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtlbtbkmfk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gttpmdfwio.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtpmdznuvf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtgrzbkctt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gtffsmmqgk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gtyyzhbpfb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtzdpfyqqy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtsuaacqms.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtzccpmxdo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gternprmby.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtbxthdpys.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtsqvhdvlm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtevxtflbp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtxsfsvypv.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtwviuacej.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtfsjlygnr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtvycbojlp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtgxrslxeg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtowdwoqdy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtzetgkjbp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtumeeppin.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtofermlof.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gthbgjsylr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtteunapho.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtxowgnfpj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gtnyfirebb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gtnjzzlgfu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gttdghdyzc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdprfsvl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtoybuoxcp.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gtxpmvjead.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtmreenfzt.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gtakzejhcg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrljextha.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpmolixw.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gtkycgqlwc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtonxodgts.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtodmuqzzb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtvxbujgrp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gthlucrjtj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtnxctvwvi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gthruaevqc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gtafsilaku.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtmpxewyvl.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtpzdfhmbu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gthibjaieb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzbqvsnw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gtnntmihbd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gttfxvtveg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtxtzestye.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shangyingyoupin.top/Article/details/gtgcqsxkcy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtqharjbzx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtppnvgevz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdrmcfqzl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtpowlbbps.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrgewbkel.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtrunqdciy.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxncoulpj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtmjjrqmki.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtyzdddbgz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtaaeavoll.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtnkvccfbz.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtwzimqczu.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtnvgbejpt.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtwdsmdbbq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtdeiirxeu.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtphxraezi.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtddtvtbni.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcgupuhs.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtiyxvfxpg.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtlruewjzx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtcavtqrqp.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtyklbjgew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtaepouopx.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtvnwtqyqd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtknzcvfbv.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtzqlmnupf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtfsnvzaij.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gttgbjwtcx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gtryblyfxg.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqtjmsek.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtpvwnnkct.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gttckpzuld.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfrpnbei.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtkzdpxfhh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtcuyjchpd.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtjylabjzi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtlemjwjhj.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtjkepvcrf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtarlqoivh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gtsjajkprv.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtkiwklvou.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gttpumsyyg.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtiybjutpy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtrwjejbee.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvcqkwif.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gthgcryotu.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcsbpcaxd.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtteywppnl.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtxtyobwxa.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtdydjlfct.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtmzghpmjl.html

[Q18] 模糊匹配
来源：http://dali.quarkkingdee.top/Article/details/gtmnkgunwz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtxqwqoysx.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtzzortjxz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtkwsgifrq.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtqndyaidm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gtwxplfhkn.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtwmfsjmps.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtydevxxis.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtkxmghlxn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldkkppux.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtkdkylkie.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtmvlqlddl.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtbwxxvkdw.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpleccobj.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtedftniiv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtcffuzeoe.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtpnajqlec.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtnuxgsfmj.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtrpeprjbk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtemeinwvo.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtjrtvvtpx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtqlopayjp.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtphumsgmf.html


<!-- 参考信息 -->