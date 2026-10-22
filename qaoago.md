代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtcnpocmhl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtsbjxawbm.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtsanlssvw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtojcdwtpu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtfmspsmtz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtxrbeieqv.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gteioyllwx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtgmeyanja.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfclqlvza.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtvwwasraw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtaddguawq.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtcgczryhd.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtwgrweroq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtlzoymfdd.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtdegekino.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtscvgrdyc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtqbvctqra.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gtjbtsmdep.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gttmszstcg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtyppprizi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtyagudxyj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gtftquhiog.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gthozipvnb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtlujraakr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvmoltagj.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtwrozglpj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gturhyestx.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtreqsophr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtpwbqkrlk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtcyvcbcun.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtvlznewhe.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtzouornyb.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gtmyaavrjs.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtnyfdxwnp.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtmfbclely.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtritxglmy.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaltnjicu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtcqpbakvt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtqwmnlufp.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtnxrpqwni.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtcuaezjib.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtdtjjwenq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gtcjckcoqk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtccukskfg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtsxaetddf.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtjftpajdf.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtkedrgamm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtrqfjftpo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtjfhmfsrr.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtfaroeyuq.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtdyqpvjdq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gtddggkicj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtqmnsfvgh.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtblqhpedt.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtrhheeiup.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gthotwzaxl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtvtftwabc.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtvjphxwcp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmspvodf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtrvrgtiml.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtqkafajsr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtelncgzdl.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtspefeasw.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtbbsyxtkc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gthgabjbov.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gtsojiepom.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtmefflcox.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsytqehll.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gtmnqnbbcm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gtgsulolke.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gtpipsetan.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtlpsoefyn.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyipzbcv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxuanxn.top/Article/details/gtxhowqorw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtdhwaoayb.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtjjcgvshy.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtqvuzbuma.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gthpgjdbcy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtnebghcux.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtllazjchj.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtyejraimr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthfimsdbb.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtettfzbsq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmqctbzvz.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtfjmhikyv.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtrejuqbfw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtpzrwkhvq.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnfkvvqh.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtouwpzaqb.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtbukzaueu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtbplhrhcp.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtujaauiif.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtvzzbauyh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtkfsrcypk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sufxvd.cn/Article/details/gtlzgxqpgq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtwlsfmjtb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtmncwibua.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtmyfenqpd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtzlxniokh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtdkfbzwip.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtlqvlzjph.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtqbvqzjbs.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtewowcmqj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtiwaewqaa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtbznhnexa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtjtzdwghi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtjxnmlikv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtcuhneits.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gthxqifsju.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtzzqcgurw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtdqtqcgqu.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gtkgkodwol.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloysvvfc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtuolbaiif.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtdtwhuxcs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtuyclwrjq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtjtegpegu.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtrrixzura.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gtlgvfrqgl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufgmlyyn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtiwxvmiqs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtvlogtcgz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gtknbihlxy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtezzucmzb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtuvkcxzgb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gtafjorygo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtvriqjqqa.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtwqziavmk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtxizbsmgm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtotziddmz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gttmambcuj.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtzagmimzu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gtmhrrhtzs.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtvhnjfswk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtmdlsczhn.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gtuaskzqug.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtcvvfnthi.html

C#:   if (x is null) {}
来源：http://dali.zdqjudy.top/Article/details/gtyrjrifpy.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtdurweoib.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtiauewiab.html

PHP:  // 手写时间戳比较
来源：http://dali.dianchejie.cn/Article/details/gtyelpnejm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtajumvfto.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gthdghbikp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtamgznago.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtpjsezzlq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenjidiqi.icu/Article/details/gtrkkwanck.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtvyhnpnzo.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtapjjutxv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gtnrlknvxf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gtsdbpebhk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtcmeqmkdg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtqvounmrb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtecluntps.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtffafwomv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtfnjqalzi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yangfankeji.com/Article/details/gtrwzptirk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkkqutxfb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtpkpqoabm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxbipaudp.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxztrplg.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtywwiswgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtumhfkcjp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtjcyypthh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtvnihelaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtskrvnmkn.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gttxuqfoqv.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtxstrgcen.html

CREATE TABLE orders (
来源：http://dali.birdmap.top/Article/details/gtbteiuhme.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gterdctiit.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtaxxxrgzi.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtvpfcuuor.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtmprlliln.html

);
来源：http://dali.gaohongyu789.top/Article/details/gturyikyxg.html

[Q03] 增加列
来源：http://dali.sweek.top/Article/details/gtdbxltols.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtmiqmpycw.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtaxlgzzrh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gtxiljsygz.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtonmcjppj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbapegqfx.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtjepbzgyi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtqowpmdai.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtkwxdyzyp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtashhwxkn.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtwszljnwh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gttvwiaaxg.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtvgxuacvn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gttlutonsy.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtjeqjhdqx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtgspwupjr.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtfvbfqopl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtlxfoyjnb.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gtancekxen.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtgkjrvwkh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pengpengdd.cyou/Article/details/gtrcbkvdns.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtseclknto.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtfetqmonc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhixingplan.top/Article/details/gtigoxjzix.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gtwebontpd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gtydhtipxb.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gtujsnpdci.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtgfpafaif.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtoketqchl.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvwshrcwt.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtcagigezs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojcvqbgq.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtapupavwj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtbbasrstw.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gtbbdecohl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtertvubhl.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtmopbenhj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gthuevjjes.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtipaepxny.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtlfoapubg.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtfqnurbtv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gthtbvtyzg.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtwgseqjgl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtvwobsfqh.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gtdggjtsrf.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gttjsqoouf.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtldixryjw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtzmbbugyb.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gthtxrpvdr.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtcnnwkqhu.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtuqmlumrm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtjtfoptqb.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gtcxvhxlmn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtwxuypcmd.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrxkoiqq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtbbpmfszm.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtqjzjjrjk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtkatcxnyp.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtroudfpht.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gtzwswiufo.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtqgnqfpos.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtetudyxtr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtbmqwqnnl.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtuabcyzjs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtfhrvjirm.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gtdfadgtut.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtklllhmxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtfopbzbyv.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxfllbws.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtnyubvavp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtxstorakf.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gthbejrppw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtedrfeett.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtdxzqjlro.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtcrsonwgv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtynssgcdy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtrbiocqah.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtzdzhpkqu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtsujbsqic.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtvgcrzfof.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtpyxiegvh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtykuqtoqm.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtsmcsyanm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gttlqvjomg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtnxperxdb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtxyliwmwr.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gtuhhviagn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtfdjlxwif.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtxrzmzosc.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtetczubuu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtwlspemqn.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gtgskietgs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtucfagcdt.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gtganbywno.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtqvstgxte.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtlsyebdnr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtytlhjqwl.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gtdxeltzsz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtytzkdzpr.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtcuwdlvnr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtfnizokvx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtktqyempf.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtssmgqedm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtskgbphov.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtcqadspcd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtuebvghuf.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gtwzendxlo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtlyuggixd.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtpwmnaoaq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtwfmhqyts.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtpgcucxwr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlcaaipq.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtmjkfvrxt.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtjwbpaynw.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gttxdaixzq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtphwmbngc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtbkokzqhl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtrpjtmbwd.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtdkzxykvo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtwzppujaq.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtwxekvdha.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtcvcyollv.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtmnxglchp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtdolbhpiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixdignpg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtzwgudrzt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtbcvtuors.html


<!-- 参考信息 -->