代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oumcizsq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2zssysqxq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2ivflhwtd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2sclztdof.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2ijmflanw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2kwfeunzf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2okjdksrq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2fwyqzogi.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gt2nirwdugy.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcibeemq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gt2hbngyugv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2ruhcqnfb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2pwgmaayu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gt2bymqqynb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2fawqihcu.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gt2rtmmtoih.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2hghlqaax.html

[N06] 判断回文字符串
来源：http://dali.yvedp.cn/Article/details/gt2lwhuyeqt.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gt2kcjbcwhg.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqttqkdp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2zqgfxyis.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2csvnioeq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2deyltian.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gt2ltvfsvja.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2amntrdcb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gt2aysxqevs.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gt2rfbnwykm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gt2mjqjysol.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2xqlilpgm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2isgyyhos.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gt2sekuoixz.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2lvswpfkc.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdjtarcz.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2kiuwaflt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2nayjvadk.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gt2zsbljphd.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2fykhqyqv.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2fbdicokc.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2sznrlmhj.html

TS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkwcuxjt.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2bdkwftsq.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2urfzhaoa.html

Ruby: arr.permutation.to_a
来源：http://dali.cdnleiting.top/Article/details/gt2srbdqiln.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2lkledmok.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2yyqqomsl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcbjqyql.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2nobgviwu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2vnglmgxn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gt2tpozcrko.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gt2qwpwlzct.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2lzorujth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2mwgpjtfr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gt2ltnsowfx.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2pvnrnsew.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2pgzqozcf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2ofgxxhhd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gt2kbbyokwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2qtiisuju.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gt2rovqsubk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gt2qdcortqw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gt2txjhwlgf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gt2kefrjwgw.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gt2pcsmwdob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gt2ozhnrorc.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gt2mrsqcrhy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2mjtfehmn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2qhckrfyg.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2gmtatifm.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2yucscnfh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gt2eimilwup.html

C#:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsrqbhmd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gt2feazmrkb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gt2qkfpnjah.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2vyswzzeb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2cbpsegob.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2nhwvxhsr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxhralgh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gt2yolfwuyu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmkvkzkz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2gkgcgjjd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2zunrhdzp.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gt2fayjtavh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcgvopmi.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gt2eqzvafbv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2ykpjmyzk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2czocdtrh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gt2pekjrwum.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntdmkdbg.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2knprgufh.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gt2cyyqgnqn.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2eyevkcbg.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gt2pcgclyht.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gt2bdrgtxgy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gt2qbebhegp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gt2nbugeqla.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2gckoglhl.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2sitlolkx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gt2ruhpuvzq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gt2wkojlcak.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gt2fuqredpb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngghclyp.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2jakondsn.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2iwxtlync.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2dneqsjtp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gt2uejsmhjk.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2nscxmqkx.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebnsftoq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gt2xzembrxx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2eppcnsne.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2dwnaftwk.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gt2flruunhd.html

Py:   async def f():⏎    await g()
来源：http://dali.sufxvd.cn/Article/details/gt2wvagjlox.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2othbaheu.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2rmhakopx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2tlibamlh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2wxgiigyb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gt2ojayvaqd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2dghwqopt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2fuzdoxgd.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gt2sgaytbcs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gt2bhaignee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2qmntlnou.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2baxslkbh.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2sknbefqh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gt2kajtuitm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gt2xybrzowk.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2yfgjfvce.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2oyjqwpqo.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gt2wtiyaelr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gt2ulfyqomb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gt2nhisqtej.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfvsrchy.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2qvyeulwe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2swngoukm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gt2ygygxzzo.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gt2fpkhjeug.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gt2gmapseok.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2xogabxyj.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gt2eoulihqw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2pfahawkm.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2wjpappoq.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gt2nprztptr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2zofohmuu.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2rtjznrkb.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xonqypnm.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2mwndsyqr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2wftzjbcj.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2pdyvnqre.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2crmktfyt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2sbtxbnzj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rfdgrnfl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gt2lkrayizg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmoavdak.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gt2xkcszjxd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2umpaitvy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsgtgluu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gt2xedpoajk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gt2hylnpykf.html

