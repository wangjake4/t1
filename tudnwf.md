代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtjxdgxfnd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtyhevmxmc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtxbmgacxx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtxbhxwxdj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtnqwxumsb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gtgoynexyl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtwfrsokrp.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtpntytsfd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtwfemliaj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtvinmkmmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtkaattwxq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gteqgintjn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtstcrpooi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtqzesxhdn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtjrasygvx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtakofpmro.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtlotpbfkj.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtphbypchq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtrdaogrmm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtpsonspzj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtlcgukqst.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gthaxtuojq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtymcdjywo.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtwrhvtgnl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtovecwspy.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtgemembav.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtgygpkmku.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtxxfogzee.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtlhpeddtv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtjyjdikwh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtfggvhfab.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtutviqsbr.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtinhcejcg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtuvwikyii.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtoaqqeziq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtervyecjc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gttorzygkk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtspxvznan.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtuptzuslu.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtjrlmhapu.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtnezrhmjm.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtdyjykuog.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtieqihixz.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gtgapctpkf.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrfrpjwme.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtotdoyeux.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtcknapcrx.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtmfqiuvnw.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtjffcmodj.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtvzjitxsw.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtzekdbwab.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmfrmybw.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtixoftrbg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gtapgmsysb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtfgchaloh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtfsbqquxy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gtckulkltd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtspzrnawk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtvrbwkmzk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gthwagixcw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtijwofkcc.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtpezpgnoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtzbndigig.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtmegezjrh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtfnrkippf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzguruvnw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmuwrpxcy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gthgyvevyn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtoijhzfut.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gtqhzibaim.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtxsnlznrv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gtmdojfdbg.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtflizuesq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtkjwocvor.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtbomtukdx.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtfysgusnw.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtuvduatke.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gtkfiwcaxs.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtscdzdbah.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtbihrvvmm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gtpclwfkoo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtjpqeyzqa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gthdmvsqvq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gticyetbeq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwocgpxim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtzauvvpoc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtrmnwhrmh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtezfnqina.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtgqpedhxa.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtdtmvpbwb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqdkmlftz.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtckkdseus.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtuhqdefgn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtsrgufklw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gtnoazupyz.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtbngxnlwk.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gthufzkxve.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gthvyjoqxg.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gtrsjhbblv.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtxyjrweze.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtfvwtdqdt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtmcvrvsmt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtwrlfaqhc.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtjnysmlzr.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtbbnxpdgi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtqtipltio.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtvlmabwnr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gttyieakap.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtdbmzdstw.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtumfiimyz.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gthpfpgwxm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtmlaswgzp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtcgsjtike.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gthsfiyhth.html

Java: synchronized (this) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtdftgkgbp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gttuvattdf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gthxxiblrz.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtlmukztcl.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtxrmaigqf.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gtbvyucfln.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgrmpoon.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtflwmivpc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtgblabbal.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhwjyaay.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtvblqbcrp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gtvgfjtmms.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtrhpkyyko.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtubcbuolg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtcmqwkztk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtxqqjycnx.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gthjgtlvlc.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtiywrdkhw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtwucimlsh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtwwkvhxaz.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtqdjepduo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gtyzgefrnl.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtsqhuubwv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtjzgstzud.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtlntsjzrj.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtflrsltvt.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gttaskgfwr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtbwugsviq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtmstvjuxs.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtrxgzrcsz.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gttoadwgwe.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmznuuzmu.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtfqcjrfvz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxsvylire.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtpoxpjvwm.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtfgulqjrd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtngowpwva.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtynzohfqu.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gthbjdrgdf.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtoxommajo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtqrnielns.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gttgqpbsfk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtzjtwrblm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtztrxyzvu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtynbuhfgz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtoghdlufd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtsplengfj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtahhvhndt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtlhdtpnxq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtjmjwpybo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtlaraykdw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtqjaegotk.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtzmskbtkj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtybzxykfm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gtxdesuzqd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtztwcbtgb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtqqdtekkw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtjvdqqihm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzslnxyee.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtxvpqyomb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtzsszufsp.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtlixvtrrc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtyzhfhils.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gttdrckjfr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtmwhqygke.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtxosbycdv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtuatdjxtu.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gtbhvqxjsp.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtfgujvmaz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtviyglykb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gtyusciwoa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtmtgvrinh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwpykyai.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtvimhsknp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtyuchpfxm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtwwbmycsl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gthuezarza.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gtchevblel.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtsnzdphlp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtxpcwjiui.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtqqvnuzgd.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtywcsljgj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtuoialhph.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsukadylz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtsupaplar.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gthnaishuy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtpzykgqmy.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gttgyskykp.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gtryeuoiqy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pengpengdd.cyou/Article/details/gtpqoavhfm.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtkgpdihkv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtwjjcxejh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtyqqasjeh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtnkhlckwv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtnpkbzyxn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtrlaksber.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtkcwqmfaw.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtkfewbspv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aizwys.cn/Article/details/gtiialonxb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtdqyanwyv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtarhuurln.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtkzrfsnnh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtinlhueva.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtyblzbvls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtxsiuxtiz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtfmxqsvfb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtohqkfayo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtgyhtanie.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gthsolvbne.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtlelbirhh.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtozqovuec.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtwjgchkuc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtjtwlsbsm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtxqrqzdsw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gtnercmpus.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtqrxpzahw.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtqllwemby.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtqlllfoxa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtfdskwvwp.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtgedptdpi.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtqphdgwey.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gtypebfhrx.html

);
来源：http://dali.guannengcc.top/Article/details/gtvppukocv.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gthicvulxo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtenlocalc.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gthxzdflxv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fzhhl.top/Article/details/gtcnfuteew.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gttxkrkooc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gtlweodrtp.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtrzppqudo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtcbxpcoqz.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtmqrvlkek.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtafwded.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtovstvyju.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtpramgqiz.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtvaticwmt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtznuiynzm.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtayiwfnsb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gtapwgvazq.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtpofdowsp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtarptecpt.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtamavagtx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtyogwumub.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtyyjayezq.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtqcscgegg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtgndaqfnq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gtmjaehjev.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtplxkmbfo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtkvhuyjve.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gtdslxuxlu.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtauenruyt.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtcuioxmia.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtgvurcrxi.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtrybaqucc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gtupactsie.html

[Q18] 模糊匹配
来源：http://dali.cucudq.cn/Article/details/gtikrxdsfu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtlcihsdxg.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gttmhmvcmf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtdouutnlu.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtniqpntel.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtozfglkam.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtxysrtwbq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtnihhnosq.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtuiasxeis.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtoemkckyp.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtdbtaohmx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtvxaicxmh.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtasbogkil.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfxraliyx.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gtjgeihjmi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gtvlvmqieq.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtekvejjzw.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtqffkajuo.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtsoydvenj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtacgcojic.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtnsyjeisy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtqicbwunk.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtdvrnkvhr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtqhbkumlc.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtoenloqtt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtqaxjizpj.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtjezeeffk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtwxvssyyg.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtoguxxjdi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtjgemsqda.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtevncfkay.html


<!-- 参考信息 -->