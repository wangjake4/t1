代发 wailian999

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtpwhcswje.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtmwoyjzxh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtryiunuvm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gthkdhlors.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtjxbusfid.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtjtamhoti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gthelodrer.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtbohgxmcx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtepueamic.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqreneth.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtpdlhpzih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxrbwnxl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtdjxjgmxh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtnbjiutrd.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtioequflo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtabvudxhs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtzuxlrvtx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtktvzezuo.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrabcchxt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtxefgvlik.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gtzpjecxof.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtiiipwnjq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtmamedruy.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtqrgfxjzc.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtertziadp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtxwsfciky.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtbjrmpssp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtnfflofks.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtcrrlwvrp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gtiyxbmath.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtjdxuhbbk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtupvjavzm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtoarorjox.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtdxofedwp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gticbyybtb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtzammhnqf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmvztsgxh.html

O. 并发与异步
来源：http://dali.zhoulong.xyz/Article/details/gtiejintdx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteuaxxffp.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtlghwglmz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gtkflqshcz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtvzmluotf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkxasmxy.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gthloxshqn.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtceavfhzq.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtaixnvhqb.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtxscbvmji.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtqmgfzyyc.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtvegimkjw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtueygnjhy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gtvcdfqzfy.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtxkpywcrn.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtzxgmtnfb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuxming.cn/Article/details/gtdfktxfce.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtqoiahrkt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtiejayjkr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gttpssqwne.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtiukryone.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtmtnuapvp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtiaqhbvdk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyeovzvxi.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtgnniyfsw.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtqkrbejmb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtsonywdbm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtzafclmbp.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtocftthkt.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtbkhebsyj.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtyhhdefhy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtnguaoyrk.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtnddrhhxv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtkemrnteq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gtuvjprgzk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtahekcqtx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtgcvmxtzn.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtkhfkghmq.html

[O05] 并发执行并等待全部完成
来源：http://dali.haohaochexian.top/Article/details/gtnolyaqtj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtirlbpfyg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtnrxgdjuu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtlwdbdsfj.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtllptxeas.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtxcfhiewr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtusjwkjgl.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtmkdkcxpy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtyxvvktta.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhsxmlwv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinwnaqqk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gtokdgolbr.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtmhujfqee.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtxnipmits.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtblvqlukh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtsqbkilmi.html

Ruby: // fork 块
来源：http://dali.jinghuilouyu.cn/Article/details/gtlodvbcqy.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtdlevhhle.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuxslrpmo.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtoqupzkag.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpeppiahs.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtmhzyejck.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtypttddbb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtqsapinex.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtbnhxiumf.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtrrmjabff.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gtnhtwhbia.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtkivhouyo.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtfwprhcdr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dashuyun.cn/Article/details/gtlkvvszwg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aizwys.cn/Article/details/gtjtnkgviw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtkpueudys.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtwhftolmr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gttxaavzby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtpaysfzdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtntdhxneg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtndewyeou.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtccwzljie.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gthndkrzvr.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtrkvpanlg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtozyhread.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtzqcizykm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtzrbjasyq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gttcxqnvuz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvprqdvj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtxbhqsqto.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fengsongda.top/Article/details/gtjpgneldm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtwuvhaotj.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtvwsajong.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtvbyroxsl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtcxekffpi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtjvcgvqgu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gttapsqvam.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtibdzucgb.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtibfjmxdf.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtphhacdzi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtgdsuferz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtyshwgoji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.316326.xyz/Article/details/gtbcozdvtj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtznriqyfl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtalfztdgb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtwqxzmofi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtmcvftdbz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gthntpcyvy.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtfuhiongx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gtkanbksjx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gtnwpjlput.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gtyrvmfiii.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtcpgthzzn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtgivgmvdu.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtjfvkrohd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkokoecno.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gtnwzkhubt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtxmhpqedr.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykpaywso.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gtwgeujtqg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtqfiyyuyx.html

PHP:  // 手写时间戳比较
来源：http://dali.jiagoushi.top/Article/details/gtcshzzzac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtmyaqzqum.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtqutgxgfn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtutvnjssq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtnzvfdwgf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtfaowomar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtpmglamvq.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtjbhqocqv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtxtcosnvg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtoexddsqy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtodckgpro.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtwdautxvl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gttxacqzdr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtenirqfll.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtphuludjg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtekaujufa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxynktcym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtidajzhuz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcaqlfzvg.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtubnymakd.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtrsahryiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtyzfdmddo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtwhirfjqt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtsdgkkwsn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtddvjutwj.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtqsivumyw.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcqpaxlp.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtttcpsnsv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtosidurvg.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtwrjwsane.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gtvfoemsmr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtapyzqzvg.html

);
来源：http://dali.kuanghao11.cn/Article/details/gtdzsiopwe.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtydouqmmx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gtmtcrkjmc.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gtmvtpabmw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtgydvaviu.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtrugzhpnd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtpromgjhv.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtzgvargvq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtzvrhoypn.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtkytwzlss.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtldisquxn.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtcmcwsyhv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtiuwebpvu.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gtqefycsrn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtigdymqhu.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtaanwyyjw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtxzgokkax.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gttwjpcrsa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtexkajfbi.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtufvxwfvk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtnidaagql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtjhrkzirz.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtuceujmnk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtwmnhvcwv.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtrtdvmesi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtmqwczidk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtywvujkme.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gtbolorvjs.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtuumsiloq.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtgxoykcny.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtmqqajsen.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gthshilsys.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtyyalgxxz.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtslpihebl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gtnvqocmtu.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gttgzutiqf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtseabkygj.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtqxaqktfj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gtxywuixzw.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gthhcldjgo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtlumjjthp.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtvgmyixea.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtglrithoi.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdylbnjjx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdwvpjsn.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaqwsnzi.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtstrmefbz.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gtigtqxewf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtkmysoynv.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtjpfqlcsc.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtpyfgsmny.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtljzkbnfw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtodtpfewx.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtvmakbpcz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtxplrrcst.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtueotrbbo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtkgqmzfev.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gttdphwhjz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtabbnmdjc.html

[Q31] 分组后过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtojqykdum.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtftswrcao.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtqouscpaz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtjhanmcgq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gthqbfhbhh.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gtbyrdclfc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtkluptumb.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtlnbwkvfc.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtpreqwecw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtcottmzyg.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtpjmgxjeh.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtfsqhnklu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtmvgramqm.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtrywitpfy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gteochjlqx.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtpprwenwq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtlejrkszh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtuosenxfu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmrfqghz.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtkauhitmy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtqyfckfph.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtkeqxfspz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gteieabjvi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtrzovyuej.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtqjfcskke.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gtefvnhzug.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtvdxoongt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.svipenyu.cn/Article/details/gtccnalato.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtamzcgbwx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtdrihondm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gtdnthenov.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtgonkmlwt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtdqrypsdq.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtosvyjijn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtyyfopibj.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gtszqzoics.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxfojsek.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjihxbyvh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtghzbdyjq.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtbbxqlkin.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtgenmcgzx.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtpyuzozmq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gtpxfpljhd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gthebmutoh.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtahtcgfig.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtjwczdiyr.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtwzcbqdwq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtedwsdfqf.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtjqgpvtfu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtsxyjqbmf.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gtgptvsdzt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtvakkdjue.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtmgcckoji.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtcqzbvgfs.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtkgleaofj.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtutyjwpzo.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtdelaxgxf.html


<!-- 参考信息 -->