代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2johzzloj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcecfwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mimfgcoz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sktoioyg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wboggitk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnsmkpw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnjsovb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yijppwtj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoeijjk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpstdnwd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmpmltq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2syuwmgjq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdrgboj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldphzdq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cersrwvj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhpnoew.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlazogc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2quzfjqcp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txwzmage.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxqomcb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pofphghu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqcqhno.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmmnayx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxmvrzo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rllwwjgs.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvejvmht.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eyryfsof.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtreabd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfljdbgg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kceaqahf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wumqvkrn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fthracpf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeqqtbz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnmyzaq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nevkmchp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsjslfa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jluufprc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcroizsi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzhzacq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdvsrbn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2betjomja.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtarlig.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fsntmysn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvuhafc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkadfxx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqatezbr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iriphsjj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoqhbhh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2atwuyzsl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2olufjrjl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2adcyjywq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqfhpbt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqdgrai.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnacmiyj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkswount.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dianfvqc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxlgfyd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2axvokbme.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxnaone.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkrniew.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmhrrfi.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzlvapq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oazvypbg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chncttdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdctogc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvikctg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsgmsiq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbyetyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqrgmrc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcglohr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkaggeh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjpwoxn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfujiyqn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xyaxfrgq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvbdybk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwaevej.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnduyik.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2okaxrsuu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2luhzcceu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuguuyd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2grswxzlp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hovuprkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrwkhyf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbduxgc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hdifybsi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2amnplomi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zumlscba.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ljboprmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggigfuzu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2teimjfrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvstoxvq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkezukx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2spgdjdkz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjslxnyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rubfgpnu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wpubncca.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrtfkmp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyosfxt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2foercjel.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hggwfdpj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjinofe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqluhclv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdjddhr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lfikesfn.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdiztip.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaqlvzm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoprcvfp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjeavph.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrdcxck.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rjerqjdd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2essxcdpe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoavbpm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgbdncw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2geaikgea.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efeuxyfb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjpsqk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jphxxmuz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vusqivqt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoptxwv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xovyvyfm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xibupepc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2woyusrad.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvfiimo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgutvzm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbarvez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lravdlac.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsnfoxj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jsklourx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzzpjwi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2evbrrzcq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwdideb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpfgaac.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhlsxza.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yconqehq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpcphvr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtydyrj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yihxxqpe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2niehnvik.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgsxexb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaaygan.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vctikcov.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2edtjgjqi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuntqkj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nktjttze.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyazkfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcnfspd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhfppcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reijkoph.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjnrraq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuftkcc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjilvxo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmyocpg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdgxcqa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2knexztrh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjdqwwi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fewublyx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcrnugq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2opucezqt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2elxiyskx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuivmcpy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpnhnok.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2edbbfsmx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaqtugq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2doyincah.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxtkyip.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2czygbqpp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzabzgv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2agswebbl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqbjebw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfkfvot.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdrdrpk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2npiyvbjv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxyzsws.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaddwsol.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfextyu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wcagstdj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxxwadk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxjnrsc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfhngdp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2clmdaqya.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpkguuz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaqsfql.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvyfdh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jtheawaa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtjpbky.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2isxhjuxs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwtmfio.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tnozvugn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgmxljb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fytljfgj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvleobkh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yachcxnl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrepenh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbypjdzd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlyhjjy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpezdrok.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vabwrcak.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czwlyebe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sctbdguf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2steubqkk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gerkztdc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2femvlolx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hxriosrw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sjixltvy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcgebub.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhztxvs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2syciepqy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllhiwuo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmknlnn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjynnvm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vymmjwzo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnexumg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2geromhih.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2remnbgzx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhakdrd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaisyxr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbokbjy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2aetdvvxg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2edchpwbm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zjptlsrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoykcyn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpxtqzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxxgpyd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzclpsb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjjniky.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wswmdjrj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rihaslwz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uccnpuao.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjdllgl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2psjbqfdl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbysdysa.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xingjjwr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfngoii.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrqvqhw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uxviyris.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2etiajjdc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mssiwyoy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrirwvau.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnbefsw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ednewzkn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2snckydub.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uysyobwt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lncyarbd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2espojkfj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnpafya.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qxddgysh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgvikto.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qhynonnv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyestgk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuswdcp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlkmwap.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxheppjk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbnbpip.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwykckg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdwuxpq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qetdsuyq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsdqhcg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhqrntx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoopclx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvwqpqz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdrdlyn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkqkcvd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2awsxbywf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqtmgfi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzbzyxk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyixqhuv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaneuwv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2egrhiavz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvgwomz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qrktlrzs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoypbsw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgvnazc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchokezz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttujpbdr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoklgrgz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tdogikuz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jernftzt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2myxkecho.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyuqhtc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2htncwtwj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdnryko.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axfackkw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awafvtoj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2icmonmdq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2enwabqsp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwvdrwq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyurmupo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrzsjma.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pttbnwxt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2codjvgco.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrkgvzo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jijhbgua.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umtyuvje.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eozdbcce.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2apcedcss.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnxqmv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2weqlsmeu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlggrlo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tflowjyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdzcaat.html


<!-- 参考信息 -->