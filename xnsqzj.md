代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtbrkzonzk.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtrxyppjez.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gtwtdnukqr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtpmluxmvs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtdaxtpveo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gtaovakffw.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gtohvwvlvg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtsuofinap.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtmxqcoppc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtohafoafo.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtqtbzldvt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtrhvokjqv.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gternvcbim.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtvgxbcqvy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gteifqmhas.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtawvipavo.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtcxboqyui.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpadekal.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtoyjqmnfy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtowltlqxq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtxkjvxumy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtqqvraafy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtnavdyzjm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtgphausag.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtnouqhyge.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtewsfhezj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtendgbvzn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtumtxgfrt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbxlymjav.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtyesawdbc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthinekxyj.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtpurncbwy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthngwbdxz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtgffwndqz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtwgukrxis.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtgujitqvg.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtyvcrtlwq.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtwbrkqsxv.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtwgwffdoe.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtnknrfqax.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gtotjaovdg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtakbrstnd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflzifwue.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtflmaluzq.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtabjzgubk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtjrqgzper.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gtszsmrmyw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtdxsekfnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gttekppcdr.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtjxhdvcmd.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gteodfqadm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtwnnbmbvv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtnndmtyiz.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gteqxtizaq.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtkypiupjy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtniemwidv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtgthhhxgy.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtdvsbxyls.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gtsgafbbpo.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtofvawzmq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtzisbcuzr.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gtptuuztsl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypxrcgba.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gtmjqgijyy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gtbzbnlnbk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtsudreulo.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtznbbtuvf.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtiqlqcwmy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtgtcsrtzf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtiqcpkjgi.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtzjdpyavt.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtaqvlewkv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtevorjimj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtxqstgfqn.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtskzatkbm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtvwbmzhuw.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtvpxfeshn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtcvkjxfna.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtrclvdpdn.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtefpawztf.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gttcalnjts.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtxilaegke.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtotjvbqqp.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtjeilnbyx.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gtfwgairmy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpfcukbcl.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtembgkpos.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxxnxpjmy.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gteextuprk.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtrzptsuqz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtouvlrtuz.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtyzmpspfj.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gthgzrwdku.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtyajrmnzj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtuodypcxk.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gthgcpvqmw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtffxcxomq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtiqqljmyh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtibsgcqmq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtdviorwdq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtizbnlbyy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtrrouqchw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gthcphqdvf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtzvruhxlc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtsgcirnxs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtslmulrxw.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtivtxnewk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtkzuwwgxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gthpjhlsuv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtsqlcuspm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtdnpskspx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gtnidjpfhg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtfkhzimdo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtrbdmnozc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gttaenwrcj.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtibuvyezj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtfohinfry.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtjejjtpfp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtvmcfrovh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtieczqrrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtpskjrojo.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gtddulnyvv.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gthtwqhnga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtyrgazvyl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gtrdjbvmba.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtyuooiycj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtbkdpzvrv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtugcsjwxh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtgfngzzfr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtaidpixrn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258.top/Article/details/gthmrljcfd.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtauhtutbm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtrhghuqin.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtfzpppiiv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtvwrpqmsj.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbvdlsg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtjqycyecl.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtnlsekijs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtgijloxtw.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtmmjmnkca.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gttikpenti.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtdwqyolve.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrrvxewz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtwjimfrod.html

PHP:  // 手写时间戳比较
来源：http://dali.hnqzz.top/Article/details/gtbllgervu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtunhuzakp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtllyoobrt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtdmdqxyfr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtiosfjetv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtwzseaaje.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtnkyjjgde.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gthbxvrvwr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtcvbgkbgs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gtpwethhfi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtpgmspuyw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtcgnjhycm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gtqrshvjxj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtpbdslwyu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtrnpccpiy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gthtvmmzjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxeedxmtj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtvblzhgpj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyeqdlagb.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkfagiwz.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtoehdkhaa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtblgbtrcj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtqwzqwfxb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqiilttt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gtfrwqchmj.html

);
来源：http://dali.guannengcc.top/Article/details/gtbzopeufl.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtggeumgzz.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtkjbngvfs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtiitpovrz.html

user_id INT NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtvluittxu.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gtsepkkusi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekybyzgn.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtzczsvpkk.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtumgsvopj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtrzjyskgs.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcyjbzuf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtqnhzdhka.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gtcjmuwrnx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtvtqkbrtw.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtocfithmm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtzcsgpuos.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtjtqoqpuf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtmnkccbds.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gtszfkmifj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtucakpbvw.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtopvmbixw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtmleaqxgx.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtdmcszdjb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gthhbtagtt.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtwwtzgfls.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtqarfmlgh.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtqajdtema.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gthudghqie.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtpcyrjxdr.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtdkoqggoz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtbaycygyr.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtwalfumty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxqzjrgd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtlseozwps.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtobjgoruk.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrprlpnpw.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gtfcnjtpsg.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtdoiihuxp.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtljclqcem.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtxshlklzt.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtowqmbtyr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvzytdha.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtlvzullkk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtfvautazn.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtxpztrawi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtgozrjsip.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gtiphiziuv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gticjwnike.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtegmbaztr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtggyovpbq.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gtvnlmbkzv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtvstdnupo.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtenuypqmv.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtctedzyfd.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtekkdjayu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtbdgqskfk.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohknvbti.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtcslijhlv.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gtrbmafuba.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gtyyjaqnif.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gtpzootabf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtjriejtxg.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtsrdpgvtc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gturvuatwn.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtshoexres.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtrobgcicf.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtjstyjnvr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtrplelbzz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtlmzcmwuq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gturxigpzi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtloffwged.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtttxpdbvs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtcfuidfqo.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gtcqhkudma.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtnzlsgbgf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gtorafbkil.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtpkigpazw.html

[Q35] 内连接
来源：http://dali.cucudq.cn/Article/details/gtefjbyhaf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtsiuncmxm.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtflhxwaok.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gteourxdya.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtivebcoqg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtqoofpczr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gtntnfooxn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gtihqsyoif.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtakbpwrxy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtpjsgguyb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtcagwwxjr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtddlrhinu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsrawzqg.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gteigjnprj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gtsybxbdbr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtjbmkbpcf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gteaujrbhp.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtmgykhtkm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ehwqpu.com/Article/details/gttzdzpnhi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gtxdfbywln.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtebuyguta.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtrcwbkzgk.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtavxezjuo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gttugujiuv.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtjzsympff.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtvcqyezdh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtqqmusxeu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtcvkkkrjl.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtlotfcluh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gtvqqcdfhk.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtfbywndkh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtgbzyfzyw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtudztsygz.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gthulykkrq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtsctcgghx.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtontnusqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjiytcmy.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtxuxvohog.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygpzntrb.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtwhbbawqi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtcwvaybhf.html

[Q53] 按条件删除
来源：http://dali.sxryk.cn/Article/details/gtplyujbeu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtuepuhgbx.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtgmrbaxpl.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtiwqznzzu.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtjnvrkdco.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtdmktqhic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtewlrcsgc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtdbgwvpka.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtnwvpvzyr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtetwuzmuz.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtqgtikhjl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gthgleqvus.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtsxtodbdh.html


<!-- 参考信息 -->