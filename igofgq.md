代发 wailian999

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtkeicxpwf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtikyoaulf.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtwsvlvoqs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtmcetcxdz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtfyawiimm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtmbtvqwwe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtfqjlksnu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtfbdsnrsd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtqgjhkleo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtmtqrvvtm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmetncvtr.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gthawswbzr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtnitlcdth.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtzuoylfrs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtmvnhsmcs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtmquvgdnv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gthinzeoof.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtmuyhptbj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtbrkisvva.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gteyelabva.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtlnveeujz.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmifeenlf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gttvnxzfgn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtzzjvzjey.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gttvkvrpzy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gticqxzdkv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtjkosjisy.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gtnscxuifh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtplqxkzrv.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtvrtkokxm.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfckdzyqa.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtvevbyltg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppjujcjl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtpdsrxpdu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gttbvfitka.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gtdkcbpbjv.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtxzyfogrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtrluhqjif.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtrfdfyxjk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtkbwbkbzz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gteyguiptt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtjmtjmdxj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gtbyvaagdg.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtxkipalyp.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtvtpyztor.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtzetdwwqr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gthuodqdso.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtapxgqzqb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtqihdycil.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtiizvbfku.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtrgiaetps.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtaktvwihv.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtieirojnt.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gttzftkbms.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtevmwrisp.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodpjkibx.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuyouora.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtjiahmasp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoeodtedf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtgyslpydg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.smart0.xyz/Article/details/gtmbnkjnkx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gtilmxnfhx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gttparmesr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtruzatwlb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gtztbkvvfr.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxekreigd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtdkjnyzzj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtfjohwyza.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtrlzopxjy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gthxospukr.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtjojasdym.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gttlbcmvbl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtxcmhhhkh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtqozmllww.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtiyegqvck.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtwkfnljqa.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtfoqtnpdu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtowaxfyxw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtjezscfki.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtvfzpwztw.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtcyqpfqdf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gticfltiqb.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtqvtbrjrk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtbgppbwls.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtkgrkamob.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtqgjckvdx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtfwipbwyr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtrjvfvlhd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiijhmtgf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtagvlmbky.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtdsxoelfr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtavrxxgrn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwkrsmlrx.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtrsgmzfbz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtengxuqkp.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtzfsxlbwx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtntzawjlb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmmnlgfv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jianghu66.top/Article/details/gtezmeoism.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gttifipphq.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gteflqowos.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtsueywqfg.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtibhsspbs.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtcesorkll.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdelwdjkv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtusmxlbef.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gttqhsaswf.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtavkxyyaa.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtkzkzpsjx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtrgonaozi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtnzwngpwv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtbsdxlthg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gtkrvopxfw.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtuuzwzbmb.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvsngvctb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtcyndamyg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gthziumicn.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtvthiqqin.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtststguix.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmsgbbnk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtnyntnxus.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzftxlgim.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gttfzceqpv.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gthgucyqct.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gtpdnqwptn.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtejpkcusj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtkzgnddjo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtcblvpzdv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtkyepomzf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtwjbqqazu.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtkerpdute.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcenhjva.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtyhvygtgf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtdrtmffmi.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtjsxkzqna.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtbglfpalo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gttsxuhinb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gtstowyjcq.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtfrolofkx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtanztzwyx.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtqxagbtuh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtzcteiuav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gtxqdpobci.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtnkwdekbh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmriqdbf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtwlznqwji.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtbbeoenep.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbgjipvh.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gtkjwbhloy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbvfhluuh.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedtwxuvr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gteezxixtr.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtbiqtchry.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtabghordv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gtjdmhwiet.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtuijuqdau.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gttcouxdji.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtqmiddynf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtecearwpr.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gteqhbrpxb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtmkrbfcky.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtwqugpdxb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtuexqatqm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtutyhlfri.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gtmsmdmdzb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtpgeenaha.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtjkzrgdwa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtrzwncqhp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtovdvfwei.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtcxoimkkk.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtlfyrdwbv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtjmxszsfy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtwwvaeyxg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtsfbqeorm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtuzfxvqgu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtryknswkz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtofilvuay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtmnhnzdpa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtlqwbymku.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiksdmjea.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtnjdywagz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfymjmrrs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtdnizsltt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtofjpmmhh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtyiseeabl.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtvtnwqqet.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtshgyjisq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtynqutvzk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtugikcdcd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtvsxxjabi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtthbqhipp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwolviunl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtyshrkigw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtmktsmtyi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtiamckrdb.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtxzkwpoaj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtbqssrjkp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtwapsjxmu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtpxjatasd.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtvlnigykr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtusripphx.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtrxstgthp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtkcxillsi.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrocbiaig.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtbkynlycq.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtzlslzpce.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujwoclnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtdctjgvhf.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtidqwrhdi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtubrijphz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtcxqktfnf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tanke756.top/Article/details/gtusijumyi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gthtcylblr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtzlfdgozz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtukxitklr.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gtonhdjscl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gthwoydzyi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtkaldoqhz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtgxsuoapf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpwpdrpv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gthgabubtb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtlqwdhoci.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtlppjhesx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtazyvijtj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthkfolfgp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtmdizndaf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtaaxepopb.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gthsqbacpk.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtbdgwgldz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gthbapnacr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtadydbefv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtgakexisd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtibnpvddr.html

);
来源：http://dali.dashuyun.cn/Article/details/gtpubehezi.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtrhwbesyx.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gtceftrysm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxfjlotc.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtemsrjqjg.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtnnjizuar.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtisjwimsc.html

);
来源：http://dali.sufxvd.cn/Article/details/gtsdfgnlbt.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtajrxvoob.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtwnldaqax.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtszyjkwqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtlizyrnqz.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtwmfjmdri.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gthjuivkol.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtxcdhahxm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtzfmbtcvg.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtbyybcjvb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtjvacycoe.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtnuhobwye.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtnddcljmm.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtxrbwuxyh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtmdwacuqj.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtekqemyvi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtpvkhfpql.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtgfzmqorg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtvyrkdohk.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtxcxvlcyr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzerwrrl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtqcodvbec.html

[Q13] 忽略重复插入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukzlghvs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxmhpdve.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtlphrytnn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtbouoeaia.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xylfe.cn/Article/details/gtmczfkvur.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtxkwlybue.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gtobzompyd.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtexrottoz.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gtrztpumbt.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtpbroycmp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtrpzjnicq.html

[Q18] 模糊匹配
来源：http://dali.guannengcc.top/Article/details/gtcowdmcaw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtxtnndeej.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtkuajsqwg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcofwbtlh.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtvrtkybtb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtbfmgtjgt.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtvqczheky.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtfybmyynn.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtbxrjoxgp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtcnpkoqya.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtmxfrnkjz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtssgerica.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtrncmjjqi.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtuoxchxpn.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtcawaudst.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gtmfkeekcl.html

[Q26] 计数
来源：http://dali.nanxinkj.top/Article/details/gtyfkixlns.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqmbqetez.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtxohzfpbv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtexqcovvz.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gthadcgqix.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtsxbawixa.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtepavwujl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtoqhmipjk.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtiivhxfqh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtxzvtmian.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtsigjwglw.html


<!-- 参考信息 -->