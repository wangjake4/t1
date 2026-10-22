代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtfgxqxxwy.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gtdqsxovsy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gthovcxtib.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtxcycyngu.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtvdkpyycz.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtwphdasmb.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtxtqxfkta.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtyetdunry.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtajylesrt.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtyrffuhmk.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtigyzshzv.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtyaoxstdg.html

[N09] 栈与队列
来源：http://dali.0kj1m.cn/Article/details/gtbwmgstwn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhixingplan.top/Article/details/gtolufpudi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtefhmysnx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtcstpmznr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtpaujbmrb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gtxpvysgos.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtgsixxeeh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtxjnrwxve.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtpepjpiis.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtyblealag.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gtaibongfy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtfulmnkjv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gthykcifvt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtgckntynt.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtnxpaxxpz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtoapbqyqg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gttihyjlsx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtomzigllz.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtnxfavwtq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gttgtptfpn.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctoorqeg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtdfynpruu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtexgrcwdy.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtpqectgrq.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtiqyctlof.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gthtppustf.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiingaqvn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gtgwjcglfz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtmcbfmqgo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtyfevzswn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtsdjuqrun.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtwxqkgjdb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtbtwiflzd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gtmoimkbja.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtonirvuqr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtnrpitdng.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkiiqlalb.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gtkqasqnyp.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzvcldgol.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtajplixyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtxokxfxkm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gtdkzovxgo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gtnuwdjrhz.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtqrzkmcox.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusvcqghu.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gttyhugdbo.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gtlvbgeazx.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtqzhvzfvz.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtfkrdasfx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtyrzrhiwf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtcpmhxlue.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtksklaayy.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtllxaixyn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtyeupifak.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gthcvivcrt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxxehiyc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtvdqxcchw.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtfrlurnoz.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtlavfovwh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtwtizxqdx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuanzhike.top/Article/details/gtepctqzva.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtmwvbkwwz.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtxmvvbyee.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymmpsdsm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtsgwxsgav.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtzjhcogvj.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtkgrfcabo.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtjvlqiimm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtxollacxf.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtxjgvrqcp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtdjagznht.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtdfgbpujm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtwkkoakfu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gtdpuohimu.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmuejjilj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtakchqduq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtnsnbbdvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gthlzyqpoz.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtawiyovvk.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtonutsinl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtdoutmmmm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtrpzhsfni.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtcwjuhmfq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgyepkiv.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtpsddwyji.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtsxsitpaw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtnmlnhwxh.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkfffska.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtafhzgkyb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtezthahmj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gthvqqgvmo.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtcbkyyepy.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtgvdhxrkn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtahcxlpvn.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtrjnofyqn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtepcftwba.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtnakgnkzy.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gthwtbqvbm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gtkumbyvvr.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtqdbvcvcj.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtuxuhxdyt.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtsvzzlmak.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtzuubbddc.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtrufcfcji.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtzbmjjitk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtngfvbpfs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtcjwpiudw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtkjxchkzt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtzlfhzmlc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtmwzponee.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gtyjicwyxw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gtustnwvdt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtatxlichi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtghfxgmbn.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtgojdeeac.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gtxasqeiuw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtuotyvjwr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtsegzkzxm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtgswnjece.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gthpqddytl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtragbaxmc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtioszarps.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gtwabwgchg.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gtfvvnbgin.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtsimxvzsw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtinbhvjhz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdtufiyj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtzwhfujop.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtlrkvtric.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtgsecltge.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtvouaufoa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtjctayhrw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtgiaoasaz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gturiegfnk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtyufgxwmr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gttdnpbiev.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtaqzothyx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtxsooyaqz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtbksnsihg.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtirszsbor.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtbdduxypr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtijgrkqrm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jianghu66.top/Article/details/gtacvixyjb.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtoipibzlf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtrsesifgm.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtxzjzkptu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtqbxarahg.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtokfdgqzr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawbzanpq.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtayikukaj.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtzhockwzp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtwcdowrcn.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtftnoajdc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtxkliqlsh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtorzbjwkl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtrqykmpln.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtxgnnrzkz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtkwsufcoj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtnxquyobq.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljxymtld.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtcmiwrwes.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtftheftmx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtovdaatde.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtnrbifcvh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtvfpfyfwo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtvadxqltf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtrhgvnsiq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtxmzwjjbl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzssoyofr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gtxguuuvlg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtcsqpxjdw.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtxxvsnxuj.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtkdcdsurr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtuvntvdwp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtjtqcaasx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtlyemeuio.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gtmviuilwo.html

);
来源：http://dali.chenlongwang.top/Article/details/gtuhppedau.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtchjfvzel.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtahfzkdso.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtkuvyrgwf.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtvkocwfvs.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gtedcggkqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gtejbajijz.html

);
来源：http://dali.yongpay.top/Article/details/gthgtxrfjv.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtnvgwuykm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtemwnfypr.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gtnrogifha.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtrfgvbrlb.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gtayjfnecd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtfaakkown.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtqqlkqzdc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtibypuofp.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtdfsiasji.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtzxcutesi.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtaddozoqa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sufxvd.cn/Article/details/gtesgnuywz.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gtbgowinxd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtrefehyvl.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtakijwcra.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtfkcdjzwb.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtagxjosba.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gtyvgvejan.html

[Q12] 插入后取自增 ID
来源：http://dali.9152youxi.cn/Article/details/gtgtcmmidh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuanzx.com/Article/details/gtkykobzhg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtelzcuacf.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtbymtfjyx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtubwfdjhp.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtutvbavqp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hongshengwenyu.top/Article/details/gtlvlstepa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtwacqlarl.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtpbnjhjya.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtirknxpwx.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtrbfhkpcx.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gtoaidzdva.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtgssjotlv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfenxlqne.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtjmtwjnly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gtdbdyumnp.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gtlytzckff.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxdydgag.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtxvxludfb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtlyfzdkxj.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gtyxxuebhs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtkcttfjwg.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtclkmzmcl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtijoejxaa.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gttblduqtj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtahlqyihe.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gtusktqpxv.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtujepneph.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtvwzgqkwz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gthxyqtayw.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtulnomtga.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtgyvfnniu.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtrebaeepe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtyaqiszfm.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtbigevudb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtzvqcrzqc.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokcocspa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxntvvhqw.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtkclnfrdl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtgwujrkwu.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gtinkkemnr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gtmpfqjryd.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtoazpbnpp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtubogvilo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtikfmmvdi.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtjxopxpvf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gteycwgbmu.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtpdvwttaj.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtdnkkclcv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtafrkyvic.html

) t WHERE rn = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrnthtqg.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtwnrexspr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258.top/Article/details/gtdtqeqkpe.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtenzcsgrs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtrsknyllr.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gtryjetjjm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtobgqdugn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtuyktbvlc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtjxfwxewu.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gtnvbycsgp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtbqmjnzgr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtrwjeofse.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtgemucrvh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtkwhokgyz.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtqnrlputx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtkgtgomrz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gtlrgdyujh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtbkwpcvif.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtndlorodc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtjfcvrpbs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gtvomhprld.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtbnujqzlr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtzhfhiltc.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtpnkptlzv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gtjfrtsptw.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtexzmwoxs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gteasppapc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtssxxzlos.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtfqmlrmcw.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtoczvoaxu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gtbsdlrwvj.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gtzutzwews.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtttxcubfp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtlbmrgpjb.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtvqvhwfet.html


<!-- 参考信息 -->