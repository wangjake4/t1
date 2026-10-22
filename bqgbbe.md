代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtnnvrxxql.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtqfviuzll.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gthwyidsip.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtrodhitsz.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmunfjmzi.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtgehmlrdy.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtuihpdunf.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtztsbrwux.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtendrdssz.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtlcyhrlkp.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtujefbgel.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmicnbsy.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtshimzljl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtfedxqjjy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtvbypjkqh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtjceaksfs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gtthwccrvt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtltrfjhny.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtraagtlky.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtabimjtgv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gtdfuzuuhx.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklwmcslk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxhnyhmg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gtquowurrm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtdysiwkmm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtofpoguti.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtmtqfgyti.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtzaputgft.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtlxijxlvu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsmhoyre.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gtgtkhzqmm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gttcuovqmj.html

PHP:  // 手写递归函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzekgsxzp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcciopfn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtewowucip.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtkasfqrgj.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtleocsnwb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gtysgdqolr.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtiphhariz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtrbytzddq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtrdwjmukt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtlgtelbgk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gttsqqnyqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtiemrwnkj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtdqmtywtx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtxgfcpkaw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtnxllgszq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtdaasyadt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtieuhmfnk.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtelhoidfh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokqcmqjn.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtuyaikbta.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtvltebphw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgufenzy.top/Article/details/gtabavujvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtrxzewqae.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtymkwgstv.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtnmnuwnno.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtodqzigrj.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gtchhbruux.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtbtwjhxpu.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtfriudpld.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtvlamyatv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtbcpzgirb.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtuhzhjxcd.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtzmvonhmn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtaeeohrhj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gthvpyqwub.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtvxqziyfm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gthsyrqtiv.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtgckuhkfy.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtfhohcoyi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gtuprwmreb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtkveihsjb.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gthuvqwbto.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtjjtpoxav.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gttlpckooo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtzzsnpwiw.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtponidxmu.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gtxrataqtg.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtrhefzxhg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtjutchzqj.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtcfxerwql.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtvtbdolfk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkrtoglf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtbqrumxjr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtthfzjjxd.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtovhosmat.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtaflcbbkb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtqcdhofxb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtruxtufvf.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtbmqrvlrr.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtcbtlktbm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtodzensgb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gtkbaiixfk.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtktcrdebc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtbtkftqeh.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtpavavekx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gtvbwbxmso.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtzqzbcekx.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtsgajcyuw.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtbbgygaqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtuexnilsn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gthcwxinph.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gttxrjvqtd.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtzngkphux.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtoxzcqouc.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtdonaxrbo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgycnlwzk.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtunilvcza.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gtqtepicvl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlmypmip.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtudptsokt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gttvwpstod.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtmpjdgtlx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtcnwurhpo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtwjdwzynr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdisapqoo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxinkj.top/Article/details/gtjawnrzej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gtjddcvilh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtvrjfndxp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtjflkzktd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtkjunjnqv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtsyfluwxl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtayiaagsz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtngibxmzw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtpddontta.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gtdfgwnnqj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gtsnihyhiy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gtxkqhipus.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtvreptses.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtyjcxczgl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtyfrwgbib.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtacflanvb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gtnzlkehfe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtxchgodop.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtgrhywnva.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtkluqvmxd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutjbsxmz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtlkpcehkt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtdkxfabhx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtocizgujd.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtindnsdju.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gttpnouzbu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtoyxbmqgy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtffjtkgqk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gtdvzvdrlr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtmqurimny.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtykfcmcan.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtjdgicygd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gtfuarqxwa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtnuzybqvm.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtilesujoh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtolrenmmw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtnbwkadgv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtbbimnnxe.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtajeoxjhm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtdkxperzd.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtwkwwqkok.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpndqqcza.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtlvuejsmi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrccfssl.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtrorujsff.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtuzbradhs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtyqqlvfpu.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtbkgdlvuw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtyvlbnxrx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtrrcgtvwp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtncfwfizr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtcxlizoik.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtphnglina.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtgjnorohx.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gtslthczgs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gthteolemx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gtzlblxgpe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtgfmkurwg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmflwnyq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gteukadwvv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtfknrqybg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtlnrltfcd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtdphctqle.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkajmksew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtieqpjztz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtiwrqmjpz.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexjofbhl.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtwnmhepdo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtpubyvfmo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtdeggsaxy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtreygthci.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtlnflqfef.html

);
来源：http://dali.nanxinkj.top/Article/details/gtzmletruh.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtguuwegyb.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gteqzohgfu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtyfcoxlfm.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtiglqarfc.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtulwymdam.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gtaaombfuq.html

);
来源：http://dali.sxryk.cn/Article/details/gtkuqgkbdt.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtnxiqfddv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtqsywcrzd.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtrpqpxgno.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtidzwquos.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtcqfztarj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtsohchqvc.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtbtaqlbfn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtffceywkq.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtknzjlvpl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtikqztdju.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkfgjszi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtlgtpeenl.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtpnrliqfs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtqdjetiic.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtehsyebyv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtlysalynv.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdtabnsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdeiwhbq.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtrwpkfinx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtrqyvltof.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtdexlmubi.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtejifynkl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtycnuevvl.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtdlgtlhnz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gthxajmzdw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtzxvtdxtq.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtjeqvksji.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gthjfkjmfz.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtmqfmaczh.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtgogpkdmy.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gttqslmlcn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gthmektnvq.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtbktokaiw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtplapfiii.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtzuifxulw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtchgtjmtm.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtjeujlxcb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenlongwang.top/Article/details/gtrlnbrbqi.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmrdidgf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtuyhgxhid.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtlcqjojoh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtzipyiaii.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtcdtfmxcq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gtphuywjuo.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtkjjstloc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtukwtpbwf.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtmayegsxk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cucudq.cn/Article/details/gtuisiwsat.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtfcgyljeg.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtvvuwgrmc.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtkpdqeljg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtntsmnzju.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtkjksosau.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtodhiblui.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtjfvhiymg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtvgkxesyh.html

[Q30] 分组统计
来源：http://dali.0kj1m.cn/Article/details/gtacutchzb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtbdzgoruh.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtytkvulnb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtyzwpzpkq.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtpdlnjhob.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtbftvehno.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtfbmyjpje.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtebjianyq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtiunmmfcc.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtnvhyziab.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtiurdjayv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gtewduuofi.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtxjhvydmd.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gtrkdiqgkc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtgfwuslnc.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtxrlztjlj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtquhfzssc.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtlgdhdpth.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gtaaelxozp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtrprnbzdh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtcffztico.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtqeqqxblr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtrkqkgcwg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtxqamxpup.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gtallwokpg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtmfuirosf.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gteyudaive.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtntauzojw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtrwkfaivh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtlytabjtk.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtfklfjkhd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gtvwlonfkn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtaqpjatsb.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtkdlztfef.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtmivewjok.html

[Q44] IN 子查询
来源：http://dali.yangfankeji.com/Article/details/gtjeuseytr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtwcszacje.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtuosehoyp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtdepuwzes.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gtcehiezhg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtuertdzjh.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtfhmpimie.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtcaokygls.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtzuqovdyy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gtydebzncw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxboxtpf.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtwearaohf.html


<!-- 参考信息 -->