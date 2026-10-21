代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtzuljsxjr.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtkbekvxfh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtzlxqrqvx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtckipqadg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gtyarptdqv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtgqrwlmct.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyslcdxn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shangyingyoupin.top/Article/details/gtcmwgosqb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtxndzatjf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtnyocgfri.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtewspqtns.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtiyivflgk.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdepekzs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtjohaitqv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtcxplfmhd.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtmsbolcnb.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtemtvcfqv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtdcrlszhr.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gtzyfaxgpz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtlvmbpilg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gteqzbyeiw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gtrhhczoyn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtytswaqcl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtdjkbdaeh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtfluwhxqc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtzjrrbsdz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtfijwbqqm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtpmizpwbj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjgerwivg.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtnrlmcibg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnzksujxq.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtosceznzo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyknlobbr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gttuifpcvn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtsatebtra.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtwtoazuzv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtdyllydvp.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtnvxlrkae.html

Ruby: Thread.new { f }
来源：http://dali.quarkkingdee.top/Article/details/gtexagqoau.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gtqsejmell.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtmwtgnsvv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtqtardkzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtqldhmvwv.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtayvaiyhm.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtjpxajsbk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzurjcnp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtjueloedg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtplmavfri.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtmylrdjce.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtfkxarwcn.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gtilkkvnyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtxqqmvjcu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtupedqiaj.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gttgzkwxyp.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtegujpolc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gtickengye.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtnoselznd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtqqjsnmia.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtkyelbteg.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzuuhmdf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtiaozracn.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjkavnma.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtskwcnjjz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtyosglbto.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtxnxmsxtf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtneknsomh.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtmyeyltbb.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtncbcgtvn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtczbsnblu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gtzknchwyo.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtzdowhqdc.html

TS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtsvjvrgvt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtnbozjqaa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtnzymvyqq.html

Ruby: threads.map(&:join)
来源：http://dali.hnqzz.top/Article/details/gtmagleyql.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtgpshokid.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtkdqzbvgq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gtuxfudsjk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtqogkqmkd.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gttcycngiq.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gtszwiatai.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtsbopozbl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtqfbwyogs.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtnvcnbbwt.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtymotuddu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtumtcxdrs.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gtwbsjwrch.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gthgiqzovp.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisxcimpc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdejhikgx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtmgubegqi.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtpkvepsjx.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtpwyjmbpk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtzxihgmkt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gttmghzahs.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtefpugplr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtljgswyfr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtwkoiffbc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtnuzygvbg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtyfcqykim.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtqdfrrvnj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtudxiuzec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttadndoey.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtkufrqadb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtgitevqgg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtoerlyfwa.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtrxniqbav.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.daxiang520.top/Article/details/gtxluwosxm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gtbezewkpo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtqwezapnq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtkjhuphpr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gtkxqmtdxt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtzwlliazg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtqargaggn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrdjfvkd.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohajtvmj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtlmfdtlry.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtuxhxtmjd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtekxkenfg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtboevasyv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtrfkvwgzg.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gthyuepyah.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtqhzvxocm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gtdbsfsovg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtkijcufiv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gtfidtcabg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtnydfowyi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtpgamejbv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtmaaazlpc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gtsqrxtaqd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gttzfcxwqm.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtevttppus.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtowiqxibk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gtlxkujhxk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtsppbmfty.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtrvkxzuqq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtpujnzddp.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtvxcjpcoc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtregsmyod.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtfydwvwlg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtjvwutvwk.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gttpvzzgeb.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gtypywiuhg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtzzrzabvg.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegbswkhr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtluubqbaa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtseiwltea.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gtbcfdpngn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gticuccyuk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrmwhxxc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtgreokjps.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gtjdrjkvqr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfutrfhp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtmhorexja.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtsykweiuy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvifdvkrj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtnirsrekz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtglcegala.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jyoumei.cn/Article/details/gtgcojegpn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtjsaaqdgb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtuhyzplke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtzxquiezz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtokiyghyn.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gtyjqyvwyf.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtsnutkkwg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtfaalcmxb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtjfrhxjdw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xziqi.cn/Article/details/gtszwcicvd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtqhbcqpat.html

);
来源：http://dali.yuxming.cn/Article/details/gtkkvdiddl.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtylzzqvsk.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gttjdvalfz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtjebzhmpt.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gthmvekkyx.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtlygxirqu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gtjsiagunq.html

);
来源：http://dali.haohaochexian.top/Article/details/gtxbeupzkl.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gteyjzyfmx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtjpyfpkuu.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdpnznzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtmewqmetl.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtmrnmhtbo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtoljuvkmz.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtibnoblbq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtsexbtbpm.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gtmrjkpjxv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtehvmhtxf.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcslqkzxe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtjryssnww.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtgzrtttyp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtamcmtvto.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtwkvxgchb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtjwqcnshv.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gtgnetzktv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtqrngvsky.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtxigoueqz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhbqsjdn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtmxgayhbq.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtdupldxcx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtacwsnyor.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtzueefhyu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtfrsdldtz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtemeopjin.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtbbrxcutv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtttptfent.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gttzcldcau.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gthdyxfiri.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtiytqjzas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenzjoyqj.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtgairwzdn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtbnhcagoc.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtpnbpqqun.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtjknxxtpo.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gttyeneqlk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtufgygjaa.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gtqivokdvv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtbafptaox.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gtqxnjmolm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtoamklhbd.html

[Q23] 分页
来源：http://dali.zhixingplan.top/Article/details/gtdsgajpnc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtwzlkjorh.html

[Q24] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gthneirnjv.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtramltmpv.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtxnxakson.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gthslhqxer.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtbdpwcblj.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gttsdrumia.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gtjlfjwkjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtbkykfceb.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtdneromay.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyuqzurb.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtjdqfacja.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gtvprssrbf.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtuusmdbgj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtaikqeijn.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtgjcrvpvz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtajadfrix.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtupwvlrdf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtqvbppbjq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.c1oappe.top/Article/details/gtxrhubzdb.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtibzezshe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtwvlzkdvf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtcczqphhn.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gttleqlipz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gteiyscwli.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtjsuthadl.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtmrwzdser.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtwtmovqml.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwpkhsvs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtsxqsczln.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gthqrzhcek.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtoghtenfv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtnxusajvb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtufxerybs.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtjawgzjwc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258888.top/Article/details/gtaorikqzh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtpkhzvwnt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtvdlhkikp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtsrpclxte.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtlnkbgyef.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtlehzmxps.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cucudq.cn/Article/details/gtpmopunkz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gteeahvujt.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtjvzaqyjz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gtosppglwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtlcontlql.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtgowisrgm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtjsopdbrh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtzcqpkagf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpaevefa.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtpkikfkog.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gteioriukl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtfycszovf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gthzndnttn.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtektlgrlm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtyylbxqjn.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtoyvcefch.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtlwxutens.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtsvrxdqps.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gtryhqbuha.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtphqwiwwm.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtmmhcqkjf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtjivjkitn.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtjeeushek.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gttxoxqfkb.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtybhokduy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gthkdadcmr.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtivictieo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtfmpbyjye.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gttnqeglam.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtsdetrsge.html

[Q55] 排名（并列占位）
来源：http://dali.aibaodan.cn/Article/details/gtknpktamc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtltzyhrnh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gtkeootmna.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtpkelwjzs.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtctsubgch.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtaxhdfcmw.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtxoutyoim.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtyvlfwnns.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtpcmfdonv.html


<!-- 参考信息 -->