[P03] 生成短随机字符串
来源：http://dali.316326.xyz/Article/details/gt2wmyilknn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gt2bkhbvrhk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gt2rzlfscgc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gt2biwufqaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2motoxjuw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2wslffipi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2qcxhdvxu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gt2kwnsmeoy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gt2boqtyude.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gt2yoftuzso.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgwbbaue.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gt2xoakotsz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gt2nzygkpnf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqadlacw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2tsizmqph.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gt2jntadyom.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2dffpbswk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2zqblpwui.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gt2bcvmxoys.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gt2uujsngbb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gt2lrbimtiv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2jeufzgoh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lamhsfvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gt2ysxawdso.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2baymxqcs.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwawlsnz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2ujyjvhzi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2nrtlnqgg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2pltifmxh.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gt2atmrhsht.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gt2vuggkqii.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gt2wwzjmvtg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbbvbsgg.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gt2oifthjas.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2tnxnrwpl.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gt2dlbbstgb.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2blikaess.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gt2hlomurmp.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gt2nwymkyoo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2voqplydd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2plkprdxf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gt2spykyejb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gt2cpjfsqoy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2bdsoeufl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gt2qusjisdc.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gt2bxkifoxd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gt2tbvbksix.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gt2oidotdza.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gt2xmhyedpw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2cwnhrvam.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zckpngiz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gt2dexmdxsn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdjcdxp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2tcxvjubf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2balfhapw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gt2qxqdxxei.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qohqivkl.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gt2ohdfybrk.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gt2sdirwjgi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gt2togupgxt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbvejiiy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vhruxbfr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gt2fqufztkr.html

);
来源：http://dali.bjfxy.top/Article/details/gt2dmvdslwp.html

[Q02] 创建带外键的表
来源：http://dali.yongpay.top/Article/details/gt2bcjumkfc.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snlgzfey.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2mgdvdywo.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2nuetgyhl.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gt2boeketvy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2vnpnrphp.html

);
来源：http://dali.gzhubu.top/Article/details/gt2brknmyoo.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gt2yhonvkta.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258888.top/Article/details/gt2hwxcpgbx.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuhkdcid.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gt2upwzsvpu.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpskucgm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gt2qhbqmigc.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2rruphlnf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gt2ogallccg.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gt2ovhnqpse.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gt2mvvoucwc.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2bezqixrc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2vuckfoww.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gt2tzeprmaz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gt2bzlwecrg.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gt2zsrvdznk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2fclqiefo.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2viynbkzl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2xfadqfrm.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2mvcnalac.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkiopivs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2vsbytszv.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2kmbdffxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2dlphwnsy.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gt2wgnrgmgy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2opgvuwel.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gt2virnluto.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gt2pxyovfpk.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2jwbigapq.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2qapjjxwx.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2nejbsxrn.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mykeqgtd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbkdveea.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gt2fvojefgq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gt2dgujzckj.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gt2wjjsmghb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gt2vccqtrze.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2pkcepijh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2fnwoymwo.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxvapwgc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2ledmvnph.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gt2dyzkglvg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gt2rbjsbgak.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gt2gxxunobb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gt2idchxdka.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gt2hdeanlbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2owowkbuw.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gt2bewekpze.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwqripev.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gt2ftdoolkr.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2pnrkfaua.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gt2kegnxyrh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ecgdzahi.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2cmewlsaw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2vxfwbnjw.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2axdjeybo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2hyarnrpa.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2flnmjkib.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2lgbvkdta.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2cyqrghtg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2euvvtdwv.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gt2haqsqewv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2tgslsgpx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2bmgpnvoi.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2tmdkmvbc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gt2bfqlnvmf.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2idxwugbw.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gt2ooxseakb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2xgyixglj.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gt2fietkpkf.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2osojgbwb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqabpsxd.html


<!-- 参考信息 -->