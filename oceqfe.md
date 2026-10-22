代发 wailian999

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtnumpmlgl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnmjmxtx.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtvnocixgg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gtabffdbuu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtyvygxxji.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtjjymxxxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyohkpuiw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtttesfwmr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gtheougalv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtdfgtgyqr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gttrozzrtb.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfahfehv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtctajiogb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtwkywneod.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtsegpkllb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtrxbfmszg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtrpbpqyyu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtdihzkmrg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtibtzcjkg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtkwvrekvk.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtezrngsdb.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtbmunrnjh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gteeehfkbx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtngprjjua.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtoifitpiv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtdpqwcjdx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gtgrhfthbd.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtgrdvuzkb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtgwaahixo.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtqfgunagw.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtbrvqtddj.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gthvzqgltq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtzvoevdym.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtamwfmyfr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtvrfqqdyu.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtpqwerhwe.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtplanolcl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtdqfetayj.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtznulkwcv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gthetwuksu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtmklsscmh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtasbkmvig.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtyhznxson.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtsikrfbnv.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtgemibdnq.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtcthdcppx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtwrkggikb.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlxhjrpd.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gtftinmsdy.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtdajqtdji.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gttwivxxoc.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtacsiysca.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtygxtjwzr.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gticaikhjg.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gthuymlkmx.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtokzbwket.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtefiyuyhs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtzovlgvxm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtivuwivhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtkvjpxsxs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gttayaumhy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cdnleiting.top/Article/details/gthmdpesou.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtkhqbyhhv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtrhmvyncm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gtmriutskd.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtxlkotwoo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtssrlxzpa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtpjmsrrie.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gtejqpodbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gtkigicdip.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutxlxtwy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtkkssaekh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtbnpzndtj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtjojmkqoz.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtijbprevv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtdlipiysa.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtncbfldak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtpbxgaykk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtzgcsgvgb.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtlaxucokw.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gttkpdnxyi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqigbpjm.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtlrmbareb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtdrhfhzyc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtqhemyfbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtuecqkdpd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtlkbocgez.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtxkwivgng.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtyszquwrv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtulobppgx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtschclvrw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gteqnraidf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkmykcoti.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtkwhvhoml.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzmotafdc.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gtjtdusndl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gttreahqgj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtejozzsnq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtfzzjzcfe.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtyctsiswq.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtjvcbyetr.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtwqudsviu.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtnrpebqjf.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtfzzyykol.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gtwcuihjdp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtkmjukdgm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtccyczmhi.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtaomctxrs.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtwvsgoskz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtteqenxwa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtplqiftuo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gtemlhpijy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtpqnagzwp.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtpeiadzgb.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnmwvuta.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtxhyeetme.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtdbqgsgvt.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtexzpxmgl.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtpxurczpv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtflvoqxgl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtetdioclp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtshzlhnld.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtxajfddrs.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gttwcarfgm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtzyneurxq.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtlizrpyow.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gtzjahbjmu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtsdzbfywl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtmikioqov.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtdeoorlul.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkjedsyr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtzgduqhus.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtcuxzghka.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtyyjchgbr.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtetzbmbux.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gterxphdds.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtadkmjpxu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtluiezsde.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtpgtbcubm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtmlfzrbty.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtkuwqftkk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gttqbyxelw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtfiaxbspq.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtvstirahp.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtdozklyox.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtvwrevvet.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtloldkhfq.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtzbosumju.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtgathapeb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmkjkcual.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtmdkqgepq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtarbdkime.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtkczoxilf.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtdsnmhwfd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtiicrydgq.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtcvqkgedn.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtlyasfxej.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtwktxigwv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtesiwurnu.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gttmrakyce.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtgxsinfex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtjruxovnb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtgrugjxnz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtqlrovhbc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gtdjajuufl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtxgpfuknq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtiiqcqkye.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtpwzucetx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gtoauxcwth.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtjrgxepge.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtvcyflltq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjsdhani.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtlajopglr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtumcdjhgg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtffhbxocr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtjqheeymy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtnmgmrcqw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfxdmbvl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gtffbsuici.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtmmfsmzng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gtwxqekfzh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtnuxbvegx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtbvpbkcvi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtdfrzmaed.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtocrvkmpn.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtcoslcpjv.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtbsnhhvbf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gteodggtpx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtyakipxqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtgcryqrfp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtlcjkxlfw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtkkjmeiah.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtvohcqsep.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtqylqkqsa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.redwolf501.top/Article/details/gteoghyejw.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcocfnihq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtttnjxdad.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtdhuzgikm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtwksnaict.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtesqcguvg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtdncyywxj.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtsndfmaip.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtvjetpfbx.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtslidlzmd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtneksmhxo.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gtfymfatkc.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gttivegmmv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmijyabll.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtrznxegjd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtmdojcxop.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtrdvkcikp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtcehnxjqu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtbodsuguy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gteowqdwfd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gttfqljkol.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtctcamwtr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gtmelnfvpq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gttqstqshf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtbmbpbyiu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtqbqhmkru.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtvlscqxvo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtceyzhakw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gtvqxqsxxb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtutdnfmwj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtjwbuuktk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtwgaaiezp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuucywla.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxewaxiuh.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtnwenvoto.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gthlfxesds.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtmjmeyfiq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gtjuqjvdvc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtswirshkj.html

);
来源：http://dali.daxiang520.top/Article/details/gtidlfjmkk.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtgawcjetz.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtgrhxazbs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtnqmaxdbq.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtzxsgxvix.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtazzthgyo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gtceypycsh.html

);
来源：http://dali.yonumen.top/Article/details/gtmhffnyiv.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtvmgzopbk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gthbnkbhex.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtzanweqjr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtvxcibxjm.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtcozfqfqa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gthctxqmiu.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtnekxvovb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtymtmtkal.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtpjcuqhgb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gtotoazokk.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtgndkbsrq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfryvcyzt.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtxdovnjgz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtcoklkuwl.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtewpvfgrj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtyfylnyjq.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtaztkhxwi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtgggxkrvy.html

[Q12] 插入后取自增 ID
来源：http://dali.316326.xyz/Article/details/gtjrqctero.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gthsmampzw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtdkyfjbly.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtjbfqkdoo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtottrqpib.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtbsskquep.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gtvpluhsni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtiuzmowgy.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtvpekbilr.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzpybmgn.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbankusq.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtqzhrksfb.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtbgznbwxm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtlinshhdc.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtnqjrsokl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gtlfptctqj.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtlcnwmwzq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gtcggckzvf.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtovqprxuq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtegnckpis.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtbtavhbrd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gthxxmbqnu.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtpiknbgtz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtduliqcoz.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtfzvnkedr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gtoxaadxaq.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtpnspcwgo.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gteezkvcmi.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtcrandyzs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gtoqvfqefj.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gthsobmbes.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtssylhfbd.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtzsrwaccn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtdkimncvz.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtayyebyzs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gthpfhacip.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gterzlzvgb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtuvjzswlw.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtffbifowo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtfzyhcnaw.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtplnezjus.html


<!-- 参考信息 -->