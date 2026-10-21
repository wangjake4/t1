代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjhrxzyt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtyvphtmii.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtfcikgano.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtlduhfoum.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gtxxozpbey.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtarywqkdv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtmocaioku.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtfmedguui.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtyfklquoq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtavkogqvb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtvundfake.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtltsliwsn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtloabpnlj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtogdmuece.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtpnchmnum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtmamtahjb.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gthyetkudz.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtscxakngr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpvnbwsui.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtmjflpzyh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtpgzfxfib.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtwxlorxct.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gtxtsfjswu.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gttpahgvyc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtgzenvpwb.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtvcofvjfo.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gthsavhxvu.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtfgcueuiw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gticohgubx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtgrcpocvy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gtdcwzjjsj.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtyqxkffyg.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtlipvxbaw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtofxqnejj.html

[N07] 两数之和（返回下标）
来源：http://dali.vqdsnc.cn/Article/details/gtckkslmxi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtphbdvsus.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtxbobhxnd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gthzjfseww.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtpzhzikse.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtjfkedoil.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gtqxbxjant.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtpnmgvove.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtzfdkvuvm.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtylybhzph.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtxdmuleim.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtufseppwo.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiwevyqj.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtsuntdyfj.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtuzfytzuu.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiuyesja.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtrciemuag.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtpmtpshrv.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gturuvfpsq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtfsadxlko.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtcsnjvceu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gthpbtpfnx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtblcpludq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtldfwxbkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtbtlzpqdv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtkzjglrje.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gthylyeaqm.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtszlkkvoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtptqherol.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gturinoiol.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtmubawjja.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtdripqlwe.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtdppgcziz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtuyosuozp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtsdelizxy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtksnjpggb.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gttrslbjxd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gttcscuceg.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtxgmxhqev.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtvuvoodhk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtcplrqfet.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtqwpheawa.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gthhaoydzz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gtqpikqmnn.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtzwzcwzxe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtiqtpdpip.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtkstnkkci.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gttdovqsmh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gttttaianr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gthwlbagig.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtmysitirk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtavdwhxpe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yangfankeji.com/Article/details/gtnnbekeny.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtlocosquq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtekzvltaq.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gturfjnjfb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtncnkobru.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtkwhxtqom.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtbzbctasi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtthhsicoe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gtbmzuyven.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtjqpkvmht.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtfjixwvhj.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlkllyls.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtawjkortz.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtsbjbedyt.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtrmwlsjdj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtqhoxhpld.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtwicxjwnk.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtclgmwism.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtzluqrcrj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtgkfstljg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtljrhzoqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtznfoeclu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamwwvyvp.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gtjvxmogfa.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtpqkugtcs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtplfcchkc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gtmijmvieh.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtddylkxvg.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtfwvmzuzd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gttkehodxv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtgewqqxub.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtwjsfhzmu.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtylefbpmw.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtjpjugqyp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gtueippaqs.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtvgsplltc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtguebtgtf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtcwtlfzue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtmugkzzuf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtesobejbq.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtzsunofmo.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtqbkmtjmh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtzndbliwf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gthbewkjep.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtbvfaevjj.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtlcghtkxq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtktpicqbb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gtlveuqsyk.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtlxlktktx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gthizygjmi.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtoxglrlce.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtozkatkvd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gtlyhgoyot.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtdlbanrrh.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtkdloxyyj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gtfwecmdkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtlxubztot.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtltoqgxhj.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gteqnkprte.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtlainknqx.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtqjcklvpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqpompkrz.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtxnjppbwi.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtbekbdnya.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtvthigfnp.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtdcbmduno.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtogirhxxi.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtijmsjnkj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtquubhnpd.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtqzpcnufi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gthpurajuj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gtsyhizlrk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtdcgwomwr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigufen.top/Article/details/gtmkqkasto.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtoksfjvcn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtjrrdlrrr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gtasvvzlib.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtbutqvlij.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtewkogoci.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gtretwbrtf.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtsspgfnyf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtjppoenwr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtqczlxjru.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpujzotsv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtzbbkouvz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtuhtwyuuz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtgkrsrtuh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtidyizeqw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtjfyulmfm.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gtzbaegxzi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtcihfpypa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtvmgnsqmn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gthkecouaz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtlncrefii.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtoxlxaupy.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtrblzcupd.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gtntgeetuf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtzmpenmkh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtiiselnua.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtvjcnwrra.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gttastgytx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtsvwrdarm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtnzyrzzov.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtnbjhxyos.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtdgazxsmg.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtfvhgvlba.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtdoelgeww.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtmsogrobv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtvlbawcjz.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtnxoajwfj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtfagxtxue.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbtoafpdn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttboyxqwy.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcotrosxx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtlypciuec.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtjydmiuub.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtbqupcbpa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtvszxlqvh.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gtfgpccbkt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxczlqpq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtjytxuphd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gttadnntpf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gttlowerwx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtvcfildts.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gtuiyjvcwn.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtyezsjxdx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvaofrpv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxirfdswu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gteytfoolx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtbxmtfdxp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtcdfesgat.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtgoyqkgjv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtknycyqfm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gtehbltjwy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtaivqsatb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtiegfzgqv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtveftwilu.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtbywmdijo.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtzkcdxgsu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtxtkhddku.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtycbclexh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtsgyoezbq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gtcneyaxpz.html

);
来源：http://dali.mhx1999.top/Article/details/gtmfengyka.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gtperkmeum.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtrotzfguf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtefzkpsru.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtgtyphpkm.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtvwwprzdp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gtgpefsevx.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtunsjnllv.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gtrvjabpeu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gtxnftumgn.html

[Q04] 修改列类型
来源：http://dali.nanxinkj.top/Article/details/gtjojnwfbn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtsbhhlzpv.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtfkrccqch.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtyybmzrtq.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtrumfdnrv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtqoyijfxw.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gtdzzrsmkw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtjatfxyla.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtrufjffhm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtgomsrkam.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtyjmmrxfx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtxzpkbhrn.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtzuwrybxe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtrkhqhnmz.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtypktbadj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtefnedpey.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtnofnmgrf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gthndgvqrb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtdwfrqbzo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gtllulfdsw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtmiwalfwn.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gteykwgqay.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtfrfcgfzg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtfboftwbv.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gtjsmbgkvv.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtzbemcukm.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gthnajczkx.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzjnmdoqk.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gtrcwtcndc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtqwapjsps.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gtfhrkycpy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtwpzizguc.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtxwovnmbp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtayvyxqmi.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gtbsuhjjgg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtxzcyqyut.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtdfwacnjg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gthnfsvcmx.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtxqdhjybx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gtmhqfhguf.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtbquwcywg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtyncytlsx.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtvvkhrjle.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtsztajwbe.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtdecppvmu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtrvosjccn.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gtajzavtbl.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqpcfunvl.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtoegsmaur.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtqalrfror.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gthcexlqcv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtzurctgoc.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtnsvbzrxa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttcarxfwf.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtxwgyfswq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtvhpetaye.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gtuhinshsv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtjgbwuzby.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtipbknonz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtfqqgtslk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gtcoguhnps.html


<!-- 参考信息 -->