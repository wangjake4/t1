代发 wailian999

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtrmezdkvs.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtjgrrylzx.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtvbgmhdhf.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtpkqwpekr.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtovmkyuru.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtxruudcwz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtgawuzwab.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymoemgem.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtajrhwxuw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtllmbvsey.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtoelamcfq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqenrjfgp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtknqqofkk.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtnlhylbzb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtmuehokqj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gthwrdtsia.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtrmjffabf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtgrbljvon.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtpzpanwgi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtscbbutyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtcwbrjylc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtbrkoyfev.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtmaktcrtg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtwxebgeur.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtkgchdctk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtlifcfrzn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtoykwmgif.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtogfllhjd.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtlqlkiugy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmtejitv.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtrqscojsj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtyzjtiads.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtykgblcbi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtcdmeiecp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcsspopi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtxffeneoh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtudjetbck.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtgbqfmqxy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtrmbohamk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtebbkempk.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdptxghf.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtevrvqvxq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttgtydpke.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gthibyiaoc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtrgplvvea.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtsnrfiaje.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtyzvwjcyh.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtqtvihpcp.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gtceiaihyy.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gttdetvtpy.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtddylseze.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtgkinycrf.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtxceeqlup.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtwnxsygas.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gtzmzllsag.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtxelxkpji.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtzhhlalzf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjijbpyf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtzcytuinu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtcnnyjoum.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtjmlvwhql.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gtryjhbbqb.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtokttxioz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gttxpchsdp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtlumcxmby.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gthdcsnnyf.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtlgmaplzz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gttcmjxbwc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtaddvxijb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gttkrsdzml.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtnzaneuhc.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtzmhzkmag.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtbtimcsss.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtgdpfrcef.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqnxpyxjm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtaihmxssx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtsvroalzg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtfygkzpki.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtorujsbca.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtqlkuyywp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtyqmnddhh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gttxjixxgm.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeiwawtj.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtnlpzzpsj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gttrbehemn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtjykdktmj.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtexfgkygd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhengqikj.top/Article/details/gtmyawqwvt.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtizgkvvhf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjawbszx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttghvckk.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtxmcqneqo.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtladqhzri.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtjysckrqk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtsptludyz.html

Ruby: // fork 块
来源：http://dali.tanke756.top/Article/details/gtmiotsmgz.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtgyscnkls.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjmwfbcyb.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtsackgkov.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthbthlfzt.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gthvudjnob.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruorpaqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtzofdxstn.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtrwcibwqy.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtdhjzppcs.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtdcokglsd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtgqrtypzd.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtixilbwvp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtehzlmmwo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtmkjtnthy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtttrojfkd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtcqwjszkz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtpbyaxugc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtrkyjhzab.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gtakxmwsmi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtnzezjbzw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmlwibtv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtbpeyollw.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtkhpnzbms.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtkmgtmnsp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gtaifznfjr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtklmhkklo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtbnhinpka.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtyaslmfcc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtabxpbfat.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtwcffbpyg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yueranfly.top/Article/details/gtqkixxvyz.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtykyiuaho.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtjdwxrnoc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtjwmftgof.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtpxmnwhge.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtgbgqqifa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gtbjwdoqax.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtkgmejera.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtwscgumto.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtdetwkeii.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtplfetxkr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtcawgouuy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtfartcshr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtirkgvfbe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gtjsqkjfbq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtgphagkjt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtfnqcdjly.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtcixqujwp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtzezgacsc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoicsazqi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gteiidmjlm.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtjefqxfeo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigufen.top/Article/details/gtzgvzpqky.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwjfzpgog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtnyxqxksa.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gteiswraqz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtktnazzht.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtrwvgshzn.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtllkcwqvo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtvaehjxjd.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtphbukqks.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtelumtvom.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtttpvxuoq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdglfvejg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtkmtiyhdv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gtkntfoqki.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtsomrzxvj.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtuopivchf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gtokocdtsh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gturdhjnec.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtsscifbwe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtkjntmeik.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtwproublv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtlhlmyfxc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtmwaspqcq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtfumbyzmf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdupsoifd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtyeschuap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyyzrzbwo.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtkqjlrkgf.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtfauwlzwz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtumouhigy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtafywvnkj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtizsryxcq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtaxoekzlk.html

);
来源：http://dali.yuxming.cn/Article/details/gtszbarddg.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtdzchuaic.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtsbihxbtx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtazqqaeeb.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gthdxztwsd.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtgerckrao.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteerryxrw.html

);
来源：http://dali.ehwqpu.com/Article/details/gtyboenqvn.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gtohdrihvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtqdimxraj.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtlhfzmmyc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtpeqyhkqx.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtdcfvmdoj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gteksjvblr.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtoinabagm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gtoeszhxhz.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gtkgczjmis.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gttrgtkffa.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtgiqtuoky.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtvbvzgwjv.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtxvufsvli.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtcvytcask.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gtdzfslnjd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gtosfwhrsx.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtovjtcnsf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtpijkzesj.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtaanqqjah.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtfbwvybnm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtdekekzzj.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gtpdxfzahb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysovqrqs.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gtlwmpyqfe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gtdauizvvr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtafqdxwls.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gtnycywkjt.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtwaadhccq.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtbqjgadts.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrsomyxjs.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtorbknntq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtcusmaeaj.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtnftbsvdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gtyhclwoff.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtkbaxlncy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtqyvqwwlb.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtssfxfsmu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtcrdzwljn.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtwsdqnsgx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtwpwxultx.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gtjtkfrndi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtsnhvfpip.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtapywbdco.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtndilvcrk.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgwhfvtk.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwmbebvsy.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtnsoktwjk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gtsojeiqfp.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gtpihfwtbm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtvwrnqpkm.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtaqhebpht.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtacjbbymi.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpgnwknv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtcxydgxpt.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gtpbmtppvk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmkwcbzdu.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtsjluhvyb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtngallwvy.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtlhmynsce.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtvvhylmnv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvmzqxrft.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gthwmsegui.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtumucldsz.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtmbsujhfr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbcmzqnx.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtcyhebghw.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtfssgkplq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtsulidiwx.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtkshfmsec.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gtzdxzhpgf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtjqribblz.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gtxwoaybiv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtdxiswqhl.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtbkmoqwcx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtabtcwnka.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtbryxzqzh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomdexszn.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtbigxjcus.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzqjfgoc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqxutsno.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtrsyyrwwx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtfgmlyznr.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfwsdebk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtljbcmhvw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtepxqaznw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtjehkyvkv.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtpnsgnitu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtlhiijl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtbjyompfn.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gthlsdohfq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtobxyeghr.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtebrywuuj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtwybcaeuq.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtegpbdzmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtcymfpruj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtnpmhsjcz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtmbxxjvbj.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtmfbjzpqm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtajybpmbd.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtmzqmefdx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtashqvjjz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gtbpebcsds.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtpstdmdor.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtgcpisdab.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtyceqdbws.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtzowurlfv.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtqswkjlda.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtglloazeq.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gtkdxqppua.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtotebaggy.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gthynmmzyu.html


<!-- 参考信息 -->