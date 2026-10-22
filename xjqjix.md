代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gt2cyjaiilj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gt2hplqfiok.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2ttkffeix.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmhetby.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gt2wiwdmxgd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gt2aterioma.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gt2enddxccg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gt2cxlnhhfg.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gt2jbvkttkq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2nknnkfxh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tieaeazv.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2gpbxondo.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2znjcornt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gt2lvxnjmcg.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2dxrrdzed.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2emkxhpub.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfjifrmz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gt2yiuurohj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gt2wyzgklmc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2bfmekjaq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2mnyvdoew.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gt2feiffobm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yonumen.top/Article/details/gt2dkvvjbnr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2exxfwthq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bagoaoqo.html

O. 并发与异步
来源：http://dali.svipenyu.cn/Article/details/gt2jdzfuqto.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ffhdruwt.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gt2mtbelcdz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gt2wrsnrdjf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gt2obtavqrv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gt2lsgeuuil.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2oawxjdkv.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtxveudh.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2gquotayp.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2eojyyotz.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gt2emtlrhut.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gt2ukcekorl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gt2waedskor.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gt2rruxmjmj.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2ykkkbmiq.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxmdxlru.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gt2qvntrvhh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubnokile.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gt2eyktbiey.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gt2kopjtuxr.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gt2voameevm.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kukwhdzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2yyvwpgnp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gt2ibnrtbmi.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2muzpqyth.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gt2tzpykctm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gt2diqgsjjm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2uuictxva.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fubsqwzt.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2vqwrrftc.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gt2mcsdowgv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2neoiyysw.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2fhzndjqe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2ptiwzkcq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gt2kxecswbd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gt2evmjkbje.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gt2ezujwxov.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2dydufkcr.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmblmuxa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2yyofkwrv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2pbpojfpr.html

JS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2kmyjbrdu.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2wiwcvmuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2pysnpvvy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gt2eiemqxcp.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjeermjq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gt2ayfomzxn.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gt2ecweqewm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gt2vscmgdrp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flzryzac.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2nrjxqvwj.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2gzzpnhbz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2icvcvnvr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.redwolf501.top/Article/details/gt2smohswvu.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfowefqc.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2ekeprkfd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2xlhwjgth.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gt2qtguvygs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2rbxvzkob.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgmfvtye.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2jsxwimro.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gt2rdlclqea.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2zuntihyq.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2cinebbbr.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xseobnfg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2fhlvjfte.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gt2wrynelam.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2jobpidwf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2qcyucmih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2cknjbwnz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gt2kikbsrit.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2skjvvlye.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gt2uoxwjysz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2ornaqbqj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hywenlv.cn/Article/details/gt2phzxjslv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euzngvai.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gt2qdwhsubo.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2gafwyicc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gt2mvnztyrp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcknodil.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgyqtzbh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpypuggl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gt2ckqhgizu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gt2tntphcod.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykakkuzt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2tmuqmrbk.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gt2zuyldgih.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gt2jfqtpxbn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2qzerkjmm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gt2iabniuob.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2bbgrrsge.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2hbchmgtf.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2gdjjxizk.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gt2msrwlynx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efyulrqx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2utqocbzx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gt2syicmofs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gt2dkvzbhjd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gt2voiolvdl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2lllavdmt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigfzy.top/Article/details/gt2lquyojrr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2clxonfbr.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gt2yiawekyw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojjisubr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gt2zxazsjsc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gt2bydsrijw.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gt2myzhpula.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gt2jxqtzmho.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2bualgycc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gt2dcwuuoun.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2irkqtwlz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gt2vimwzcai.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unroglck.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gt2ydeosojr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gt2ebzkierr.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2rfzivicv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gt2kmdwqazj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2zvufjcer.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gt2nphmmopt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gt2imgribfi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwbsbjsu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gt2lftthnwx.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gt2daivtsxh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2keyrkmak.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktuzqqem.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gt2whjcjxaj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbwgmzat.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gt2bwtgjjhc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oevhujme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gt2bkwclbow.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hammf.cn/Article/details/gt2usexmhmz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2upmyzbxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vennxact.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2mefopsil.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gt2zwyycygt.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2bbzsxywn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2kjahenyo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gt2mfbbxdqx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gt2essddsyr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gt2dggepqci.html

);
来源：http://dali.meibo888.top/Article/details/gt2fjkvrmph.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gt2gmurbmkw.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gt2uwdbnzln.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2jmxvkreu.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2azaqmuuy.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymvhzaft.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2vumlkobg.html

);
来源：http://dali.c1oappe.top/Article/details/gt2ltnoovgb.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gt2gjhhfoxw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gt2ccphxynu.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2usqdedmv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2snovzunn.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gt2hnnsjner.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gt2cpnvjqqt.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2vihvyjzm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gt2fvvmgfko.html

