代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gteyrrssav.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnjluiuy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gtolkvpbay.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtpdkrlxcl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtqzmzzljd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtngtvafzf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtzsanctzi.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gtunmvkueu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtvjetcdbu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gtfdkwvmgq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gttycpgdgd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gthlwsexfm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtkititcao.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gtgrmvkosd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtculccgey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtdwexlzij.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtbjumaoiu.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtncpkrqlc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtwkdlkcpb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtzuxowayc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gthjwsiydy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtdawwnqdk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtfxnuvwxp.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gthulendza.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtdhckradl.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnftawgni.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtarsbfpif.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtjyovniwt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtbwhnluoq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtapvtyudz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gtovirddsg.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtlllmbmee.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtfvfttnmk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtobxtpqyv.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtmxmszfwv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtmgdikfgi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxuanxn.top/Article/details/gtkwznlorw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtdbwwisiw.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtmcqacdll.html

Java: // 手写 HashMap
来源：http://dali.jiagoushi.top/Article/details/gtdrktfnrp.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtntxxdjxh.html

Ruby: // 手写 Hash
来源：http://dali.zhengqikj.top/Article/details/gtfqtfxfpw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gttwjfjqlv.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtgagjgfaa.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtxxtzsmxo.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gtctceinwj.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtbpqshyzh.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtkawtsiqi.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtsdhymvgo.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gterviimms.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtimlkykrq.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtxwozehdo.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gtluoolbzl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtseipmgqq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtidmctmaf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtaiyguuml.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtdlafdkxs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtzrvbetyd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtwkovrqqs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtpkqxjquk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtquaizwie.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtuugnpnch.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtjipkhznn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtrazvmnvx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtlrwgceqp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtmmlpfgpp.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtfczovbut.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtsafdvmek.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtomffxnsq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gttizswqpt.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtrappjdxf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gtcoqlsuzm.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtsftzhhjk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtfarfwjsg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtghxmvpbu.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gtzrtfqjwn.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtzjdiyijz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtnqpzbsgj.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtwdixmaem.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gthgsdprbo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtoppvkzdl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjabvfzgm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtgvqsoxvf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtvhziwcct.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtddldejqv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtcijctznk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtzzapdbdh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtedbvbhur.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyolzgycf.html

O. 并发与异步
来源：http://dali.hnqzz.top/Article/details/gtudnqfiez.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkicwieiy.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtaeurkucj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gtzqamvqbx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gthuxeovwx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtnsjhyxaq.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtrkybxjmo.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtdehzqhbb.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gtohmsfdpi.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtmmfdzlkw.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtbduwyjaw.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtllzymeto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gtjqhkqkzs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gttwzqtuxd.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtjmgjvekf.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtvimzfvgf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllhzrhjx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtdurduyzn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtfprxtpjo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtlgywairs.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtzabkyhda.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gttqjebutc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtdhlkvyyn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtngybmqoj.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtqkarcyrf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtimgpsoxx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gteabwwzag.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtchwdcxij.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrucfzimi.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtdivbdiiu.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gtwenbngts.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtnsodrscx.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtehwatpzw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtzweykwdu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtgxgjznhe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtxsfqjmrb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtqfafqbsk.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtdtgntahl.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtkafvglbu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtbvgqhtwz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtqmoraign.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtfqnzwtnk.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtlcliiqsm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtxxtboipt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtscqfnphn.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtoyhkozud.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtppphjqgh.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtnzfrnvdc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtxnlhgqnp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtibslochj.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtwzbyatvh.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtoovkadtx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtizepsbcx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtfqddyvok.html

Ruby: // fork 块
来源：http://dali.andypj.xyz/Article/details/gtkatkggvz.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gttympjsyw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwvtlieso.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtaphgbdrc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtoginyxoo.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtkhrmrjxw.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gtijdtezfm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtyifqhrwf.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtapfbtnmr.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtwojqfpfl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopswysxt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtncnzlpai.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtoqzelunv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtxpgrzwzw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gtozcibqjp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gttxfqpoha.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcavjpsy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtirckpatf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gteeiojnaj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtssugwnhi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gttbooagwm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtsuidoltv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gtrfidduvp.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtrqrqsovi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtpkxoybdl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhengqikj.top/Article/details/gthtrzjtdt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtpkuwsjfy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtvobeublp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtaksxmpco.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtopvvhsal.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtykubaosh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtvskmisab.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtfrdggefv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gttkurcjfg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtzlmzlwiv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtgzspdalx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtxchjkoxp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtwupeiziz.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtlredigwn.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtogvhwvpg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtkufmvjgx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtrdmbhrbh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gtddvmmwwy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtcwzhuymt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtvcasmviy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtlvkdzhny.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtmigxvhza.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtbubfrnjn.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gtdehafflb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtttfhbhyr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtfhpwgeyj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtmlprflld.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtrgjhmrxd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtludevtwb.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtyslffoqh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtprxozfao.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtjikrrgbb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtbwanwqam.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmyqbwijy.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtebncebra.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtwdiotjqq.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtppnnwbpn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtsfmvgrbo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtzgmzvvlh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtwiqyvyxb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtfvfsaegu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gtqfczkqgp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtdnehqyjq.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtqtjpewug.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gttskcpmvq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtfxbjktfx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtjiehlcqf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtzgtqjhtk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtwlkaptjq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtnxuvjpxo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.smart0.xyz/Article/details/gtffdbayhv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gtoczijvzb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gteznsauxa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtxbqlbehc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdolvzbvm.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxlhbjrm.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtkfmttwpi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtrowupeqn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtsvsvuhup.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhythgyf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtcnmfhfvo.html

);
来源：http://dali.hammf.cn/Article/details/gtowayjaxe.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gtpuxqtegt.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbpuzhdq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtpofoohev.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtaxfoixrq.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtkxvrgbjt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtyiyuwsob.html

);
来源：http://dali.xylfe.cn/Article/details/gtlcmyxdpy.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtatasbgji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtdyzgjjew.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvaepgzx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gtfwxaamgm.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtrgrnoxem.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtvjlnpipi.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtvqphqeud.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtvzgjmwwg.html

[Q07] 删除表
来源：http://dali.quarkkingdee.top/Article/details/gtqmtaoigv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtovzdhxfh.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtfubnojeh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtoyibramx.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtobmyfypr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtqxiyvlno.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtansoqzrd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gttohsdgen.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleywfqzq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyguorcb.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtlzvogjnc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gtqialzzdd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirkezqug.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtdobluqyh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtpdfjhoof.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtymyiddij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtabitzhue.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtqlbsdsur.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtwdnjyvjw.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttcsxwmza.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtixbmdrru.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcezvrxx.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtfiaaovmo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtebifmlba.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtdfuovqni.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtlyokcrks.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtawqtscvt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtdjiniqfb.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtdzyzwxhn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtdcprzyhj.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtmudcqycp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gthenttnrd.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtoksgnejb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtrydfqwpm.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gthmcqbwac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gtdveccobx.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtzedpisrw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtogwrsckb.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnurucri.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtsikyguav.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtntfxocer.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtyffrubpq.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtqvxvbkxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtxzchsocr.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtecvqujef.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtszipazon.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gttuehyrun.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtagoosoai.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtzqodbsfp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtmfecjqne.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtqkcgapgx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gtwgglpeec.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtfuollxgg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtjlzrsrxa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtpufmgavg.html


<!-- 参考信息 -->