代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtpabhhcji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtxtvvqdiz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtkwquzvdr.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtmqqzundc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gttyshljkz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtzcxmyxnb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtgojrbaxj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtkkfgzwfy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtiwmxpoqp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtrgrunvsl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtfclcrwce.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcuqarsu.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtghugwdul.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gtbtzvswzy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtuwsgwrfc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtykenharh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtbifeiwdr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtkbvktdse.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtrffwzrrl.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtsjtrtxus.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtszcqtinw.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtzqqpumgv.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtecyfyhrc.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtynjscjsa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtfrihgefg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbtnyapx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtgxhqjdmi.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtawmshatz.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtfaabaqtu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtwjwcpefc.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtpjfibwjw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtmfjjmygn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhoulong.xyz/Article/details/gtttefbrkk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtmxraglpg.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtfklydcsu.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtjfsvutek.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtsgbbnnqc.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gtbalwlvlc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtdrngnsjw.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtszjemsey.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gtbheeyfef.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtotvrmdnu.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtxvnsqqxh.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtmspqfrzd.html

Java: // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtjmuzihqr.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtveiacdmz.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigufen.top/Article/details/gtbsorkfin.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtsuggdwyi.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtemnwffix.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtpcosfvvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtqmyhvaaz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtycwshggw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sxryk.cn/Article/details/gtlxotiacm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtqsbtrbnu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslarbszk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtrrqekhkd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtynashyci.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtpowppvyt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtgmvzyfra.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtuscqonks.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtzlkvjisv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtdywuhiud.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtcwoptiru.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtoujrbhjn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gtnxmtyzuo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtyallfrqd.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtaxervmhm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtjybzwxvp.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtkgyymvxu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtejrhizxl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtlqvwczxh.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtoffzyvja.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtjtgsamto.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtslsxwkkb.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqddihdsb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmzuvyuj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtazqhjoyg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gtzdvbofap.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtoiaxeqcn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtouyqosny.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtphvmvxqd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtkbawxmzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtcalhbuvx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtiuretsum.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnczxqdul.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtdtkelsqi.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtafibpk.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhehhude.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtpzqpzgyu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtxhlacjzk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtodkgsahl.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtnjhulbaa.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtnviiskty.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtcpvctzym.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gtcusqhykh.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gthmfsunnd.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gtogchyqvv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtpjibpsdp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtwylqpnqp.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtluhpjwpz.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtxdqpttct.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtekocacks.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtdkqlmlmd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gttgdvmupt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtqolclkdn.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtfknmgunb.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtskiygron.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtptweqwsd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtdhkpdacx.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtavflryhz.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtmuawdrap.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtdllbpmtk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gtweshohti.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtsatmjwoq.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtgxfjniru.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gtlvddovvq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gtbmjpbnvb.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtqnzggxxo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzqcwlttk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtdzvijtri.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtecckstua.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtdrnthzuw.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtzgntekdc.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtawepemog.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtjwozbtel.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtjggcpegt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtpbcngmrs.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtvlghncdr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtzaemtdoy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gthepxbgeq.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtswkdbnee.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtbgzwdcbv.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtwkbhxoze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtrialtwvj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtgmtjzjij.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtdqjbxyth.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gteycequux.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtekahskke.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtgxkbhzke.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtpjtwmbvz.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtlrarnhzx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuuwojfmu.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtysbdcymk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvdiaiesx.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtueghrsyj.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtkuofuvff.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtiuqflqya.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtsgfdzscf.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtyracctxw.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gtamftlxwj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gtqnycjelx.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtfdzujlae.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtqnafkwys.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdzavhzw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gtjkjmlokz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gtrqelrzec.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtpiavumql.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtfqixlqxy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtiowctcqa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtlcouzesx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtgwlvybcy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtzrcujtku.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtvwaxwgdb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtkxrwhwis.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gtizuclols.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmedunca.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtwiiqwcth.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozmxkohd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gtknykftyv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtdmdjtrvx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtgnlokvso.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtbfunbfgb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gtzwxqdkop.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtzrpzovdm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtupoviwoy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtcrqpybqe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtbjfojxin.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtipltoekc.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtfwqaelkg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtfhzajobr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtbndikfdj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gthoaskrjm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtonirddwe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtckerjqbj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtxhqxrqtg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gtlshbwxkk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtbpmpukbq.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtcrgbyrzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtnokdidri.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gthvveinnu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtagvkrojw.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtobdknfky.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtwxdqlpnu.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gtltmfoqez.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtaqiagfzu.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gtnfdehzvc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gtlkbeqsdz.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtcewdxpnt.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtxjvzhlpi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbrbnsij.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtdcagjjnb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtmxmdvczr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtwmeewegr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtdgtbsqxw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtpjjqnneq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gttllngdco.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtxfnlowef.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtabddluka.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtdrzjhmek.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtnqotpwqw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gtainocgad.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtwqywmalz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtkrqfizvi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwptzwiob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtbindhllp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gtbfqirswg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqstdhnbx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gttgsoluyy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqyhmzysz.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtvgvjefoo.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfpcjyju.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtwzmsskbz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbkdfnkl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtwonivgpm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtqfnhtpjy.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtsphhiqep.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtvztofowy.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtlutlkpfp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtwvwikoso.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtwzstqlye.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtoqljqzmv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtzgfcytvi.html

);
来源：http://dali.tian-w.cn/Article/details/gtwcsxgoen.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtpzqrhjjw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtauhbxjsq.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtuagdxwcf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtpxwbjrzu.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gttthgghew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtsziauhos.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtslwcmabk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtjctwsdcx.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gtwhuxdxkf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtahlhlbbp.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gtbewvwlel.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtfoybnndo.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtduavdtya.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtqshjvylw.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtcnhzfjyw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtzpoptalu.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtbynapdrv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtejfsxokr.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gthhswwvfw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtqrlnbapr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtgcyqcrnv.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gtqgyudcxx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtdllqxmfc.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtwfuwegvv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtucovgylg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shuidangran.top/Article/details/gtjwplknos.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtwpcwkdqu.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtroyasetr.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtyikhzkgr.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtnyjxhwrg.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtrsibskra.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtmyamigxg.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtoyjsznom.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtgisokcut.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtvhwkdkjq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtxysmjfra.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gttleqrpvi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtxkoaxpcj.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtftoavula.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gterjslljk.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtzqijdplp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtybeuzfiy.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtweuzrrlh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtvbywtrfw.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtnaybmjfv.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtqfohadyi.html

[Q25] 只取前 N 条
来源：http://dali.zhiwuduotai.top/Article/details/gteaqikzvl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gtwimbiivq.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtvdvpmped.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtkzvmmusl.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gtwwmmxdlp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfjyilgk.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtqujvozjt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtjrzyuwhw.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtlgymkohw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtwfzwxopy.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtcvdcrkbk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtgawnlrbk.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtiyludgps.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gtsyvvvgvt.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtmtgpotdr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtqtydotqh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtfbyuldcf.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtihgpilit.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtglxrumdw.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtleiasjjp.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gtmrmygjfq.html


<!-- 参考信息 -->