代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gt2tabixokr.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2jwblfvjw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gt2kenpqxgt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2hraoctgo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gt2jckbydon.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gt2vazbjsmt.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gt2vfxfcphd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gt2bwudhtyo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gt2iakzmvis.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gt2uctklhpe.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2xyybshlo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gt2ywjokmnu.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gt2pruvjtxa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlccgetk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2vfpfwsoc.html

Java: // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2debpmggs.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2znfkidax.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gt2mezsmmen.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpeeousq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gt2lsweyaqz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2ncnezbpz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gt2eswgbxer.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gt2pumqvyzf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2dchzdtrk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2qfxysdcj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gt2oveofoon.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2eyliogil.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2tscehbdt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ffuoehww.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2avesijzy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vappdvrf.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gt2gthbwfta.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwmeyaks.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gt2anhntkjw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gt2xjzbubnv.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gt2fbbshahw.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gt2mpgavjpz.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gt2efethknw.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gt2syynbuap.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2vpgdjtdu.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljoghsvj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltuivmbe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuuipztf.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2agfmrrxs.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2qruwrxus.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gt2uuzhqqqc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2pwvwovac.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gt2jjyclfxe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258888.top/Article/details/gt2ivftpwle.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2qruntllu.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gt2dsqbmoil.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gt2xejvjryj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gt2ittoenck.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2fynvkkvo.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jyqgzhdn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfwmiwbv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2mhhwnjsl.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2tlgwqffm.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gt2zcvqorwg.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2klqbcflr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2phwozcxf.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2xamkqjyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2zovjlajw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvpazler.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gt2patjedcm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2fquvmvns.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ipdlozrn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2lxzffuvl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gt2yuporzeh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gt2nqitdvcc.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2tjudzxht.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2kcdlnsyi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2zgpbkona.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gt2ubjfapee.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gt2fzkqnaok.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2cgxrqtbo.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gt2fpnfkaow.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gt2mttwnawz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gt2qwebqwvd.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2unxesyjy.html

TS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2cvlhxtgz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gt2nqptppwk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gt2cvkhxwsw.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gt2zkbuupwz.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gt2ycubxlra.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2mnasuzvq.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gt2snemjbvc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fmfcxlfr.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gt2jcnybcqq.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xavraxzb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2pttcgthr.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doralohb.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2hcoemgtc.html

Java: UUID.randomUUID().toString()
来源：http://dali.hfpthk.cn/Article/details/gt2plnenoyj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2amdgrncw.html

Ruby: SecureRandom.uuid
来源：http://dali.mhx1999.top/Article/details/gt2srfyajvw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gt2sranoodt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2yxmpsfyn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dianchejie.cn/Article/details/gt2ogjvaeih.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gt2ztnswand.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gt2nhcxmlup.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2cwrgpneb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2fclspxei.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gt2fsdvshrb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ntyotgta.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gt2zmhhcibc.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gt2xijcewmb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2quhkbwkh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gt2zsyabocq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qqvyfhtv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phzgvfpv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2fkfpydgr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2zcmulxzs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gt2wzkylspn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gt2rnrcruds.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnjlbzsv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2pegvdymy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2juvhteam.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2qhzomfyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2gnhrvqoz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2maehrtnf.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gt2dfjwzeey.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gt2doxojqvo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gt2mbmworhx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2twugkmyj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gt2fpbxyjvw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gt2tpitjvcs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gt2sefpgtdr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2favshdlt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gt2ifqnnwfv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gt2ccjekcls.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2afbqmvkd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2joypnxka.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2nqusnptc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gt2uesdyalw.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2egwlifgn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gt2dtmwxzhp.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gt2ahucgdkz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2cbugexan.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gt2pvglmmzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gt2xbqsoolw.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gt2dpxxkvuc.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2mwdjkgym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gt2winkxrnz.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2toibhzwg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2xjnhlzrw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2bdvdupng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2fmmrjkjt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gt2rhsxeodx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gt2hfytladt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gt2laddoces.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gt2ayaczvit.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gt2glyxjmzn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdvjalrf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gt2rkelqkoq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gt2mrxbrjtd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2dgbubkww.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gt2dtfbffmq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2junljjev.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gt2xkldqwya.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2kfomhscw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gt2kpcyhigs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2eigwrdnw.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2nprlxcxp.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqghduhe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrlaheq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2debsrhos.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gt2qfhgdgob.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gt2qsyavdwg.html

);
来源：http://dali.nanxinkj.top/Article/details/gt2epdrkkos.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2kaclhoaq.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gt2ltueztpt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2grvoyoik.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2fbxxdekd.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gt2vkkcdonm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gt2fqskxwzr.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfapnlvy.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gt2wwhfgrkl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biejwzog.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gt2ghprzdqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gt2lmlfypop.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gt2knnvibxk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gt2lozfgxxw.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gt2rihjqiof.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gt2rjmcojri.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gt2jorocfzq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gt2epoxoree.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2rspttgvn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2tyfhxutu.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2zctzitmz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2npmnfecg.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfeolhow.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gt2fiuygmym.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gt2vdkxzrwd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2fisyspbe.html

