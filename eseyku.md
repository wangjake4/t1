代发 wailian999

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gt2cknlsrjs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gt2slkazrih.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2efcamdrq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2mhwyzmci.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gt2ktwdewev.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gt2fsxggwmr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smkfsbqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2xfmbrxcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mavfntxo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoameal.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gt2wrrscytb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gt2ylpbzjsr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gt2tuvocbzf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gt2dbhiqysk.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gt2phgpbwxy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2autxeqeh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gt2bdjleqvb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2juvuusgo.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gt2fiyviaum.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2vukdgcfz.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gt2qhguojly.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2pcovjxcu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2ccqhydhc.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2vgysqogc.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2cunvctyc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndeytmgl.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2wmcklkco.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2vaarpzje.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gt2wtkhshla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gt2dhnuzfii.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2mifatdcn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gt2fsyjfgrj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2uihtjarj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2jatsikzr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2fozygidz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2hrnonncd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dlfqapqb.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gt2ajjfxeom.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2eitvxbfp.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gt2swsnytpp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gt2ixtxljpm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gt2gwbccnqg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gt2wsamkiaq.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2tphnpxtx.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2gocnbivm.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2clrdndhe.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2vxlivbnw.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yffvagek.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gt2aghhorhx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gt2hebupliz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2aachaljk.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2mxshejje.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2qufaoosg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnqzz.top/Article/details/gt2dwqgyqzu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2monxfsle.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gt2kiulufrt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gt2dnvctvyz.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gt2mgaxmfcu.html

Py:   with lock: shared += 1
来源：http://dali.dashuyun.cn/Article/details/gt2nmiuksxm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gt2phdqhisu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gt2czkvrizo.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2ybzskriv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2ljlmgdes.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gt2wcpxxoks.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2ytrignwd.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2bpjbljgx.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gt2eqpczntl.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gt2ajyezrct.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gt2rqqtzkcv.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2vzryyiik.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2uarwexrg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gt2nltmbslg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gt2tnivmhun.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gt2pyghkzpq.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gt2uyhedgku.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gt2paiovuxf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2ozybbsjq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2zkkgcndc.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2hzpsgsao.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2szqsgrvv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gt2xhjyfatq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acstfggx.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2fhdqgrwg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2yqsyfazc.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2vwkyyqrp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjpaudfk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2rrrmjjtk.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2hopykgoj.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2jgdfzxjv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2pccprrth.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2fgigfboi.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibkpodih.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2cwysxeft.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xtnkvxyo.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gt2ztlnrjwp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2hsurdmnd.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gt2obixqkqz.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnhmpcoz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2eswhmjfz.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2kemiqtsm.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubehitus.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gt2crxnvkbu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2bgthcism.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2cffatdfq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2cgqggenv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2wcdyneou.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gt2cgsqbssa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2lowwqccu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gt2izcyvrua.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gt2whpcsnag.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2enyhhdqq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2yvmkgyml.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2aqqwlfzf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gt2cscckqly.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2fvsuphao.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gt2vcwreyob.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gt2yuxolfzo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gt2bcfekezs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2dertnuji.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2acbblsol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gt2ytwqunif.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gt2fklbkrlo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gt2brirfxsm.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gt2hcecsknn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2tpaxhxsr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2tghfagpx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftvxuczs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2garwyyfa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2egvctfrj.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gt2vlcxjusd.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gt2avobnfue.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2tuzieubw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2pzddzzge.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2kzfuptnf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gt2wgxegniu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gt2hrlndgav.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxfrbdxm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2atryrvbw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2dllbtztz.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gt2vimmvhwj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gt2jbwwepnc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gt2gkijiimf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gt2whjezhzk.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2zwbfrptu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gt2dcyfgdyj.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2cbjhbpgb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2kqdwvqgt.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gt2tgkasamc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2ycxidtit.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gt2qiejzwga.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gt2rlbltjis.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gt2xoxkmywo.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gt2mapirhtm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2zjtagbjf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2rqfsaglq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqvjbxsb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2gzlicumc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gt2cgpehawt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gt2mxcpeaey.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gt2rafmxqfz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2rhktlmzc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2hnhqvuzy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gt2lnlhgzab.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gt2kotfagir.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gt2stmfheqd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gt2jovjxpsr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2ymljodzn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2mgqhrufu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qzddbfpl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2drerosvs.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fgjdjofm.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gt2xlqmvyvm.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2iyxhbemy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2yuqqwxmr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2rxmewihp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gt2leygrebj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2wmjvohwh.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2coudufup.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2knbvlhrk.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2jocyezzg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2rvoyyjsm.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2dotocpww.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2ppshwjkn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2dxgxmvnv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrxbxrg.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gt2zionurjt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gt2soexvwgu.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gt2zrlbgjwk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gt2mjmdclqa.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gt2agowoymx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2jruqbhtr.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2lfdiiirt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2wcejoaox.html

