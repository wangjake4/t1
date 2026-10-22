代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtljkdtige.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gtpnseebxo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtrpbiahlq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtxrkpeayq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtwwtipmtv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxafwaps.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtbxmrnwpv.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtqdbfjbip.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtgobaluie.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtawtxijnj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtzfpokqlm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtmscsaxck.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtdydghltf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtdyquoirl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtxnjhygtd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtcauzhohn.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gthnepmwwu.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gttxryqtei.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmrnmbltd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtgnefvjsb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtgjcwqyus.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gtcsiavwrn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcncohqy.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtaukcphpd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtnpwmeywh.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtrefjnral.html

Py:   s == s[::-1]
来源：http://dali.xinyue.icu/Article/details/gtiteiwrvq.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtjyjsgiqu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtotmrsknf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuihwbwp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtoquuqykz.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtzuitrdxe.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtldgfcvgm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtlcjkwnwg.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtfswibxvz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yueranfly.top/Article/details/gtawmaqary.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtnrdoztgu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gtpavqbkij.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtoepigowc.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtkzfuvtob.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtmuevnbmf.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gtueycyzpa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtjktysxwj.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtnltdvxzs.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtoutwnoji.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtxhjopadi.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtzerrnnez.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtxfyheqji.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtbubojxhk.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtbsivkrku.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtysrmkedz.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtchkhnndo.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtfypvluaj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtrlxogybt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtufjstpua.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtaisrnqhu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gtjpmksqrx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtmdbmkmlx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaodfmbf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtwidzzthr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtqsnsljjb.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtxivlgnqf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtdoybeauy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gthvsnzzfj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtkyfzcszo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtynncfdgt.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gtgrrfgjzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtsacsnwsd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gtqwyasfzc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtcycrmgce.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtzmjkwmxz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtomrzgrvh.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtbabkswvf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtpdodusfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gthojjeeuo.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtrwyxaboa.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtrweokhoc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtohvqemsn.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtrvqhtkee.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtyyzctauw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtwxktyynm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtgmxbxrje.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtknwmlmpd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtrfrpnyux.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtonvevxen.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtfgyzwzub.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtpuqkhena.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtazzkxvmw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtucafzgeq.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gtvyxidloi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmhgmhbdo.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtasvnnekh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtgdyqrufd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gtqecjcdjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtlbgoueto.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gthzcspsov.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkulwjrxq.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gthjztlyza.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtrnipjxvd.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gtjeqibvsf.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtvtnfavsq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtvcjwqcjx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtfuxkjvzw.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtfubemgox.html

TS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtygjmriwe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtfjvzjlcr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtmjqfgkvr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtvkvwwffm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtjvyqpanb.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtooddfcxr.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gtqimhcssq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtafmkqfix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtyhyqxwan.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtuhvheafk.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtllgqifpp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtadkjnlrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtoatbuphh.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtdyfizwqj.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtelcvakgr.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gtszmoqpgp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gtpsxzunyp.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsahgatsp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtihxoehie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gthbyxfdeg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtabjnvznc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtvefcamxm.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtkxkaxdjh.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtkhvuvpjx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtivegeozo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtpimwmhot.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtkylwryiy.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtexiwoqxc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtbddmjujl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gtejtxbvly.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gttpvamkea.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gtckprnnfk.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtnaccwuou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtmkguyuih.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtiiimmkmh.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtiaubrxir.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtanlnmamn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtmsqmfgjy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtshjfntdg.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtgtkxrdzd.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtlwkxomzg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtclbtrlbd.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtjptfwweo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtumhaqlel.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtfddcnpfo.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gtbqursnqg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gtkimveexi.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtpzpiuchq.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtavdmspob.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhengqikj.top/Article/details/gtdptsauoy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gthmxcuegt.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gttpjrfkpa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtkqhtuhia.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtkhmhuesa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtshrgvlzu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtrljywynm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtajziydft.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtknnempcm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtruwmmltb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtymunsesk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtcwoemyra.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtucwnamup.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gthydtkgrc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtqsrfqvtx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtnujlnmbp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtsryrfnbi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtyhtqutet.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtxzwxvsrc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtutsnbimn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gtytqfivaw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtmteodulm.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtirrwuinn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gtideyqiuz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixegejyy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqsuehkj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtudqnzhfk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtfoflibrp.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtwmsuudcc.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtzekpvmpt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtwbvjidpc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtfzbfszha.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtncuevcga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtxpksowru.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gtiyhvguac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtouomjxra.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtdolvnppi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtiaolfdiu.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtnxfwwnir.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtqgohdgnb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtudaidajd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtvxqewvxb.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtjlfdxokz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gteyewnhbl.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtjfhwtvnt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtjepgnpnt.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gtlytvvbac.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gtkokpfmdo.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjnrtwkui.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gtzfowuexx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gtluqcozqv.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gthaynjkxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtqwhgjjvv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtrxzbplgx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtujqkfltj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtfjjmgnew.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtbvukyxhb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtmvpqrutx.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtrejhwqlt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtclprcvfe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxbfpuwj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gtrzijamcs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtlqrnksea.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtuqtjibiz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtollijrxz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtmwvtlmcx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtnimrtclg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtznoqgbht.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtfzuffhcb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkjuuadgi.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtzupeyrvw.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtfytbvvbq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtfxjofxsy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtyafpfxds.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtmtkcyhlx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtcpwyoftp.html

);
来源：http://dali.jqgfzy.top/Article/details/gtkqpbuffc.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtuatsotad.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gtibtlgbkx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtlonxnowf.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtuauejtnz.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtzqoxerri.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gtvuoopvzz.html

);
来源：http://dali.bjfxy.top/Article/details/gtjxsyqymg.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtknvcnopi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gtgwypqeyq.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtocqjulzd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtpidxbbbu.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtlryplygh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtbbxqobmd.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gtxxavzkkf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtrkdjjxeo.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtoqsssfqy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtrdsybpjj.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfozbnnh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtzvprcrfx.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdcvkchb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtparkarcp.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtnqppbpot.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtzilujxub.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtcycogxvy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gtvvasgtow.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtulbgcukb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtnsjwmbdb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtaymjcybg.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtolvbcrjl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtksdskvtl.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtkdicicwf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtnfqjyslx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtpdromibo.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtsqnlodwf.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtfblpunll.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gtonqhoidn.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gttbhtmzlo.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtvanxnhtg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sufxvd.cn/Article/details/gtmuxgxfoc.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtuuubbbob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtdiwhxjfh.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtoshhltyx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gthsonzevb.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gthsmzjieo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gttwhrcldd.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtzqorhpqx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtxabtknag.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtsmamsiqh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtyucjwqqy.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gttyhqhktv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtihsvgpbe.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gthjkmlkcc.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtvpxejnjx.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gtsrsvhncu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtihljgrzy.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gtgplxikru.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtqfpyctiq.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gthbemamjz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtismezzeh.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtfunhyxts.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtjedwomne.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtrivqlryy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtyraildht.html

[Q30] 分组统计
来源：http://dali.ppjwa.cn/Article/details/gtdonyellk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtrgbzybuw.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtmyvhpmdi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtlypoiwas.html

[Q32] 分组拼接字符串
来源：http://dali.fengsongda.top/Article/details/gttgbtxqks.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gttubzmrvw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtyxgdaxmb.html


<!-- 参考信息 -->