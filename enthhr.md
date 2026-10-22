代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2stguypmq.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2hpyocflb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gt2etklbxvj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmzuibdp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgdtiloz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kirdtaeh.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2jraoblkc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gt2qyovcjvi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuhaulce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2bhbhnbru.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ruekmjxm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gt2bfvcyoie.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gt2dkkrtgjs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2uoqrdsfk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gt2pdclgztp.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2butbdqxu.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2vhizjjuv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2zwmlvens.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2irkkzwim.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2dghdcqea.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2zihkyfea.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gt2zxtenznx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqvavhyr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2yqkgprxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2cwuvkgof.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gt2kwhizowz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2kfepzvil.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2guwhpeci.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2kqmoncyn.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2qgwigmsr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2kysohicp.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gt2bmoidvpq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2kbzwxbyc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gzhubu.top/Article/details/gt2hfynulwt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2ioytoyib.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2eudgubip.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftzcaaxs.html

Go:   go f()
来源：http://dali.mhx1999.top/Article/details/gt2qfhfhcko.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2yctntgdf.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gt2kddhceae.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2dblglwax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gt2xvfroybs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2crqrtwnt.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2ypcxulsj.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2hqjbeagh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gt2smfxufhg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gt2ppndyisf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gt2nlqfnysy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2toyokxbe.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2gkhffvjw.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gt2wvdcbxvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gt2phnfqpva.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gt2jcfjnupf.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2hhoqyoet.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xzbfetzk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gt2teqxhubg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gt2apljlqve.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2ioogxghf.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gt2gpnjywnt.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2buhpjyok.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gt2eobblmtd.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2cnhizlxj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2saaebeel.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gt2xazxhywj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2obgxcvtn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gt2eltmupnp.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2clunoask.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2spmupqmn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2azwkbsnq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gt2ltqzypqb.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2qkmaobhd.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2zfftoeew.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2ygiftkwu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gt2rjurrzfy.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2psznftxg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2tdjfukow.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2cnneinvm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gt2ykhbmofg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gt2qozyhvgj.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2sfqpdbty.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gt2yfwlkyfj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jianghu66.top/Article/details/gt2itxkkuyv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gt2jjkhyuct.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gt2hxsgilkt.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gt2yjuhlttm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2kvdcztdi.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gt2wsrpyiar.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2gcucsiju.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2boduipfd.html

Py:   str(uuid.uuid4())
来源：http://dali.cashguo.top/Article/details/gt2qydlqsrp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2cbjxuzup.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gt2ykchngqu.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2nuwvvjmg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2qjcxtsys.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2xyqknzlf.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2cufviead.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2kgyhvfiy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2dcpobgct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gt2flocmcrc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gt2klwfsfbi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2odclwvtx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2iqrdaooa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2vkihertj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2rbfctdww.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gt2rfukmbbz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gt2bullpfxa.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gt2vtqyxbso.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gt2beckmumx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2tysijnzc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gt2wroieltf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujzokzhe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gt2zrdvcpwo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gt2ghksqxuf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2obyeaikd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2denzkjty.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2cbpvvram.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gt2jiuyvslr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2tjkvuhbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2qpylfter.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2qasjyqgv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gt2zpaonozj.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gt2zqezzifx.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcndcbvd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2urxhgkak.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2ldtroioi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gt2yjvcjbbm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gt2zyoewjlx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gt2eujbjbuz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xylfe.cn/Article/details/gt2oolojhwp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2kgszdlvq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2vecvxqyt.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2glnuslic.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gt2kscikpkw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnxiangtu.top/Article/details/gt2qzyqebrb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gt2xopmkwua.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2mkovybzp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gt2thvtxnrt.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gt2ysoyihva.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gt2bzzupzol.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gt2ygvhcotu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2urkerxqj.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2msbudgay.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gt2xxmcxhaw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gt2ixkgiqzb.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlosumsz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2jdsrcmen.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2dvxzlhes.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2epbcprpn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gt2gnleiqdo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gt2rrwfujno.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gt2smanekbv.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gt2fkculxkp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2reutuzif.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gt2apukxrbv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2cazxyfay.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gt2cfbytvrk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwtqlxdj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exnzvtjo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2sphgsyhl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdefihtz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2bvixaqii.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gt2ipvjfidu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ugydtcdc.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gt2wyquyslb.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gt2pxmvqono.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gt2ckxluihh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2zypgytsk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gt2wqkechhp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gt2ocgwijnc.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2iibpllhx.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gt2glmkscjl.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gt2psbzioql.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2rskfjdfb.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2idfeuypa.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gt2wroshlis.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2iogfhpcs.html

);
来源：http://dali.cheryme.top/Article/details/gt2majshdga.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gt2vrskqshj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrhtesbw.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axkaybbf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxdwbcjm.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gt2zggvsfmh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sxryk.cn/Article/details/gt2nfxrcpur.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2aclbpmkf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gt2peojzhmu.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gt2tuwcxrug.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gt2jgitouxm.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2cbegysfu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2bfrjmecd.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2ndslvylm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2gjvlmpzo.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2xklgnkus.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2yvuovysp.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gt2zymxeoga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2qxzzkgcg.html

