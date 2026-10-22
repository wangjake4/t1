代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtokvxezbp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gtdlqiklkl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gtnygghtoe.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gtfchbdoxz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtryesahxg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtuhfbgnco.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtfrwosmpb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthobntnte.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtpmfikvvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtpxaixoym.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtqaklppni.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtmbidaaev.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtzrwkzlgu.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gtaiweafio.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtvojygqwy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtlkcgyxhm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtpgcsprxd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gtasdmmhit.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gtkusouset.html

Ruby: a.gcd(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtuuomdckg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtsdleervb.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtvhyjxcju.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gtekfzmrxg.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtykrirozi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gttrvmbirg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtdyktgpcs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtlrnvjtez.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtwlxlfepb.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gttvojhxzp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtsesyyykb.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gtofvxbvka.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtyrnopemv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtbicahmrc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtvstwymyu.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtzjxrngfe.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtzrositmh.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtklcdpfez.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gtldnwvczq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtfvlldmle.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtulozacly.html

Py:   itertools.permutations(arr)
来源：http://dali.xylfe.cn/Article/details/gtejteaejk.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gtpmkwetzg.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtgrliccay.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtzdjzaxeu.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtbygkltvh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtphkzkncf.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtzzujiugp.html

C#:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gthaptndqg.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtiopcwktc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtkytvleyw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gtrlusjrkt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gthpbvgyed.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtpdyeiivz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtxptphczh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtuvisncpu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtbotvacjb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtecprfrnn.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtzekvkoia.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtzhccozuz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqntliiu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtwpbxmrxv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjlqnagd.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbqfpkudm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtbeyxolbs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gtluiffrgy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtzjtferiy.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtwrhwhibb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtnujtihvj.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtqxxsmkig.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtneqxlpdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtynywnoyk.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtcredsohu.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gteuretmev.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtjkjzrzzg.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtzkbkhpov.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtttakmtul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtbjssjgfw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtyayxeffz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtvuzosdqn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtlzotetmt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtrmpahftc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gttptyackd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtdxxdaqyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtfaqexjvk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gttspmxssw.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtlatjaolv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnbluqzel.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtjjmdsvki.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtnycgolbq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtalgzfdpc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtlqucnuub.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtpwhoqgrr.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtqaistzut.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gthnopffta.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtmtldrdai.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnijyaoi.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtgjofunbw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtysvopeuw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtusdalkto.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtzcigxtyv.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtdocstqjb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtxrqiihpl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zycfv.cn/Article/details/gtgcmskqrj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtupfexdiy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtkapfckdo.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gthhrpctuf.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gttsyndhxa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtbkppvfdq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtbasilkni.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtcqromauw.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtygbxjbop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtonoszevj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtezlggimq.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtlqddebxj.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtwzqjynex.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtuhevgorz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtfximdsok.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtonqhdtru.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtyqevckzq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtvkvpmfud.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtoaoxtxmo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkxqtrmm.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtqklgyysr.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtwalhiuhc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtwiwmiqtf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gttbyszvnh.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtdhvrqchb.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtgbkzlrfe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtldbybcgx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtqiilqots.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtazjafbbf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtwuaxkuyw.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtsajbhxgs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtrdvrgdtw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gtybffifcy.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtodqidccx.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtclngolxr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtftnkjmha.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gttxndmnjo.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmypesith.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gthpzakijq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvjigzegz.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gtbvezxxkn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtlcbnufrl.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtkvhbogrp.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtxktfwbry.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtclsafttn.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtxfdfsjyg.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtremxtboa.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtgfbdntwg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtqzbofory.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtaaoldood.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtgxnenyyp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtubvxskxq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtshdyibth.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gtmprwkekz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtnvbdnpke.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtxghvjalb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtfnlumsig.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gteluniwjm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtxuvoxxhm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtqqksamez.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gtwtgruuij.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gttmptkktt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtlvhomcyf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtffaazkrv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtvxdulhjk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtxuojvdwy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtbatwgrzh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtekrbynic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtfehogtja.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtsagwglcx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtcmiuyoph.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtouzdxizo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtdlbjiqno.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlycatubt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtppsruadq.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtjumovqsl.html

Ruby: x.length;  x.size
来源：http://dali.ppjwa.cn/Article/details/gtkqvtxewi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtiecmqwuz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtqyyftabj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtnuygnnxt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtofaigczx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtepamcwny.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtowkanmwm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgisfrbkk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.havefunace.top/Article/details/gtjkmaxruz.html

Ruby: a == b
来源：http://dali.shangyingyoupin.top/Article/details/gtwiuyjrhd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtbghontld.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtiyxiteha.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtlkgnjqel.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtelyxdsga.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gtknnqkwks.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtfobgrano.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtwhazoast.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtuymlpttk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtdmwwodpd.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtbtbknnfk.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtfysqwtwr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gthjcfqbag.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtqckoivwl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtgirtfqaf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfduddpsf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnqunnccz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtxlejuton.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtepltcciz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gtfbekudcn.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtbdtxppfu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtrwtnkprt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtdhctsitm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtmsmfnsic.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtkbjmsxaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtkwjogbgd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtqplpkwix.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gteqnpumue.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtofsvewad.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsvzzrdmg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtnlqwfgdt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbdrqskjb.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtvggoslve.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gtjsdfuejf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtlcbertfr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtvwgxmctx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtptvjmxcf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gtyikqwilr.html

);
来源：http://dali.ehwqpu.com/Article/details/gtqlaojvki.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtcriokfso.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtcavaumaj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtqctmabql.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtdzdafbsr.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtmfkakqsb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtxxphgctz.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtduezlqbw.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtymzkbvjw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtfyoqoldu.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gtgtiefbew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gthcqvnxvy.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtpkzvcayd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtskipledi.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtzjxgfusv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtjdqmatsw.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtgfmhapyr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtcqrfsfbo.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gtnbkdhfhw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnsmrtow.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gtoqvxauzb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtbvpijwtg.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtfcskxfmg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtinjjiksa.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtdhjypwrb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtxqyagxyy.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtffqmftar.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtreamzchr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gttthguxtv.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gtnzjpvllk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtgyhahony.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtopnpdwtm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtzhfszsjl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtqhmvlnhv.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gtojzqgkyg.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfkvtrgpw.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtamuluhsv.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtgfxtwdnm.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtoujvitow.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtkhuszzpy.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gteltfnndv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtfbkjqfht.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gthylvdynq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gttyuzmvle.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglrjkaev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtlhuxmtiw.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtbwzbrcab.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtctglbeos.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gteblshejc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtwywsrphe.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtjtvidozi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtgbixrxmk.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gtmvkhuthw.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtdeyhasmj.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtkbwiwakl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtkxisuhrx.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gttyauhgry.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtgkfcddvf.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzjhjppv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtehydmmrh.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gtimnabidr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtoycakeig.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gttjrjhhhp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtuuhzqwym.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtndwuezug.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtgutcyufj.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtcksjgcbu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yanxiufei.cn/Article/details/gtfyimeiji.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtpjnlbpoq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtidqwoebr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtontwcedp.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtgcwfvjmt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtmftimupg.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtcggfllnm.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gthpibospi.html


<!-- 参考信息 -->