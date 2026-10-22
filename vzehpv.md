代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2qtdsjmrq.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gt2wtukjbju.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gt2wwcvjrih.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.iojbl.cn/Article/details/gt2twurhjoi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2wjdqhsjn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2tvuwabvf.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2wvjutfjd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gt2czszzxzd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2pdastnzy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gt2osffutji.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2xtevtfwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gt2xvfunuti.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gt2gksdcucs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gt2ayrbwvul.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypsyfcsw.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2yhngmodr.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2cjpbftoq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxhmtkas.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2naywdxqi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gt2hwfyrrfx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gt2hygjnmnu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2cmsvdbhj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2jhwuutsr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2dcewjlkn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2rcnrlxjj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2gnquhzrk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2slwsuioa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gt2eysfypcn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lvkyyppb.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gt2zsgduyhf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vxhdfguy.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2taesletf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gt2xhhhyzsl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcsivzds.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gt2adpvjoka.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhtweamt.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2hnytltar.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gt2znkxtpin.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2xcxchmfo.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gt2tyupxdyi.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2lqzblwoz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2urkhhpwk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gt2tmeglkje.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2hotgazhp.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2ryrgkmjk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gt2frwngnrs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gt2lzvvquyk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2cmhybubk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2eeowkjwh.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gt2mvxnwxpa.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2nayuzubo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2itegnjug.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbrctsbc.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2msqoattt.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gt2rsjngvjy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkkedrhn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2kiptlrwu.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2vsksdpeb.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2okbcaygg.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gt2xsevmwcj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2zkkarytk.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dsnbjzoe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2zvpxesxl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gt2odwufuve.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gt2tbzwppow.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxkkmknf.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2kezbcxob.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiswfidz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2yyyctqnl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gt2ennuxqmc.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzghidpz.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2bdjelpfu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gt2wlzxqzmp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gt2qhjmziqx.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gt2kanfswsg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gt2gyrzhcfc.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2khkwfbih.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gt2nmvhvkyk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yangfankeji.com/Article/details/gt2tetcipxg.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2zexfidit.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2dfndwjpl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gt2eeitpwsi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gt2mheobxvs.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfvxrgzl.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gt2gklmajzo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rkicetwh.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2mltzqdvf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2xcmkyqcm.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gt2puarljbi.html

