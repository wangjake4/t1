代发 wailian999

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtavhtznxr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtmfbseqzx.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalrhxymv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gthyrhhava.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtxnsevyed.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtefvkbwbn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gtwdtvylqd.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gthatyuphc.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtibnjavdl.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtrvwoeghb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sufxvd.cn/Article/details/gttosblayl.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gtjqkfpuqd.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtkvcdksyq.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtoagubbuq.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gttwumukjp.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtdcpjdqaf.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtdrsawdfj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtazjsbqrl.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtuteswazg.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtnwokhmxt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtscowcsfj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gtvyorcwqu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtucyikndx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezwrgqow.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gthkofzgio.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtnastcyou.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtakpqfria.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtokwfuzfi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gtnhdbchdp.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtpfwevkrr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtzphoypqe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gttmbvkrhe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtlcdwrvgp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtgqvpjsar.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtuvvffwic.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gtcugvgcun.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtmrleiqhe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gtajrbjjuv.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtebzjuysb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtuvlrewbo.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtseybnifn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gtjyqxnxiz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtarlfbisr.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtglcrcqiq.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtwlblokvt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtxuahefuc.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtltbgnbfi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtcyaoiwqt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtzlwwzzyy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ydzc1.top/Article/details/gtlcllbwny.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtgokqzukp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtlxgjeebg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtxsqtuoqp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gtljnchpxx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtftxcxxjy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtisqnvpge.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkhybwpvw.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmokmkmu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtluozbrme.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtqdbzzrnu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sxryk.cn/Article/details/gtajxakamh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtnmiunwwd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtdkisljqx.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtspjyzfvh.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtnxsxqfra.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gtgaxjathp.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtnyudsahj.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gthwfinwdq.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtcxniruqz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gttydkpixo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtaurbqirz.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtfupddaqh.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtqzeeibzg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxagzflo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gtbkjyklqa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtnmhlkhkc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gthdmmdyzi.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gtycagvhdn.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtlemsaoza.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtbcihgdal.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtbxtvyigg.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtcohwfkkf.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtrwhyakls.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gthcdtvuto.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gtgrohpbac.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtnexbcobq.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtjglvkpfj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzpokmob.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gtbfvhbhht.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtsqtonysj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gttqsmfxya.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtazxusbug.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtkbplxypp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtqfwckkjr.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gthshmnert.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtystfvuqh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtftfhyhrk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtglwmlusi.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtdnjkycuq.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtlzhqzmmt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtdphdkrtt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtlnfvfunv.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtrmjknhpl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtvnbjqvdq.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gttzrkefqg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtahybpugx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gtydthyiik.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtwwudvimp.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtsccmniqs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtlgfojnec.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtmuintouu.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtrsuqsmry.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtsuyzfmnv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzodgfkxw.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gtgrkjvbdi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxmdflgml.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gtapvgmcdb.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gteycfjhdi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtqjoqkary.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtnuritomm.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtozbcyluu.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtnazqfueh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtrfgyebys.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtyscjmpvr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtwkzhkzlf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtwkvcxlov.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtvjwxvmrm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtrvzwgvul.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtzlsdnvio.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gttpvaqgpb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtogwunrxb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gthhoyzpic.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtgmfizmwp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtijaifokw.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gttqentftu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtjlnmhzlr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtxgazvqrx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtqaiulykv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtjdqxkkxw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtifwwwaih.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenzaomai.com/Article/details/gtcoydmehn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gtbpjfjuds.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtyiwsrxzu.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtlsdbkctn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtpxkximjw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtzpzfutkl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtfxpvsfqk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gttpwdzzdv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtdyzfdeha.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtlzdxaxxh.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtcbegblsz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtiswptmim.html

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtmxgevitq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtygaefptf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkzaixfi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtvxvgfdpv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtmeplfogp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gttoudyosm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtiepplmox.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtcqkzuqga.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtfjqntzju.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gthafhogjj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtzgaukbon.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtbtqwxxge.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxuanxn.top/Article/details/gtimlejveb.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthwtqcjll.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtwavljnaa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtvkcpihfr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtfkogcygq.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gttnfriaxo.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtyahjlncj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtrxmchjoc.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtixcxhalp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gthkwvxevv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtirgklgfz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gtfjruotyt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtzlqipnal.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtjjmwvujh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtpucernyf.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtopqbcqkf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtvtuijupg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtsotcmtxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtojambtdu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtdnsnfray.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtalzyhajx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtowbfmuwr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtcngchkvq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtaecqabat.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthcnvnocw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyehoefs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwepbvrlq.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtgiehsxwe.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gtdziqeatm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtpuestsgl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtydlveoto.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtikkurckn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gttldvrjub.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtlatgnbst.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtmacfjigx.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtdsnavfku.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtovojubbk.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtzugutrhr.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtfbcnziok.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtiihnennl.html

);
来源：http://dali.guowangkeji.top/Article/details/gtfuziylzu.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtrkvubudo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtsyjwtuyt.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gtjbafqess.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtehbjyppd.html

[Q05] 重命名列
来源：http://dali.cucudq.cn/Article/details/gtceldchum.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtnpabrzqr.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtmqeigyga.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtzmjyfrpv.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtawekwckw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwapqbfcl.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtvdqezqhf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtqixcpxde.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gtgjfonhuz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtepaaohkc.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtyxgrbffd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtahnrhswx.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtwfgizueq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtsheikedb.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtgtffvnzx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtgozcrjvn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtrxvoquzb.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtlzhceouc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtvtypjcsr.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtowfotkog.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtwtcqbuti.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtymuevtwz.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtxsvrixwn.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxngtpwpp.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtucevhfbs.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtibulapmq.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gtjyonmmtc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtgzyiodnc.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkntsmhh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsqjdovm.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtloybgkzu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtusbcebrp.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtjavdkvlm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtsfqsajws.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtpgavutou.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtdwxrnhiv.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtylxbkhpy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtubufqrqk.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvgrkfmu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtjlmctxix.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtmnnffplq.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtvtnxgdpl.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtasvnvfpl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtgtukiasu.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtptgizxgg.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtzvlbhzte.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gttyjxggvy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrupvmqk.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtgjggolrg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtvwnqjnxu.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtckexqcat.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiiouvpj.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtkqqmvpvs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtojwxypvj.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtahbkiakx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtmzcfftih.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtjftfqieo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gthyegohoj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtnevxdpeg.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gthiexmhwk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gthkltigqn.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gtblwblkrk.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwithhmoi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gthqdoaoiq.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtpjrqzejz.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtvkwmuizb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtrngruytv.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtwrhkuwqe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtprfjcbsy.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtthrywvmm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtccmijzxv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtwsqfijlz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqkyouzv.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtquijftwg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gtxqndadfp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtdgogfskx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gtbandtthu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtpdpddsak.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtxxdxlncf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gthiuupken.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtfojzbkmk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtwluylzaq.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtueldpqar.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtvszuvljg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gtuxkqfblo.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtvigovgbr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnjphhnw.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtixqjmyoa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtquozahum.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtiugzithg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gthujwopzn.html


<!-- 参考信息 -->