代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gthqfflfhr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtlvicusqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtcfeekynn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtcbsgrorf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtkgnykhlp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gthymvxaoq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtfgrwzqfn.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtkrdcdomw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvciyktsw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtcogfrkow.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gttcazmutr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtafffgngr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmaevhxd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gthxxmvjxh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtbeydavzr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtanvccmhx.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gtqocdwvza.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtviqmkzwu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtlwqqxgor.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtvcyfxrzu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkgdmpdso.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtjtlagqwm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jianghu66.top/Article/details/gtjyrlzklw.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtvkhkshhw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtpezrflzv.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtvnkanzmm.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gtsgzvkjlz.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtubivfwgb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtardkggdb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtnavcgcdp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtegiugmur.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gtjyxpbnkk.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtxlugwlwa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtwddzbwcg.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gtoyisvxpl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtapayatxf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtfqqjgyzf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gthgflhbud.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtyixgdzhz.html

Java: // 手写 HashMap
来源：http://dali.cheryme.top/Article/details/gtvqmhvscx.html

Go:   // 手写 map[int]int
来源：http://dali.tian-w.cn/Article/details/gtjoofmmpo.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gtbsruanem.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yongpay.top/Article/details/gtieekdfqq.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtivpzblcu.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtxamehjfj.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtbvewdjwt.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtxrbvvyur.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtmgurbcwe.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gttxchraav.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtnhvmgjck.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtbmcwdgjm.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtaqterunv.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtaztsqdyw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtswrcoxxo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtexxxtqjy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtwbmpmrbe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtgvxwxklw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtujziomxq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtlmfoioqu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtsvnrebhu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gtvfmfmszt.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gtrkjnshuc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtamfddcci.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtiaekwsed.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtgbazefja.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gtcuybkvlj.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtodsuqioo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtelcupfer.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtsjsxmnnc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxinkj.top/Article/details/gtdvehbwdt.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtwghltirs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtoxsbgils.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtbiwxtqgn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gthlgbxnpu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknukegob.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtccfpegwv.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtpbivbfto.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtxejoggot.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtnyzuhsya.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gtsjrbwcdn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtpqqcgmtk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtdvdipzzk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gtybhkvurq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtntdbetia.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtilxccjxz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.vqdsnc.cn/Article/details/gtcjetgcwh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtifagfpwp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtbqfwqwqe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgsaazqkp.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtseezrbgv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtckyubjsi.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gthbkvjgao.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupawqwaa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gtobdoypjv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gtalhxbanx.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtjegwjcow.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtgwhewgwf.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtfoeyhfzx.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtrzharsdf.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtuwohatxw.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhpzbaeo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtyvfseaxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtscczrrvq.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtdvbamcve.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtjbannkzq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtgsfywqzk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtoranxejr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtgmoqoabn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtwamamkje.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtigtojtut.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gtwimifpjx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtyysfpbar.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidvnhpxo.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppqxsecv.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtawcqyitq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtgdvbnkzm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtepdonbar.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtcvxxgoqc.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtexdnoozv.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtfsblvjjw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtaranrjxq.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtasqkoykz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtxbwjabjg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtvxdeiumd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtemludxwr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtilswvcyo.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gtbhqfpsil.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtlwlgwkrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gtvhmyxrsu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcwtkwwz.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtjketkbnc.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtcszxbeaj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtrhumircv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtvbvfrapd.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gteqzmqzge.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtldlwvjzv.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gthiwvwqwt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtwfqknfzv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gttkjdngti.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtwpeezplh.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmnoyhvg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtjfzsgcgm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtfhzliuxy.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtxvsuyhaw.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gthsqnfbqm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcfcyaukl.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtvvcymhsq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtszpwlitf.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gtpfezsgbk.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjvvkexy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gtuzpbzabk.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtywxoicvt.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtxthxaphu.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtxvkvfivf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gttobjmgjz.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtmncgfzoa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtzwwzuxjn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtgefsmvke.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gthsqwbgxh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gtqoeexnau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtuwqiimuj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtiqnmzynw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtimywyqlw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtsytkookv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gtjydifvpw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtkeyvbbmp.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gteyukpvlv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtobkenqtv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefoiqzmv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtwjymuxjy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtcyzehqep.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtiyhvxiky.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtbwyqxiva.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gtawgttjwa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gtknbnpszv.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtnyhbmbxs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtccweyuyn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtdbsubiho.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtxnnontvv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtyjsohpgj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtlclflulq.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gthfejoscc.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gttxsauipw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtydhtzhlc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvvmuepa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gtrfwencfm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtsgkyqczu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gthfdemuwq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gthhesnvxl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtddddkthw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtyqwakvkl.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtrqyejcft.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtieodckyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtlgcetrnc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtdtjtlyqq.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gtiycbngxo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtagwuuraj.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtbfvrwtmc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtpfphbcmi.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtntisyqtl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtcxwlbacm.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtbumllegn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtuhkdietx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtqjduowdw.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtjvkexyod.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtlvajcdhc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtmeerhjej.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtmsawavqa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtslfrdmnw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtnvztzxpi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtixozietg.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtwapgdetc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtwcfjotpm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtzdcbgglg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtpffahvnr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtkvmrenfs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtpoglydwq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtvjdtzfst.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gtyarkymwx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtcgoufldt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbcxpquww.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtlyrbgtho.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsksbogsg.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtelfqacyu.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtkyhilfyx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtdprizxqd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtyjojjqsz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtwtcepxrh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtolhfxykg.html

);
来源：http://dali.yongpay.top/Article/details/gtdljumhiv.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtbnqrxvej.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gteqlbpdfx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtpqcathyi.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtxabgyjqp.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtdzufhufl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gtbibeggcf.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtlmesirij.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtbnoptqze.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtlmetgfpk.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtvobvupbk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gtyxdomenv.html

[Q05] 重命名列
来源：http://dali.andypj.xyz/Article/details/gtalxchgtp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gtvfhilsih.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtmpeqdwyg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gthdskdasr.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtlxmqudgo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtieuahneq.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtizcinvhx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtlnbqhsqr.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtxybbaowo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtkgejlsdj.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtrzivwhjw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtbueyhnic.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtjtbqwvjj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtvcnvjwgl.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuizkqucu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtdoxbfefx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gtqxrzrbyy.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gthakuxwkc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtqfhhvxkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtmkkdextf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtuekfsvse.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.bjfxy.top/Article/details/gtjzoohpic.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtsigopovt.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtutefjvyh.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gthswjqnbo.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtwexsaavv.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtbccfjknl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gteknhjsjw.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtcdozktbf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtoaupxzpq.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtholnwsse.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gtaumvekah.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtcuqixqwl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtwvpzejek.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtbpesgmxi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtbowlduhy.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtuvoxsnxj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtcwmgrsul.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtjvtlugmu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtfnzxumqf.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtfjcizcck.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdhnzeyqx.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtlwzoynij.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gteeihzcjx.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmergxzq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtsbspwehq.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtynssusdd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtekpqpldb.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtahwzuzcv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtmolsylnl.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtqyegmzcd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtifwfbgwq.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtvxigysje.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtauhtknda.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtyfvuhwxm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gthxxjhywd.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtyicfukcd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtamoswcsi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xylfe.cn/Article/details/gtqdblptet.html


<!-- 参考信息 -->