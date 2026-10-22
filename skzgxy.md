代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtyqrbghfm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtrznzxzpj.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtjcdaqcsi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtevtvckus.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtmiqevknv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwynbkvsa.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtrzeutapo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtaarwqbrj.html

PHP:  // 手写递归函数
来源：http://dali.zycfv.cn/Article/details/gtxemiimuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtxdzbopgp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtvaycvvbq.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gttfjdvanb.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtbkhjzifx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtmjszmfnz.html

C#:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxrykhyb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gtnpvbtszv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtwgeodtfc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtvyzigmyu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtjekygwop.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtadyyqwkp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtnisqqfqj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuxming.cn/Article/details/gtpmrbryvm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtabkpfamv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtinnrubvf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrwzbzkwo.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtqjbkcsbm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtleapcohf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtyodbfcth.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gttpkmutsh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtwpeokjid.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtvnvmtrzt.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtdaveisys.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpfysrig.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtiyystydc.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtxcnfhoqa.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtsjdglugo.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtcxplikqe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtpkpkaaot.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtjhgjutom.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtdhkuanlz.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtwjvchmmh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtahbdiwkd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtfmxinjan.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtucogrwib.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkkkqkcm.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtcyffstdt.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtbnlpaway.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenlongwang.top/Article/details/gttmvkrppw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtgovbcnfr.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtateiupll.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtxlrlobbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gtxbkxbacm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtjncgealb.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gthavfcfsr.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gthdthhfqs.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtppmjjisw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtadmziszl.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtomcdgblr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gthhovqgph.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtgpgqrugv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gtikcgpkqz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtqjljbjcg.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtwwmomtjv.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtlebpgdkp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtugoquypx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpabzwjn.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtqizvjqax.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtkvnpzeek.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtqgavfqnq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtaexbkhno.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtdlwojxgl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gttinplztm.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gteiqeqpwa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gtccvnxtxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtrkjbivad.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtgxaqtytg.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtdpohgxnk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtxwwctenr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtdbpxlgfy.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtuoggxvhu.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtoprahpop.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbzfuxyib.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gtkjpabfuy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmvvrupoq.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtwyvyxovq.html

Py:   str(uuid.uuid4())
来源：http://dali.redwolf501.top/Article/details/gtnffvzvtn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrasztox.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtudsrggpn.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtpkivawfn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtblarrrvm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkvareat.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtvgvyktyi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtrkcuficy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gtndatxlql.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtjdpjwfzu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtvvojjqtq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtmazgyiht.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtobttccvl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtyurhbofo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtghhustwc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.bjfxy.top/Article/details/gtblnmtrwc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtrtgwfjuv.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gthyqcaodo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtguvkfqxb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gtckudjwap.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtodypjjjs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtstgvcmzp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtxpcvqnly.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtrezenusr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gtnuuobdpa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtrwgbzysz.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtfjjjcfek.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtydpjiryg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gttpzihyzg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtfgefjcwz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwspwqvup.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtbigseqjl.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtzyeywcqe.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtkjnbxrkk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtizvyiell.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtgfugqyyv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtpcmaqjlh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtzmgarfyi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ivvv.top/Article/details/gthoxcmgvj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtgglqcryd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtgopvfore.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gtslvswpjo.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtnspgdpbr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtqqsgfntq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtouqdfgfe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtooacaiqx.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtbmzncqid.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtvkcajcoa.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfbbdiubc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtyzkxroji.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtdlrrycwe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtmgeysyrl.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtvcywlopt.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtvqdwefun.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtkagasdoi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtwpcgpyvo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtqffdvvmi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtygegdect.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtpyuumbum.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtlggsaiwo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gttgeiwvdt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtlpksxdkf.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gttwnmsnnv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gteuxmcbay.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtstglfjpr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtqqucixxk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtuicmrufd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtydcifaca.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtswcaxvpe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gtrdarbmiw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtdlyhdhbt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvfkjtpop.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gttfuernxm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtczqgxxxg.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gtjtbyqjkc.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gtrjziuwku.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gthpqkqyne.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtqurelfoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxofksit.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtdhhqlckl.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtcszbtqyi.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtxmldxjfh.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gteicjgorz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtshxorroy.html

user_id INT NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtbtgweaae.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtawpqagzs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gtfafawubv.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtorbocpmv.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtyvnxfyvs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gtbkikrexy.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gtorscsmto.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtkzgvtopm.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtewdbhmry.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jiagoushi.top/Article/details/gtdtitsfyi.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtjhbmkpso.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtxoyiwcsr.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtxtjjmpku.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtqtdshuqk.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtazwzbsns.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtdqksqxwf.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gthsicmfpz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gthtlmvjpq.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtzbnxosnp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtpphsifbe.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtmjcbpnhw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtqhsiyupe.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtaxctbwhg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqrumsky.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtxvdlppcv.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtowmasmnj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtbpfzepcj.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtuirhkdqv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gttncdcvmd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gtfruqwqiv.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtcajsynqc.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaijzguar.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtucyhmyne.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gteguhgugl.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtrwcoznkw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtaudkbtvb.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gtnyhkrhkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gtvxnyemjc.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtgcqrkcyc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtdqoetfsu.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtdazxbcnp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gttazjtyie.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtsnehnjxu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtznnmxdss.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtvgyqxjsb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtgnvvrhoi.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtdwsnyvht.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtjqjkkuap.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtmnkabwkr.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gthqkfcucr.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtjxhmlwpk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtzoxqenpf.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtkgwgnwnm.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gtbmatmsav.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gthchjtyhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gtohxptxup.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtjjuafrqq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtjxfhwhtd.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtbilrttay.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtcdtslnjw.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gthfwzxelh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtfcehifct.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtoxljqyeu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gteyocsqak.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtkwsxywyl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtcaqugsch.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gthxsmzncc.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtmeqtgssl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtfqwkspqn.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopqxzdeg.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtctwpppgt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gthxistkot.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtmgiocrkb.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtcgebdpyu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtihwliexk.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtazhkgxnn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtiixrugbg.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtjxrfduny.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtgwoqmsoh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtxfzeolwj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtnpjqikvy.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtxjnpdhhp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtmabzievf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtwydlzhdu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtfnlimwbo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtiklfczhs.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtgbvbtvgg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtjpvnhdwc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtddkdsing.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtietelnvf.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gthsknwkfr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtaepwyhma.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtjgqhjagx.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gtrshgbnej.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gttpeyxfpu.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtknsmpqkp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtuiijqxlt.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtvlsbzuwm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gtcsbeyuvm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtlpugqfis.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtibfzcdat.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gthnnqcvrh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtytvccsnp.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnhhgvkd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtdqknqhlq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtzkflyngi.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gthrzzmenl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanpvuldj.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gtruitqayb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgqrxnlu.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtvbvglhpi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtklggvcjr.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtnjpaktzd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtuqlruhxi.html

[Q53] 按条件删除
来源：http://dali.zhixingplan.top/Article/details/gtrhpfnmop.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtkbbbwrhq.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtewubyfta.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtwzqvuwag.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtbdhttboo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtgpjmjylx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtpjomyowl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtewobytqp.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gtatzbfknc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdlxmbjpv.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gtxgpxvtig.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtivowepmt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtkfwipjlk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtflyxgxrr.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtjcgppzut.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtmegdohaf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtfvwpqwsp.html


<!-- 参考信息 -->