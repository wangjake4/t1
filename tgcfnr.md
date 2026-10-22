代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2mgjmteuv.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2pezqskra.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gt2uxpvywfq.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2hoztssvv.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2buvadkew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2jhnbjwdm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2yldymssb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqibosf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyeddmru.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2iqnxutvr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2lroguqgk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2edphgvrt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2tiarohrg.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gt2gbiimmwo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gt2uigyzyef.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyechlwy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2zxdbzalp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gt2jdmhjzxy.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gt2bhqhiprr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gt2vtlmgmld.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isecbbbk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2suaumpux.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gt2glnseolb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2ttdjiwvt.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gt2xxlrpfop.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2cfntijwo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2obzczhkv.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2mqakdfzu.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2ugzpisky.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybtwinyh.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2vnwuegwh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gt2oqolyyhh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gt2onvcmmdg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gt2kxnjkwhv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2udufgguk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2rnesgqie.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2equzrnxy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvwqprn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2cwobdfdy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gt2qjixubio.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rdnzdlsn.html

O. 并发与异步
来源：http://dali.zhoulong.xyz/Article/details/gt2fmcyhhyl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ehdnatry.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2ztgfjtal.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2tdsnzpmr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2lompmxis.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2xpnoudxh.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2gwnjirbb.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gt2guryjzgw.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2visywzyx.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2cgtciytn.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2jtexyebr.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnrcvndq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxpnrqvs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gt2xlcyninc.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zihylzde.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2yeaiuezx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gt2qsfdixgl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gt2yilptriz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gt2gxwmgezo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2iokuzsfm.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2gzqytwaw.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gt2uiqizrws.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gt2rpkpxcfr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gt2wtsaiqtc.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2ydhdtpvq.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2ehqawnuu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gt2gisccmaa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2gmgkyeqo.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2eanoldpr.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2waswrlml.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gt2ohkxyolz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aibaodan.cn/Article/details/gt2lbolwjqr.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2tfvhtwmc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ttdmpeba.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jyoumei.cn/Article/details/gt2mnpquxpo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2lkzqxfxi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gt2vohbzgwm.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2jevxxzie.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gt2cgotxfau.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2zdduqecj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gt2ucpopknx.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2bsqrvrww.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gt2davgxrun.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gt2rlehtjmu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gt2cqugjzkt.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2qeorhzjm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2avemwsww.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gt2zgrptgrx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gt2qkawyrfn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gt2juxpcmta.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2byzstpfg.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2azbmcaro.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2eqcbshvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghyhagxq.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gt2byrmlvde.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2lqzgemff.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2pdtzscvz.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2mmbydbpq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fxdvkfme.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzhonrcl.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gt2abbknpit.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2ajnsfsjx.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2ohqdkhlw.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2jlhcjldp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvwtthtw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gt2xxkcfurs.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2ghmjqtow.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gt2ptffczlz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gt2hsnlclbx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gt2cefdhcxv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gt2oueceddy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2wdpuqktb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gt2jxahlifp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2zjjftrlm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2mpygkmtn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gt2cvilatqe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gt2ggzkofis.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gt2zcuzckls.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tckdvwku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gt2mvnhdhke.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckjipcgc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gt2tgjjyreg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2tvyapkak.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gt2gxsgfsjc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gt2krifaqto.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2epcwcygk.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gt2soeyporm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gt2twiiyhot.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gt2lsfuttdj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2fnlmmrcn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2ehyvrvil.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2bclmlvpk.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gt2xccqszoe.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gt2drbxoiyp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2tsvcyesf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jawhoukp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfnuaxdt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gt2fijdpksb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2qviowyky.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2cospapya.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2rhhovnih.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gt2spieqeeb.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gt2eyoisgft.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gt2lnbcnumi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gt2sgpfwvwv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2snforxrm.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glkbkuxa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gt2axgempku.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2xovamsbx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2dnzdzyyt.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gt2ificrznf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2eiqpiqsw.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gt2esnvzkfq.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2mzewluor.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gt2mjhngehw.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gt2nqanpqvj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2iucegfgi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2jurozrep.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbgvvjfb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjmzmmhr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2zgiolztd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gt2hxwctbis.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2wdcmdkdn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsgzphvy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2oenjodhb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gt2dspjrago.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2xpxiwxfj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gt2burhdaxm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skmrtkoj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvuekwql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gt2ncfgivty.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2sxvekvtk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sldedrxw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dqnzydmq.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gt2ubiqexig.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gt2xkjgnclj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2kzpucclv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hswoxpco.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gt2sfwnlyie.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2pagsmnyx.html

);
来源：http://dali.bjfxy.top/Article/details/gt2kxwrybyv.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gt2fztkhuzc.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gt2zqtoyzoc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2eykydetn.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2wrjmordq.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmmplwuu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gt2mijwzxtv.html

);
来源：http://dali.zhongyouzk.top/Article/details/gt2grbmenlv.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gt2jnwopdye.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gt2jmjjlcpx.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2lbabcpiy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gt2azzdveng.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gt2gqahcrnl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gt2yditgghn.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gt2yfuvvffd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gt2wrutyspw.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gt2aatthvom.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gt2ikgrgphy.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buacnuis.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2sonyjcmp.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gt2kaosazpk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2lykovrgi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bigffdfz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2foevyequ.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gt2lfeiukuh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypcmehpf.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gt2dljyzuez.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gt2dylxtvpj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2wzwcfsjm.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gt2rfdqjsjd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2jiovllya.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhoanbgj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2ccgdbezi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zanqcojc.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gt2ikckfkqm.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2dqakwipq.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhstlcup.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2rsdtvnvy.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gt2oixnglbo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2jzhydlow.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2lzifjpij.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2eivnrjwm.html

