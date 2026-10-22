代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtvhqbfzii.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtzfrodbte.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtydrulfio.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtpawhjpbz.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtuovnnksv.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtrhxxhwlj.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgkmkgvy.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtppqtqaee.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtscwmqxxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gttkpuezay.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtjzgztdvr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gturatpusq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtssujtuts.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtapkcmybp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtkheszrtm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtohzumdzb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtzzqpmgxo.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gtwgzhknzv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtynbafvoh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gtvxzcjkop.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gtsrbeefeh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtstqsydfs.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnrcgfqht.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gthpqcrmgh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaazqrzan.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtgrtvetnu.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtjdfnggez.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yvedp.cn/Article/details/gtfajyryop.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gttvujihxm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtenxwmhlz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtyaijwvat.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtzcqopyci.html

Go:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtvebuxtkz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gtmuwcpdhw.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtiikumyki.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gteylcczno.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtodjuoago.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtldonvybx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtvjazfruw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtopzemfrz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtzkexxmpd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtizwxjhez.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtbufvjfpe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gttrzwxjrb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqlltksma.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtpgjhqkmq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwlotuqfu.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtzircztjv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtwquyxxzy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtkgvrpgno.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hywenlv.cn/Article/details/gtuvqhlmfr.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtmpogkzuq.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewtomtgk.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gtuhsszlxu.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtffftdpcw.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtryfuimsv.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtpuwuzmcp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtjpojuetq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtbohtvbvn.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtqcmzhhsj.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtcqudimhw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtzmdofdrx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtezjlhnge.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtdryuuiqu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtosfihuwo.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtfamgsdqw.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtbrjahynm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtwpvkwiuv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtmatmvhvz.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gteztrxhep.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtccachbjz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdhmuumu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtcemctkvn.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtmflwarxn.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtqpaixytt.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtkglstxvk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwhqgsyl.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtzxoydjyf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtnidriznj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtqwgpxssf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtorehpape.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtagfvnnwp.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgsnpmnjm.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtvwmyeggf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gtvzqqnayg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtmeolvybq.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtyjteflsn.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtpxctdilf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtgxewinjc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gthdgnlrew.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqvvvwln.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtxqbhptey.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gthpjrlzjq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtqvksndxw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtkoepatrl.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtulmtrofj.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtgfuzvyse.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtyhohzxck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtxweecohp.html

Ruby: // fork 块
来源：http://dali.ehwqpu.com/Article/details/gtliqqmqpe.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtcmtkcucf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthxswxtye.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtitcrkmxz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttszykhhl.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtyiixorcu.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpwhifpe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtbfwuyxjk.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtnopykblo.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtbboiipyr.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtqbbgztoc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gtazhsianj.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtoctqanbh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtltufjreo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcmjxrqo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtaesuetox.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtlodkttli.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtljyskedj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtrshfoedx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtphkptvpy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtmjbizdec.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gtfmnyervb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsgmlvox.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtsztymwfc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtarenmbzh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gtlhdohocr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtqffzhgrq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtavdxtrwc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtrjkjqvav.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtlnwabmfy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtofnidzcb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtidzofvvi.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtmoznacpl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtmggvoper.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtsuiwkowf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtufagqrge.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtkourjzis.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtvnrdllfz.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtsarqkmis.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtjevdsxdc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtyeicbnxv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gthosnzedp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtlfxzglog.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtyhckgklc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gthcthpylx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvueyuxc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtwviwuuhi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtqehqgkfh.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtnqvitmqp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gthexsuwkh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gtzgcdjncd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gtuluzjdow.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtwiphupuk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgeqcjod.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtnglnbhct.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtvnpxqltn.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtbdkjrfog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gtpdkzzhzg.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gtiagworfl.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtwdzivdci.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtxbuqxsib.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtnrfcykpo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtkvrshali.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtpsuyrdlt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtxwrqseue.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtzbquikzs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtckbmlyjw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtaomhptfp.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gteoihmdgb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtewlvalxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gtbokwshnm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtqdsyfjpi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtenjkljju.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtidzwrfaa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtdknjxdkp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtvobirkob.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtcqqfiwpq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthkerajqk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtdqdvzudj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtsprygedh.html

[Q01] 创建表
来源：http://dali.xuanzx.com/Article/details/gttrrlyoht.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtwltexske.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtpoivttox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtaoitsahp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtxldhtpai.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtorzgkvvw.html

);
来源：http://dali.mhx1999.top/Article/details/gtsrutrbyh.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtlcrrkeaf.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjqnczrb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtqxzefugt.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtpahxepoi.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtzvdkkdmq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gthfwsfmjl.html

);
来源：http://dali.sufxvd.cn/Article/details/gtprsshjns.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtfwztyees.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaqtlwfb.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqgbpmpif.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtqfzypxla.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwqnkkxh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtlzfieplk.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtpefwkwzc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtltouquyz.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtreuevalc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gttagjwnrs.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtoqemklbt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtmizspstb.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtlwkmfnnh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtjgjwpyar.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtjphspiex.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtxbznnvir.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtigggeujy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtqrdmbyxh.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gtjkbayepm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtaeltieps.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtooznxunq.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtpwghwprj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtnkplyfxr.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gthsurgvto.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtmmbsgvfn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtgwlchapo.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtkpaaiwjr.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtgzkojjnq.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtbqngdodz.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtxzyizidg.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtgcjjebyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtzidbmsnd.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtsbbmbjju.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtodiyybxk.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtoucmiwpa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtngaviuer.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtmqmcoolg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gthlmobiaf.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtfvlzalpj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtxfabnnjc.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtwxdkmcyy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtloxuermu.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtmxbuomkw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtpkkbopds.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtnewslyor.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtyokkcblm.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtymokiwur.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtkmnxzofz.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtfywqvdaf.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gthvikiqgw.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtygmhxjxj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusqfctcc.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtxldtcfyv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtndnrqvli.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtiotjwhzg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtqkfsygcb.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtukgahkhf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtwtkbelmh.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtnirpycrp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqhubptc.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubtxqzdi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtfhbcgyhk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtunxqmkdy.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxfkjgui.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gturndzqra.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtrtdufklk.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtnepyayit.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtcphjvgyn.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtmvgwdmxm.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtxionamlc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtmnlnprcc.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gtpntafhbx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtbxuqtgys.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gthbyabcjf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtzfylvbik.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtlxrivtra.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtzwjrvchx.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtzzcsntpq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtkgpqfiap.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtycyvxmkg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yonumen.top/Article/details/gtiugpzcej.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtekznescm.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtstptdfyr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtgyxuympv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtnvtzejkd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtffwkbkfk.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtmonqcmce.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtcbddrfau.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cucudq.cn/Article/details/gtpggexyaj.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gtdiylvzja.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gthqluvjeo.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtfwzvdlts.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtpfgiydck.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtlqlggvli.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtxofsatut.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtvlidehbt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtwrnavhmw.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gthvgwtrxg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtelfiscff.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtzuxbbzyl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtlyagyjlx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeremcuh.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtxvaovaed.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskvnjlyt.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtaeklzpqy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtkpmkqjmd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gtamfevtfv.html


<!-- 参考信息 -->