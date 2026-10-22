代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtasvtkqem.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gtflxhfkvh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtcvcrsirf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gtkxrxslos.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gteqhsdvsf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtmgoxuedw.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gttvtrnhkc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gtndrwlyth.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtkkxaquyl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtfdashspy.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtwijqlkca.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gtirsgzmlb.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtffqozykj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtlcgoriml.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtnrmesbzx.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gtjwgnzaic.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtmvaolber.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtivbdiexe.html

C#:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdozltfw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtvdnmpbxa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtrrbdbaal.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtuqonzfis.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtvjxpjtqp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtncroqjgf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtsicswegc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtnhtefyar.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtwithkddp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtivmfxgln.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtknyvnknb.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtcvdvpsap.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzkevfle.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpydnkcb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtwuvxzfug.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwuzpotd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtolduqqrw.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtozcuguar.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpxdzylj.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtzyjbdwvq.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdzoprwf.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtnneowakk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gttabaezrh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtntvjtpgo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gtixyempdm.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtzrzybtpm.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtrwnqpzyz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtrhtpeild.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigufen.top/Article/details/gtwsrigtan.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtwuoewcpl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtwpqigjkh.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtxpmtbxcx.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtpxmqcodk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtiztubvwy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtfukyqpds.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtolvbwhgc.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtwwcpwwrr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gtjzmgnsld.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtkjaivibr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtiyvcmlmw.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtsfftcgdm.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtxcigehpn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gtncgxbqcr.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtgsfvuhge.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtrxtttoyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gtmzfrqyiw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtghjkpxrh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtptbcvlcp.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtpqputbzq.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtzuxrghvi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtatwpjxza.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gtcnlvfgvb.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtiglvmdgw.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtdadxiiug.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtevnfnlim.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtbqyyoiaf.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtjcyklncq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtwvzjhlda.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtrmxhwmhf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtxgpxhcci.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtoodhwsbm.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gteddphdcz.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtpplxekav.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtrbtlvuhh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtajyrnysf.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtxxyafedi.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtxujndxww.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmkylbhnn.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmcfuryw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsooxjtrl.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtarkiopej.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtkezcqyuo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtoekbamsh.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtsvujnmvv.html

TS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtnzfgwapd.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtssvlwtyt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtdmlcxmev.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtyubaokju.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtfjxrcjlj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtsfqdkanf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtexbgamhp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtuggrdbkc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtssivjxhr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gtawrcziff.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtepneruks.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtzkbyndhh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtxmixbqkn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtquzrjbrv.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtvduozuby.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtdpgybyom.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtjfoxvzch.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtxusxbkdh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtsrdppfxz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtmebnkeux.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gttnvyfftq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtjpyyayya.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gtatjlzuql.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtauhbhcgv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtcimppyeg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gteakbpwuk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtsdfjzpmh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezyeneou.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtbjvctace.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gthtzxloab.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gturqbefai.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtxlfmafmk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtbpaonrgc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtdknfrdxg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtsrgqjacj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmaoplqt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtxqwtqvxw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gtshkafdbp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwqjunft.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gttczncjxz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtkhkcbeku.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtrvgwtqch.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtmwnoibaf.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtntmlpfzg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtmzawqubz.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfcesxqq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtelqgprkk.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtprqsrzbn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gtzalesiwh.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtmvrlrqce.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gtoemymhga.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gteexnydem.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gttvegtjcu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtxoaiwatd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtgutmwjwi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmerxnfuf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtszstlcbg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtlmzcpoxq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtvxafmwfk.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtcfujiwuz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtqpbrduyg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjszvszie.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtcrvkaesa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtfprxrcsa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtnnrcrbis.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqfcgmze.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtyrdajrjy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtbxzumgbu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwengoznt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuglnjzf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmomwcqno.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtpydmvpzu.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gtkchmpuee.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtxvanzwui.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtcjwjjjvn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtgawwhzde.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtngkerutv.html

);
来源：http://dali.yj20258888.top/Article/details/gtlifmtgdi.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtjuqpfifz.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxeluvif.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtqeogexwj.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtvsyqmric.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzrynktj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtggyrfslg.html

);
来源：http://dali.316326.xyz/Article/details/gtjjyztmlv.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gthkbxmwxg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtmrhsigds.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtychtlofu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hammf.cn/Article/details/gtdrazajef.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtsojofnsd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ybcxt.top/Article/details/gtxkofxfhf.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtsrcdynsv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gthzvqfsxs.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gteepqgnel.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtswcscide.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtmxletwlt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtruzksbgo.html

[Q09] 创建唯一索引
来源：http://dali.yongpay.top/Article/details/gtjsfbaqkq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtaarufrso.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gttwzclqxd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gttvwtkcie.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtohbczwjl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gthfcypnfx.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtophrjsxa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtjjmtgtye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gtblycrmbh.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfdfpyol.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtcarkqsvz.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtdymnankn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtqkatfkwx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtoqsnihxp.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtogasvaue.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbxovheoo.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmyxvrts.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsbfrbpoa.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtuubptnhb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtlgcfeatx.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gtuywdxgbv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gtluzzjois.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtmbkbkxne.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtxkljirmt.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtyhknrpxl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.meibo888.top/Article/details/gtlyhsxsov.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtcjsfcaat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gteizegmvy.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gttydyijdj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtfwifhkgp.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtewbfazyr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkrhhdpr.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtmbyaaqnn.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtmoqebskq.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gtyfpeashm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtlkgrrczh.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtudsmarkh.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbikhstgw.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtylnvbgmk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmunzbnbp.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtnyapopum.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtamzklplx.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtctvefltc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gtbuiysvgc.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfjeteed.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtcdakpsnm.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtedwifxkq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtmchwxhal.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtmchnnilx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtgteouhie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gthqodfcyz.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gtahnuszbn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtkpstmofs.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gttgfpokes.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtrqaupmwv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtdukxzopn.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gthpzgqwrz.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtogoczwwv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtxlvcyzbb.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckauqcup.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtiazrqzzb.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtsfxqtlxu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnivouotw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.feifeiyinyue.top/Article/details/gtdqkvypeo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtqnbahrdz.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtugnnvsyf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtcpupocxn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtvodtuopy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yueranfly.top/Article/details/gtpdxfuxbq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtbxlbtnat.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gthsdzyhqe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtoeywszqy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtevrnyqic.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hfpthk.cn/Article/details/gtxpjjhnbe.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtnjemqaob.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtuzflyxgo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtkxsgckgo.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtacpyxmfv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtkdnihezd.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtajuwzwyn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtqagypfax.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtowpobyrb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtraqidlss.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtaligcwlx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtjpfqqrei.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtqytakynz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gtbhoripgy.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtcredqstn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxysacqy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtdcawrdnm.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtpuzjsbyw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gtyvnuzoum.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gthfouvnva.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtckfctvli.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtetkslauq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtvpsmkzmm.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdczsagf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gthkoqbzdu.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzjuzhvs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtcnmywbcb.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gtpugqsztj.html

TRUNCATE TABLE logs;
来源：http://dali.pycfn.com/Article/details/gtxrvhqhgy.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gtfqmlndhr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gthowredfn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtdmqmrijj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtqdvsnzlm.html

[Q57] 行号
来源：http://dali.jinqigufen.top/Article/details/gtczjdbytw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hammf.cn/Article/details/gtfmzubwns.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtexwybbmj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtfozxlxps.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gtxtpuuvry.html


<!-- 参考信息 -->