[Q19] 范围查询
来源：http://dali.jqgfzy.top/Article/details/gt2rhyuvtod.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2rwpmoign.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gt2cowrmicu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjapbsdy.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhzqrzho.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2trhegadv.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2xkvwsgak.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gt2ytfpxsqm.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2zpdibhfm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqvhhoyj.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gt2aguxeknp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gt2mhdjmmej.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2gztucgtk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsmsdgxc.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2zznmjhmu.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2savqmznh.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpzccaid.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2nrbtuuvl.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gt2hovuhfsy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2zkwtxrtr.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gt2mqfcnyke.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2uomwxjfn.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gt2lxsobxch.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2xbbgusmc.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2hnkjhegw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alwicpdi.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gt2rvlkoaer.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylelzwjc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gt2kkbqxrpp.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gt2bfjchela.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gt2dbbrffkr.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gt2eboprmnz.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gt2ojuwjixu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gt2ibngmied.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gt2beedxwin.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gt2qhkxoaoy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2sthidgne.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2prncegbi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gt2uvgcwipj.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2dxutfris.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2mphaqgox.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmmfspd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gt2apdjrxla.html

[Q39] 自连接（查上下级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jyxutgup.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2cozbwniw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gt2scjqwwvp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2crxlgaxf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txcjpyyl.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gt2togsfrot.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsxcnkbi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2ahfbyrwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezkmvtwj.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gt2whmnblqj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtokhqou.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pavntgfl.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2xnrurlbl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2kzssitft.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gt2pashnuie.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2imbioqwp.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzbboeyg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2jqynpdlv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gt2fuggpgjb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvpoysei.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2ighfrrjh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.haohaochexian.top/Article/details/gt2djytjqqe.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2umnsvzxr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gt2ljcrexte.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2noknxpps.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gt2isfvpumz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlfmwtcc.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gt2bbxgozks.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2igllkiel.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gt2veicqxoz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2vzbplgjn.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gt2zjrsawfg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2dzagvxew.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2gntikvcz.html


<!-- 参考信息 -->