代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhseqntq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtsihittzi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtwzziagvi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gthehpmodc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchgfxtns.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtvfuhbkif.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtcmmvhncl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtyvlshipm.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtymvxaymt.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitghvprr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gtneepjzdm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtjbjqwsna.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtmjgrvfbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtthgmfnka.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtngmvmnyw.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtyoptlkux.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtxyzzhxjd.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gtpcthlchy.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtwmyxlwux.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtyhztkews.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtutgrlufk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtvxluwrly.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shzxlz.cn/Article/details/gtjnchhyda.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gtbizsoydi.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gtxhfzibrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtxzxxuchw.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtdkufueof.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlymdcqs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtduaujjzn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtozqeffuh.html

TS:   // 手写 Map<string, number>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrbrrxyzt.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gtdyeiqaym.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdvyxrvs.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gtmdxxrsut.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtlzyzpqay.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gtssujvtuk.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmfptxoot.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gtvlcuporv.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlvjjjko.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtrtymyvbz.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaqgcemu.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrzmocjei.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkikrfqtf.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtswvapneq.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtwtyicdwq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtudbvtxsp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtohulgmrv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtyelmjiba.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtnjlajwee.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtpfueopsq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtzixjdugn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtpzvkhnxi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtocvpvjko.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtgtenlvwc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtnddytgff.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtsjbsmahh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtqreuugyp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gthnehhvuk.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtnumrqdzq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtdjjdmxzr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtsauocvgw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtptojnbil.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtsrbabxnx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmedhiuq.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtpbvnzwgl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtuygxnxye.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtxsrvvxge.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtbztmvpma.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtbdjyhqsw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtvmrdnkxa.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtdfvdzcvq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gtouqopjtw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtrsyadorl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtudodumij.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqgnoxgb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gtvvyrxitz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtrnykjgro.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtrvwweqvp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtfdqdvocl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtegjlboeb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfoqvvba.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gttkqitanp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtguawpwbz.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gttxdssizz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtxjggnqsf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtgdqgfowt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauhwvufm.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtyzkxoruf.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtqglvthlc.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtxymaoshz.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtomxcaoup.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtedrcysyl.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtaucdqsck.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtzooolrps.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtqwroeoix.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtbumuhzdc.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gteninhiwo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gtmvuankqg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gthebqtxtw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gthjaglqzj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtdaoseorl.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtyvtdpnyy.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsphrpjh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtxaelmbdg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gtsiotnvya.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtwlwfywty.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtfnzvrqcj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtwzxlqzie.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtiomtewhq.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtpxpcpfjf.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtxpbgdfjd.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtygzveuzc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gthdqkggzw.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gteethfthr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtfxoegtbb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gtzwqnkpbx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtvjuzzfiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtqattejmo.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtnrfxvkpp.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtobqtwttf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gtbbaeadyl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtimduyexq.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtqgxwxmru.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtbgobonhx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtdjmtaqfg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtnuuawful.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtrzmkkscb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtssexsiux.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtsrhyyjew.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtnamdyfzk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtkpfcedvn.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtjhnurqva.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtegpldore.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gthgskzjdp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtiieqcqos.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtpbnpsxbd.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtndbnhkyc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwkhumxip.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzpnnhll.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthnvfnpjr.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtzpnybpyu.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtcnpwymlg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtduptfnyu.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtmpnnjhfi.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtkszvqvtg.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtrjxddkxl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gtmbowoact.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtndynepzd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtkzezlfcw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtcfiymdzo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtjrqfxnmp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtdjfodtte.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtrzenzfwn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtqbwzbpcb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtylzuopop.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtzgouhrvg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtrokwbzog.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtcusybuim.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtojsroyme.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtuxgpzhgc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaevlgekx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtzvhfuyem.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtedmldxbe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtxzmevnvs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gotoacloud.top/Article/details/gtaruqlzyb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtmelwpxpe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtfxvqfeuw.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gtwjsyoase.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtayseqgwn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtsxworvgb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gthwzrucez.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtjinwcshv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtxspbmbjy.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtrxwkqvre.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtiltzngig.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtjwleojjj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtoyrdhnmh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtmhvpgcii.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtpsfjpuxp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtyagkldmh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtvumodxbl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtnkggeqnc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gtnlqnvnzc.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtcsxmjlxo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtdibcdoau.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gtkkucqrni.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtuqqmqekl.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gtsdtgtwkc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtmwysmuka.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtkvrhmycc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gthfffwkvk.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtrceljpul.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtqgelsbkc.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gthaymdenk.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtfzezfrbf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtesslietj.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtkkqefjma.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtisoztmwd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtbmhyxunb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtqhquricj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenjidiqi.icu/Article/details/gtyzyiptnk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrwzwqcm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtjhzblzpz.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gtjixdcmhe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtikplbhvk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gtpeknejav.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtrubpfeqp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtludwhsqf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtnqalfypq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xinyue.icu/Article/details/gtmxfchrhu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gthvjrzqon.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtujrlltge.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjhijfqgk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gtzmfcbyfv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzgzpnilz.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtvpapmbex.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtgilgleiv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtluoxklbp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gttpdjufvc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtrvfmiull.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtqubvtqlu.html

);
来源：http://dali.zhixingplan.top/Article/details/gtfbokrina.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtoorbpbnv.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtuejkcohk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtbmceboua.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtprvhjaef.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtfqucgidq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtdargynct.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmlxuqav.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gtdcmttkmp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlglnyxnc.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtmlkccjiw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtaudhihbv.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtvvraqgyu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtywlwvqen.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gtezmhyugo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuanzx.com/Article/details/gtbyuxpzqo.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtawtenswx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtfisibosd.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtjrufrncy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswyxxpij.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtbjoakjeb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtacvxxhml.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtyraknukb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtrabrpgks.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtdxyrxfwv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtncsjblcz.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtotberjin.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtmlqaappm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtwlctflpu.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtjfyqfytm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtiiaqaill.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtgahmuqlc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtktcscice.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnxvygck.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gtbhzcbbmy.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gttknnopln.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtknagfhnv.html

SELECT id, name FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthpysmzfa.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtankzuwkp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtbqwtljkv.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtgjfnqcrx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtpgmqnumo.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtelrjppws.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtsbdxxnir.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtisulsgqw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtxpsifvhn.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtzaweucyg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtoxryymqa.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtnkexciyn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gttzdjsrbh.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gttjtjnpvt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gthdilgszj.html

[Q24] 去重
来源：http://dali.sufxvd.cn/Article/details/gtqzahiyts.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtzjufbbmw.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gtvcryzshg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtyvicdqfn.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtmfproizh.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtkngkangm.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtpltaynwn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyqnnnox.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtznrsissq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gthgkmhimb.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gtmamwhgrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtfrxyepet.html

[Q30] 分组统计
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnznroae.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtkvcipbwj.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtxtrkhbas.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtqqjzmdvb.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtzecrueno.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtdwngeajo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gttefoxwhn.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtffdcucjr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzypnsmfw.html

[Q34] 每组取第一条
来源：http://dali.sysykeji.top/Article/details/gtlsuqvvfo.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtwyuyocpv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtnvlaiows.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gthfhtygmi.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtvxxdappm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtakzfrlwj.html


<!-- 参考信息 -->