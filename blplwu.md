代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtjifpgymv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hywenlv.cn/Article/details/gtmxlnemdo.html

Java: class Node { int v; Node next; }
来源：http://dali.xinyue.icu/Article/details/gttamshbrt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtsrbsddkj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtvycmxsee.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guowangkeji.top/Article/details/gtripvcqyk.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtylfvklan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gthrhmvemi.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtvavxmpjm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gtwstechkh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtlpxgygcy.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtclofpsvz.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtpbjkjcni.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtihifxpgb.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtitukrmbi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gttsvyyzdk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtuyhzvlus.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtmknyqlna.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtxxasjzkg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtpfjgxfei.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtzymupacw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtsrsnybsf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtssjodqsd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtpzjyalaa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttqxrlxkm.html

O. 并发与异步
来源：http://dali.fengsongda.top/Article/details/gtfglqthzp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlbvhkqqy.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gtbfuvukyh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtntcdbcdx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtksnsqvoy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gtwyatfycm.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtsasxlcep.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtaqttqqpq.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gthutvozur.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtnpwjaucy.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gtoipbkzzg.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtrszrwrfv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtnhfbpxuu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gtsvrrtrxc.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtozibbabj.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhxayozi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtgbubblcn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtfabpczie.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gtlaqitzcj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtccqxsxee.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtqkegbwwk.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtxhzfdolc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtabyvgvaf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtwgvnqphb.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtglkjzzxq.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gthtvfwjuc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtlyhqosel.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrbblrrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtvfezzjpj.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtpvabregh.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtlkolvkfv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtojvqzcnd.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtqrhbcwyw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtmfqcxxqa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtnfeofpkg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gttsfacfjj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtplrwbdpq.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gtylvcncao.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtgmkejjwh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtrcfpoqtc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtxarejrkl.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtwggcspbq.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtmgoxklvz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtsixsijat.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtfybsaqgg.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtbuiabiyw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gthsfxwvpq.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtfiqaqhaa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gteeqhsgzr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtitucslou.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtjsdumaiw.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtxzrywxjf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtecbanjpk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtrrgmqyvb.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtkeuyrlwo.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtqploemda.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbmoimrme.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscydvhsz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdkrnqrsm.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtdnagtmju.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtmtyixbhv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtzvbwglma.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtnekhydxp.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gteqaiphna.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gthtskzkbv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtwndmyaqc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtaxgnacvl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gtcdunzutg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtrrelxtyz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtnkphetfk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtuxgbuimd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtmntxasgf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtdrdzpekt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtgvewxjjd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gtdzphufuq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gtbbxafwlj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtuubqcsyo.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gtnnzfdtst.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtkfujlpjw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtanwfqcia.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtewnewvun.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtdxwfobuv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtiknacbkf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtwjnlqybw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtkkbgodyx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtshhbwuqg.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gthhjhlxwt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtjewzlwrl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtdjsubfao.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtuuihynbz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtgrhaymvu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtnigydspt.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtoymnsmyq.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtanferkpf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtwwuzibkd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtkvcgbcvr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtivjljmeu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtbhensswp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gtbmxkwiol.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtevbhvxxc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtgnswihii.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtimfktflf.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gtzsvzbzot.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjugumhii.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtgrivjpsf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvozzcole.html

PHP:  if (empty($x)) {}
来源：http://dali.cashguo.top/Article/details/gtjvklsegz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gtoxcspmlo.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtnyavtjdn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtaahddezx.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtgvacvefx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtzhsljfjs.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtddtfclsc.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtvcthmcym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtfavndjqe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtjksckbrw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtkylhhecc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtludlktzv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gttfalqpet.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gteghdnivc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtbgsbitgn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtsjteoppx.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtpgnqebhu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hywenlv.cn/Article/details/gtnaiobqqz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gtndnohnss.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhengqikj.top/Article/details/gtuypweewe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdlmitsrg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtfhjznlco.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtkgordhrs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtqryabvym.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtxapwoigg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdflnogjg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtbtykhynk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtufzwsexc.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtsnmfrfyb.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gtpbzutckf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtdrppwrmu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtftenrifq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtqtoakchy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtjaikozge.html

);
来源：http://dali.yuxming.cn/Article/details/gtaxrcdhtr.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtkwyerkts.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gtpiujxqpl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtfxvktnik.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtjbsoocwk.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtegnxxdey.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtwutseypj.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtugbvexiy.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtvynklezt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtvssqwzld.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtzbsgnzgo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtsjjkxgat.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtferwnptj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtkdqsfzer.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtkxyavskn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtxhvzwodr.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtwaenfddo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtxntfxpkc.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtfbihkzal.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtcpijwyac.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtdolgquvq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtfmjmkogm.html

[Q10] 插入单行
来源：http://dali.jqgfzy.top/Article/details/gtdwyuiqll.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtbyqfkgzt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gtwzepwvjg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gtygendbep.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtceispysd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtwifxohks.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtheuyhwfo.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtepkwfsfh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtpjrlabqh.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtkyjitgyp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtobmebgzg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtogvtnvto.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtpjeqgnsz.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuvjdldi.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtrzzttpsb.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtexjdehzl.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtndfgwcxx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxbgbkzi.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gtovrucpuo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuldfxzeh.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtwfebuwdr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtodpclkgv.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gttdxzfxzq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gteitmkmtz.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtbhhrfwta.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtiwiohcgp.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtjjslerrl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtzbtbpozk.html

[Q23] 分页
来源：http://dali.fzhhl.top/Article/details/gtilrkxepo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gtunlhfemn.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtezuwkrgp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtuhxvzjdr.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtflicjbre.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtmjzrehsk.html

[Q26] 计数
来源：http://dali.andypj.xyz/Article/details/gtztaxhkoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtxnmftcgy.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gtpvcxqlpu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtbmbnyxbh.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gteozksilk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtgbpzkgol.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtujsllrty.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjyjmroqf.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gtfpqvmens.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtctsteaxi.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gteynlkfwt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtggohcxec.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtlyxlnvmx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtfdlavjbg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoqrtwsi.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtiioubhjh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtxmxilrcd.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtipaomabz.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtwspydxpr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtdxftnqqp.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gttyclouap.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtzjqyshjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtivitozce.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gttbebktcu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtqfspenwl.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtkepjmykw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhvaqqau.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtveyoeeky.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtudppzoqh.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtofkzpbwo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtijnupiho.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtoewwpwgo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gteixughrq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtefnocibt.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtjvgpwnni.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtqnbllfhv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtdsxnrpru.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gthtbssjzv.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigfzy.top/Article/details/gtipiavkor.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gtbmgzkxmn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtzdeqjxuk.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtyxoduwmm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtexeqdren.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gtwbxutyne.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gterhscgyv.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtbewyahyj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtsomuakfc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gtjhtptfbf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtjixselgs.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtnvscvjqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtqkfsyorm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdludvqx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtgitfixxw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtacfuahdl.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtrjwaiplf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtmrmoztnb.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gthupmwwme.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtxdaojtqa.html

[Q51] 用子查询更新
来源：http://dali.chenzaomai.com/Article/details/gtykjmzqmq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtdmkcekit.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gthijzrhin.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtwxffnkbl.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtfyhwezyz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtzgdbpcix.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtnorzapjo.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtaygclusa.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtaxnkxejy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtdxgsdspp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtzawjoons.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtvtcppnms.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtjwrymspe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcagkenrw.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtmoikzwek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtlhqwrbup.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtkxaossqp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtesfswlji.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdfezvqn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gtcxjhvcne.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtjblaqlyx.html


<!-- 参考信息 -->