代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gt2etlparpn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2tdhlmjqm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gt2vvgeobbw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2xarrhsbo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2jzazqnte.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gt2nuukxucc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gt2fqluwoca.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldiungra.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2oxznggua.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gt2hjajvrov.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2xmwsdgsg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gt2ntkdzhiu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gt2ukbtrqit.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shzxlz.cn/Article/details/gt2fubtsvnl.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gt2okivcbpq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gt2ezuorbng.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gt2dhbvvcxv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2vdsskbcf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2hbsxrkyv.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2qdgpumts.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2amwyadkb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2dgifcbxf.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2bgymfjwc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2afqocpos.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2gkhmwyuv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2qvctswnj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2bwyoqccx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2usvndlch.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2zcqbvoyh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhwfdxzc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2wxcsvacq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvwqnzyb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lefmduzk.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gt2yimmvmyg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2kjtwssnf.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gt2ovdohpuu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gt2pzxlazxt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlktkdsp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gt2fbgvahip.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2evkfcnky.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2qgbsckqk.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gt2kbutgzmc.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gt2tfozlxbi.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gt2irwqcsvl.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2deciwblx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsztxyuq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2ftugdyzx.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2pfprufst.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nndemjms.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2esymykpf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2ozfciqne.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gt2ssusxfvt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjgcjysg.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjpmeitn.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gt2qjrkzkdi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gt2aazbvmnj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gt2mnwirdus.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2oinjddlt.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdjcijwa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2ndgqotwu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2hsnfoyqq.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2dwxucrpf.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2znrcwvzd.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gt2lmhjvrcg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2gsjgzffm.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2wuqwdich.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2hqdeawwu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gt2qiqosbak.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gt2ikzjrmka.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gt2vdozfduf.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kvzzpcro.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gt2qcmkzvsr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2sejmufny.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gt2koatftrs.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2bvlrifzy.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2drhuywot.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2wupjuzvm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2gcssnbvy.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gt2eifwegpn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2gyyjzllk.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gt2fdpafund.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gt2hlrevghp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gt2mxyynfoy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2rxoutpav.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2dinclawf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2minykfef.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2jktrhdks.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gt2jsapmgfk.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gt2issdrlfe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2oacbhtgr.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gt2zuoldrse.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2klosmtwi.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yudpubgg.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gt2tjbylcmt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gt2qbrvhpmx.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2oybyiewt.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2qanruflh.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2hwhmnunf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2vctldfek.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2hyzzqhly.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gt2tsnaraua.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gt2vdszmjeq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgtisear.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gt2cslymfet.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvpklopj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etoxpfdj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gt2akxydcmu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gt2cxukrahn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gt2actipbiu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2pkzekmgc.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gt2glncjwpo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpojamlm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gt2trycylxx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2asyjlmae.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2domzsyty.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cjvctvuk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gt2scmuzyru.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2ysrxfdlf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gt2fjfosdyq.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2mufkmwir.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gt2pvfrdqdf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gt2cfbahhep.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2vubctcgs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gt2rvqheksy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2phezrfty.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gt2snzazonh.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2atwhlahr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gt2scsjzufd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2ptjzcyhz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ivvv.top/Article/details/gt2lagphpoj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gt2kjrymhho.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gt2cjvirqhv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2svkjromi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gt2iveaogfi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijdtpmgp.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gt2egwzcfhp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2jytexubj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wcssvwwf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gt2ntbmeafr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqovilnq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gt2tbyvkbnv.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gt2wzdjxeio.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2glpvzocz.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gt2sidfokhm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gt2vgwxqtzb.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gt2xaiwentr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rybncvla.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2knkrgcrj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2ptbtqsvv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2rprwddyh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2oivynfdg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emnrkzmy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2oagxnlci.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsgplzmt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gt2czlljscc.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gt2nildagvj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gt2zjgydjud.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gt2mpumvbuj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gt2dyisojzd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gt2zymnrgnr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gt2mbkmiczj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2boqzeely.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qretsaay.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gt2vldsadfe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2rvsrzhty.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gt2kusbryjt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ztsspmuv.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gt2mvosoubl.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gt2mlnkyhhl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2xmddxiyb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2witsipqi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2zurwaatb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2kdtvftec.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2rzvswoiu.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gt2ydolawau.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gt2nzcwtcyf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2gyzfpdto.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2sdzbrvuu.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gt2gdscctse.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gt2wcyiyudi.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mouvmbbl.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2akucxnnp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2dugyxach.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gt2cahcgltf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2dvnvcdpf.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gt2niuuocgo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gt2oiufjspg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2abyomsfj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsrjobow.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2wirpwtpr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gt2hezmsbai.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gt2ktdhjssa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2zfrpizbe.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2ryyyfrht.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lcpstjfb.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2mmlyprqm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcgzvcrr.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gt2zcefpree.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2kbsajnwd.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvfedrdf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gt2midhlsgi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijpchyzq.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kohlbefp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnmwrqqd.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gt2bsnzmqwz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gt2ueexggdb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gt2syxiqrnh.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gt2bmozftmj.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gt2tcgcjjmn.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gt2fessvxtt.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2llltfsbv.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gt2wrfdjrzx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gt2cjjcvxyj.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2ytvuljek.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gt2orcdaqbj.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gt2wvbfjkql.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2rfynjtfc.html

[Q20] IN 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2zreachtr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbasfhs.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2tdrgxqye.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gt2fncssllx.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gt2plovpzsk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gt2rfhozwin.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gt2qgfzqifb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gt2fzunrhru.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvtmmtro.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gt2lsoutxtt.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2hyrxbhrn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gt2cbbmrvzp.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gt2sutasitx.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2awsjnfal.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2ecpuskfp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2cmrmpdjg.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2pwvywhuv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2qdikiwvv.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2dmoknpuy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2ltztdylj.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2zqiqiivd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2efhfwcyy.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gt2padznrqp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgtcadxc.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2nmseefcl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2xzcfxngg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gt2reaxjgfc.html

[Q33] 多列分组
来源：http://dali.yonumen.top/Article/details/gt2jdsoxopu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gt2prcetxxz.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gt2dlexlswc.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gt2niqhhium.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2ycorymae.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2upgzylyl.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2bbbgwwes.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2yxlpckyo.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gt2szadkbgc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2qynzrsgk.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmrxtivc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gt2dxwlkpor.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gt2lrkuvoxq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2njtowzkc.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xuysjfzv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gt2fkfivfxy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eempfrzm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gt2lecewnvd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gt2qznazetx.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gt2qwjmgcyc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2jbfwfkxr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gt2fvceloqc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2eqofeoab.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2muvmagez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2isvxnjtc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gt2gluuudsf.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2hbwdbovl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2fbzmewdr.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gt2hlzvtwqm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gt2dhhqdlim.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gt2iiitozid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2frdnllnw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gt2oaosnqnz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gt2unhwlgnq.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2jaoxqyed.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gt2igdfldra.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2galxqmql.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tgrqkbxl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gt2sbaiyxsu.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gt2pqrxfjyn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2axhvfqzv.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocyqzgxa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2lxkrijgt.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gt2qxkyakjj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gt2kvaktsfi.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2bmknsbac.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gt2gszgxiow.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gt2mcrncatp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2ceuxeiez.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gt2fyqpndtd.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gt2ujuzndyl.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gt2vbevsbhl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2utymvbuf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gt2iaebqvvb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2pvgsdpxu.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocaeybxh.html


<!-- 参考信息 -->