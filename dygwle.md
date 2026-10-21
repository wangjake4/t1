代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtnjqoyxms.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtrlcuvyet.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtypoeeigs.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtocofhsir.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkdiddtb.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gtqigvzlnz.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtrvbghwct.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtvxgxigpu.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtlrztuiwc.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtpjpztdue.html

Ruby: arr.permutation.to_a
来源：http://dali.aizwys.cn/Article/details/gtijqtgioj.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtcuymazqh.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtykubuyiw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtdjinssfc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtsqwfmsxv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtdidvgpsk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtzcagqhls.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtqohrwxck.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtlkfrplnu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtvkecburi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gttfxzefsi.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtoieshcbt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtynmszrmm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugpwdbep.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtszrhmwum.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gtziorjcfn.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtnucdjkhs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtfapdlhkf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtqxsxjkai.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtbncwmkub.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtdfkbruoc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtmibcwljj.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gtcqpbtsny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtusycifrc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtxslhtfue.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiokjjepv.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtucabfgdt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtpauqciuv.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtiibnxpnq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gtldxhkuvy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccpuygta.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtgsgkchfo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtrieputsa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtigcluajz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxzyeuoi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhixingplan.top/Article/details/gtoyckbtzu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlalqhwja.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtohjcvgsi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttbhchddu.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtyfbyakdd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtflzjjgnw.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtynzprpko.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtxlmtneiv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtjnghkdad.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gthhwlwbkd.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtgxzbjxiu.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtkiikdckk.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtdnitngpd.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtkmczmyhf.html

C#:   Task.Run(() => F());
来源：http://dali.pengpengdd.cyou/Article/details/gtavzrpeqz.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtollsumin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtfayqkpoh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvjebhuh.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtdnvzeuqe.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtjqwqxsvu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtfptvlswp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtkanxpbmp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtjlvkrifq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtfmorzubw.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtknazzbty.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtbjpfttag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtfruuanqs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtxkypoocb.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtikdoeeoo.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtsqfifohs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtnqrjpjgc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtabmkmbcn.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gteefdpfri.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtybkkyxxc.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtggsfmisq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxyatggz.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtstohctpr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtbzvtqkfw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtauylbupp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gtvcoslfii.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtoyehnucq.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtvpoqjbpq.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtxgddnbzo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gttfljvcfn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtcphxyqpw.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtqcvdlkiy.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtptobpbju.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtarkoycyh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtttalxlks.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtthkzsqfm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gthoeldunk.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtgrytufno.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtvvgqtqge.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpexarhsf.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtvzzymafa.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtgpnemlhg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtrdoyflbr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtxvsqgtup.html

Ruby: // fork 块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxigeqejk.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtuwfcjlyb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtggvysnid.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtwcyydcbc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gthfmqfddp.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtgbonuyvf.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gthfglsiip.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtdewkpmhy.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtiokhnlow.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtywpztoxo.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtzsqwoefe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtawfisezd.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtawmbnqfi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtjeavlqmn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gtxnuugibg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtnrxvyvan.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtclfqpuhl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gthmfhmbyg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtisvlnsgu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gtqqvthdsm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphjogalc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtzpxcerej.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufiqxeti.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gttseruhlm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gtvpzlkhwx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtpdszliac.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtaulmutpw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtavgigpta.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtzbmyhkqe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtzwjkzutz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlddnilw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtvdpobjxa.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gtetkcopja.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtqpzvbrop.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtjhhafdqu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtvxkdtcnd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtruzdhwog.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtwlqyvpqa.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gttmyisgti.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzpcsvrn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtoztqmamv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtcqsmyhab.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtoyfaacnm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtxobmiyjm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gtzphidpwx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtnzrablsi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtztpqexzn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtuczsumeq.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtkvpoxyei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzylqqsx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtnkeldvwd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtonowdlfl.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtbpxaujes.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtjdoiozzf.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gtwkldnhxd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtchlcqdoj.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtusxhvtyh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtqawhyjlc.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtsqucoaxq.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtzvetckym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gteixflqjr.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtgzndlxyx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtwhzqdtej.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtwpsltget.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtnpqywdvv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtxbxhklkn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtnthfkswv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gtxhueqneo.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtlclmipeb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtmgmcroyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtlvhrgeoh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtpsjvsyrs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtmsbppbte.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtunhrbpyq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtsddkwfug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtytyfokds.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtaxcdhbuo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxxodghgs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtqftzofqu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvsjcjrfk.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtyrefewfb.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtdljaqehi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtitdymnob.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtqefmopwv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gtmoswzduk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtkvbbvqdu.html

);
来源：http://dali.pycfn.com/Article/details/gtyppjfgsw.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gttrdawebi.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtvbycvxlx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtcxcwoidz.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtwfghmped.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtomgynleb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gtxnvpiisk.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrehjbcr.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtfikffaoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtyraqnvei.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtiymaqojo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpowmbfd.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtekprvobf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gtnkhwsdhi.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtcapkpkxk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtevqbcwng.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtklyxduzr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtkghdvqdi.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtivcfsjwz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtbrwtcive.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtkflbwuyc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtinjbpueb.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gtffhfyvdw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtzrlyplcy.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtatcibxms.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtsmzeacon.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gtxplueidi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gtbpwdsmlf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtfogladog.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtjrdrwrkt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtlseimblr.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtwcfhxwmi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gtskqplpqn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxienaly.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtfkwmodzp.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtfkrsalxc.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtwwxhjsno.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtgtolwuel.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtmjywdnoo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtjwyunfzc.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtuwnauaau.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtblditbpa.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtjrhwtuxv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtiosuppjz.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtpknqcyul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gthplbgrlw.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtxfrmtprc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtzpopiape.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gticlwrger.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtzreyfubc.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtrzfrmvif.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtkktppryg.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gteliifiaq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtnacpaqwt.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gtoyksixoa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtcbzbzsez.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtinkyevzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtutvqhjnq.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtffpulwpk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtdbarvvpi.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtyuwnigua.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtdabpuxhh.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gttfgtluge.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtkombuhnc.html

[Q30] 分组统计
来源：http://dali.sweek.top/Article/details/gtfjgzlioe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gttyylqcik.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtyffoqzhc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtwdlsbond.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtrodwglfy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtpablwsje.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpfajedb.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtcbyfixnt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtpkhuwzup.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtxojxuogz.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gttcssseop.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtadyahxnp.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtycwcnhbj.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtqidniobf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtppznwnfv.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtrsxjuayz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtnthelxfn.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtejndmnbm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxzafpio.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gthqtpidkc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtbzfwvsvw.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtbqcgbyxi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtnbzuybum.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtadyjfyxe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtdwezmran.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtdvxzgtqu.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtnquwhiot.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gtnyxvbvsv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtsduroffp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtocqwbqkc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtneagsypp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtgiqwsgfu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gthwdsrags.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtgfvsnauo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtockglaul.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtyvzyjtoq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gtmearmuvv.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtjmfmtfxw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtyepidlqa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtkhrvkxkk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gthywtkbbj.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyxhaenx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtpixuceyy.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtlvhdhoms.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtnunzjilp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtruiqkies.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtfyxszqqy.html


<!-- 参考信息 -->