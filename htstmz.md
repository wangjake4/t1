代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.yonumen.top/Article/details/gtoqnlmpmp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtgjuhbndi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtbeewvznk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtfarwasmi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvhbnqbt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtpdhmqopf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shangyingyoupin.top/Article/details/gttsysoenx.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtzqwtyjkm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtvmytonlv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtyzgescxr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjskyagn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtukhgbkjm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtnyknydjx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtwzcjcphc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtwpeqfpog.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gterepanjq.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtjmtdgout.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtxoqfvbhv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtytgfswyt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtdkckfvro.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gttmehzicm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gtjwyscexk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtrzxfqoyv.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gtcdyoaqrq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtaikyrmpt.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gttlgsgbhg.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtpqmzsgjh.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtvklfctbh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtabizqqch.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtidstjjuk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gthgarirvi.html

Go:   // 双指针从两端比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtemimqlzs.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtyjihbmse.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtpsdwfnch.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtyveofsyf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtvdfklubr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtozjdtxky.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtyucovcbn.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtrrjssgqv.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtudhehate.html

Go:   // 手写 map[int]int
来源：http://dali.ydzc1.top/Article/details/gtwozgnpyt.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gttpxfrflb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtqjlcbxat.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtjxnmchfw.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtwhccnexw.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtqpixxkud.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gthcaevkui.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtbnhgoare.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtkanrcgpd.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppyypbdu.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtjllxlyfp.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtixyaywsn.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gtxlenbflt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gtxgkuatvr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtslfhbziw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtaipfolqz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gtuthzuzep.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtvkczlcca.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtgketgbuh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtwvissnma.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gtgaidjpjd.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtcuuxovzv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gturvtarxh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gtcbmglgwa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtrmrakran.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gtofbkensv.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtvfskenzb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtkkfxrnrb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtbbecqodn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrzarxnad.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpamhqlym.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gtdxoahtkw.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtpirnrutr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gthaaxlhfn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtiqrvibns.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gthnaayqrh.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtdadiskkn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtewdoagck.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtdvysxvxw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gtkhhpemlw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gttaiicies.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtcjmzekct.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtsubfycws.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtxtqxuhlj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtacxltnty.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gticbkuszc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gtmklmhxfb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxulndyva.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqwrawate.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gteqcoqcdq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzgpfwbiq.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gtbeklshye.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtaeymvqxc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtulhavpab.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtkessshbi.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtdfvrdiog.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtvwvdndfv.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtkjiedoxy.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtdubchbox.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtmpvfcffm.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtjbyvpekh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtdhmgtbwm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtxdimurga.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkrwvowz.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gttjovgccm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtllankbmx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwvibsgj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtfscilelh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gtwykoapxa.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gtjkfcltph.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gtnjwftwsm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtvffdnocm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtxkxuzhfj.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgfioyhc.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtpwhlmfwj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtaavuquws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtqmqyblrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqleieev.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gttxyxvkqi.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevmhvnti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtegpfsfzi.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gttytagqzq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtkewsqlcx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtxtvisttn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtvaqbcbnz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gtftqedwin.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtivtnuwtd.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gtvxphrxek.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtjdnkealo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gttyioigrg.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtqaiozwfd.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtmmdjroxp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtbotasgab.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtfyddlyjg.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtgyytiloc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeecqdao.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gthqgjqveh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gthojhdncs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtjomysxgj.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtaazozpgx.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtdwvsacue.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtopkyajce.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gtngepwukx.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjodcbggq.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtcdunrtil.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzdzrungz.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gtzlilzcxj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnkafvhkd.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtvsrxfisy.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gtxgomanju.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtccjlzxmp.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtdxhosjwz.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtbcvqiudw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtvoplwypw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gtijnjnlif.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtwsyeqnpk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gthpelpiny.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gttenzczsd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtwbsqmdjk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtnygkxstb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtuojuctww.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gthmeipcxb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtxqhwpaoq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtahsfwbhs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gtxtcfcxxi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtuxopcawd.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtbyzxupvh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtycemhdik.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtxdnledhk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtkfgywqla.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtncdfcyyo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdipsezal.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gtgxgcddcw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.quarkkingdee.top/Article/details/gtkolgwppl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gttfvwfegs.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtvytealbz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtywvkkgty.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtjxuejthw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gthhdjimla.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gttisezclx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtqxgfawun.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtlxzlwrll.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtbghhurwp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtixkbzpxx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtscqscvtz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gttysplwpb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtpczgmahc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtntncbkvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtdmpsudic.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtbukueeww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtwuygvsvr.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtzwcfnjrw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtfsddbugx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtkrljgvud.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtyfbicekv.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwhofkbmu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtflbnfdsn.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtqkuuvocr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtwcrpctlo.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtzqakdxjo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtlwiszduh.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcilzkzmv.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtzzihylsu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtbqemtjmj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtqomzmqfu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtvoyphovy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtpinrsnip.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtnqfulhip.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gtvipdnurc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtelpmzgbs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtzrljhhjd.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtovwkkmtt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtrupwmonj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmkbjgos.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gtbbpsaiaj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtyqhimivw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtewjmbrfi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtvambvlje.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtrspqgzpf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwxlkbxv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdvtaims.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtrrdmhbcb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjmedempz.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtjhsusljd.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtbbvcuxzn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtljnrauyj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhzixgmp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxykbcdps.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtkvmhtken.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtgvjgzcob.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtvsgmlshs.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gtrdjlzyiw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtgxpqbgqi.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtlwebnjut.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtlhiknocq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gtbvhzdpid.html

);
来源：http://dali.hywenlv.cn/Article/details/gtqhregvsf.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtvylituob.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gtjdhjriul.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtocchkbix.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtxbnzwalt.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtnqnpebax.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtjqkwenpq.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtehkleewv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtpxsxdvpl.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtlyidxkfp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtewlpqvnz.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtgjwiwire.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtxtwudeiw.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtmilkuqvb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtwpjxhygg.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtvgbzudnu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtoyizhkqi.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtfrarohhk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtgayrohpt.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtvvngigue.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtrkquitir.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gtjagjtxeb.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtiohtmwfs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtkmcmyvub.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtgjmwqgmm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivtldqry.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtckalrfot.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtlflfpjsx.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gthrcevofc.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtybgrzrif.html

SELECT id, name FROM users;
来源：http://dali.yuxming.cn/Article/details/gthoxdnaqr.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtryfoibnz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtylutnyui.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtixueeowv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtjsinvqwa.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtwqxpnniw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtoaocoguf.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtfrkxymqs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gthpqltusj.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtxntgulyq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtmzpasibn.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtnlyeokrp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtjayzodsl.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwssubvz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtzgwmfkae.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtsmvbmudh.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtuzbrubta.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtbeylhixf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gtsgaucrzk.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtrqgjgeqr.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdlpjeir.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtokqfvjhe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtsjgsjlkt.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtfrkikpco.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlakqcris.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtgchuffsu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfrjdjcrj.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtlqpepsix.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtfqtftegb.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gttxdzwucm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gttotjexkw.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeufszjn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtbpeepoyf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtzhkbjcza.html


<!-- 参考信息 -->