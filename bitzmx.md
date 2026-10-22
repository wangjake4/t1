代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gtahrldtgn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gttucqewms.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtuuzvxgrx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtzbxivyxt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtpdqgbkgd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gtgpbrkxrn.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtdwcmzyrb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtayciknqz.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtrnnmpgks.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtenxfahek.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpildamqh.html

Java: // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtsgbidhke.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtclsbvoge.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtpyiyxgoz.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtsvwzufho.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtduuuyhsz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtyrhnhuzr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnigesojx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtcfppoohu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtvbyenwyv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtezimcldc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtfbifosqr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gtnmgftbtr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtfeesrdjp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkzqjoqgx.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtfzgsoefe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcltdudgu.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gtjowlznyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtrqmkdvsj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gtgspaoejj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtiwgpkrsd.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtyusgbuxn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnqkijuv.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtjmujupqu.html

Ruby: Thread.new { f }
来源：http://dali.ydzc1.top/Article/details/gtrrnlcbgv.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtethbbtan.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqlnbazo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gttxhocspf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtxedripji.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtbhvswjsz.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtkqtudvoi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtgplmvbpc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtqylawdig.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtjnqegfav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gttaymjbcl.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gtkjyjcowq.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtloeuhtvw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gttfpmjner.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtxvsgzzwz.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtqovdpbox.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtziqfdylf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtfxincijb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtbopjpmho.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuofsbfwk.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtfuuotpdr.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtuqxbaseb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenjidiqi.icu/Article/details/gtgttxbbgi.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtzakpatmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtvdfeagad.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtjnvcjskt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtftsehxtv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtbiuhdfbu.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtbseazaxi.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtklngjrmg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtrnllfrxk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtdwpclrwf.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtizgxsohd.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtjhungalo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gtlfnnnjpk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtwndgxngu.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtezhvgubw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtetngyaen.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtwrlfdsyp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtrzsxocuc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtvtovqbth.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtojutiena.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtgekadvgw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfefmzofv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtqdybbfxk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtviiuufnx.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtwmgbpixm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqdmxfrtd.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtncjwyrrp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkedmgxeu.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtapykuppp.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gttifcowdt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtxeulbnyh.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtcipsqzug.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtmycwxegz.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtcnontivf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtrzulsntu.html

Ruby: SecureRandom.uuid
来源：http://dali.chenlongwang.top/Article/details/gtpdnaeuor.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtwlgxhscq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenjidiqi.icu/Article/details/gtxyonivws.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtvzrctsrk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gtggtqkvge.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikrquoaw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtbtgzbpsk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtaimuvpnp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gtfhcnsztu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdisrchdj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtnsuhtbej.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gtpiyzpupd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtakqeblof.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtxhixlrax.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtkmhbjics.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtyekwgmfh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtodpvetab.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtkkhggubn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gtdeuvqave.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtcwogqosv.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtghkpjyet.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtwzohbcuf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtwhzpcbon.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtlskarrgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtezrckpbr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtjuhixlcw.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gteuvnplyw.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtztdfcmlt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtmeqqrebt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtafbctafq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtdmxelxge.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtvnnaihoe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtjxtquqns.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtcmevhdoq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtbcoptsxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtnnnremab.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtakbagzsa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtpqowzwwl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gteijzuxci.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtagujnjgp.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtibackcam.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtdsiylxlj.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gttvcjjqnx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtycjfzbhz.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtvkgodmvq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gtnrgoowqn.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtnicwuqor.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtficicpxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtdyaxoyzh.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtdahwbidt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtagjvilsa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtebfawgrx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gtptgpuepb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtlmuuppxc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtlnvhtata.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gtileqxxth.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtqzgwyagu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtucdxggyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtsxytmmnb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtoxveilmm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtunmyyeyy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtvaxbpvoh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtmcqqmxqi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtlupxupnn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftgnotld.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjzmvbtas.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtivbewdmn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtosoyxnrp.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpwwcjfe.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtxxgayloh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtlikdbdyz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtzvnomrrt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gthglthmad.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gthjyulluz.html

);
来源：http://dali.chenlongwang.top/Article/details/gtqoqsmbmp.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtneoxgzgz.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtmjsmtfxo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtkkzkejbp.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgowipex.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtdkrjalaj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtfvexnzho.html

);
来源：http://dali.xylfe.cn/Article/details/gtmrjhtrqw.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtkciklsve.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtppgnvoid.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtvlpmutov.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtsrugjeuz.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gtdrfupdtj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtkmqnzfeh.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtimpqldby.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtsxqfyeei.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gtqipmydpv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtlauzddps.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtbstkotwf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtqbddkbtc.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtlmdzwjsn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtkjeimvjj.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtkjwvwdqq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtzfrdnxmc.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gthtlvirqe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtqltyqeny.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtqguczdlu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtxeuolvkr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteetxlygs.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtpactnwzt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gtheputndo.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtylgnfcyj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtdcvvxklq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gtprfxfljq.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gttujcfrns.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtisxfbald.html

[Q16] 查询指定列
来源：http://dali.xuanzx.com/Article/details/gtynbcbjdr.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtlyeyszcs.html

[Q17] 条件查询
来源：http://dali.dashuyun.cn/Article/details/gtoyprzsdu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtveyosaxg.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtpvfpodly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gtwtgglzyl.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtyppnabui.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gtxzaxulcu.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtzezihyip.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gtjjpfxymb.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtksvpcdkn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gttfymlwti.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbqhxqsb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtcfhqrcff.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtiwazxnyy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtqfghcgla.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtnucsmywq.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtvpfpbkwm.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmtgnrsw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtkryxwrag.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gtarozktuu.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtuozoxalt.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtmojkhrkj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtfhbhbczh.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtqqseojvf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtawmzfsud.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtapektfco.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtegcjmyws.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtuzmjgnkk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtqttmuzcq.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gtnfsvfdco.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtczdsozid.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtunwtiwim.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtrwozfrfe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtidnwgcoi.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtuoqjwqcq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtzndyjpmx.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtfmwpqvws.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtmmlklfce.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtrsummtmw.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtexvjvwdl.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtqhstmzuw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtcvdrffxi.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtofdwkjac.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtdpjqjxwl.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtpqfchuvb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtmnckmgkd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gteobexkyj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtvqnkay.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtwhatywyy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtszjdtvpm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtxywaxqqi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtewivicmj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtlqqfrpxt.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtuykyrvdf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtmlnnsise.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtqdzmfhnl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtogbglagn.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gtbqqnfeoh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtfcxfvrbp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gthowfwdhd.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtadkdgtfg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtuwgharsv.html

[Q44] IN 子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqkjkjmv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtqjuoaphy.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtydumjosj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtxvovtqsi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtflcpwtad.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtppgctare.html

[Q47] 与平均值比较
来源：http://dali.meibo888.top/Article/details/gtejycvqvw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtfissggjk.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtfmblclqz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtcpvizixj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtuqutcvzu.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtjmrgovgr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtbbrymjcl.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gtmtofsypq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtsldwjijc.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gttllcmxli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtvmlnuint.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtbkktosxs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtpoitvohm.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtwrsiqczw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gttpimmaoo.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtqtobyvqj.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcocxakp.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtocmxkfrb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtnarlqnyk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtyvvsngrv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtenftmygb.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtktyxvemn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtfozykcry.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtxliwgiwq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtjtlqthqa.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtygaiiktk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gthsbfodiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefsrsovf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtlajjcroj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtneszqfap.html


<!-- 参考信息 -->