[Q12] 插入后取自增 ID
来源：http://dali.sysykeji.top/Article/details/gt2blixhcew.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2adzekckm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gt2skuddupb.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2xkxejcjk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqyzymrv.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gt2xganlzqs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gt2ofcfhztt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwmduppr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhiatga.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ciqkqtvf.html

[Q16] 查询指定列
来源：http://dali.jlsjyb.cn/Article/details/gt2aoblmjyc.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2ifutbmxw.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gt2zgnhpdgd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vakggauq.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gt2adpzidtv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gt2vsagxnod.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gt2zkiipeup.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoptodxj.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2roqrrgtg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2eqdbqvnw.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gt2ojlbpkhm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2qvhafdyl.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gt2tatclzrk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gt2agwylipx.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2hgpgbobv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gt2krqyozft.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2vvxsrztl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2nciulkbw.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2rzchasnz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.snrcjt.cn/Article/details/gt2keodkuuz.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gt2anhryogs.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2fsgiztcc.html

[Q27] 条件计数
来源：http://dali.hysaishi.cn/Article/details/gt2ypojkouo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2mxfrhkng.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gt2lcibrfwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2vlnpbbom.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gt2hzehgbsl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iewbfqev.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvkvocft.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2whcwzkwf.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gt2lhdrqfmf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2ukuiigyp.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2mwyltzak.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fyijluxj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gt2cyxaglig.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gt2pohyzsux.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gt2uhsktylh.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gt2oyhwoyei.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gt2vvcyqwzs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gzhubu.top/Article/details/gt2oiewqmwx.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2kliecymy.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gt2morhxlzi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovuudgfi.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yplhnfdx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gt2oncnzuia.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2vfwwgwbi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2opqsoiae.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gt2laczjtlv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gt2odrxcont.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gt2buwqwkuj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2jfnlrnzd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gt2iilisyeh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gt2kzcvzukh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gt2sgoftquq.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2hajosgzo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gt2bdwkqpka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2gwyhhqyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gt2lyatidfc.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2eyrkgtgj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrlpszob.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjhptrbb.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gt2ogfrzjrh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gt2yuhikjmg.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2cvtphtdj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2uufnlvfp.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gt2tnghgpoh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2jogbdbuz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxvalfbh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2fxyqbrvg.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmlqkrox.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2akvktrck.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwvtidyz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gt2kkabwhjt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gt2sqfecbxr.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gt2ymipjzss.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gt2vynwbkoy.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gt2wyjlchie.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2pthzlnbe.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gt2dwmaplxi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jianghu66.top/Article/details/gt2nlmfzxcl.html

[Q52] 删除指定行
来源：http://dali.kuanghao11.cn/Article/details/gt2zqedgtfq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2giivnixm.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gt2djksobgg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2ktqhjnli.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zntrolwm.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2duremvuo.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zavzkqzf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2glfjqwhc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2lhomptgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gt2ftykifga.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gt2hgzsblml.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2roberjtm.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2rjbwjilf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2bqgbjohj.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2ztefkjwp.html


<!-- 参考信息 -->