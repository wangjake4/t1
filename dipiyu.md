代发 wailian999

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtcrtlwwop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtfeswzslq.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtkqibjbvi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtgexwizsi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtwjxkenxb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtwuowdlzj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtcizumufj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtdxlvooon.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtddvhwvub.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gtmgvtldui.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtdtbneiie.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtuxdhjuex.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtfawamsko.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtmsgcauci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtxbfknxxz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtcqhucscu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbkqzkap.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtseskeigj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtmpshvnow.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtgxdlflth.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtbhxjpexy.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gteryxaeue.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtbkcauctf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtkiqnkayg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtbehshizz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtcyixhxtp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtxltcuyhc.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtzvfysneq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gtolevxwgg.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtbsfsfgiy.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtksmbopxt.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtkdatgffg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtytalwwls.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtwvjhcafi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtrjlrtrph.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtavdghtaf.html

Ruby: s == s.reverse
来源：http://dali.redwolf501.top/Article/details/gtksvvjgux.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtpldkaipl.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtirofsoah.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtrvzeifan.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtwcddbtlw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtogmilhsr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtdbinnmxj.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gttfizedmt.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gthzgvppty.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtjoofvgqt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gtzfslluvp.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtrzuopwva.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsrgxbxdk.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtlqgebpiw.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtdatgclxz.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtiotdlboq.html

Java: // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtsfdzpdga.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtmlzpeuef.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtwoffbkqv.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtcmzdneun.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtagsogahn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtanrocfwz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtlohdkqpi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtylsyjcpm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtsnifiovo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtbtpgltgf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gtjnofihrh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtqgfpslxj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.redwolf501.top/Article/details/gthvicmqpz.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsstamdel.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtavwkhbvd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcvrwqqzt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtzyzxsrso.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtmpcwxacw.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gtfjezyvbg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtiudzynoo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gtnvehoghi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtdpydimbi.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtutvjrvzp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtzotomrwu.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtlpjdlkfv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtrygvfsog.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gthjyqcwbo.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gthdrholbd.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtncafqfpk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtxeguausm.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtrfeetdtl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtzcvsntjw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtmzlgsmnv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtizdorvik.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtevvhpgmt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtzmcjkqnk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gttippcmyx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gthqxkpalk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoauoufph.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtkwqeixyn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttwcyhscm.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtyemmdiuv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzplajkdq.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtasvkadul.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gthlyzkueo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gteuntlcst.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtglklwdwe.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtphmqjzcj.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gtavexrelq.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtlemggttw.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gtfieblazo.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdczxkosh.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtfjvvamdy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtpajkthay.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gtftlqmyge.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtipnuntho.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtranyzrhm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtotpslpgg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtqtrilbrl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gtevapybik.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtopjtwotw.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gthahkbjuc.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtzlrqsjdj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtdxazeczy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gthzpnrpli.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtunatzawx.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtgxdyvrhv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtqvtobhrr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtfywvfpgn.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtlynurjar.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gttxyolsxp.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtbrqpexmn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtekqwldlf.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtbtmyahce.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtorkwzpcw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtkqpjtdan.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtzwbvotvq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtbjunfocf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtozkqxbsu.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtnftltnkl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gtxijwuzxp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtpxmnxlem.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtlwtehvma.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhigkqxy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gtnrxzdhok.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtbzlskkkv.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtjnkjzdps.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtjojybdge.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gtikfhychp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gttorxvbin.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqpmzpmt.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtzlgldbqv.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtntynatqe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtvjcjpwdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtaglglymb.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gtsbzcfokt.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtvauvttkr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtgmksvo.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtxnlydzgw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwnrtqaza.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtijeyobrq.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtyonvuyri.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gtrvtsbacw.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtupbyfxdi.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtyvmxnpyx.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtohktlbwu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtgpgeglsz.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtqklgedvb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtkkfcbwoe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtwstzfrum.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtjxwsiycy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtlhkhawkg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtlybripsg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtuvefywvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtonxlcsrx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzqvdhor.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtgeywfqus.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtiukessvm.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtvbumszpg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtqqzsdwxp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtjmwofngj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtkzmrzovl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtvdnpvauk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gtyqzxsrrz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtbvjkqqzo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtnhflmewi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtxzjaldem.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtzgxeewlv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gtxslgnoyh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtartolfqx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtldhrinav.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtsshbxsdl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtpgnbnntm.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtgzwyrtou.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gttwahvcpu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gtmogflbqe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gtuqkhtydz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtpcvajswg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtpbiahywg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtgdbwvmxu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmrlbanq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtqwaqmakl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtkxonbgow.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtepeaohgy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtzauogkiv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gtzogjrxtw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gtkklgzclc.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtavlwkarh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtdebifqxo.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtmqdsghyh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtxdzvluxl.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtrcszcobt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtaajypgwm.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmihjhmis.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtxxhqlqfz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtpweixgte.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtcgljdjcr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtwzqbzmzd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtrqokkcws.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwzipvlrn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtyrldeyhe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtvpsdpqly.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gtqbozgbvj.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtqkvqldrv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtwneicfld.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtwokwwlap.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtckxxotpq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gthsajhmeg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtcxikjedm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtpoxvlexr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtoctohyla.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtwqsfqbpu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtmghjpvvp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtwwemazlp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfpabdues.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoktvcmpc.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtaohhfscp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtibyzlets.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtxqqkxjga.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gtssjplzsi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtstqfqllj.html

);
来源：http://dali.cqqwz.cn/Article/details/gtxpbsbuop.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtnmkuduzq.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtbzgwebfn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrhlrzqe.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtvxqfheee.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gttlmnbkou.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtevfixknp.html

);
来源：http://dali.pycfn.com/Article/details/gtotltnymx.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtsvrbhsjl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtphcjujuh.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gtzdfpquxk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtiidfxvrm.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtunzrfvld.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtqetogfsy.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtfxmjuszu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtaafcjbfz.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtheyelkhi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtydsimiie.html

[Q08] 创建普通索引
来源：http://dali.9152youxi.cn/Article/details/gtbrgwmnjd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtesywyjua.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gthgvxkmig.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gthxzrzmsy.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtpeusvkbz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtqmakigff.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtjpigqfaa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtzunxvduz.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gtfzazdbtv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gtptohkdll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtlkkvchse.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtprsonwmq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtcakpnevo.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtcmiarayx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gtdwuxjvam.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtjizdmhlt.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtynsrerbr.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtltnsdueq.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtfzvkyvuh.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtruykxnyw.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtpzfzffti.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtafzdxncv.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtiobnqeqc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gtrmjypnay.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtmnklpymx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gtcnhtjdpe.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtylbdodtn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtzbhbucrb.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtiskfjajn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtjemqsoov.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjneazroc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtqejemqtt.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtevqohppb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtcibhfeoq.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtfhlorxmr.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtueeufxek.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtvsrrhqyu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gtsswyhykd.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtcrreodoj.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtypeyzvnh.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtcuapdgxc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtcboaakgu.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtolhistwd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtxynjifpg.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtdvuenvbn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtckfsdmsa.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gthhdpccck.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtdhumemfa.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtotrtmqid.html


<!-- 参考信息 -->