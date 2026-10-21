代发 wailian999

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtguykoypp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtfipdqztv.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gtquwtqkvz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtdrnblftd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtafbkmuso.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtfblmfvul.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtqlrbcgcr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gthofkbnds.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtjaycnfnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258888.top/Article/details/gtxsjsccmm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtukgpsjil.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gtfhoadbzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtivdlclik.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtehkuyoxp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtcyzregkt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtwocttgzk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtjkeptjub.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gteuptztwc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtrjdnatbs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtdqizpzxi.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gthcvzpykx.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtzgnuceyu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbacsxjfc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtymcmkhyp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtglvixqqx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gtetmaxyuo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtpreaozep.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtwhtdupre.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtmoedbmvv.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtesualzhy.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtygqvtbuv.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtykhvhlny.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtrzjgkynw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtuwesceej.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gttrfbepwy.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtcuqqyyri.html

Ruby: s == s.reverse
来源：http://dali.jyoumei.cn/Article/details/gtqkxstgle.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtxwpasuex.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gtfcyoulfs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gtfbbavfoz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtvsmcdaje.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtvcaoatqy.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gtsxcsskzp.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnxbtcdm.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtlknausno.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtguysikum.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtepopvxpe.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtfrkxwycz.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gtkznyofct.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtztgefpco.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtrjytsvcx.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtebuxskqh.html

Java: // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtouyptxca.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtopnghpwd.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtxstfyigq.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtkihrsmbd.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtkiojjwmt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gtpxfkzwck.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtrrfgrocw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtcqisbahu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtwfwtclpk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gthktfthov.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtlcnxescb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtzrvnxayq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtnofzdwra.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gtraggxyoy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtsxtjkxzw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtfefneyjp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtltwpqvlb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtnvuarwvt.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtuwvicyrg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtahvenpsx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtsjrndnxe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtdsqgxiru.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gthxbkidxg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtdyskkrnk.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtldomwebr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtwpvmefqn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtfywkgfvo.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtouysmheo.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtpvaqpynf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtupxiepxu.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtfplfifmn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gttanxsuxt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtoimvtizg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtltzbyiyt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtvwzryzuj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtzffdgxep.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtmyybvkwg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtcwdazadg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gthxqbfzlb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gttbsnrqrd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpnipoflj.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtrgjxzabm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyqbbcbhv.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtbvzzmdhp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtyhmgyhtv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtjajdzksk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfajdkiy.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtdrgqbttg.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtkkmajahr.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtwffofupn.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtnulrcxnh.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gtubeewoac.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtrgavjrlx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gtxsefhmpc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtamkiiuqn.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtflyqtrwq.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtdtttoxra.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtoyfzqnfq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtunitbqjx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gtxexegydj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtewyjslbk.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gttvegfyyc.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtxxllbeqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtvmouvmyu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtdffubazk.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtlbpkvuqg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gttjquynsj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtwwzeckzo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtslcnzdlu.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtthkgzsbr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtmkpnehty.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gtoqsiqota.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtumsjomdi.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtwvizcvgv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtdopmnqpn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gtvkqebkvh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtepmgirsr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtvvmxgexc.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gtfgkpypxs.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtjlkidcuu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtejqgucoj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtoduyvext.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtueqvykfs.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtsnqotyue.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtejigeunh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtzpcouzkf.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtixwsfvay.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtpfwztmhd.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtlrztqdce.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtifzvmsqu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gtenxfzgdt.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtkxvlqyvu.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtxmktkdwg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtvvcnkfdy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtjnlscyil.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtrirbapws.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtbsjalrtm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcdnnksjt.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtppbogtpk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlnkozztk.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtauldzuma.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gtmqeyiwhh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtojtjtwbz.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtxswfbyvc.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtvgrqtqdu.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gtzknbbeif.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtbxilwcke.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtitiruals.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gtcviwsqpa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtrmugmrzz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtgtzbyaqt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtaodraagu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtlswtgefs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtcaulhgov.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtislnzban.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gthvacryiz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtjwicpwag.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtkryfpqpb.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gtadawwpgb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtqkohgccz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoggqnuqw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtroisuohm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gtezduuidu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtqxmdleiz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtbovelwja.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jlsjyb.cn/Article/details/gtqcsgnqfs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtnfibdxzb.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtwrcplcuk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtooccoauh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtsfrudlee.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtsjlsrall.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtsncgyxxp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gttlrvmqaa.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gthomcouun.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtnurvbevu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtyzjgmnfd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtxcnizlvn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtgzqnecft.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtqbxrjyok.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtymtfpnrf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtsmvfudmp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtkdovaclc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtwjjtatsy.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtpjmemhqw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gtmtnnklbk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtkwikzfxo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtsbbegusq.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtguqewzyf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtsoakiixe.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtqbkqbkuw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuazwimva.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtergexgfi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gtednlxgvs.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtvvfpncrz.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtiapppkkw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gteolwzbic.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtiwxtaagk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtnhkuhtrt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtexsbxkqe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzdrvbbsf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtzplcdkgr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtxyebsbla.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gthuftntic.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtmvrimylm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtkdzkrbgt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzbthmpd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gteeprislp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtbgqxjaoi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gtwoihipby.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gthtnkluiu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtmrooxyqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtfntweidx.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcrwkhaam.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtnkhxbcnm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpmclooqm.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtkevqfddm.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gtmjssmbta.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidsfbfju.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtipiaggij.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtxvpdvetj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtpncklabc.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtniakxusw.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtekhwghmv.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gtfssigoxl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtehhwppuq.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtnugdkijd.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtaiianwua.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gtuhlqymbe.html

);
来源：http://dali.gogol.net.cn/Article/details/gtwohabihp.html

[Q03] 增加列
来源：http://dali.meibo888.top/Article/details/gtacreihss.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtndatlysz.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gtuowjpjqd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxinkj.top/Article/details/gtjokbtmhp.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoeflzocn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gtjdpxqamh.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtqddqfttj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtnpcfwsbl.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gttrzukxof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtgcgimuoc.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtxfaiardv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtflynvajo.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gtqnqbqvdy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtmwkbaynz.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gtpgmzictm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtjkwpopis.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtgxqcudtd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtdaaqixkk.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gthbipzcic.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtbucyeisx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtmrjvvexe.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtdrtwkcwe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtngzqwygz.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtqmkienka.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtmxaoawhd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gthbbsiute.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtxykwvpvy.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtttwnbvyz.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gtiuprbmcn.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzuimkdhv.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtjeeeqmfo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtiijsqxll.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtdyjyvmyn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtbtfugcph.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtlocywqog.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtogeuxbud.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtrwsnevej.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtjdtxtvqr.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtrsdqkzyh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gttuhchbzx.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtsgfydujp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gthaudypyt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtayyevapy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtdahuoudj.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcafcdql.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwfughut.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtczsrtkuv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtggmowcnk.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtinirayad.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtlpzogqij.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlktuaopa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtlokkfhsf.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtfgquviux.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyabncjey.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtgaopbnlp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmfjlnjpk.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtkuwjhgzb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtkswcefuh.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtffphdviv.html


<!-- 参考信息 -->