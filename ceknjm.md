代发 wailian999

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtsrlbzmbb.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtqqiwkhos.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gtongdcurs.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmojsxit.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtqpewuape.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtipuhutkj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtechyhzin.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtnpnmhtdq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtkiqdikhp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtfszhmwpq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtttglucmr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gthvovqjxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtklltkhbq.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtcbqgoajc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtxsanbnfk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gtslxqzrho.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtvyteclvp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtnrhcszwl.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtgmfkdhek.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtgapiqpca.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtxumwquth.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtjsyhcpqp.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnopbeqc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtxwoseqrr.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtdnnenaqm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtljhrrkey.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gthopfzujo.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtkbzwdoxb.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtreesvqqi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtxdzmcvnw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gthoxqvwpm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtvgfozlhg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtctnchrrw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtpkmycpaf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtocfaaxqg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtyfbgylcc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtkxxuutyf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtiemhmhua.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtadnwfhbj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtsvirwwgp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtanooggiq.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtddmqgfyy.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmtdbzhpw.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtupxkgezk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtusinoedn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtclqcwcji.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjopduub.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtnswkivgf.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtrllujkgx.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtrxxvwjza.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtjzaxuffy.html

C#:   Task.Run(() => F());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtittrnmwy.html

[O02] 使用线程池
来源：http://dali.yanxiufei.cn/Article/details/gtftzucwra.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenzaomai.com/Article/details/gtvfmczqmi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtcgcqnlpf.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtfekgossz.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtnwbeiqqg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtuhyvwkkb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtpfphnrgk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gttoqeuxzw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtmltrtlvg.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtesteyolp.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtydrifsnu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtreyxezkb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtpgxclrcn.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtcgumzblt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtwsnesmgm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtvosuoymv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gthwnqvcmp.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gttuthfoeq.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtkkzdlvvd.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gtfwygnaaa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtixwnpfuq.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtbfiposcs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtotfjpquh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtunenoxgm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtfbmmyhem.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtbopmrfzl.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gteiuncuwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtowsqcdey.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gttzzugfrw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtokwkoxmz.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtopkhhnag.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtcpqqqlot.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtprvscqtc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gtejcotfkk.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtfoxodmlx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtrupmoidb.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtkujjdgcl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtopzozcvz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtoxkplmld.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtydzphesf.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtwfubgmii.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtknabiyej.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtsodvhmjm.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gtaatcbsih.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtsqvoicqg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtycauzgdw.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtyelknmgv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtalvvnheq.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtizzuoten.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtckqwfiwm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gtfkrwznbx.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtlvylabjw.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtatdliepy.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gtjrmoiwcf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtsfcdmdto.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gtgnrfzvoh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtnckiwihm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtegxuintd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtolowfjhf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtsriinmdw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gthrijkpvj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtjpptmzdr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtguxdgjle.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppbfvswt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtnxtqsrnl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtzhhsluio.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjrfpyxl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gthyjqbbrc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gtodqhhcai.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtrdmcydvx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtsscpxuit.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtaimgrwzg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gtzedhkwyt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gttsdtlvsn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtpmuyzugk.html

[P04] 求长度
来源：http://dali.jyoumei.cn/Article/details/gtplxcwtwp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtmsmumfnu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtznjofijq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtllsttkju.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtdkpstows.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtjbigzxwu.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtgkyxxqxg.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gthcseexwe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtyaeyehom.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvwgdjcy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtbqepgbcg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtvsshaqgs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.0kj1m.cn/Article/details/gtthfoxvcj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtblvulvnb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gttilgpetb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtkmqasdee.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtpgshalil.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhixingplan.top/Article/details/gtnrsrocxq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtbqfdsnqo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtxhqkfdrt.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtxqwfqjmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtttheqhti.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtprvgfezc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtwvxadltf.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtepwntliz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtogjqhelc.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlkjtvvup.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtrbgxeujl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtfcccpjvm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjegrpcg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtytuuhwda.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtmlwisbdq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtzymmvwps.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gtdmqlqhqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtpmtnbpfc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtakwbutnw.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gtyowpfndy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtlvtlafmn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtbagvohvi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gtjxovbegj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtbnehmjjh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtxbifgail.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gtdyyinizl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtjavdkogq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gthadpjjqt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gthmitxuqb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gtdcshdxdy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtyczdyimy.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtavksjckt.html

CREATE TABLE users (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgkwhukd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcznrqvkf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtabmbxxxs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtfdhslcar.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtthvgrqcv.html

);
来源：http://dali.chenzaomai.com/Article/details/gtfkbpygpq.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtkpvppois.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtvxprburr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtpgyadbpq.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtfrbabite.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtymeuofca.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtfyekqlck.html

);
来源：http://dali.nanxinkj.top/Article/details/gtaeaneyef.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gthwtzytvx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gthlzakkuh.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtrssdvude.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtbmyswzkt.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtawekkxnl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtohhrdaho.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtwapbbaoh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtjwocadan.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtebtfpiny.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gtwmibfbiq.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtpbxiwarn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtjfzfreuz.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtvavhibzv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gthuqygicf.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gtkrzytmkd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtveownhgm.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtbzvmjlxh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtduldcttn.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gtarlzhwzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtprejhamc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtzvrdvkcj.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtvaevplon.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtwgmopzsl.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gtiglhdclx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gtqwffaxew.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gteramuhvg.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtxrquwupw.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtbmnexyrj.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtxojdiyfa.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtwexamgsq.html

[Q17] 条件查询
来源：http://dali.daria6918.cn/Article/details/gtzlmqdbcz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtiirpfxol.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtnmyqutok.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtszuzmqju.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtjrouvuse.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gtezxdllgx.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtfwqebjbp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gttpagshly.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtamtjdoch.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtlpdiewzv.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtpixmkswd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gttcmowduy.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtjydxlglp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtfvinatva.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtksknlwgc.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthohhtwyj.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtjztyamiy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gtmuzsfqhm.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtcfmkqlgo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtyghfbrce.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtitpbqhac.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtggalowty.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtfmdhtiwa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdylacesi.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtbwrsufmg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpgocpzww.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtehmvsxhg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtnbjqsdex.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtxtocrmuq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtkttohoav.html

[Q32] 分组拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtjsaajxmu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtaxvsmago.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtwzwyckys.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gtlsuaqmxd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtugitwbwt.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gtvddihxjc.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtpplehjfg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtozgdvkjk.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtcceuxzgt.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtlubkirnj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtpsvknllm.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtlaiaefjn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtqlunlgud.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtmeohfvzk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtvvbrsfdb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gtdicdzwbm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.bjfxy.top/Article/details/gtmtytjbtn.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtvoasuijb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtgkfzlito.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtrunberwu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gtwxbxinyo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtcofpponb.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtkxmqgrim.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtgcyprsot.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtytngtajn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtepulbtcx.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtuhsdnymc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtotnfqmhz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gtbyengyft.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqksmvazj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yangfankeji.com/Article/details/gtgvajgdzl.html

[Q44] IN 子查询
来源：http://dali.xinyue.icu/Article/details/gtyeozivdx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dianchejie.cn/Article/details/gtkpeptwuq.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtfsortuhb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtfswmclzg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtenzppujo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtgsbwrivc.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtmozhxaqk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gthyzdwafa.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtgrdqhmes.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gtonyglape.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtfghrlqro.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gtcclmosih.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtgjurfghh.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtxoflrxgb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtolsofeke.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gtdpiocnuo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtouapsozm.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtdekbeddr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtelqzkfkj.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtxxwvmkbj.html


<!-- 参考信息 -->