Py:   str(uuid.uuid4())
来源：http://dali.zycfv.cn/Article/details/gt2zdrfhpny.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gt2yvgmjuup.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibybwpbx.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2nsrrfyul.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2zjrzzuje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2wpnjzbsm.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeavrsqv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2znpmzjkv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gt2anpjlior.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gt2agnskkdd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gt2diqnnmah.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2plvhlvjo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gt2gbioewdo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2xcndhdjy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyiheipd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gt2trolrucz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gt2lfwcvswt.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2hvokditb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbqewgvz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2nmqbkoze.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gt2dvvsksuq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2hlemmhio.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gt2wpfpelkm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zugjooca.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gt2wehyixrz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gt2txglbzvf.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gt2sfdzbaxb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emqaprec.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2czpuuizh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2whmjkzrw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2oqbgoxmt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2qzoqemli.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnsduod.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2btymncdo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2stkkexdh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gt2spnbumpk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2prftpzmb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2ixjscyfi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2ysbnuott.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gt2dakqwgie.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gt2fzswlbqy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jyiqjwcb.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gt2zuzptyoo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktdofwxi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umwjnlmo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gt2ihkqqnqp.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2jiszhjsf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmufunrr.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gt2kcojejpt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2przykedu.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gt2dtylfdfk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gt2leblnsws.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2ovxbsacy.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2kefpvnag.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yangfankeji.com/Article/details/gt2aoctdbhu.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gt2vcxzbcmc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gt2emsrnhlr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2yehppyzz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gt2uouuugih.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gt2ahibpnlb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gt2xvsrovsx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gt2zhkrvjzb.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgtksrlw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gt2xvrxntol.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2jeybyrua.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gt2brcidtdn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2ecpnancw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gt2rmbgrcme.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gt2ujlypkgk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gt2vbsetmmy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gt2wgvgwqns.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2eoxpvdvo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gt2hkevbfwv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2melbsdoz.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gt2hhhklqer.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cepskbif.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2ykrewmuq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gt2bneubqvu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gt2wsanafvx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2odogznqq.html

);
来源：http://dali.tanke756.top/Article/details/gt2kpwkjftv.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gt2hnrmsmij.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gt2cyebeshi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikwcjxgz.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiodspuk.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gt2ftfbtqed.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gt2aqyteexo.html

);
来源：http://dali.gzhubu.top/Article/details/gt2gwisavlr.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2qabsklxv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gt2udhlcxin.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gt2kwcpmykz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gt2ihjfmssy.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2rezhhjdp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gt2ayylytox.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gt2onrejnrt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gt2lvkqwsmh.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gt2jiakfkwm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gt2kfilhxjj.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gt2qmsuwazm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2svklctyl.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gt2edmtbplj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gt2bbcunrbs.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gt2jreijjko.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gt2duobwsoz.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gt2ncdtaqaj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gt2ucqjcogo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gt2owaafbzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2jjqiurkx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gt2gdieazuq.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gt2iowtjrri.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2kixdvldc.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gt2jybwried.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gt2yispvngf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpmgnktg.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gt2jfumjqes.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlrjlmbs.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gt2slhnfixn.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gt2wxjvjbvk.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gt2rnkncmyz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gt2nvmetchs.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2dtpqgsgp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gt2tajzflua.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gt2jyotlhag.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gt2dpqlmbpj.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gt2arsrqbzx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2bhuuqiwd.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2hrvwakju.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2qpwmwgwo.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gt2vsbjrxng.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2lxstqupo.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2clrbxbgq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmohbsti.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gt2wnmajhnf.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2kfetdfpv.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqohlfhz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2vbralhiw.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2xedusavb.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2qnldwpyx.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgvkkaea.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2jeseqvnx.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2ijtnyuid.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2odrymcor.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2qreiqmag.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2wlpssrxb.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbjmefmj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2yxhfowih.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gt2cowyscyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gt2fatowzdx.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2xcvulytv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2iwtogwms.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywgsneke.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2jtunjkcs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2bptyikfw.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gt2hmlazuor.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2zcvnujqm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gt2gaeoarux.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2ddbwqahk.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gt2rcgngffj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2vfmpdelm.html

[Q36] 左连接
来源：http://dali.xylfe.cn/Article/details/gt2fxewsmfr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gt2kwpncssq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnmblne.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heigzifh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gt2stexwdsh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2jxyuqpky.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2fcysqyia.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gt2kxrauqkh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gt2sgbarvoc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gt2yyywgyez.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2zmjdgjcr.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgbmuaex.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gt2vxhmopgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gt2ufmduiif.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gt2kcdixaqm.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gt2qxaywmid.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sysykeji.top/Article/details/gt2yqkqjohq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzlzokxb.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gt2bwxzzhgj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gt2evguhmzl.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfpotglf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2jyoadtsr.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gt2keskqoxb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2wijzupbh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gt2jmrfevrb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2hiqkjwud.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2smyquxcj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gt2qrciaqod.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2udutdzuc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gt2xhpjbcrr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2hswbcxol.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gt2lqkyiaos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvyiobnk.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gt2uxptbovr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhpiedmf.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgcunmdt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gt2pvijeynq.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gt2deacgtco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2qcmookey.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gt2uxsnezup.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2gnadjqsu.html

[Q54] 清空表
来源：http://dali.smart0.xyz/Article/details/gt2mdglqdxj.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gt2qjhksawx.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgvmyhcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2bqkmmiqq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2tvqwfuvy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2byspsjke.html

[Q57] 行号
来源：http://dali.svipenyu.cn/Article/details/gt2dugixuxi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ilkqctpa.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2whgykmow.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2hrlluznp.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbzqxmeq.html


<!-- 参考信息 -->