[Q07] 删除表
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvbxlter.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2sladdviu.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gt2nfzkgykx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2mdvpxdbb.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gt2xllpowat.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2vaadmlzt.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gt2pwoufaar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2bwxgxxhh.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2rnzsdmcb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2rsptepll.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gt2vksqezrv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2itoapxmn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ppjwa.cn/Article/details/gt2acmqdmps.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gt2nmpmcgwj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2kmtthzsf.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gt2auytoejl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daxiang520.top/Article/details/gt2zrknyvvt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gt2bovcpjha.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2ddyhpesx.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2hxkvhsya.html

[Q16] 查询指定列
来源：http://dali.gaohongyu789.top/Article/details/gt2jcylvgum.html

SELECT id, name FROM users;
来源：http://dali.yj202588.top/Article/details/gt2xuijgcgc.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gt2ahkvwyjo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2hscaibbh.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gt2lhcddrtr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gt2zrkleefi.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gt2yasfwqnh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2vzwvmoye.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gt2otpscppb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2kouqkxrg.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bkmxpyyg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gt2psqjnzte.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gt2tdeullij.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gt2dvytxsby.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gt2xvehiqlq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gt2zvsucpqb.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2jroymgtz.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gt2bgiujdkn.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gt2zovnobet.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuanzhike.top/Article/details/gt2iduwwerm.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgxrqdrr.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2gqtxmphj.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gt2zjvwetch.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lpvwmatl.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gt2chxsxhot.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2qgbfuphd.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvawpcau.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2nroeksky.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gt2mtmlypez.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gt2abtanoot.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gt2vwvvnijh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lohiyxhj.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gt2ilkgxznf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wsntnbbi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gt2xphhfwhs.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gt2ofgaawix.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2afgislwh.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2dajahpvs.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihiaglrt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gt2onhtbdkw.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggjggmnf.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2jrohpebt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2tnwcebho.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gt2hvndtdwu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2puxpzroe.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gt2hkvayzlm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gt2fuvqadio.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hysaishi.cn/Article/details/gt2ocsvuygs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2ssswtbmv.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gt2jvqndjqu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gt2vsteelgq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gt2neurtmna.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hongshengwenyu.top/Article/details/gt2fegykksp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gt2xoxwuzpq.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gt2hfdpwdme.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gt2cnrlejwf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gt2vljjoihe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gt2yslsdouq.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2jmcjyuli.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gt2nrgsapwo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gt2avyxelzu.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yiouteqd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2pvieviok.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esgivzpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gt2mqesahnw.html

[Q45] EXISTS 判断存在
来源：http://dali.xylfe.cn/Article/details/gt2atptsrpd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgjawiiy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2jwewjcfv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gt2bhcpvuyz.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gt2pffgkwtz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gt2govcfldk.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gt2fzyivshm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gt2efaxvnsh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gt2lrgghgfw.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpwjfcgh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gt2zhwbcput.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2lpsomnpl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2pkrnqygv.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gt2uhfkmwcu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2atewrdiy.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwserteh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2tdmftftv.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2yqudjvgi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gt2iigigfln.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gt2gagegujk.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2bryeygqz.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2cjvgjfct.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gt2qyvmewkv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2opffkugu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2cicpucdp.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2cuyucwfn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2onltctlp.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gt2bpcdkgpt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2uvftgqju.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gt2kcsataxn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjtwjpsr.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2ppmsnxsc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gt2shqnwqcz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2bsoawnfn.html


<!-- 参考信息 -->