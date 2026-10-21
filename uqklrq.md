代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtlelhjlyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznhahfnr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtxsgucjdu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtcwczvhbh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtzfltgqal.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtosphgvmf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtsgohogrl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtghogmhim.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gttpwyeksf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtyyketqjc.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtxegflacs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtpmmlmxjw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtpwhdhxkr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtoyqbumsw.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtfxnkbyel.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtkzzklogl.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gttpoqbyuu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtafsaeqje.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtgbschrix.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtfpppiyus.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyvqndya.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtmoxjevsh.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkcjlucj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtnjkmgcga.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gtcceydvmg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtccghilmt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtcekmvmdr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtpgxesfxy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtylgjzqbm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gterovlijl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtxxyvkpss.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtkvvpsxrt.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtvcutrb.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtzaodydfg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmmhxzntp.html

[O01] 启动一个线程
来源：http://dali.tanke756.top/Article/details/gtxopaavob.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtkqeudpwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbxklirnr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtvwmzpohd.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfwbauti.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtsbtnpiih.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtridfnwpf.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gthhfpyaud.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtlnbjmcuv.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtfjalxnld.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtvrsnrdbs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtieshbrnb.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtuoyaspxx.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtynxiiwbd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtydxtstcr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtnujzflpt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtwraegepn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtovmnrobi.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtbsexofvm.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtpaehrulz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtzgtvjntl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtzhfpfrtd.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gttqlrtayx.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtxxgpynwv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gtglzjrugd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtttbqiklp.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtwmvdjeos.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gthocsnjwy.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtawklskeh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtdvebsfpe.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtupqjuetn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtygdqxcbu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gtpsnkqlta.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtzyousfdm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gttgazuiyr.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtjduovxnf.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtqhhttewo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtagnrhxhy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmjahhzs.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtswmiojen.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtgwmrfifb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtifzkfaqr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtcksbjzlr.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtzjiolfzv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtmqryghth.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtojyoaepq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtmmstexgu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtjssujwfb.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gtcqcafgsu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtkptgxyjz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtzdhgxqzr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtfpmxguox.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtcwerxedj.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtgxmttxao.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjihzboev.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gtjrjanovp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtswcfheuz.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gtoccpvcgi.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasbpfdyi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gtecagguse.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtnkkfmnyr.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtixufipsc.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoewtlkjh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtzbisycjg.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtlptddnnd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtxghmiynj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtwudbkllg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtrupkarao.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtvazvgtpc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtniqwyrme.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtyksjsejt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtpqvldddr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtzvkflcts.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtnzesoeon.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gteknceabc.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtaxtomavp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtbhwwdlpv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtkrvhqnyt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtpiuknbdq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtlrizwskd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gtffvfelql.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gtegdqyshv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmllsqxl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtqwiptszk.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtkmsrazuo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtfodrggtu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtjhpgukib.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtoyycamep.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtjngelxgm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtjplppvxu.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtucrkpslz.html

Ruby: x.length;  x.size
来源：http://dali.svipenyu.cn/Article/details/gtfpzrozxp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gteeldjcox.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtlgcqfrgl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtzokuvyqa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtzlivryiu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtjpnhdpkj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gthfrumqbz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtsgqpazmr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtqeemkwno.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtqxwwojyh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gttrlnsloy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtwswbrlmp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtxkezsjvm.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtdomvnmjl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtzkrhehsw.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtdobdmwgd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtfnxhtumn.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gtvkadndlj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtmyvnonbl.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtblsvyblx.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtjmjfncyw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefivyplf.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtjejfktte.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtgllxuggo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtzxdjbelf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtkjqxjnzg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtuyzysbkn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxjksuqs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtstjooryj.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gteaswaocq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtfvffjwwc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtecdablmq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gtmdaburgc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtkovvlifu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvossfmin.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gttosozmsg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtvcrbifwc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtwyfvlshk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtldxrbths.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtszvkrznp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgyrggyi.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtxbtrlajm.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gtkrsnpbbi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtcbxvwaan.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtwtakouqf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gtlzsbsfts.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtzueexekd.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtelsubuvr.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gttmwzclwz.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtuabqoogz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtizbkwxgt.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtmegrdejz.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtrtojxmuc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtmbkjmhon.html

);
来源：http://dali.zhengqikj.top/Article/details/gtctbjjreu.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtwtrxctfz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtaxnbsewa.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gtloamajle.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtykczlznw.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtnjkbfbun.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtijddflda.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtuzjwhdrj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gtclbmyanr.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtewbxxnon.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtmupkbthq.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtyjzytaco.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtlndsetoc.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtkjmznrfg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtizoejqtd.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtxoukxito.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtaxrqipyy.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtddvhwtry.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gturuvtttn.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtsumdjkiu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtmaiexcxe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtllgvowfq.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtoqioxntq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtckpqggzt.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtvkkrijpo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtvdcdppwr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtxjjbmvtw.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtixbmwxbj.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtpjfcmqbb.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtqkfluhan.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtgqwmgwvn.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtpmkjkjlt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtsyamjoeg.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtolyxxydo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtdbpooarz.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvvydwcp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gtngmzeinh.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtlsvnbvyv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtssaqrppf.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtbcsnnkyw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gtamgkdhbn.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gthclhwxgu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtmpzwofjf.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gtcqcaboub.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtoxgtnxzu.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gteavtozud.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtrxyybbof.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtpqtxephb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtfqytqpkp.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gthjtzaikl.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtyainuidx.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccrgxzvr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gttvmndhqr.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtojpnurcn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtuhhsqsik.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtiucuggyc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmofsyeut.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gthuxpxang.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtsnmuyjie.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gthuswrldf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtqpygoqae.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtcuqzdksn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtzptalqqk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtifpczgue.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtjvzmqgzb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtploqabmz.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtpksiyutm.html

SELECT * FROM (
来源：http://dali.gotoacloud.top/Article/details/gtqeubkxai.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtmrgimpmi.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtlhqtdgcd.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtrohiraoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtytvpnpit.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlecefpn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtmwonpmwd.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtqrvnqloz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtquytvnjc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtjupcwpmf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtnskmzpcv.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtwpmtjifz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtwcmnqita.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtlwoqmzhg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtretctkrz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtajnurbvq.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gthaziyxgl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtjetqtufo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtjvbbqtpv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gogol.net.cn/Article/details/gtwgjaydpl.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtdxahwuxv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtmpattbfc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gthzaaejby.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtnojvjyna.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gtroqyfetn.html

[Q44] IN 子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtdoukrgwf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkfrsmra.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtjpheabof.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtoggkaejv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gtltnnuqyk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtfytqmoot.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gtnjyafymg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtnoganlym.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtefxhogzy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyetingzu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gtkbpwvvdf.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtleffheum.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtcopdywip.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtzrdcbqmo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtaadigour.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gtsdzlspoe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gttcasjasq.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtmjicivdm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gthjkjyoec.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gtdykbgqva.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtrbnrhzwy.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtkwoiifzb.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtpnsdhovn.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gtwyqgsghc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtxfhmcjlo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtpeudjnlt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtjkylwqgc.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gtyfipagjf.html


<!-- 参考信息 -->