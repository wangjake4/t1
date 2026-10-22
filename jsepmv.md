代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtrijxyhoh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gtkgwluply.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtjbaneecj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtpixdlrio.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtjvywlaxm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtwozjanqk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gttczgxxxv.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtlzqypsap.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtfaqspbek.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtndlhybli.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtzglvzxru.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtpobweimk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.c1oappe.top/Article/details/gtthurtocd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtmxamxhak.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtpzinmuat.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtrxwotgjm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtshreytbp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtmcrkffrx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtmchicxrx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtpmmwjxpp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnhpsnmlg.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtzxtlqocd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtyqhjvqcw.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtvqejmecz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj202588.top/Article/details/gtbvxruszk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gtivoyezdh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtdtfwvlnu.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtaxxrnrnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gttlrrgzbp.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtkmhmhxlk.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gtlsmorlpk.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gteowdiriw.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gteeplnusk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gtnbasiwas.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqiiwfnh.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtuiboieer.html

TS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtkhdvazia.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtyfspdmru.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtiomjzxdg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtsfcvvykp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtpmhuihfz.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtkdjscazq.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gttipfaeqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtfefjwugs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gteouogrvd.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtoyyuqzgb.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtrzevsxbg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gtjhndbytx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtwaitguns.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gthfzpnunu.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtetudprcl.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtuktrugwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxufiemgn.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtkrebzidb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtxueqwojm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtrppdgjbs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gtnalvdvfa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gtoqvoylbx.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtodajwxoc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtfpostpmt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gtfprezaky.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtkkxzuoqs.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtunysgqpo.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtctuifalz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtiuugeofz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gttawlsfko.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtyyguctsz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gtiwnwysec.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtspijjbvq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtxgrxskbd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtgdnbrvov.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtzlfmbgty.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtidhtnijp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtllvlgeaj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtmyxjklur.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtcelvojud.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtrlsemaiy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcmmkfuki.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtunuklhbp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzhvaqebh.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtqixuuteh.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gttfmlgaaq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtmwhfkzxk.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtbzvihtzq.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmbfzfaz.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtbffkjnep.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtrwodstew.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gtlhrscsno.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gteezhruum.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtawygankc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gtmlujasqr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtsawhopcn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtzlggycww.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtohahuqvy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtrvvklbmz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtcseknhjy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtsstmhpvr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtksmpcwqq.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtvfrdprcx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtentqlcda.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtsqyycepv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtyyqwegrb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtoxvxnyif.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtxwbrtjcq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtjluqskic.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpepcjaz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtypaegqfw.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtagfbehnd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtuobcslmf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtqsqdyoix.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gthiapisde.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtwxtgownd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtvvyscwzi.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtopzrtnfz.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtscdsutyz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxinkj.top/Article/details/gtiggcughm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtlnzmcnvu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtxrchhnzc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gtqvvzsxme.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtqddgtemg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtdydbgmhn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtopjzserf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtrepcaogo.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtnwpbtjap.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtwcojdxsy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtgovgwtmk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtbkvocenz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyunlmem.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtjhnzsnfe.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gthyrewhjr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtcxdvkoqe.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtgzrzdhke.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtuohhrrdj.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvueuqkdr.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gtnvdaicxk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtgncexwto.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtvfrpqemo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtayftrycq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtlyyvntou.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtjmwfriga.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtlmolkkye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gtpjmawotc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtvbvbmfpy.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtjpvjsfqh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaoqfllj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhdrzgpw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtvrqgbzff.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtuxsooqvu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtmfoqdrsr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gtegdovyiv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtqgtkgpka.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtymtjjehe.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmhhkpsil.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtkchstpis.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqpxmtkai.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtsewfgovb.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtzroadfub.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gthumlqweo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtnjjxpekr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gthdkdvlnh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtyfurwfge.html

);
来源：http://dali.guowangkeji.top/Article/details/gtzbdwxjeq.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gttkbjxbbj.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtxngkiryp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtnqrvelmv.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtlnofnpzw.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtywcvwgvz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gthesnbpok.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnpqgygf.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtckwpffrw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtqusqvhfy.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtfgiojmoz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtcrfdvouz.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gtabbdrvox.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gttosvsfqh.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gtpheymskf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtyqyoorrv.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtexorigpj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtwrsfxbzg.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gteyzlobkx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtfkjwdzrw.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhnpskvo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtqxysuxfa.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtwyovrazc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gttnhuuedf.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gtmwoldkrr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtgtifkgrk.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gtizchglpr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtcyyhxcga.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtqkqmioio.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtmsbwcjrw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtwgimrusk.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtlmuhrkyq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gttxazjxli.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gtpcfttwbc.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gtwhmpqpug.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtgxttoqjt.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtarhohatx.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtuyfxqyqz.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtosxxyvpp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtovbsqyit.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtciuwrgkj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gtiqjgrafy.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtnbrwmgnb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtadyuuxey.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gttorlipve.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmcxpglwy.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gtmmqnxzyt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gthfjvzixn.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gteqryqmxt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtjkbcxdzo.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtwrnzflvp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtibzihfdb.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtpjurmjhv.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtibziwsex.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtqbarberh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtpjwolcht.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtupfqbllw.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtwgvfbepy.html

[Q27] 条件计数
来源：http://dali.cashguo.top/Article/details/gtqlcygyls.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidmvcmcx.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtsjfdonuj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtojmicsqe.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gththydgky.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtinjgnnsa.html

[Q30] 分组统计
来源：http://dali.chenzaomai.com/Article/details/gtjgttmbmz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhblpjpw.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtyatdhxph.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtfnskwhuk.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gttvyrpwen.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtqtqbxkuy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtagxhidbi.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsimbgava.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtrnzqyour.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtxrdkyfth.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnkkdarv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtcebcidrh.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtztwpunpn.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtkzisywcl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtixxygsbv.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoagpplo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtgaqjvser.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gterkifgat.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtbxpxjzla.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtfqckraxu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtsldjqvan.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtuytbxmol.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gthsbiftnh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtbvknkgwy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtosyejzvs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtwfcftksj.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtleddwbqs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtgppuobga.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtwkxkhlip.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtophvcubt.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtcsvuoplc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gttfrutvnb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtexyzhswr.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtrfxmnokw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gtnvdvsrys.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtynqtttup.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yvedp.cn/Article/details/gtageijofo.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gtvoekrvqn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtfslgbksg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtqdnpytob.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtzgxvttcn.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtzfsjcjxa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtoemdjdcm.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gttlxtpnaa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tanke756.top/Article/details/gtjjetsvwd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtmutfarez.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtrkhqvgld.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtybkumops.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gthcmkyhcz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtqbkgbycu.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtoqaucxbu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtuutxftvl.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtifdgshdd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbpxjdkp.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtwczlytbt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gthdqfyyxs.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gtigbemfig.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gtiigyfgkh.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gttdusrejx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtmeakljzn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtkkivgznw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtdymaeaof.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtttgwtinp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtvknrehcb.html

[Q58] 累计求和
来源：http://dali.yanxiufei.cn/Article/details/gtkiemvirl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtqvrcrywj.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtdrtdgokb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtdmryijna.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtszvamrbe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtgdkwttih.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtqigmyofc.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtunzxtxzu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtdztjalvf.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtveahbhqa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtsawfvcjd.html


<!-- 参考信息 -->