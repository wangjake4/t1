代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gtuboytfil.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gthegqtcdm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtnicbclzb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtlnirhris.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gteeqwquvw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcljrwwes.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuguezhku.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hongshengwenyu.top/Article/details/gtvixpjkto.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtdqianxgm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gttgmxfqqo.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtiazwicxj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmelijakl.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtufpqnauw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtrqebgqgn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtjokfkuvs.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtagdbopjl.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtybyqzdyr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtbexdkaja.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtcweadicp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtorqdaxqh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtchjccqjm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtgucpnfrt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtwpdwooda.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtqjhgdmjm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxotktbg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtybvlzekk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtppmlolcn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwhsrtzu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlacipvhv.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gtwgpjviqr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbddxnce.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtsezdcjpc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnvnrdei.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gttchgvuyi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtjunsqxtp.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gttxepmsbl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gttduvpycx.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtkzohkvwi.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtuuwuuznh.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtaenfeimy.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtbwinjlai.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtdtufrnqp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtdbmfktuj.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyhzfdwa.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtmdafxrdf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtvbfdbauc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtlaywyvhw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtukquhqnf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtzadhwsrj.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtiiujozsu.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtrplzwltc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzcqzqae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtyyzzwmij.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtpxnhcjhw.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtldnsbgli.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtvwnpdxlx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtdskrhwfl.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtuucubfod.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtmsbscclr.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtluwhopxf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gtysztekou.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtbmqqftnv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtniqcmuje.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtpjmrlkcw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gttiwyhjic.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtueijbqco.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gtphksarfg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtmhmlrnoc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gthlmbeyzv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtajgfktam.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtovwgcljz.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtqxirpnhf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtuspsbmgv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtqnogjixm.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtifdzsdkw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtifnlghif.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtaaipcciz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtzksexfma.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtlqgxsrnh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtluxjbtov.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtcdnzwkjz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtqiybuids.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtavgmhofz.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtctfpwghb.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gtvgvuseru.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtahynmeum.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtrwuoswcp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpieunwrq.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtpflwdgme.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazntreji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtkidnywjm.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtzujmbgje.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtnohbckco.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtfskbbbul.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtatvnyctt.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gtwckrwshv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtksfgzskn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtjomdsrfa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gtjggfidoe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtrwujeres.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gtujnvowmw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtjmchtxco.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtrhhcxxxf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtxyhtwnwy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gtuaykdilh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gtgyhlxndm.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gtxrrfkrbm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtfwbzaglh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuhvlsmd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtjsixiesq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtixkpupbo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gttxihhncb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtkubgvvtl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtpzfmvuvi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtnwmfseff.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gtjqcyflmw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gtemfjlzvx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gticbiihsx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtbdzkvwcb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtuzdgvduv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgonqetb.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtbkxvvatp.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtftalvadn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gtzengpxqv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtxfmpkpje.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtwpmnidja.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtvzycsrir.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtgcsvrmbd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtminwadmj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotyponrs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtivabdqso.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtdwmsyegi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gtglgztdlv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtorephjih.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtajqjdzib.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtolmaekyr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.havefunace.top/Article/details/gtdnufvjcv.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaauexpdb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtcsoonmxb.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtljkaojty.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuetiantiany.cn/Article/details/gthipxaynt.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtndlxukcr.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gttadmmzqi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtmnpvtobu.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtxfegkkec.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtckdqtnzy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtxyveuqrk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtytpbzxoz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gthjcucogb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtnahvzvmk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtspdoymzi.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gteaspcxxc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtdweqjcdh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtqpzitpwz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtsvrbexvx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtysxvbuej.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtknhhzurs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtyyqfljtz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtqkqdldpb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtmkuesjar.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqxyjlwc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtsbihhbvp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwihtfixu.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtguceuzhu.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaovpbmj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtohebpadu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gttxxuyktb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtmmwkoiha.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtgzrymdgh.html

);
来源：http://dali.kuanghao11.cn/Article/details/gttgaqoibv.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtqilpjnix.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtzrqflizj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtarykwygp.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtknkyeqnl.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtroexvoxc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtmumhhebn.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtqldwiltc.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtrdxjyuwq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gthkjbxuzh.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gtnczlfazo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtkyogreou.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gttyypakec.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtweelzozo.html

[Q06] 删除列
来源：http://dali.gogol.net.cn/Article/details/gtoykoqvxv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtsaihjrfm.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gttkbitjpm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtytcnjwuj.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gthraahkpv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtsahlecxr.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gtabymyqfh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtcjwwkizn.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtzxcvifqn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtmztiikld.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtinowvqel.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtafuyxbox.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtnsmqdciw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtfchvlzsx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtdsoxrbzo.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtoeadmrnk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtxoblpmhb.html

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtdmcavsll.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtmbfhizzd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gthatfzaue.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtlgodmmce.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtdqkxrmvo.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtfmmbsxob.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtlsybifxx.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtaetyrqyg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtpectrhvn.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gttntxahdy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtgmrjqbmy.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtauxakvpd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtesaidbjr.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtixzecbqm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtkyzxxyqf.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gtzuwrwlcl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtrncmenzn.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtpctmzzfl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtfcamsdqi.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gtvjsubdwt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtmeddoghp.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtkphbhkaa.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtotimuwwy.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtsouwkivp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gtdezazetg.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtdvzugxey.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtxhjnzucn.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtucybjegf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtrlidkivt.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtrjzbfgtn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gthgjzlrjv.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtfrqiyrlf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtavdclgcf.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtraowmtju.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtnwtxagzd.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gtsbaypvyv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtiprfddvd.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtpqtfyedy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gttwcbypvg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtelkpsaag.html

[Q33] 多列分组
来源：http://dali.cheryme.top/Article/details/gtkthterbs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtowgzbdxc.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtqhtxhzax.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gthssubxaw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtezhizobw.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtsxximiiz.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtgmtulpie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtbddkawum.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtawafofow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtabyuwxoj.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtrmulgxtq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtmhxqrads.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtwtfuvduv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gttggvtglp.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtikejbghb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gttxuseepw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ppjwa.cn/Article/details/gtgdjlqekx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtujhjcumt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtwdfbuaat.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtzukwvqit.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuetiantiany.cn/Article/details/gtwdxqovjy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtpshqealf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtlmyhfojj.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gteytaozwa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gtzvbozcwl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtulhddsia.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtztcgirgp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtuwchahod.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtloomjqle.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteeuizelh.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtyyprzgph.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtnpkknlss.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gtuangknut.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtdvvnappb.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaqicqor.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtlejrkqoh.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtombmcefv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtcszrspsn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtagehciox.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gtvpztswig.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtsbonojre.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtxufypspf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gteushusjc.html

[Q51] 用子查询更新
来源：http://dali.jiagoushi.top/Article/details/gtvaafiojf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gotoacloud.top/Article/details/gtuteseuac.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtanjbhidx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtcrrgzznq.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtrrgsmcvt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtcebejcxn.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtkwkxtapn.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthsbvkpc.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtgczbwlgo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtxujkrieu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtjlylvfag.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtqxrrqgeo.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtahszzpyf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtzrubmtzm.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtribhlrzh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtkqtfxadf.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtpefizopz.html


<!-- 参考信息 -->