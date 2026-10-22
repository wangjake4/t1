代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gttmtkkywd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtkcnneamt.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtxelevemu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuanzx.com/Article/details/gteqvlrgyw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gthkhaaoyn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtjkatdvhl.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtvrzldybg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtnjcmwygk.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtbqikgydk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gthvxwnjvb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtksubbedm.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtlbvqysdf.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtueqfiewd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtlgicieip.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtqtgoqztk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ehwqpu.com/Article/details/gtqvozutmg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtfnyuymes.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtfftuwrcq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gthtwchwso.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtjtkslyur.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtucssuaww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtloktppjv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtijuhxref.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtubjtrhkz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtykiqzvwq.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gtuujthstd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyxuxxryh.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtgsiedtrv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gthoymgbbd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtxhjairqw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtczejynpb.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtityrjgno.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtytysnpth.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gthwuganff.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gtkqezhdbm.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtjwxxmbgu.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtytckrifn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtbefxznme.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gtxyeroups.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtbbwllovo.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtnyhlcrlq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtpqkfawas.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtjuwcbrbg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxyvzkye.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtezihkzvr.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtzcvexmbp.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtyylefntb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gthonihcxc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gthqakaheg.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtaebumtid.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtmydquvhg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtmyzkyxpy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gtnmmdlbcl.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtbbmffkav.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtvsgfftjn.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gtczmpjeiz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gteafvrywu.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtizfdyxus.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtsbwbhfri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtggjftaqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtttdqounv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gthraakedh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtwtijcett.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gtpafdbhrq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtgwgutlmu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtmnuqgwhm.html

JS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtkdaqwlwk.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtthmwvaqx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtmltrmqud.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtqcpcjnvd.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtxieznskq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gtpgawvtdk.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtgqqsdpij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtcspxxkrb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtebomzeiy.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gthmyctrwp.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtyxlxhkjz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gteblanubn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenjidiqi.icu/Article/details/gtmecraggo.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtubtbenql.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtiqepudak.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzaytftgw.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtzllrgszp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtypdeifjz.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoammgdi.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtuxvlgbxd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjfxqqnd.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtgfemstcu.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gttzgaetzs.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtvavckdmo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtoopjbliz.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtmadlcnrq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtojyudaof.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gteckbrfou.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtssffoddv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtzrmrlrby.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtmwavywzt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gttphjptem.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtruqygusz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gttvgoothq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtqurlwrfr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtbkfxkuwm.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gtvicqjbcm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtbfaccmjq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gtntapvmvf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtamtrsmxl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtjjathddu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gtlutezmvu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtcgtvrofx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gtegfkyqbj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtdodpkovk.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtufrdhqaw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gtziqjxfmo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtnzsygwnh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtunwgrtmv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtyoapaqeg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtrfwuusiu.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghrzqjop.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtmssqbcbl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtyifgflyv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtxyvyzrtz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gtgzffvxqr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtzcidpsoq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtabznuqde.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtkhykvkld.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtdgbwpesf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtcorypylt.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtskmuqqhf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtgonaougw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtzhkkaext.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cashguo.top/Article/details/gtmgrmdvwc.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtgxrcexwx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtppsgbugo.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmtztulth.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtadkoofln.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gthnowanou.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtopeeigeq.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtjtvgncdv.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvyhjusv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtyptntwol.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gtmgeitcuu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdtplkzt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtjlnpydiz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtycmzoiwy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtuafkfrcb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gthuoxhyej.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtmfocssmb.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtniythzfy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtxvkhndrn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtamlvhwfx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtyimfcuih.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtdfdxsmdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtvntprvfe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtcjfvakxf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtbadtessu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtmojhetvg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgpsdlacw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtipxtscbo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbkgglhhg.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gtjztyprqe.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtggjrjryw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvjsgxvl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtlovgfrhd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gtztkppfmj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtjwqipkce.html

);
来源：http://dali.chenlongwang.top/Article/details/gtlnwyjkpq.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gtmywuvgpm.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtywgeutpi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtypdtfhrh.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtlettubjv.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtslhvuwgb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gthaiecuwl.html

);
来源：http://dali.svipenyu.cn/Article/details/gtvcpviwij.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtlkddziob.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gtwdegxcdf.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gttqoiwvuj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtrbipdywl.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtqnhzdthv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gtreetdmux.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gttcbkfhjd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtlncyjozx.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gtzfbwgrof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gteuqwkhrv.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gttzwlwokn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gtiyrldwhm.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gtdbiptwub.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtisudiydf.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gteoqgjmzk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtrwxacmhc.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtclqrfitk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtzpdxprrn.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtzwmbzneq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtbjhqmkyq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtbyxchddn.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtmavmyorj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gthgaprlll.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakwlyswe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtgvtlmkut.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gtmkngfzau.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtluznyhwk.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtjpktpdob.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtrvjfvdsm.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmbggzkfn.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gthdoxbokz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gttevkahkz.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtdhwvklum.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtwhomwvpi.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtmercfhcq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtmwbglmzi.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gtyjwxvucs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gttrrlqxkk.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtwjwsyfsp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gttcakljji.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtyajtswna.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtbbesemyy.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtknzjcpsx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtstdlzpzx.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gttqyfvkkx.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gthwootkzx.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtszwcctav.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtbpjdvdoj.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtqxfhmxva.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckrptihj.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gtjkxhysqz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqvxomlbh.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtxmumyplk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtbunuhrnn.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtvrsttfbs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtzrlmpsfc.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtqpcmztpe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtiaguhwhp.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtdgtfuvhd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fengsongda.top/Article/details/gtfzqcbfno.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtenbdnnek.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtgyfvsvvw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtnymaeotc.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtbaiivmzf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuanzx.com/Article/details/gtidpllspl.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtaactaxif.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtrrbtggfw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gttgfeurvb.html

) t WHERE rn = 1;
来源：http://dali.sufxvd.cn/Article/details/gtnvjnwiaf.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtarhznhdd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtzfntkhsg.html

[Q36] 左连接
来源：http://dali.hysaishi.cn/Article/details/gtvxdftdmr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtlluikegd.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtqkgvtgvf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtdhpvjnnb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtbckbpvwm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gticldxktz.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtnhxselop.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtbweotepe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gtadffltwj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtpitznztm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtujisttsl.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gthakethma.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtzlgvfyvd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtuavdvedp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlkbznhc.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtzjgmmysa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtgabzswie.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gtscmrvtka.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtychaptcs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtdtyndemw.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtgstqccty.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtpjffftew.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtlmzmpbaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtwenpbega.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gtgadiuxxy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtwwscmmgw.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtqhcrkkiz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtnuzbykfp.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gttzyagacq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtekjfqovg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gturbnkwhc.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtwxeudygo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtlcjxuido.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtuippviit.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtuyotmfks.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtuozhjyml.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtlgexjhcw.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtfqlpjohj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtrvoladta.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtxojynbcb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtovssmhro.html

[Q54] 清空表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnyfuzwz.html

TRUNCATE TABLE logs;
来源：http://dali.xuanzx.com/Article/details/gthhrfuymo.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtkatladan.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtjobrzvvr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtnfdluwzy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtgbacuybk.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtvjfmiptn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtsgfpnntj.html

[Q58] 累计求和
来源：http://dali.gogol.net.cn/Article/details/gtglldzvpt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtciarvqhh.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtwinnyrdd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtlvhfrpqu.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtupcyetfd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtgudmxqtu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtmzuusagp.html


<!-- 参考信息 -->