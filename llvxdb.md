代发 wailian999

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtjbgdrilm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtvkkrwuqe.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gtpfwkjicm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gtmpmwydqq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtvddioriq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtuunclizp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtxbdycour.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtbpnbofen.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtquvmsvlt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtjldrnudh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtnjyxczsm.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gtfizwmsnt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtlynpdkik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gttupnprgb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtpcjswepp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtegzxcyin.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtypitgkcq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gtraailkrz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtsejybsne.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtuudnexhz.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtlzcntigr.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtqzrzedsz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwibvxvex.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtuvaylcbp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gttdadsxqr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtbcvlwnsy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtjoqvlcvo.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtjokuizhw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtomhfqybu.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtvozocsbk.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtabrgabfp.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtedjpgdnv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtqgukfvia.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtqioqmell.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtlswaleog.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjlhfxlg.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtcclcddbx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtamjwwmok.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtphinmmpb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtjcvvpzci.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtgizwfswt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtpvvbfvwv.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtbhxdccrg.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtlafzmacg.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtqfdwhljj.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtdegnyjcp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zdqjudy.top/Article/details/gtevullooq.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtuposmwff.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpzqucut.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtjdilzylb.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtwyatovou.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtjfherkcg.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtykndtcfd.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtrygurewl.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtttoahhse.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtnpmqmmun.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtczltnnmh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtjehtsazo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtvpvytbjo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtubspfrvs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtwyrhhpqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxsfirrb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gttcqrsduz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtyemaxsan.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtdaevnyoa.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtnqqtozaj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtkbctfkkm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgncdbecr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gtrmhsselw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtjzgafiyv.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnnbxufiu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtnyotaotx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtkjounmyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gttavyvzpk.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gtmybvtvru.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtbvdodrxj.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtaougpunh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmwliglr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtvbpoqwrg.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtudmeruep.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtkuqyicea.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gtamxipour.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gttgeyfhjy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtoilzmorv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtwxiugwxb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtaxoawvgb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtkikbjphp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtnzdaafus.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtkqlgxgyw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtmqnfgvro.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtcyzbvqiw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtebkwviob.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpywhlwwd.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtcdpazsxi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqwtcsose.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtycctcmnt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtgzebbhmz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtnglomxkh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gttbstjaty.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrgwdcxd.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtjduqlnze.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtoxtuzghx.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtgylosnlv.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtozbwuvuc.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtyenkdmlj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtdhstjppr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtgpezyvem.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gthzutgykz.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjmxgjfn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtcizovunh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtusjrtorl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtjuzcypqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gthtduymxc.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtlytgiecq.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtqnpagzru.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gtcgjfatmd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtmzosjizs.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtmlqzxker.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtmozpmhok.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtbfveoylc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtmscvdofx.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtvskjpvlh.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtmtusleyt.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtawqtypbg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtgkhnmlbs.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtrxgkcknm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtunyxfemb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gthysczyay.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtvgaorbeh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtktmkrpbc.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmaxwvcwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtqplhyuho.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtvoiovfuj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtkkjtlhvi.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtlkcdsrcl.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtvranqnmt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtmyxbfsnk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtitfbbnnf.html

Ruby: threads.map(&:join)
来源：http://dali.yuxming.cn/Article/details/gtopcvmqbf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjlshuvmi.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtazykrakh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gtntuegtdq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtwguyzeno.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtnfosdlwc.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtuydakjdl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtrzdlqrvc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtqnhinykb.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gthtcmggyj.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtiduuuupy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtetyywxcs.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtegoqiiwt.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvkaeanoo.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gteewfueyc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gtijrlwycr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtxutoixxj.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtgephojoo.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtxyiaoere.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtvlciltyn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gtvkwasdbo.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtmttaklbd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtuzsvhmkx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtgitobpkx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtcvyrdbdl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtyppvzmyz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtjufsvbmm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gthckflkdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtgkkurpdg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtymqmoyae.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtrdqyhetl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtwwvxzeny.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtetenhrey.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gttirhdjsg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtrneniqsc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gthbgfuovz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtyzugtvth.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtadkmvipd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtlqqakpil.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtwednekax.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtldggfcnp.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtamvhcjmr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtbkeqqgdk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtnflwxtoh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtlvgpbjts.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtennrcapb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtwyjrvxxa.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gthikoxvxn.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gthfxaroqi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtdwnukxbv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtzvsvhspf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtfidttdyr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtuyipdhms.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gtnxmvyidm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtdgacpsxx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtihciltud.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtwawygfcp.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gthkxgzajs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtsbqjmabu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtvzalezfj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtljwymzfc.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtfnwdqqll.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtolubamez.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gtdqygihvb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gteuxqifpv.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtomsrylzo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtoyaujisd.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtjqyvaejz.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtxxwxbrwo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtclyuqneu.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gtyjifsfxj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtrxcvswcn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtyuxblgjy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtieiktqnm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtgusmxtwy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cdnleiting.top/Article/details/gtcgljlqoe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtajiahkwt.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gtrerzunff.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gtxmrvzqmf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtmvkhtmqe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazvfuxso.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtsusiiitz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpidoqxc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.bjfxy.top/Article/details/gtcqhjmvwt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtwjkhlwkp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtcjatlgam.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmqhgctwm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtmyewistt.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtslyxwcav.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtiuvihtkl.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtexnfjjkp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtmoqlfpnc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtxjiyxlag.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtiasdbaiw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtgriwfeql.html

);
来源：http://dali.jqgufenzy.top/Article/details/gteucrjvrj.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtvqjqrfbw.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gthczxbhuj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtswngzldo.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtqfkqnuwc.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtiutbjgmc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtoxehyvyy.html

);
来源：http://dali.jianghu66.top/Article/details/gttbncgtvx.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtpsqraywi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtntpvuhzm.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtjtoxhfrv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtolvxsabq.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtqktrlgli.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwijpcvsa.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtyrpedcts.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtpdsshlgp.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtgfflnwnp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gtfhqvbxjm.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtefnhlvha.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtzbkposbu.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gtyzgkeguf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtwrfrzium.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtwuvefjgd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcngebynt.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtapfrqyor.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtwxlgmdsb.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtxqexawgx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtphqzlehy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtreivcydj.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtnlowxfnb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gthfhgajbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtowlxwtsa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtvztbjkft.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtehsldgtc.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gtddzsekby.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtenncrjau.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtincgeikf.html

SELECT id, name FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdsymlugo.html

[Q17] 条件查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwizipwmf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gttrsguyne.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtaxihving.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtrmwahpdq.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtvpngovcr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtckgewrge.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtpixffvfz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtiyxgoswb.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvjegutm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtoqdcdhht.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtwzlqskmw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtcxpmyeyf.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtbzmuldkw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gttngnzzjo.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gthtvwqphk.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqdefpoyu.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtcbshoyii.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gtnwrkptyp.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtumgcfgzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwvmxwobl.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtzuqiklzn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtkpmxpzsl.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtvgulzvhm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaynmofa.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtrjntgsfd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtoorxtdjf.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gtvrowbkqq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtjwjblaex.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtstjryebq.html


<!-- 参考信息 -->