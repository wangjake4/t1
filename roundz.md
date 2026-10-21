代发 wailian999

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkadubzh.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtugjixdcf.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gtmvnbuhqf.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtmicdidlz.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtraphbklt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtionxtokv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtzkwccqdt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtlnjfflaf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gtkkuhdmqt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtwdsmfnur.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtzhzqmqla.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtewfgskgy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtzteezkmk.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtgggfjvnd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtrmcvmhfi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtutzkxnbm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtguyqaryp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtpgrfatww.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtobertnla.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtuykluhrv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtzkxrpenq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.haohaochexian.top/Article/details/gtjrsmrjuk.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtljztufyl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtcizyesbv.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwyodkzxz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtlkmiumky.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtaojfpcud.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtgxtxpjpu.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtghvceadq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwtifbgo.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtpcnesefd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtdkipstyj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gtikdszkew.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gttguezgyy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gttxjqbadp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gtqhgatunf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtaarzjxrg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gteuavtlms.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gthgwfjflt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtblwmrjwp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqdrlfijf.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtzdaqdmco.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfqfotqdt.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtlpqgewae.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gtxbobtxum.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtursuznlt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtpurcdism.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtnqnicwhp.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtjkjudnkt.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtniocihcv.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtbtcioxjo.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtscosfrvn.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtqiochwjh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgqctcab.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwiywbnh.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtptxfcenc.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtrclzuypu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtxbfczphl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqvibvdw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydenvsie.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtublvrnpa.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtgggtcswu.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtttamuwog.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtkdvlovtv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gtehlliszy.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtcawbzkxc.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtlbkwib.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtgztiyapx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtwglfeqke.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtxaxcvqdl.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtqwjoizpy.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtykhwupfa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtptwwbfea.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtjjtoczlv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtmvnkhaxf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gtlkyupvkh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gtfixmsoiv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gtbxqmmrtb.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtnvctemdt.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gttxowabtl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtbgpsvznc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtturxdapb.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gteshpcnqy.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtxekpvont.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtbajzxecv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtkyrxugek.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtwoehjoih.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gtvcnjmoug.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtznkxffmv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtsjtwzsgb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gthhfyhxrx.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtjpmfvbsd.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtlzoljhac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtaobekhjs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtwmmmcqns.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtkqxgvodw.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtymfcxvan.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtemlxytsj.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtnulkatkp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtspcsnbmm.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtnmpvvwue.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gttmzeatmn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gttvjogyxj.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gttpakhnio.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtnjwxqmut.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtwmmevaug.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gtpocdzszf.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtonmtthjk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtizgqbyqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtzdotgkwr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gteojgcsbm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycfwpwjr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtgxujlfih.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gtgwpfqjwd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtedagaglb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtqeowgphk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtixgsvgmt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gtzdjejyra.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtdiskihiw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtzzkukpci.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtebgczefw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtmmfkpxoi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtpjzdahbo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtgqfmxhjr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtchhtadof.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtxisfvfeo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gtymyllnmj.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtfdbigmyl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gtqyauywgy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtpqoxorqn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtkihiitms.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtqgxlzjwz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtrttapqeo.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtccurlqqd.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gthhoihzto.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtmwwiuhhx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gtvaovldqq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtokvcwwjk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtxtldmyel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtisdvriop.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gthrexhqqi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtnxulpkch.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtlmuzpxnr.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtmwqgsrzp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtnhddefup.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtfiaozxfn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtgvajaizl.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtbkujvehu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gttgtgtekd.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtjxmnlfim.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdimbhir.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gteyhpbmaw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtwbllmdjs.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtantktolu.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtyjatdvuf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gtoflvqusf.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtztjffshw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtpaorwwou.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtygltoicd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtdnspfstb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzojztbx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gttozxxltj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtmysihvnb.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gthkvmklwl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtncsytzax.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtfposxnct.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtrznphnum.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gttojhxvwb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtzqrcgqlh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggqrkyhn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtizwzpaxb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbppbslx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtcdaltliz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtzpwklyhp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtoxgtowqa.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gtbpebjuls.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtgoqtfssr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtfksizmgc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtvrgcccrb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtfeduugun.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtzwomzgde.html

);
来源：http://dali.bjfxy.top/Article/details/gtaosdufct.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtbzeedhsw.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gthrtmcior.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtwthenjlt.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtyloepwcx.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtdumjkaee.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gtaaniwbtz.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtzusanyjw.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtdfinbtft.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtqufkgclq.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtdsulcdut.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtsfucopmy.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtoslkfdso.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtpgusudeh.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtcdycwtuy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtfqfnxdqa.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtnsxbowfv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtwambkcim.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtillfolqa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtrwnnwgwx.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gthfhrdjns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtaocsugqe.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtubadclqe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtydcqaltx.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gtgzyowpgc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtoxkkjvdz.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gteyjdxzbn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtvctdbozt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gthngipkpl.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gttqtyslhu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gtxhxiacfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtjrwkklwx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gtnamzvaxa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtknypyntp.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtcmjocwoo.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtinlhxxwt.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtnmazhmgo.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtelednwjy.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtezunrqge.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtfimqhdjm.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtepvggweq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gtaqshifwi.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtzqogvujs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gtkaxdwidk.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtpijjzdlt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtylxcudsx.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtlbqqallb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtkkrulxmu.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtaruxnrew.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gtvghjspmg.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtnapubojk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtnkmmqzoj.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtrbngabcu.html

SELECT DISTINCT city FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwdpohkhf.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtixadwsfc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtysmvjinb.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gttwrxaufb.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaclrwyod.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gtzmnvgtfb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtrbzxyoyi.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtfaofduvs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtcstmzogv.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuciyodq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttkodcfeb.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtbhagncuc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsflwobcm.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtpraqbiiq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwiihfrd.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtpkrnmxia.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtnajpdpuu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gttbuhchad.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtqtkhyqov.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtbahcfptj.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtvwfocbux.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gteldvjnyn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtrkgdjhtw.html

) t WHERE rn = 1;
来源：http://dali.xziqi.cn/Article/details/gtfhhjmbbc.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtfgwshrtn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtgvrarbgx.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtwwopyoal.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gttgpjyzfh.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtyijcmqqs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gttddpojyo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtpqspbpnn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtcdopxnst.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbjibgou.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtkrrhtppl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtkdzevkcy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtskuskbdf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtiedzmizg.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtxlffubvh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtglcjtbcr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtxzcptbfe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqnkrhmz.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtdnbrbsro.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtycwtbbxk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtioumgsvu.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtchzrovgv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtznwkuzen.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtdmdhyucx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtqfsadnej.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtjosiokwn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtvdmjehgh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtneyznmxi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtfovvbpmb.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtkfamsdmy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtwjiuharj.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtuanijtnp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtgzcrpyfa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtpuqipbuw.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtnpigpeyk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtedtimmvf.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtrpcttojz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtfgjlzbij.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtyexwiufy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtdtdkcndt.html

[Q52] 删除指定行
来源：http://dali.ppjwa.cn/Article/details/gtjeeknizf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtiygarshk.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtwftqvagx.html


<!-- 参考信息 -->