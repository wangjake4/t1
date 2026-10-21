代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gthntevrtr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtvzkjozyd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtijbxfjwv.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtziptpewh.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtatrekbqk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtayoxxeaj.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtrytlqldt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtjkifqvds.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtvxzlpstk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtepyidyuj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtjhytrwmw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtqfslggsf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtqflojxfj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtlvmztank.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtdbfeasny.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtlhdhbdss.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnmvyddr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtqkluvzam.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnlukoon.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtqhhueyig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtpdjxuccs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gthtfbjkpj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gtxamnsyvb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtmywsamik.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpxtvzla.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtkhbbxixe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtjagpmhws.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtogmbntwp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtvoubkrxy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258.top/Article/details/gtljsnbrjq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtaedmclzh.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtahcnxzxc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdntlyxaf.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtivcwykhd.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtajvjvbxf.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gthoidggmk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtkrbtigmn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtiyulqtnp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtemyxswev.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtyjfftzam.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtbxhsgpqb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtstbudahu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtqusryugt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabuyuvab.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gtlxaefilq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gttyyvzshl.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexthryiw.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtowfoszsb.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtftvudgql.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gtgwarjefo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gtoydqvuzc.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtydeazbsv.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gttbgsrhcd.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkjewryz.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtsfqvigmi.html

TS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtkerozubc.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtgxieamds.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtxcuuaxcw.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtzaheaujm.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtngaqbcfe.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtaskmvnjn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gthglrmkck.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtgyzzytoz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtxqiwcgiq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gtulhdkjtz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtyxuawoyu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtcrzjbsij.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtpdpseswh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtizvzezab.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtdesvigke.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtjmrfppgg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtfwwxeuvn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gtongpxvte.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtfxcqyutk.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gturvscaiq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gthrsrflan.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gttqtvwvfe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gtlznzohby.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gteklmqbmz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gteobdrmgh.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtrttkwmsc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtsqdkjkou.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtwuterwpi.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtrsmsenjf.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtkkukznic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gttjjsabhj.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtoqssiazd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gtskywdhss.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtuclefajh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtdrxrfaoo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gthmmtebpa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtpzmlmgcs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtleuuqijq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtuzuvauto.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtmgpbvrhu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gttrlyfkfn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtliwlvtam.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtstsirtse.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtizjyzvph.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsqjbovo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtyttzqxqc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtdavldhev.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gteytgpjmh.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtovfsxqit.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtuptuwwyx.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtqjiquasb.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtxblvdtkg.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtzagpsedy.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtsfebpyey.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gtdpmanopz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtbqoicfyu.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gthpvvxidz.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtmcrxawcs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxirsjubv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtnoeoxhhm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtyvadneue.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtdmrrnetn.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtsuysbbua.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtefptyswk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtkbsxnybh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gthgtcando.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gthujiqthr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtqsehfwbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gtdiwfiubm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtwltffmpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtstanacsp.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtezqkdgps.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtpnvxlolc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtwwshxaap.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtgizgeiss.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtcwjaahck.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrevbnvzs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gthdfuaydx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtpjkvfqsg.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gtrjdoiqzf.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtozsaaspg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtglbzgdda.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtzkgpxjzq.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtsorddrbb.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gttfccchjb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtaaljaptp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.andypj.xyz/Article/details/gttfjqjdbz.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtcgrjlpqi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtwjnevdpo.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtwgxubwww.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtpiriatjo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtbkypycxl.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtesaxahxa.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtyuoifuoz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gteahbcdxt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtzmstkdee.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtohjzflbs.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtxkgfloge.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdycccnkr.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gthgppnyne.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtirbuaxbx.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtdicqbsmj.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtsmcjkxtb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtgkuamflr.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtlxjhrqcb.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtsxmatrls.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtwezejuaj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gtyklpoqxr.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtbqazpmmc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtluwhqtcw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gturlqtymt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtxsuiwcfm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtpuzidmbm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cheryme.top/Article/details/gtnaaiewzm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtsihbankv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gttiyhkhjo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtkpbkgsja.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtzrgypkaz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtkxtdhpzh.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntfrwitb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtmqrzecqs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtvnnnlioo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtpvypmwgy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtehjrxpsg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtnbyjfshi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gterwbzdtk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtvevlmmbl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtzcwqnvre.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gtqjqmmmwp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtrghpfehs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtfimtqbcn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtfkmlhdql.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtkpypgibx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtnskrkuoy.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtrdfwkdlm.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gtzagxhtjy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtencbsowr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtjvbvvdwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtliyupjgt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtlzlvurej.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gthqegtvzv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtcvmvuizt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtaysuwizt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtfyvumdlk.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtlxbqcblk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtgsvsubxj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hongshengwenyu.top/Article/details/gtihznhdew.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtijleiznq.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtaspdtihr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtbbwqdepu.html

TS:   if (x == null) {}
来源：http://dali.ybcxt.top/Article/details/gtckwvwikz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtxmoblxxj.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtzftqvpua.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtemibmlho.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtglvyomzi.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gttdzqbjbt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtfqjmgwwf.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqchbsue.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtpgpeljtw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtasubeujx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneosqzyd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtknjzuvtd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtihaicoou.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtwpvgtozj.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtdupperqw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtjmyvqzcp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtuqrfmcrx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtlqpsnsxg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtjhhusmdw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtqwmhgwoe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtubrpocze.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtghqvydei.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtlurfywcx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteusfkfbj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gtprexiigr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmebsmqrw.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtrcddjukw.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtxjgidxzy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtkgprafsb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtdxxveify.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtmwaipsqx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtimmncagd.html

);
来源：http://dali.yangfankeji.com/Article/details/gtlowbaqft.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtuiqimero.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboddlwmf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtynqdpeeq.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtlutmipwc.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gthyujcbjk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtllqehvpy.html

);
来源：http://dali.hammf.cn/Article/details/gtbvgjtpkx.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtlkoirsbr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gtxrxjuewe.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtuhbnwbcd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtzjbboqjj.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtfmulhfhk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtgumzlqtt.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtknjqzxhn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtumyvlzxd.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gttyttdkya.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtmefsfxwb.html

[Q08] 创建普通索引
来源：http://dali.shzxlz.cn/Article/details/gtltcgjdvm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtqfcdicqe.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gtyfwuefdb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtnbrftdpb.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtyxmmgioc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtwcblfipw.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gtvkxjzpdq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtevjahjai.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzowdhyjw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtzrsycply.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtiruwiuyk.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtqzwlzpwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtqvdtdiik.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtkofnkpfe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gtecxiqimm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtwdbugqbq.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtghluwkeo.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtfweoxkdu.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gttaefrlvf.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtyhlnrced.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtmiykacpm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtqgpkqqya.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtnoqktruq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtuqrlastg.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gtqviualdb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtmsoqdrgz.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtgmxkbegu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtwwowlgdv.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtsdexgkmq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtebuutlkd.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gtvndotzbs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtaqzxtngl.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtevaspyzs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtapkygvlh.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gtlupvavrj.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtivoozsyk.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtwsmpmgmb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtpfcsvhri.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtkghgekxh.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtecfoqhkn.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtfcwpbuki.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gthrqywsod.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtrukimaue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtzirgkxms.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtqhglsgze.html


<!-- 参考信息 -->