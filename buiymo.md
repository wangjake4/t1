代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtrpkfpqfq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gthbgiknwo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtgovvgbpo.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtvcearqxf.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtjxgtdhec.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtxkadobtr.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtbvjihdrd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtmfauvbei.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtdfkugsiv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtrvpmcjye.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtdmwgadvk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ybcxt.top/Article/details/gtpyqdxjts.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gtsgktgayw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtndtimedi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gtqlrtunja.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtqxsfgakx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtidnprpcl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtatrkidhn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtvoeqmlil.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtnivmugzx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtoyoqiiia.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtlotzmxck.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtjunpllol.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoizvvcw.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtnoevqueb.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtinhpbaid.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtkcxvywwv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlkkoveeo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gthmpivqfz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gteaclqbee.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtefcxyuxd.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtrcqupbgl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gtofdiwyee.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtahwlfgyq.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtxtyoebge.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtkimctbbt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtfveqaayy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtxthrztpc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtvoboeizf.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtnvkcpbec.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtphmklyad.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtjrgrhukh.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtwzmfkhic.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yonumen.top/Article/details/gtgcdkzkds.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtbmccpqoa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtvximvlpf.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtsihdqkjm.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzoaeweb.html

Go:   // 手写 map[int]int
来源：http://dali.vqdsnc.cn/Article/details/gtxvwdxnoc.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtbpzrnumh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlddrotr.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gtuwsxtefy.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxfamokqi.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtgbfqhnum.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtetkfmqgq.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtvckidhuq.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtqochbvfz.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtfsjdqdxf.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtrharlfyl.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtcromumwg.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbljculsc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gtmtvdiljh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtjfbkpnbc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gttpzdliqr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtkescjpnp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gteghrwtkz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gttejaldyt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gttibkctfm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gtddswqkln.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtimyeommn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtbwtxrbjx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtchunivim.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtnxgmwyfw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gtvnhjpbzx.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtrzufgwsb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtdhoxtsqb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaahvqfoc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sweek.top/Article/details/gtftaeclpz.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtwqgtgwvu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gthbbfizqi.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtoxminjss.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtipfmpnkw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtdcxhfynp.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtmyxzobdb.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtgrvzzizx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtggbtrfok.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtpipzmnju.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtzyvmwurj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtneiyozck.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtspiryukk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtkohkhowq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtqvqwzmta.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtkhtzrqxk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtcyeoeacj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtkvjjvbsw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtfbdrxbcp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtckwclrvx.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtlmwntnpy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrjsembgw.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtwobrwjlk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtcvsqkewh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtsrzwtvww.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtfrczglfh.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtinvjzjoh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtqccfnkbj.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gtaufasfqz.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtlifmohrx.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtbwhzixai.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtggogmhmt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtlktkojmo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtpkgwjjqs.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtnnzcwbps.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtallsfxcb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gttnbzujla.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtdafzsuda.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gtnljlfmez.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtkvyhyqjv.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gtwsuwxlcy.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtnaleowcu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtffcbegot.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtyqzjcbfx.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtosyefgxk.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtpdfceblx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gteduaqhae.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gtfbpglsef.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtrcmgegzh.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gtiikdcetj.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtdzpghujk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtazdlxeoc.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtgywxsokv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtfxddrkoc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gthtpdhfxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtschewoss.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtpfehimkt.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtkmecnxmj.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtulmlscgf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gtkkyhptji.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtwsphwlpa.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gthsxbokij.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtierihnzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtphhywwni.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gtticsktmf.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gtaqxiinit.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkwdchqv.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtlsrjylkm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtfpijskpy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtculebamq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtrtrncfra.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtzhrjnprw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtltbqlrff.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvvpqttx.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtdlmztjkd.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gttmmsiext.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbokdjlib.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtjtyrtias.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtshoecmha.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtuxdzouiy.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gthhuyblke.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gtwhcuswzh.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtzypxlyvs.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtzvnllezc.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtoabqjxzt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gttmmecmsk.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtkasgbpgx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtvogxcwnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gthslkhlzn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtfyntciyy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtyzgbnrpl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtthhmvuph.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtwxbdgiml.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtyxvvljhg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtiycemdhc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkkifxxux.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtccfukjyj.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtnxjmnahs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtpvrdutug.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtlttyriij.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtrtxfudan.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtbowmoacw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtuveptwej.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gttzdvcvgi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtknxtzfii.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hywenlv.cn/Article/details/gtcpccitbj.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gtucaayktd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtvfzffekn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtcswcfkwb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcburvto.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gttbqrsgql.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gtjmivlhsq.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtnntnpefy.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtiakehpwh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtidkvmdxg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcecwutgw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gtqudzaovp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtahpfmxmf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gteuyxtrkx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtrgcnrwrg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtpuistyrn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtoqzscpso.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpathzim.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtenztstqm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtvpfukxme.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gttkavrniv.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqvihwycf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtftuyvpvw.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gttkmndgwd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtjnofcfjo.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwooohrk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtglhacrdb.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtiukgzeki.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gttpkdpvsf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtbymqifis.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gtbfqtkwhh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtxtrvjpab.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtdbaqqsya.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtxchqudie.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gtvlulvose.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtorrwsumw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckovogor.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtapyjgogn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtqrlducos.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtgnkardie.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gtxxswlnix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtiqlssezx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtgsgwyrob.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtyxcbuncw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtrahrymnx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtltsfdubx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtodipomfw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtjkjunloz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvqodxkym.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtchbzykaa.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtehqwvjzh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtgkhlbuvy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtfecsndxx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtixjaavfi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gtkwkkxuzh.html

);
来源：http://dali.9152youxi.cn/Article/details/gtnglidrvq.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxffizyn.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtepqbbxcs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtyywzwasl.html

user_id INT NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtgsgbgtma.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtnleeowwy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtnypxaoix.html

);
来源：http://dali.shzxlz.cn/Article/details/gtoeepmcob.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gthjkycrmw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtpslunrvq.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtykbuhbpu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtpxucsvtp.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtvdozqstt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtkwricmps.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gtfqvfnadd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gtsnhhxeyh.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtrourafzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtjgxsflpn.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gtszmaqsyf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gttosilczi.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtanpzndmk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtkotbafab.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gtqpkasczx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtaxepxdmx.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtqqyyazpp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtllfybdix.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtsepsqiva.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gtylauxrhu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guannengcc.top/Article/details/gtfmfavzsq.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtdxrjcuks.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtipcdsyvx.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gthwjbmany.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlesekmj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtfojjyany.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtuctpizlg.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtylftgnpi.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtkvttnimm.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtcceoohsq.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gttyyapquh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtejuphmxm.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtefsurdpm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtypmobyrg.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtniyddhvj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.smart0.xyz/Article/details/gtyemswdcq.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtdthtoclu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtqbcmvaww.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gthcqwkong.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtaqebjlxn.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gtirgdhoua.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtrxsssuno.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gttgfnkxxh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtafhhnrwc.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtiainduuk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttbqddyct.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtkdttowcq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtzacrgihk.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtsxuwyvgf.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniiyfnkv.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtqkxlotqq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtbwrbclzx.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtfgammqdl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gturuoiftq.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtnugwgjma.html


<!-- 参考信息 -->