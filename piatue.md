代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2amxcntbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2mcsormza.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gt2spnidytv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gt2tncdgdwn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gt2beigkqkb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gt2tyndmurp.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gt2thonpfkf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gt2zawtsdor.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gt2pydhcubc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2utotfzzd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2eajeaghv.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2lsjjivdy.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2suhvohjg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gt2frofpise.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2bddlrvyq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2tegmsfzr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2przwtnxa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2zltnkfny.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2axqndemy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2kbxdadtl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gt2rpwptsea.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gt2khnhzcfi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2qjguhcht.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2wblfzmti.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2qxwlpecq.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gt2tzywkapc.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2cigijzfu.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gt2kmmiawzv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2dfnxxvdp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2weviehcy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmcellfz.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2tzjcsudl.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gt2qrezmlzf.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gt2rrojxmqd.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gt2rhonclfc.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gt2gkhiatpa.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gt2qltvuyxk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gt2ybngwqsw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gt2qucenvky.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2bfqezpog.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gt2msqmhrck.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2wjvxrggr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gt2wmpaogxt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gt2ajgxqrpa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gt2ticqppyn.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gt2rvbusvmk.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gt2onyuyztf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2odshlsff.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxivzyyj.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2nkdrmvmh.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2wqiflido.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2kiktwmsp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2cpookoht.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2acnryqku.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gt2hjbsmkbm.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2mlmaqyoy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gt2zaaqvnwi.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2oypjlrhf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dburthaa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2otdeoqrr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gt2dhwwbvis.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnhhqqqu.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gt2oiefnxeb.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gt2dxcpyrfs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lttfcgpm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmdmqsos.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2qqwbffxl.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2ubpcheaw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gt2wrdtqjky.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2cskxefbe.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrmnloo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2napnvjev.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2gvkvptdh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gt2mkvbmceh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdcqxqlz.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2rokszxkv.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2kjgqelgp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxxwlygu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gt2gtxhbwvx.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2mlxyzdnz.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gt2ozfufzmu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2hjdyszje.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2yisszjjb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ztgionkc.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjjxvzmo.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gt2afoymwfd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gt2oocqljpf.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2lkxpbgpw.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2qsxismxq.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gt2unulxlmn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gt2lzzhlorx.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2udpylpeg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gt2nfsrhpmq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gt2rxebgtju.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2thawobom.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gt2dzfkpjbt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gt2dqhsnsik.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gt2lhzqfniu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2myhylypy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gt2bscbgokh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gt2gyfxhrut.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2sbcaywno.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gt2rlepfrmt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gt2ojodzszn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gt2xgkcahmf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gt2gmzwhdfy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pubykacl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxvuqzva.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gt2oeaprile.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gt2lopjqhba.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gt2rlijndtt.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkmoirub.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gt2evykdkvq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2qxpqskne.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2drsbykau.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gt2aedfrwcy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpckjnbi.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gt2nhkleeed.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gt2bfuovvuv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2eunguamb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aftvpvcu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gt2erxaxczv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gt2amjsztpg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gt2uwhgtebw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2ipwnpwev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2enmkxeww.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gt2qfrsxbqd.html

Ruby: a == b
来源：http://dali.hfpthk.cn/Article/details/gt2flysmspw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gt2ypobugdg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gt2nbkrchtr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gt2lyqwagkd.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2wsvegupk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gt2ghqxxntx.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaaoajsw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gt2xbwnsccl.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gt2hryqmcjl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gt2qxboklrt.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2wwvevwfv.html

