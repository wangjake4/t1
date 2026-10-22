代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtgtarfcwb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gtorfztnpu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizgcivlz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gteytagvdm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gtwuqiviyk.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtnlleyclv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtjnxomuda.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtvooyhxko.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtylhzpynw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlotqrmd.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtexxmsvqe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gtyxqcpyjv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gtbdvgjods.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gttlhdavbe.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtteugfirh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gthkhnzzcz.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtclvjmpuu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gthwgaprrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtieconqia.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtpizwidbn.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtbypahqiq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gttwringya.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtlqeadxkp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gtqadjpoot.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtlpwfxfdy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtkdjxyscv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gthrpcfqof.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtscysxqae.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtqlsimdva.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtnlgnhigz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtpnqrpkll.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtkirvexio.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfhphdibp.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtozfqjuih.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtopnojjcm.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtlmpxtrks.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtmurolocn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtxyxqdqot.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gtjzffwznl.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtrwlarhfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gtjycvkhrd.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtsosfonnl.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gtomxgtmuk.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtbghhzkek.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtgbrumjey.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmbccfqo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtcpahqugm.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gthrdkxgga.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtwyeeyldp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gtzegyhhnj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtpugfdble.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgznpnsz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hammf.cn/Article/details/gtxtocvipp.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtcbejashl.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gthjzobjiv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhuorhuy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtmzlxezct.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtfgpgmdbw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoiaysose.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtnvaphtce.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtxjrqylmf.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtcijbuowz.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gtdzcqwyiv.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtgyshklqw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtdigsbchk.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtgohpuryu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtgrypfbia.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtnehgzqde.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtxgolmwbc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gthqucgzcs.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtumyomiwk.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gtzdclbkee.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtfiealnen.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gtejhdlyse.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtbyuyecrf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtixjujkye.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtkhozzice.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtgikrqvxy.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtiovyrrjf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtlqzbkiya.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtbgjtnjcw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtxgbxjrdy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gtzqnrlhqg.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtjnjhxwlq.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gttegcegpt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtpzwhayjn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhldowhf.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtvojblnmf.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtbenrrykq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbpvuigdi.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtnwaxpdtj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthulgnvlm.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtzmyyahax.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtzlqgtnvf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtaudnnlxc.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtmnnrzsgt.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtarlazflf.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtvbwhttkt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtiovsabvc.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtftjwcqfv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtxpagckpn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtycmiqvbi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtvefnphyg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtzejjvchr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtpkacngwi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtiqqriltz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtnyergoah.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtgotjbzqa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gticuszzml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwhppnlv.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtequcmaoz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlecsmbci.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gtmmfwacch.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtnvwsmmox.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyjyapbg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gtygypzyoe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gttgkrtsyi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtsgnihtbi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtctjbdjgc.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gttjyinuyx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtrupkojhr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtctqpbnmz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtehbbfrml.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtmivxuelb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtwnpdyixa.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtnvaciukq.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtkdiftmzq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtgkethhav.html

[P05] 判断两个对象内容是否相等
来源：http://dali.smart0.xyz/Article/details/gtldqjmkeo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtlojanlkf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtownavxfg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gttoyztjuw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtwnwgvyzy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtwynibnxs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtzxogwgup.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtelaulvyz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtnsaalmdk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtgjdcbbwo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtccssoomh.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtnkpaezoa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pengpengdd.cyou/Article/details/gtggmmbqak.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtjfyvovau.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtnmadtmfq.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gtbxdxyzxt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtduztzamg.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtqujpcnji.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtvvwyijoq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtrnpyoudj.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtmivuiavp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtmdfgezym.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtabbuvqqn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtohbmqujt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xinyue.icu/Article/details/gtvneahkzl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtffazgayk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtofddfibo.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gtdlrodval.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtjbkhdbrc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtuzttpivz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtqanecyjo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlzmddrqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtionntlcu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtkutcgdhr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtrnienxmx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gttvjgfycm.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtbjduhdls.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtjrkqkbcw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfjlfehvl.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtxlyrbjhu.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnsulxoz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtqshrbykt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gthbavzlde.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gtswwfgusb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtliqsxvjz.html

);
来源：http://dali.yongpay.top/Article/details/gtbjgvzuzp.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtlieynogj.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrthtfeqw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtyyxtwpvb.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtwmwstzzv.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxmtrsrg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtrsihshno.html

);
来源：http://dali.yongpay.top/Article/details/gtglbgzwtj.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtjixhehbn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtobecuuvo.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gttvftoguc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtyndnltsf.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtdtnytrtz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtextocegg.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtiyduemsr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizcsuomo.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtomdriili.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtvycwrqyh.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtvffokdao.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtuywivxwq.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtygiokekr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtacauiiti.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtmuhhnvhp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtgbfheciu.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtcukwuzox.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtdcszulxe.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtrwikrjsp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtasgcekzf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtbsjqsyqf.html

[Q13] 忽略重复插入
来源：http://dali.quarkkingdee.top/Article/details/gtmsfpodfr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtyghsxmpb.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtltahpylu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtblgevgsh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtwtacatvp.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtlceyaijr.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtabvmtakn.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gtcsapefam.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttzecwmsg.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtayupjciu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtatfqpniu.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtsdzhavut.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtcstdrejj.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtycuwbsbx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtvazmzbqt.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtmndodycb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtddfaupzl.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtqnlogjzg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gthivwwxuu.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtrztvtlcq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtfoofcpsr.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtgwzrosqi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gtbvrtydjk.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtommdarlv.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtomhcetno.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtridnbrrr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gtseaowxyi.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gthmkxrpqb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmcxrbjjj.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gthjhdabvc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtnbxywgmv.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtovdnmgfu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtslbpxfow.html

[Q29] 最大最小值
来源：http://dali.gogol.net.cn/Article/details/gtmbyjfluz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtcnhksfvk.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtmtupyhkf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtmadonjbt.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gthllxfwqq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gtfysmpyyz.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtkzbrbetk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtzobhyihb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtkcloblfa.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtghifnvbc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gtbbrxldtm.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gtuznudxil.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtjxwiwrwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtxqnkhewa.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtqucqmfok.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtivxfwzsr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtynqfgqft.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtipupidol.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtrvxisklm.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtevxrvdqe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gtujedutnt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtmlerylud.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gtoiatlhgd.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gtinszajmp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtmmslmzik.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gtezlmeawm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtfgqorzaw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtzydjogkn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtvitnifem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gttjivsflw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gtpfrhoift.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtmkgowtlz.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtvuaaxsrb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtmqlwkixq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtihtvarem.html

[Q43] 标量子查询
来源：http://dali.haohaochexian.top/Article/details/gtowfqwjvj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtsttzafgr.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtwzrzdrgy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtwtgbdopc.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtvbclynsl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtvivaqsmo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtugahhvhm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtqabgjlms.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gtqimsglqo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtumxudkmn.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtnscamerr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtihugbcnc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjjzikox.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtqzcfhuam.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtixmsmlkg.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gthqjthulb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtklwygnor.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gtunafmkbw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daxiang520.top/Article/details/gtswrfgntu.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtxupdadde.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtqopoblor.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gttdnflntd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtqjaucfea.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtffewfotr.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gtcmeiagbk.html

[Q55] 排名（并列占位）
来源：http://dali.chenzaomai.com/Article/details/gtqhmkbgxk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtystphwir.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtglsvcjhb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtzblmavnx.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtcvekwnot.html


<!-- 参考信息 -->