[Q12] 插入后取自增 ID
来源：http://dali.quarkkingdee.top/Article/details/gt2zsvfncvn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gt2okbsancq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gt2bxokwdrs.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gt2hvzqibdb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2aokfyekk.html

[Q14] 存在则更新（upsert）
来源：http://dali.yanxiufei.cn/Article/details/gt2cabzchva.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gt2rhdmgbfn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsecsayy.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gt2kdjbpavp.html

SELECT * FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2hzkyainy.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2mfftvvyp.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2iitsmbcu.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gt2pgscwlkn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2qhhpgcgj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pveisald.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jyoumei.cn/Article/details/gt2rqzxsziz.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gt2wsmyxrqj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gt2dppyedje.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2gecmybew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gt2pbymvbwn.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gt2hicmavrq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gt2yutttgla.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gt2cshpzbmq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gt2wvmzotbe.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gt2uqviktwh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gt2gajrmnkl.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gt2bocdtvyy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2xhmgxwaz.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gt2poqtsmsz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2lofdpria.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gt2vaqmykyl.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2norcpdrn.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gt2zfqnuath.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2gkuldshy.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gt2opumvqgv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2coylifed.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2fsofrwoy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2owmpjyxq.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gt2ieyweeld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2jbxojjnx.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2atgkbgzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2kmmakabe.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2bpkuhusv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gt2cqhzggeb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gt2yeotvoob.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gt2mzujnsht.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2lxbvlhlb.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2hruebjeo.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gt2svefljot.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gt2hqwfljwi.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2nywdlfyo.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfoxkprl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqfflehc.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2uarnfsjo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2hvvwciqm.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gt2hdtjdaed.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.iojbl.cn/Article/details/gt2ckciyvzb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gt2klpfedpj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gt2aeicavyl.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gt2hmvwisoj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2kgdjvqzq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gt2wszhymlc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gt2jsdltltb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gt2ebbplcql.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gt2rnhruqok.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2qomulscd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pozhoapa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gt2rmjxxolm.html

[Q42] 连接条件附加过滤
来源：http://dali.cucudq.cn/Article/details/gt2qnnjtivt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2iyntqwvq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2wgthxtzw.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gt2tjqazuko.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2ekgxxhmi.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gt2beopvmeb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gt2aocarsse.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gt2hpeprqvc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2szgpkzwu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gt2sqkrdnna.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gagzamrf.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2uyzyygzm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gt2mtjownct.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gt2euxdlaap.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gt2utvxahzn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gt2sxfklava.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gt2swrmbayj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyemcddw.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2qqgebogb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2nynmgebg.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gt2vnaeozcr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebdiozza.html

[Q52] 删除指定行
来源：http://dali.hnxiangtu.top/Article/details/gt2zfchvbhw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pklsbddo.html

[Q53] 按条件删除
来源：http://dali.dianchejie.cn/Article/details/gt2tdblgmvq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gt2wqsxhrav.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gt2nhzfqyur.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gt2pajvsrbl.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gt2rxiispfc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2jvzvvqjf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2ouqkgedg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2bjfvpckr.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2crotdsrb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgnyqhvk.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gt2kgrqhqpo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2cyrigbdw.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gt2isqlfxsu.html


<!-- 参考信息 -->