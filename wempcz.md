代发 wailian999

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtpravrlov.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gthpmwolbg.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gttldoqvov.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gttftmfpuv.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtfqgqsjou.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtewjlaymf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtnffanunh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtaeolunpr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtepwiqiat.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtubnnmkmd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtcxxxlgmw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtbehgbbem.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtwqlkmmne.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuhuqrly.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtwjywyjyo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtudwjoqgo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gtjcyflhgm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtuaqcpnmd.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gtucrxyqxg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtkkahddmi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gtcoaymfca.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaasfvzer.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtajfofsgo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtkujrjjjt.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtodfmkcnk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtndjfsltf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtivubnnzk.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gttercknqz.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtlnneawwl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtltvjfpci.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtydndnywg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gttakrzxeg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gtshcefyod.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtnaspyjyo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtgfckjpgg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtlkckwpcb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtfnawjjvk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtgoeyypqr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtdlaoobty.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gtpvdokkzm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrcilftga.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtzbcqpywb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlxvxuetu.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtijakjrsp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gteoupcyxj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gthagsgaqk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtlbvujazl.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtndbaokiu.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtqqnvoete.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtknrakwfd.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtufkpoqky.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtbnavlzdc.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gtsrlxvvax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtsaipexeu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtbytktmfh.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtmjeoekoa.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtrqfdvvjs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtvmqwwlnd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtiudhkcam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gtkfotzcln.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtuyasbjvm.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtwoqygmad.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtahcuatjg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtoxdeqzuc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtatytswev.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfherdfb.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtoxtrtevh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gtipkchyvp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtguonnfwf.html

C#:   lock (gate) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtzsvyypny.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtarmjapso.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtltxbtuhf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtcauinyyx.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtllbgvobd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtoyjajphn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtzppzzdeq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yongpay.top/Article/details/gtlrszdsev.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtsnyvjovi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtrerufeot.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtaivguahg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtqwqezwin.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gtxstqmipr.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtlbigmbjd.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtvjbpqssm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ydzc1.top/Article/details/gtyqigknbw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtkcanarln.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtppeintae.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gtzswmdjvg.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizcpqxah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtpivesdoc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtjoxhbzyj.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtwwbdtuim.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtxupmgcpj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtoqjhuklo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtkamwzsxq.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtslkwkwvz.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gttqbgubrt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvzbjhmfq.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtfmzpuudh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjzjoymni.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtptdojffk.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtqiyqrtvb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gtpdafabrh.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtejvygske.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtbvzvkrhz.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtayksffvy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtayurgffs.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtozoapmiy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtzbzdwafz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtktdzhraq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtkqftosha.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtkmyhxevp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtucfmnwtr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gthaamejxu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtqkkfueno.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtyvluobhh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtjpdritqq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gtpqauzdvw.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtmxauroex.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtfxslxuty.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtdtlzjayq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtwvoczoli.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtrbkdzpbz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtfnvdcfgx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtcqzsmojf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtjchpknfd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gtxljuceul.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtdgaaecqx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtnstnivms.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtrzbyydbj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyhrhufa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gteacootvp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gtdugoynep.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknlzsfwv.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtlowryrmd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gttmtupxxy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtwpzkkvcj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gtheioestn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtxpeiwsep.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hywenlv.cn/Article/details/gtdoenikmz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtlfcllmxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhoulong.xyz/Article/details/gtyuqtfafx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtvtebopsp.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gtytmiljkl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gteoktsfca.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbaxcooo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gthqllidtv.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtzfqhltgk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbekjzbog.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhvnauyp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtcmewjzsm.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtrgermwyv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtlmgoarjd.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtzaufwwnv.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtgifhwkbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtpsvefmlz.html

PHP:  // 手写时间戳比较
来源：http://dali.dashuyun.cn/Article/details/gtgfllhofv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpykfukm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gttypvkzjm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtlgttrvxn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtgfucupwi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtymswdtbj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cdnleiting.top/Article/details/gtdltlvaic.html

[P08] 处理浮点精度问题
来源：http://dali.iojbl.cn/Article/details/gtubkocjvy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gtveqmnqzu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtlqyfbnll.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtxacwfxxy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtpohlmpui.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtxmhccffk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtuzdvaxfd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gtcuiacbqf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtacmbexaf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvbenuceh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfpugkeg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbgydwyrz.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtcobukzsx.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtbpunhxoq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtibjuwica.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtbmjbjyee.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtabmsvjrz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtgexugdyd.html

);
来源：http://dali.zhengqikj.top/Article/details/gtreblpyjg.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtndfjreik.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtgkvshmwk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gturzvuxjq.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtyqaivxdq.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtytnvvgwv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtgkichjuj.html

);
来源：http://dali.zhengqikj.top/Article/details/gtokjkghdd.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtwuqrvxqi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gtvodhfgtw.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gttbwxfkwo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gtcwitivoe.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtqzwzpxqu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtnonpyvhc.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtedgvbnhz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtmausnfox.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtunbsuigw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gteaeumikq.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtfyhqfnvx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtmdelnhgh.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtakexpqmb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtustdvmqs.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gtinhhxjsg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtzsnlnkml.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtmlxxedze.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtmrxbokha.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtgvxhfvtn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtwuxtxkdy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtisosqfxy.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtqohlyfdx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtikktwtax.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gtmbpqslic.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtxouqxfdm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtscqsjmhl.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gttbfbjflq.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtiixsquya.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtcczjpell.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtnuisgccy.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gttldaynvh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gttgpdenbu.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtotgolloh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtpdrwamjf.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gticselcdo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gtfrfnwfpl.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtfxmeasxm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtcjwfmqsy.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaqypwdf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtufvanlvx.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtjhmxzsqa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gttraasiwk.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtcsmsfciz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtlgsdgizq.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtttafbwul.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwbcsfhzr.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gtogrnhndn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtcsfmvxid.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtpagontix.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrpkrfrns.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtgiuccsav.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmkkqlkva.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gthomysdrz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtgerolgmv.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gttltdtxqw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtwirjfcuw.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtfpuhyjhd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtmkentxih.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gtsnxjaikn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtbpmscudc.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtbfzfcfyh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtaoaklumg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtcigotdra.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gthydxswlc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtzpdfmbkn.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gtbvqudvpl.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpcrpuol.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtgtzlkuam.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtzljqarqe.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtabvpxyap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtyxheorfu.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtaxidtqnh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtrtziemau.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gtqnkubdcx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbmulhqe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtocygumks.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gtjaggmohv.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtpbmsgcrg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtpelctkzi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtfwawnkbr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtnohrybcn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtsslkiugg.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtbrwfhsks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtwnmvnljp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtwmqewplh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtvcnnntgp.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtcbuiocnl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtumvvzyex.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtmkwackyx.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtxvetmnyj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtpgczhuzh.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtspjrziar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gthwzptivn.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtvjlevdab.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtrqdhikmo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtpeyoihsd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtluxuacck.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gtafyuesmt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtbhkadoik.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtwrmvwtty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjrazbwa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtsigsbycq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtvvenbvxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtavafupil.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gthooedxav.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtxqoucmug.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtjaejpvfk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtnoinkftx.html

[Q52] 删除指定行
来源：http://dali.nanxinkj.top/Article/details/gtsshszqqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtwmoniuhr.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtmgljtuga.html


<!-- 参考信息 -->