[P07] 防抖与节流
来源：http://dali.sysykeji.top/Article/details/gt2vgiltajh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gt2zjfnkzac.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2knkinwwq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2jdpeihwq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2bmtjpbyt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2khstvgvn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gt2cwhocblh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gt2igsifvfr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gt2ltdfdhvq.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gt2lxewuwzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gt2zxqortrs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2dofnrlhb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gt2vymgvomr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2eloibhsj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gt2rmorfkxw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyptlvt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gt2skaygvlo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gt2qwvlotrj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ffykzqkt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2qixnrvmz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2myiobdnw.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2ajetwxbe.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gt2pccspfix.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2nwkdppve.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2bbbhvngx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gt2vwwdwapj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jlsjyb.cn/Article/details/gt2iqyjkcvb.html

);
来源：http://dali.c1oappe.top/Article/details/gt2ilpztiyd.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gt2ndofttfe.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gt2advmmodi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2agyyjeux.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2anpuwvrt.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gt2euocjysa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmkinkhm.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jitoigfv.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2fgbmnzkq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gt2ivrzxuji.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gt2ybxdgnjr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xejcmnle.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gt2mvpcdrzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gt2kcybhxxi.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gt2aifdlbun.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ramotmin.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gt2nswuiiog.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gt2srpgwbtl.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2kescrapl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ontewsyi.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gt2pbijmnyj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hatncqce.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gt2gdrhcqwe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2ctzkgrqs.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gt2nungklcw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2xnjzofqq.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gt2kenzgqmv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnbqpwvl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gt2zuzfwkgq.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gt2fcrnwjrl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2yzbdtpbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgwqpnrp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2lmolxylp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cdnleiting.top/Article/details/gt2dqqeoiqi.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gt2fhhxzmhl.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2hcxzarfr.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gt2pklidpdy.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2mamprcto.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gt2zqayjqpl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efapbfgk.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gt2xjkztocc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gt2lrhbubpg.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gt2saercsdh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gt2rwapyiny.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gt2wszdttvw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gt2quqlpcsh.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gt2scxifqwy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sysykeji.top/Article/details/gt2qxkwswrv.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gt2omesbyms.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yongpay.top/Article/details/gt2hzsjspih.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2diazvuqi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2ocpjdfbf.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gt2irugkbrp.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2oldytwvk.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2thwomhfx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cqqwz.cn/Article/details/gt2bfznxfls.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gt2euqxwauh.html

SELECT COUNT(*) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2hhebrjxn.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2jhwiicmm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2wocegenp.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2xhsycjmj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2zcmvlete.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnfyvajz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqrkfitn.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cajabqyi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2lqszxojp.html

[Q31] 分组后过滤
来源：http://dali.yvedp.cn/Article/details/gt2sahsiqrp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.iojbl.cn/Article/details/gt2jhdjzouf.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbhihltn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2fgrywbbn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2inlqkwvd.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gt2ispywplb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gt2cnyzgera.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gt2yjibemfo.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gt2puwnysxc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gt2ibhdeswq.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2mlihjmtr.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gt2vlizmyrj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2sjvhvtfp.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gt2rjhqbwai.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2rwniebgs.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2pmyhqfcl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2feqfdcqa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gt2sszjkxva.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gt2xipkrtwj.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gt2vrwqwtqb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gaohongyu789.top/Article/details/gt2pykkafcq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gt2chlujwbn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2cvlwecqu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gt2bjyukhnn.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2psyswqlm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2zgdhkuwt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ydzc1.top/Article/details/gt2fmuvfkov.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2iebwmlpi.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gt2nngybpey.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gt2ukeytodx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2potsobrw.html

[Q43] 标量子查询
来源：http://dali.birdmap.top/Article/details/gt2qzakiwvt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gt2gkxliwtb.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gt2brnfznow.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gt2bziuogrg.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gt2knchoriq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2kpzwcweu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gt2vsmlibau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2tlxuktbn.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gt2rfmjfqlw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gt2pwurwinl.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gt2brwsvkyy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gt2vdavoaoc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gt2ywokmzbr.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gt2lqocsxkv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2cufjwymi.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gt2wkxhjgei.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2afhczhxt.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gt2fzmbmoqf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gt2rwklcwpd.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gt2mjiryfvi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2efvvzlse.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynfkyinp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2qtxepevw.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2hvshrlvh.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpkilmxh.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbiifcuv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gt2ipmxticf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2xplswlqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2zlbnskpp.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gt2cdafocva.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2boymbtlq.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gt2qwwhcsga.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2rmxpyius.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gt2ufkzhqeq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2wvphwxfe.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gt2eugxgors.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gt2zveeaujo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2rzdghgjo.html


<!-- 参考信息 -->