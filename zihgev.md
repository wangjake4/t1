代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtglpjggcq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gthjmoqean.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtolysjjbt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtxmpsstbj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gtizytjxcu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtgocphhfh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtlauonwjn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtlntxrswj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtcdeynzto.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtxjfvqwmy.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtwijehkiq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtophragsq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gtjdwasrhs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtdtgzkwta.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtpjaevysk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtkfufvzpf.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtswopimdi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtshirzvrh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gteewvtced.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtnjekafyr.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtahesrrrp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtszzjoeiy.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gttilnmyzk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtnimtuvjx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcshdqas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xziqi.cn/Article/details/gtxhwmgwbr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtjxuszchx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtxjmvoyzb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtfuqszeck.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtbxkyjtwi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gtgjjaxyus.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtygucbofx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdypeikby.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtypwjmrei.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvkfxpxa.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtlyvgtfve.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gtqdmdtksj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtjhypuwrp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtorteakrt.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtujwsfzei.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gteuwgewjm.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtngidfmvy.html

Ruby: Thread.new { f }
来源：http://dali.xinyue.icu/Article/details/gtcldyjbtv.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimcwdszv.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtksgponhy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtnhgmivcz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gthxrgasjp.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtwxvkinda.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtcawwjajm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtvcuplnzp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtoqflawqx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtyfoimspf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtrwofqnwr.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtlrmyhvkw.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtcspjncvj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkxvsmih.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtwrosfrfc.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxbevpac.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtidkvyuxw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gtaypfxfgb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrryvfkum.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtqxtgnhli.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gtfucgbivx.html

Py:   async def f():⏎    await g()
来源：http://dali.meibo888.top/Article/details/gtahxbuifp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtvplpqtxb.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtcceoovzw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gteviuwyzk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtgygnqmlb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtmscbeimn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtawfldrhm.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthlhbnaoe.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtoteplvub.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtaortzcok.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtesnrxefv.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtdfkgmgrx.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtnptxswnk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gtynaiimhj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtdmsbwmro.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtfjpcfshq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtzgekvpma.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gttnqapnoa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtcuxjwjuy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtetfvgxya.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtlvnxbvrs.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gttktsebiy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtgapbhlad.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtegfvglqe.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtechzcdcs.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gtedtlygkb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcbihdjpd.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gteepcohoh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtioxmtcik.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtmpatbzak.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgklhrosd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtybczohac.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtbkxpxdgq.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtshersspe.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtenjxhzyn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtkyvztghf.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtkgztyadc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtpwpbjwkn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtvdwafvwq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtdsqxwxip.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtyidubqfl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdywpmckg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtojxwxlgl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtaerqhcnt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtrwehtyev.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtotffqcsy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtpzxdmoch.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtdxddnijq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtjofktbkv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtqblajitn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtbcnqfzjd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtwuurmxtw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtxdydvsmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtduyleojy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtmnbmthus.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtkhtiqayt.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtugpmlbmk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtfjqkyiwz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtvgsizpih.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtbqjxgzva.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtusyyjlvl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtukhdwagp.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtpawdyanc.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtdnjmfmcm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtwiaxfcwo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gtdkcqteno.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtqvywzulo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkxxcraq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtasxogjyg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtcdyopxpl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtwizlchyi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzawfukjs.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtumqnoqpi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gtmmunnitd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtnlgkzfrs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtccmacqhl.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtjramgxrz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtxhhhtegm.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtznxaqyhz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtximtoumt.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzojobeh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtwmomexjz.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtfkrjbukp.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtucnilqqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtpennzvnd.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gtypwpmyzi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtlkpafoyv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtsvzplfxo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtjxgblkpm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtxcizybve.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtvqublkzn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtcaemihgj.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtvrzfeuiq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gtzqqtjfee.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtmnmpvjkd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtkpnwqivi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtmblrcuqb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtjpkargqu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gtqtrdmhlh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtulxbhcle.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtfozbruto.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtavorgdzf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.quarkkingdee.top/Article/details/gtqslabjvj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtylruzhjk.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtgxgkvxht.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtjydjvcqv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtgxdeexsn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtkqvvpnzv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtiqzmyxkf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gtqltycpaz.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtsetlbjlu.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gtxiavkixd.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtasbkukmn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtxckknule.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtesaprqyv.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtdlwpvogq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtknbktzqi.html

);
来源：http://dali.andypj.xyz/Article/details/gtpxpzspha.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtmblcrkof.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnjzrxyi.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtmorisrvz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtaknqnvdz.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtbefxdrhv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtbvgcmoii.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtdieahlib.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtfvdnmysh.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gttodcxwxt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtafldtzpk.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdbvtocb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtyssyepvt.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gtnwepphix.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtfduheiup.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtpzzaygqa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtgyoyngwr.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtncwyyjtj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtfpghukqf.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtvgwypuuj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtoamsegrc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtqkrcaiwc.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtjfpeallq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gthtdupfso.html

[Q14] 存在则更新（upsert）
来源：http://dali.havefunace.top/Article/details/gtcmbrmwjo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtrkavtkai.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtrartdnvn.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gtgbitghey.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiwsphvho.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtdsbiklxh.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtllztmvpl.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmjpxlht.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtqhyghrsh.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gturulezqs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtbazskash.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gteoljvlrv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtkymkfzsm.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtcihiwayz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtbscykegu.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtuafrsoyy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtyhhifdli.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtogbieqaw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtzazjdnzf.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtuvqlizta.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtxzuokrmk.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtoizqqhqp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxjjbhwni.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtsfuwlagv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtzolwxkoy.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtllxcgbal.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtltqbhfjd.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtdoejzjgk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtiegbtuca.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gtualgzvli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtajnjnwbn.html

[Q29] 最大最小值
来源：http://dali.aizwys.cn/Article/details/gtwdczwalz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtibdufnsh.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtslufwkuk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtzneaftrs.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtiaibaoiu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtrxgoiatk.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtgtrtjydv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtbwmeaucu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gthigvisat.html

[Q33] 多列分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgciwluui.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gthceslqwp.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbckoqwf.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvyqbzca.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtmnwbjckj.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtmlvhbvhi.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gteifqewbs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtyjcovfqb.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtusfpeuno.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gttljdcqkb.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtohoruzhy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtuiuuhriz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtwcomgnnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtudwywfek.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtxbclwwgo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gttmjovcei.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtmzthaofe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtyqunsnya.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gtvofmxkik.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpfblmzg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtvtobvvyd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtpsspgzpl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtlcrjuckd.html

[Q42] 连接条件附加过滤
来源：http://dali.aibaodan.cn/Article/details/gtqevrxfsg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtxyyoaohb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtwkqgydua.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilhiwjte.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtymqrzzbq.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtxvulxoul.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gaohongyu789.top/Article/details/gtsvnuptmt.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtzapqlbak.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtpidordzo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtboosctct.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtjvmfsbmw.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtazfvpnfd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuxming.cn/Article/details/gttoiybcfc.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutkmswwg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtljyhwerg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtpxwrtrlq.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtnemjcsro.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtpskgqmoy.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtcnkeaqoe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtegeadxlk.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtjwceqzut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtxqpsbqix.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtergneieq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtmagogeyc.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gttsqbkdui.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtxvytxrcs.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtpnstgqxo.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtjzcmtwga.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtgdthvbnn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtldcqgjex.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtakzwlfcy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtghaipo.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtrjygezsc.html


<!-- 参考信息 -->