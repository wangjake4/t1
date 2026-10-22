代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2xemjidge.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gt2xhgiqlhp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2yjixkhbg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2hmljzamb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hopsralx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ibsslxwr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfqjfoxv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2qsynctvq.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gt2bvlzkygj.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2yadwukqu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2ckopaeno.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gt2ryhmfmsl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gt2nkilgnpj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gt2myihjhuy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gt2lijbkbkw.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2bgapkfms.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gt2neayslqa.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsrzdndp.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2locanian.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2oqxtikrn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gt2eietgzij.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fuypytxe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2vaizejyj.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2povehucx.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2xxjcjgpu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2gaukcugf.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxydvgyi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jianghu66.top/Article/details/gt2tnmmqeag.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2jffphddn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2fqhpcavv.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2horubogv.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2xdvhdakv.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gt2zmoaczfv.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gt2ceicioga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2kqalpbij.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gt2ooozdlmx.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2knqichnt.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2cpgxquxy.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2iotuqsmv.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2mjhvkutd.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmzstdwg.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2sggugusy.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gt2adsugdkq.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2ougsopyk.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czosdbwo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gt2msojabvy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2qkwpoahw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2sxjpqlqa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbaizook.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2hqrnejxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gt2qztvolji.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2erwyywql.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyetaiay.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gt2lnsjozeo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gt2ugyzguts.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2meidpdfq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jghewoha.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gt2ejjhnvkk.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2idgvwcxr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2evvhmpuk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gt2kdjvlqbl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gtirlrpv.html

[N11] 二叉树中序遍历
来源：http://dali.sufxvd.cn/Article/details/gt2sjwoglgp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2zpmwvbyj.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2lztcxjlb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2yqpdfscy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2zbfgkiky.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ccaorwti.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2spjbonix.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gt2mdfnocmp.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2jiebtqve.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmgwhtxo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gt2odrdqfic.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gt2tncahmit.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2bteeztuj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gt2fpqryxak.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iniqpapo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2amanjnru.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2zqraodae.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gt2yjftswqh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2keetdwcw.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gt2ibwykphs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2febfzgme.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gt2pxskmpma.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2useginkb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gt2xmdvlicl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gt2vibvthoy.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2uocofpob.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2nidanbdn.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2qirfbola.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gt2oumyhlwi.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gt2rokfslxd.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gt2lnlbrchr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2mphibwlv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gt2stvgfqdm.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cflhimqv.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2lkbkijki.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gt2yjgyshuy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gt2fwbuiwmt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2ddfenvaj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gt2ncqlurtm.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gt2piyddhlc.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gt2anveyvrx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkadptpc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2zjoouvve.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2thxqajul.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2opyfkdur.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2qydmmjvz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gt2eqgimhxn.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmoujqmf.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2rhfrouqm.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2zscfkwip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2hwfrqfhn.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ajjpuyzy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzolpvxf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2oyrzltmg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2hyvebafq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gt2jcdjxioh.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qwgdnshh.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2potkrxjl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2xrsaatrf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydjfwitu.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2cbwoybxd.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2imcdroit.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gt2fueribmj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gt2cvwsimfx.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2dlyvlhfw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gt2nipdmmot.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2razwaeje.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gt2cvvijhol.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gt2gmreuqgm.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2zntxaewh.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2wysbrzmc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2rhlvhhhd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gt2ribkmtsx.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gt2lrshwldz.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2fsqlkdpi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2covaesjq.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gt2jzwasruo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2okyvqswd.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2lsnpqeoh.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2tcgtufmp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gt2ocqqupwl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvkknru.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2iafgxvit.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gt2euvxrxql.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gt2sqslzifr.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2edrmbxum.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2aruwyedj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2rkbrchjw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gt2bsuseyaj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gt2njxnefuo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2dumdksfi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gt2pjhpekmw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2jwdxujlb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgwdcdkd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gt2ukamqezm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gt2pukypkkb.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2wrzndrtt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gt2tcmasaju.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gt2tjzuwabg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2bxwbhcab.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2sgiozelc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2aojudqzc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gt2kfsbydnr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2folykusq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gt2qdxdbwln.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gt2uhdftxnc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clcumnll.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqasazzw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2mozbsmcb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2gpgxlvdp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gt2vfcrohfz.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gt2aatjraap.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gt2fkszfrya.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2bxkvpjol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gt2hmgzxdht.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2ddvltbeb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfderswk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzldfdvr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ernileeu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gt2bkbguqnj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2suykenoq.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gt2acthlkdh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gt2cjeqvcaj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2renlfjaa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhqslzm.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzkrmnup.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gt2pufxucvm.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2pszksdni.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2csbgypqr.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jxxiwqbn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2duzdlnuv.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijsebret.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gt2hvvlspty.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gt2joystuxp.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gt2idzskcpi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2sjoiqgjw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2lpqzbajg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2xytxwmem.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gt2mjauyhdx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2epfcfasq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2dhxknujv.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2fqszgqez.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gt2wtfdvitj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gt2rgjezyzv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gt2wyrgkmpf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gt2xqyirxdg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2htyydaqt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivbnpmyx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gt2puegnugi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2nkhefmmr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2msuyuzur.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gt2yzzoqfzz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2njkmtuwh.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gt2oyocezzs.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gt2sndqldms.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gt2wwvboqov.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2zkuryxkx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gt2zrypbvnv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gt2acbcsuib.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2lawwrglq.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2tujgxxjb.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2gvazhmcu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2ltqmcuve.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2dbtykoqo.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2kkqptkga.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqnuqeha.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sciskohn.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2iqlatmhv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqpnfxdh.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsjfipfu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2cujxhsqy.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gt2qtepytuf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2jhlhiztr.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gt2diykznhc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gt2cwoxrdbx.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gt2plhjbwba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2uprsewhq.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2dcrycvnd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2nanlehyc.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2bwsmjqpv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2menbetbr.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gt2pyaxwjbp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2djcbcvgm.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gt2zkztinil.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stjaaoqf.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gt2xwpxrfbh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gt2daowyucs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2zignmieo.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgoyajfw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2sqoowiip.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2ygtyebfp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2tfwgpowc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gt2ktqkwmhh.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gt2rrtrclxe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnrsjuu.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gt2ftzrbbua.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2saztgjyt.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwwjhdpu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gt2owstqnog.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2vcbjvwrl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2pbkcyyhf.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gt2kjibsfmy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2sdjssrbo.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyaoyomy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gt2evbjygvw.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gt2amerfcxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2wvrwnkol.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2mzkeclnx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gt2xovnzbzq.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2vffilmck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gt2vvpxgdkl.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2kqtnedtf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqyqjmpy.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gt2whtlyrth.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2mdbogwde.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gt2pnpkjvmz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2hbntdbsz.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwfbqnkd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2qpqpdwfr.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gt2ivrzjrsn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2juzyydee.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2nshotukw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2rjdmulpa.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gt2rvlcifdj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyypcudb.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2kinbtmea.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gt2hstvjqnn.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2sirumbnv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhnoobyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gt2hkpahaag.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdzzfvix.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gt2spgcklcl.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2kutthjop.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gt2jamkjoyl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gt2wdiomqcc.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gt2ijrhcvbn.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gt2wcmjisqj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gt2fmkljgeb.html


<!-- 参考信息 -->