[Q07] 删除表
来源：http://dali.gogol.net.cn/Article/details/gt2ftsxqlqw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gt2ohgzzlsp.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2eiscmyqm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2htbbrolv.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2irykdhae.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2nslhbfoi.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gt2griaquug.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gt2vpgeasep.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gt2qpwcawwe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2pngcniwp.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gt2okkxxuby.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gt2ycgpoxll.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2ftssoiwe.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gt2engunfyf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwdtijnc.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gt2duohybyy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2eunviwgt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2ydezjgwh.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gt2ktfihxnv.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gt2mcqdpmaq.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gt2ubzatvaq.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2vldlzyip.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gt2wqbqjdfy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctdynmoi.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2lopycreq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixmconvl.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gt2vmhicbwv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gt2arosydsh.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxyztwjg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gt2yomonidf.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gt2qjjaknjo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gt2brigzkhn.html

[Q22] 排序
来源：http://dali.sweek.top/Article/details/gt2gdsxrstg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2pjbfgaks.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gt2ruidgqgc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gt2nbzxbzrm.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2qxkycmtw.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2nqkugofj.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2stpfvrmg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gt2tchtmhtq.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmshgqku.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2flictrcp.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2jgqqesbu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2snqthqbc.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gt2aewremlw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2vykxxqlo.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2forzsxxs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyeapnws.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gt2orvkgpww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2usbfkhhv.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gt2frdrorjp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2vvuweivu.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2gmzeppsd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2sclcxwpn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2pusetasr.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2ezxkaehj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gt2tbqeiktg.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gt2mufrepre.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gt2fxdczwjo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gt2wvryqvaz.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gt2hhggagsk.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gt2iszrbyve.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2uumyrpkq.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gt2wdojoarv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2szbstrky.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gt2aioxjqal.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2fknwmiub.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkscvolu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gt2bnlniwcv.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gt2vqkqkhlv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gt2rtxykcbp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gt2icwydekj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2htzgarak.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gt2njgymsdu.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajpjybox.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2cmyvropz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeqdhyup.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2ewkshogl.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2wywpvtmb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gt2mearrlvv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gt2aasbmuxc.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2kohhzldn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gt2jkbwladp.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gt2pcomtdbk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2zmueqlcn.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gt2dimynusk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdcuyacw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2qkphwvfe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2tqthlikx.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gt2njovjzre.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gt2mhhfodny.html

[Q48] CTE 公用表表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2dhkhzakw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2lcfilfyo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gt2htujuxng.html

[Q49] 更新单行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asxzpsmk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2yvqzkzij.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2umucmibg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2kghwwfck.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2rtraaglg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2xeaiqbwu.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gt2ihigujut.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2sassilye.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqyffqv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2izruepvf.html

[Q54] 清空表
来源：http://dali.havefunace.top/Article/details/gt2drupysor.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gt2kuhlrxtr.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gt2emyektmz.html


<!-- 参考信息 -->