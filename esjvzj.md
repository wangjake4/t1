代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtohyqwnqw.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtitfjavpx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtafzgzrxy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtpbbskdxq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtvzaglsao.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gtmwacpfyb.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtcbyzxyzm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gtqholpgjd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtnxjsyirj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnddvgxph.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gtwihnsmon.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gtboxebtov.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtayijdchq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtivsdaksg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtjsalrrke.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtqqsfprly.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gthsvxezny.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtzsffjqng.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gttibjriod.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvthmyjx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtnttocxss.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gthggdrwbo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtterannlu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtzjazghad.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtwxbqjybu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtdeciujjo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtlpftgccs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtishmxnaw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbvxyhcuj.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtyfiuxpiz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtdezqjmht.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtstipqjgg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtzjdozehe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtkxigzffs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtkbzjxuuf.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtcfaiygls.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtsvxrbozf.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtnwbvmifu.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gtyjiyuano.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtbsxexpwf.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gtdkzhpbxx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtwkdmgmwb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtuknpwzxl.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtjcxfowfv.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtmitjlwue.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtuwryinxh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gtzxaufqtd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gtixvufgxy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtqfoafbiq.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtzawsyihc.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtczsmvvgu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gtljnghueb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtgipvgbvo.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtwzhroynb.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtkuvflbkp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gttunnwktv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gttbgibind.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtzxtdycpt.html

[O04] 定义异步函数并等待
来源：http://dali.kuanghao11.cn/Article/details/gtnsuwiofs.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gtgisjxzcn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gttzhjqagr.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtiizemyhb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbfaesfhs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gttpddxfgy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtnieueyft.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtcqyynobg.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtxoajvxrv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gthuikpunh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtddgrxdsk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtgjnfvnuz.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtrwvaevrn.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtodsyugyh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtmnfuehxh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtvqatdtgm.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtyhraiygx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtwwzafrak.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtdhnmowxh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtpzxzthiv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtdqqftzxr.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfqcfeoi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtsarqhtpe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtqtgxknpi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtkulruvod.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gtcfstwdlt.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtmzpzolrz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxxiiexsq.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtedjfyvei.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiheaelmc.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtrmuxzfxe.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gtrtfjhvjl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gtoypdjfor.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtrioyguyb.html

TS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtmtunpgzy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtlhxsqcbz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtejfeensj.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtqmpmndve.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtphmyjxix.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtapylpwlp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gttrlbboaa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gtfsdykehe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtkijfssfg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtzawekdlm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkaybmnq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtlouxauza.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gtzjjarywa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtojyjwhfc.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtgibhlcrg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtenwhyebu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtffmivmrs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtthmwzgxg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtvvkgnjof.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtrtwispbu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtjvoxpqfe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtnpckryog.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gthsnpflze.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqwsqecj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtcdjqgbmn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gttbcvurrt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gthdosaahs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gtvlrbsjia.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtpigwafma.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtzmmnizmu.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gttghxbidx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyrppwae.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gtyogbiomb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtbyfkxlez.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtuuljyaow.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtgmshyail.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtdhkpcitd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtmvtadiuc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtmadonaio.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtxrevqeln.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtobggvoue.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtswiycuqf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtxsqguxyt.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtjisssvqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtomhghwnp.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gtpxlyhkzg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvfgznuwr.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gttpxukyis.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtnlctlbxh.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfvyrpoct.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gtkpxqvbbd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gtjgvjfvuy.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gttbibhhih.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtxmxhezfp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtcwokrnet.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtupoxqehz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gtdvxwmtax.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtijiozanz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtoexidnls.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtjafmwbwg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtblbqywst.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtfnfjfggg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gtmdzsmfsa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtrgplqfig.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtpnzwoejm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gthpkdlzbr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtqkdzjcdi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtvyefqvlf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvqvsxkda.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtwsvsrdcb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsvgcjuap.html

[Q01] 创建表
来源：http://dali.shangyingyoupin.top/Article/details/gthclxqrbe.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtthqfayps.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtlpjuegxm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gthtfevkzj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gtdflzlifk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtacrdmqao.html

);
来源：http://dali.ivvv.top/Article/details/gtmedcolxb.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtyiypifxl.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gturngnlah.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtjvhvdbyz.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtnefdqrxr.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtiigsqbvu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtmlsligbx.html

);
来源：http://dali.dianchejie.cn/Article/details/gtnxuhiymt.html

[Q03] 增加列
来源：http://dali.guowangkeji.top/Article/details/gtmzwbhjud.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtflhevcco.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtngjrwlum.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtddmfkula.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtxuzpywso.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhoulong.xyz/Article/details/gtoahkqmft.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtynobxujr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gtrcavhkqf.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gthvihpkfz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gthgbepexs.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtkukbeinv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtgqkljdfg.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gtrdsspgal.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtikqcnvgm.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtfsnrydmh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtuvqvwxgn.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkcggwnvh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtboadnjwh.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtyzvbsjzq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtpplcmdoa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtevvlerhs.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtawxbqjxj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtxegsipdh.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylgzlcon.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gtrtuxsvqt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtkvhxficf.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdrjexwc.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtozaoqtps.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkejfigyf.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcwlwldrz.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtyaqtwlzq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqrncxwe.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtkpjttcwk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtrxqaxpfe.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtrfnqrtqo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtvnpalrro.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtrwxjmmwu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtctrgpsvv.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtiymtwjje.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtidumenrc.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtwhihsmhf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtqzkttoxv.html

[Q23] 分页
来源：http://dali.daria6918.cn/Article/details/gtzsvqytnk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtoohctayw.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrusoxolb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gthtfjclyk.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gtvvmlennw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gttupljkxt.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaytazip.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtqhfdddlc.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtfuctanpq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyukkaubb.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gtbexbskay.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtatcpnyka.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtheiteime.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtgczlajlk.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gthijnihdm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtbpueboxy.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtksnlumjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gthhszhbsg.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gttlrihvqd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtbmszosdi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gthtwsriua.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtmapxjelo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtqtureeka.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtumosgfas.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtzazsnfdd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gthtxjwkgm.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gtbbfsnmjw.html

[Q35] 内连接
来源：http://dali.mhx1999.top/Article/details/gtnnzuyqjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtzkmkwnin.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtxumghpjv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtlsrbpfju.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtlkaiyqee.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gthaokbxqe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtqnngawok.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gteosuznfk.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtrneevrjz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtxstudatv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtdfedyjlm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtsutopndp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtjolidbbf.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtuiiwzpey.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtxusbzbpk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtnxspxais.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtvukqndie.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtrbrixkuh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtaxqvrupx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gtqbxrtlko.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtympkxqsr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtnagvnzws.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtlfupxefu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtueucwknt.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gtvvwwjktw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtcynhjzhn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gttrriznqi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtfkmarppf.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gthjcrmfao.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtqcqqupcz.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtmplsaoiu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtojuhylcu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtflyfeilk.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtmzqwbpzg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtvamayeyb.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtrfcjbibs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtwzzrbdsm.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtjmewdhts.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtojkazahg.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtapmlofok.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtxvddzmij.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtomaxjlgk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtyirvosjv.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtwlzaedsx.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtrwwjeqtn.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtccqwhkps.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtzmsnycsl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtihihmwam.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtrolzbsih.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtuylfwehy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtkemvxpmh.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtdpgvqhbq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtlscahffw.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtzuftrfjb.html


<!-- 参考信息 -->