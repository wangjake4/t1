代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtbgtvkbov.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtvxzrqfdy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuqebbne.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtkairtyot.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtykkhcioe.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtwgrwdbdz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gthclzffqi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gtanvgfwtt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtredmpejx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtenenrswt.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gttxvcgmfl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtwbgylbyg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtvsipcnhc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtmuqaimxg.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtxtszygnn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyoejtkl.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtpmgwsmmj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtuqbnkugg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtlnyodpxb.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtwkgiktiv.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtodjetcvq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cucudq.cn/Article/details/gtzqjpzyqt.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gthnnuykjq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtlohwvhsn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gttuvpmupd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtkdkswpwz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtgzolpxwg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtjyjbrghu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtgrhaphyd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtmhosreiz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtkasndsef.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtysualaga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtescbmnrw.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtltppmbjs.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtycgcabsp.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtlsxcbzrt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gtsynwxram.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcobtraw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtplcfislu.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtnnltbrlc.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtumpjnhss.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtvmggwxdb.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gtykrapfdy.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtjxlfbunz.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtkzzpbsus.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtjkeokjta.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gttiukllvt.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtrntnfodf.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaudvvez.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtnvszdoho.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtksdgmmrp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtjqigfvha.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtjnwmsobl.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtjmvanvsg.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtjvbgdxkb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtnmkfgsgu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtpoyvblof.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gticucmsgv.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtxenyibgk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gtuytqcrcn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gthdtplmfh.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtfnzlapbm.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtgnivgcbx.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtjksbikqr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtdrwamesw.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtbtvsjfqo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtlyfvwhfl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gtlcinvpaq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gtyrouqkpi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtenigfbgw.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtqjwqfemm.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtvkcsppkp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtfkcpqpvv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtyoyqdpyi.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtievtdypc.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtqphqaxri.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtrlldscut.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtawesywgp.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gttfnzrqvm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtkhcrbmyw.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtnkxqrran.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtthevwomz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtzggrkfrp.html

JS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtbjcqequt.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtkgjebblk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtutuzxapq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gthwezwsnj.html

Ruby: // fork 块
来源：http://dali.havefunace.top/Article/details/gtoacbzlfd.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtelcvisuq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtekbopotv.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gthovjspcf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxiipsmx.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtloxaprnk.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtzqgpljst.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtttcemiet.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtskletdol.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtqgzbbwqc.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtnlaeuxeo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtphkamwvs.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gtqkuujefu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtyppfmwbc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtznwgilqu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtuwvrpuuw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtyxneibrt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtbdusktxu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gtydmyqncn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtzhqapwhd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtzzljkdnj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrosfjvri.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtxzqiyxjv.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtiazmyzod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtclockntz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtylflqmuw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtqsrtjavg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gtgxafyaoo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtmfjtjute.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtliddwemj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjkbvody.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtnsnsuuwe.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gtxmrrgcvm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtjiwswuzt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtxmmdwzok.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtulvguyuh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtliapxnkb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtpaqxhroa.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gthbwiflhq.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtdnipjpsf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtufcssgiw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtgdkucaeh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtcnexpptp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gteosdutdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtaazqnvfx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtqvgdqfbd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtxbpuqzhn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtndyortxf.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtdpfmathg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtsfosjlws.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtttbacmev.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtufboftli.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtobjpyphf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtyjrdrlxo.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtbritpwpd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtummdejry.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gtgnzsfrul.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtwziytcbh.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtrwyazolv.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gttobhjxlc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtxzlyjaxt.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gttaozxldb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtuxtvxiht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtxoencvzz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtuukkopzo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtmakqrzrn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtohnsvjki.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtvwqwssdd.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtocsllfdl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtvypkfaie.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gtdaervsql.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gtyiictmpe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtimyglwry.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtqxnblugj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtiognocqp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gtrmmcepdn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gtbfgygiwv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqfpysppq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtqqycgtub.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxoazoiju.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtjlxweqos.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtleqkobtf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtlokbwgga.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtdobcdwdx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtnhqwshjr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtjfprdork.html

);
来源：http://dali.yj202588.top/Article/details/gtgijzwcez.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gtjkfnrhnx.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gtiznmzyef.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gttfwzhafp.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtwejwddeo.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gttervrlnj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gtfrirlapv.html

);
来源：http://dali.ivvv.top/Article/details/gtfjlkojme.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtlrthnkku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtyalwneug.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtmcduwvtm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gtstsafurz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtibnxecbb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtmdosutub.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtdazylugq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gttcwrrqwj.html

[Q07] 删除表
来源：http://dali.nwbrower.top/Article/details/gtlgslsada.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtyzcwytcw.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtrwciydut.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtrduuhxmz.html

[Q09] 创建唯一索引
来源：http://dali.ivvv.top/Article/details/gtkayxfflx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtmnxiysbo.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtikbsbdoz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtkqqzwauf.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtpsnwvjrb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtikebgtol.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtwgpsbcyt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtrxwgehuk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtspdrybcz.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtzszpoeah.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtgzidisjt.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtqaskazbw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gtutomezvt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtvgsewtnt.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtsqritidk.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtldwbtzeo.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gtlopmyckz.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gthxrmqkgu.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtfhpuhrag.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtyoaxdujd.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gtdgrsqxep.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtyejltptu.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gttcmllwlt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtdguhejxz.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtmyobwmwd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtqtrndkei.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gtkvtnefwr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtdonvgikf.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtljbixaxd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtvmtmzbub.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtszqopjlp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtchyvbcvs.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gttqygbmuu.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtitdfkqpn.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtxzotdbdi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtimgtlnqa.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtbccedtdn.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbsgaqcfg.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtltefaeyd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtakpchmnv.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtpftuecar.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gttftoanmt.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gthmpxxgpz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gthptxtbkz.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gtmgimjrcl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtucoidzao.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gttzxxksue.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtmjduuxhp.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gthekatrxv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtegcgmhle.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtwdxjlooj.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtsrijkamb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtzibbfygb.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gtzuwwilyd.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gthkmazaqr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtmqthstyk.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtutxmrqxk.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtfpkqudgh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtpydipazg.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtmhcganvc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtzwytykqj.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhnifsdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtkyhmnbon.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtnjnpiptx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtncplhgvk.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtrcjssmwr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtjmrkxbhj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtsrdhgcoz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtnylonnsj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gthpucnqdi.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gtzvxfotpx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtutnymlhy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtsdffzrnm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gtqmaegdnv.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gthjaogqda.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtwxoztnxw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtpgdtlzwq.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtxnzlaujj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtuaezdzsv.html

[Q44] IN 子查询
来源：http://dali.zhengqikj.top/Article/details/gtsvlcffsv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gteomuzbfq.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gtbvlhzqkt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtirkpsvxt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtxceresms.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtyqfmkyhy.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtohxnwkgi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtckwjpxoh.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gtgfiijyhp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gtbysoaadu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtkbxlwnvv.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtqzkqaqnv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtkaqvezjo.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtzjwvpjcp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtdkggxemz.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gttequtbfv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtjlcbpzud.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtblpyzozn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtjdfkvbaz.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gthsekabep.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtgvmnccsn.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gtbebquysd.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtrlxhjmro.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gtbxswtbsv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtwclnsepu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtmtpoopno.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtiubkskxt.html

[Q57] 行号
来源：http://dali.aizwys.cn/Article/details/gtbzpezccc.html


<!-- 参考信息 -->