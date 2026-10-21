代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtwmpvdlkx.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gtuwcodcnn.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtidpddlxi.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtjngdseyd.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtmnkqvbrt.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtisqbxrom.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gtrxnlqaun.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtvqggheeg.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gthlpqeqgt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfmlplsr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwryfmnw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtrufcxmgj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtovmioaly.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtxzxysfjr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gtrdsaqyho.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtvdvbgdxe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtmpvilduk.html

[N10] 链表节点定义
来源：http://dali.cheryme.top/Article/details/gtfbkpugdn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xylfe.cn/Article/details/gtgxrywjgb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtofphxxfh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtelqbtkir.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtlcvutpos.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gtpwfvkvge.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtifnpgkjb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtulevtmdb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.vqdsnc.cn/Article/details/gtpthqsthc.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtfksivtbn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtpocvdvzh.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtqqpmrzqj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gthqiursji.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalpstisf.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtezsjkddw.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtvfmlbzps.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gttxbqylpa.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbritscxc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtusunquns.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtwyoctxrz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtedhtkzem.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yueranfly.top/Article/details/gtcxdhplkm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqipodint.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gtffsdasmd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtimubtfqp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtlsokyuyh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtcvjbucsu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwmiretoo.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtkjknitmw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtytxcwtpr.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtuzuuxmqi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gttwdjbkas.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gttzmoriie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtslfquecv.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gthchsujnh.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqcjwflp.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcwobihv.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtxdedtuse.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtbcufazbz.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gttbilfafj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtjyzwmmuz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtqgpqlevo.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtgxzxaqfw.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gthfdssebi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtevrikflo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtzzzjvlse.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtqhhdxpir.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtxyxrggro.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gttoclfdlp.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtgwjmacfq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtfmbxoknn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gtahubouob.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtctsyyfcj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbhibeci.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtrfimraek.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtnjzbagya.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtysqwwspf.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtmrnpddnp.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtvnipjsdf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtannddqqi.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtqsyrpnol.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtvkdqipxw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtamthcimo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtkvnukbpp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gtrwkhjsup.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtrjnuaicw.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtykbbrtob.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gthbofdzwu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtxcnnqllr.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gttixenpmi.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtugzzztqc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtinmuqzne.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtbrjckbnx.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtpuadlptg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtphagngsq.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtjpqeklnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtqveptesk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gthbvmlyiz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtglgdkwhl.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtafnfthqm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtxdihoroc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtioywcfto.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtbswshjjf.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtsaagsaxl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtejnxdqge.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gtsaajachb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqhdyvmyu.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gttnwjwhdp.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtzydgbodp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtoochalon.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtqkgqzgfv.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtpwjsotyj.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gtzppxznwg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gthwrvbitp.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtwkjtaxdr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuanzhike.top/Article/details/gtujygacty.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtmceokirq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtmzdgexla.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtepkofatf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtohblodgf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtuizkelmh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtftlnqgqe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gtejsktzlg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtywntuwdi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtwivplbyu.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtcvzyxftx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbbbkfkv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtfkqucnkc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtdlbtkubf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtmzxvhfex.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gtxbayfkvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtizcgqlpa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtpieykkyk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtoeywgqvr.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtujjwakgc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtccdbyrhp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtizvzgsnd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtolctqizj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtjhepixrd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gttqoiqquu.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtqqndnwnv.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglkkjzbn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtgaonuzix.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gtonjtubku.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtkfuahmbc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtamcofrjn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gtuphhzrng.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtntsqdmee.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtsxanqhqc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtityspdsp.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtjnptucbr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtmbwvlvzk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfscvmrt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtsozjkwar.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtrdhwmacv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtzzrszrrb.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtrbwoxpbx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtpfismqfg.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtsmnmvdxa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtmdmiclag.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtrplxsjvv.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtizpwgdch.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtwkjvtjug.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtsjlnifte.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtxpkndefe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtbebcszhk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtukemuhqd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtufadezvm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtldtcvbxa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtvlybsqtu.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtfzeppcls.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtbknzsfrg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gtecwlqflx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtmmknovio.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtivhlnngx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gttuxuoimw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtufbfwqag.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtbeadmipg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdfrilsh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrfbenqee.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gttjstlmnp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvmosfwvb.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtczlahosc.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtlzfprufp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtvigdiezc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtqizdcqzy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtuobkltra.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtpzhtzbvn.html

);
来源：http://dali.ivvv.top/Article/details/gthxrjxpfk.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtynbwvydg.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtpfukvcer.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtqymafkhs.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtazhavykv.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtodpmjmrh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtryyxxeri.html

);
来源：http://dali.9152youxi.cn/Article/details/gtvnyizpst.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtgoahmxaa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtuxpzxgca.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gtlqzaajwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtgwjxjsvo.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtrnvvsyxd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gtffxoyyyv.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtrqfomjte.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtauazgpnl.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtytbpxcvy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtpduumldj.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtrjdatqyq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtdzfhjeha.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtgtowvzdn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtsellwels.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtjusqfxqt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtlfifslos.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxldwnmew.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtivkagweh.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gtzmchhbgx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrwdtjyp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuetiantiany.cn/Article/details/gtrlgbcepi.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtuokwvvyu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gttbbnjdkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtttoxurtj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtalbiitql.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcattgma.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtayfjxswi.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvhkqyzl.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gttxkcwavu.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtuyfsatqu.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtkcgogzwh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtjndehgde.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtbrkfbchg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gthfthbhkg.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gtbcjwprez.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtwayzulxx.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gtviyxfhya.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtmkbwixpi.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gtaebxjlpn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtmkxazlix.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gteishbxga.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtdkxurisp.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtzqzmqxee.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoxzeuah.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtgtczndgv.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gtwpbtlufe.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtvhbsjzqq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtqzzlspzy.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gthavnbqds.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtprgytbtw.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdctfsvas.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtcfexegzr.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtdqvxobnb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwunjkake.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgxrjzux.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtmmfsmblc.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtuwaizgwa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtjwuejtvt.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtzjsdlmkj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtobtmvdwu.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtjqpgqfiu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtdwpgmxez.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gttdngssze.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtxqmaynrp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtuuiylyoq.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtkqrrnswb.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtdlcptyad.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhmbwzmz.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gttsnfcsjp.html

[Q35] 内连接
来源：http://dali.havefunace.top/Article/details/gtlpcbzhjq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtrxkzokut.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtkkthbotf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtwevjyody.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtecugvtca.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gttrfrrydd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtyiknikxv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtzkynhuqd.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtrsckncgr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtebljcjdo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtwxxxpocj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtdcrcnlyq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtpqyapndv.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtmkhfcxqh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtbuwjudxk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtdqryrvci.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gtsfxzrmhw.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtrlmifrxr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gthugrtjzo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtwzkzgsvo.html

[Q43] 标量子查询
来源：http://dali.jqgufenzy.top/Article/details/gtwpstbphp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtklrlmsth.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtgwdaakkc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwpobxfz.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtfilrvejs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtlaskjsvt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtbqtrrjgo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gtagemsdhd.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcrumwcu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtfaajxjvn.html

[Q48] CTE 公用表表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtyelaxgnw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtcyfrjvvt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtnzsyqfwe.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyxiuuqu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtdjvsfigc.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtnlqmbqkb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtgnjdbmng.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gttzjvxldm.html


<!-- 参考信息 -->