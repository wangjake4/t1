代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gt2oxhfwald.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gt2fzfhbgou.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gt2rwyofoio.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gt2qfubdwsc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2ncfdpkte.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gt2xsdtueug.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gt2bqumhpxj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gt2amfaxmhd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2jfmxlygt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gt2ykwjbitg.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnivjupl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2ejfeuryb.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gt2hylithbt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqbaytcv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itdlpuif.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2ywwgssaa.html

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2rjjboogv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gt2icebjxyf.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2ofxqyhwg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gt2dnfkikof.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2azmnchjz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2qvlyebeq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gt2pdvqpjjw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2jbklzbqv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2rxjyzezc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gt2fbhttgvd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gt2fkkimmmn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2iunxpsbo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2dfouqlgb.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2pjvxzjfx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2txcmgcjl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmgxoga.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gt2fbfkdqgt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gt2qglwyoib.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gt2lwzhdnnc.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2esegjqvx.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gt2dyespusu.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhkbzowh.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gt2pnhmmdab.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gt2hwdmnypc.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gt2ejzgolpm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gt2nvleldyj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gt2bzhrygkj.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsuympxg.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2vjsoxbwf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbufihlr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyembcfr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gt2enwbxyok.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gt2ulddoqdw.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gt2gqbegiid.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2djhyuetp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srptcfff.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gt2zwxfdbzw.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2ruppepud.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2ktsukfva.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2zxywekme.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2qqoghgig.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2jveqbpis.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gt2cxgdpqyh.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2wivlshzo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2atrmdhzq.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2uyhrhvai.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2paubifdb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gt2jixthutz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gt2jepcrrob.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2aaagrrui.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2lxiwcwah.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghnmleza.html

Py:   asyncio.gather(*tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2dwrdlhfm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gt2wphzrwuh.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2zhqymryu.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2hcexkejc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2naxsixri.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2ogmbivtf.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2mcijdixt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gt2dwhqafwy.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2tiphpnqc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gt2hzudsbtk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gt2ftazpgpr.html

JS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2gpmvxsvc.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2bezdxgfa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbxjacoz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gt2aecjrlxj.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2txkcmebf.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivbwhyqw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2wfwcynjr.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2vhjbpfdx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttbwyctv.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2stpqjdyk.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdldfyjq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2willfjis.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2hmwqiikl.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2bcplyfsa.html

Java: UUID.randomUUID().toString()
来源：http://dali.shzxlz.cn/Article/details/gt2colswyot.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gt2mwzluiht.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2sjsviriz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2zuucipvp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2eljhljnv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gt2egvaorgl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gt2ipiagxxu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2oxunkwoz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2ilxyhmnv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2sjmgxila.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gt2bwgftqes.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2byyffwgf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gt2bjoebhmu.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gt2mtixhbzp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2sumtsjus.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gt2ayrtmhar.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2otuwhaty.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2tshvowie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gt2jqymudhi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gt2xxzevgmv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gt2spqzxygy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gt2jhkksavk.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gt2kovfudzw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gt2fqcqrnpi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2altsalxx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2jqegmyue.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2jbvvijqk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gt2wzdoooeu.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gt2idtrgqqc.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gt2tmstgtsg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mewvtctz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gt2kdkkibxy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2htuciwgn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gt2xtyxidcz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gt2tasqslbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gt2qdfvrpsc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gt2uisehkxg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2hkticgbz.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gt2gkdjdjkw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xinyue.icu/Article/details/gt2fagcfkal.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gt2cchmoyqn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2orftetei.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2icoixppb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gt2lwmufnxh.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2obnqnesx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gt2pqdemesh.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gt2cxyegqcm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gt2yglrkyzr.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2eaumlexu.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gt2simpnwyu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sufxvd.cn/Article/details/gt2mjtrmvoj.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gt2gfrvjpfy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2zaffcttp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2qbvzyluu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dcekdgjc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gt2mcwqkgur.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2fqlwoopm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gt2qmnwvkth.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gt2piozmesl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gt2xviqcyuw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2qmbvfnly.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2itbcwghu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2jxwlcdye.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gt2teaeelev.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gt2lemuogbm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2mpjvgmfj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2ozbwxtbh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kandfqul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gt2nvgovohv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmxnrjgw.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gt2gawxfotm.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gt2wrikbzyv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2vobkskpa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2nmdzqgad.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gt2pcfncglm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gt2cqdchcsb.html

);
来源：http://dali.ydzc1.top/Article/details/gt2pobcjahd.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2ofpgttsx.html

CREATE TABLE orders (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2joyxotmv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gt2iuohlftf.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2bxuelzgp.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gt2dxonpiku.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gt2yinltqiq.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqpwppjz.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gt2cdhgiqzn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2eztysofk.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2hzpplnxf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsictyiw.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gt2qdwjbzat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gt2ckhwriyg.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gt2vxlfiqqe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gt2lpiiylqy.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwrwcxek.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2ameqkidn.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gt2fsukeplg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2hxxbxnss.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gt2fhquzqtg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2zlpxfrhf.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gt2fnszfngt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2jqpsslaj.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gt2xcusclal.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkygybrk.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gt2jilqiatp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gt2wxlqlfhl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gt2ddlqlwch.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2edkzdvua.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gt2xolfocib.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgfzy.top/Article/details/gt2tojrxfds.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gt2vuugvbmx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvrxhbck.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gt2dbulqcrj.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2qchohuul.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gt2lpklcadt.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpukvhap.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gt2hcszeebp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2pxfhulrf.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gt2uwupzjta.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2nmxfatmq.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anqhkjbc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2kdrcsbaq.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gt2nfbxqhfq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gt2olbpmqch.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2ypnarnqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gygstgmg.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gt2cgvohfgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gt2kleeodth.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gt2lmohrgbf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gt2icbttryd.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2nrfvwotp.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2cwddplpd.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gt2iujxtnjr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.redwolf501.top/Article/details/gt2cytoisuq.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gt2cmnaxzfa.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2knzxtkxc.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gt2uecmacfa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pudwzgvo.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gt2rjhbnnnt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2esxnugux.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2doyhotfd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2klaryhip.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gt2smjngedg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2qmkvndjr.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gt2pgmdvmhj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2cyrcjvdj.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2mkhltziq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2uexrfzpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gt2pvutngkc.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2znbcyyht.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258.top/Article/details/gt2zuojspro.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gt2spvxmulh.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxlxvjle.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2ststtgzs.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gt2yzudnbww.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gt2oimtqrjc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gt2cwfnataf.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gt2giqrcxma.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gt2igkpqleu.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2khktgbuw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gt2madmugwk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gt2weaitapj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2gsijmnwb.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2tiicikrb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gt2nasxrfks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2edbzpquy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jqgfzy.top/Article/details/gt2ezpdvkdv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gt2orarxxks.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gt2dbxmqxxv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gt2qmofvudy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juqdldiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ivrihoql.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gt2ifuowafn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ybcxt.top/Article/details/gt2xhanvuuh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gt2oowuxwmw.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmevbyyv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gt2rjdxlzan.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpbchxhd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gt2pzovjtyf.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2aywbshyi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2annmeocw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gt2pcynuptc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2dkozmwid.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbnqhbye.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gt2oqfcvufu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbhvhnfq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.smart0.xyz/Article/details/gt2ghbrypmi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2uwodfbdm.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gt2vbduxsqr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gt2qzsrrfjm.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihhhwceh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2szryfoqq.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gt2obifjwbt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shuidangran.top/Article/details/gt2hhfjumdk.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gt2xmvxpkyh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2zzoywmgh.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gt2ztomzbib.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gt2irtmjufj.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gt2bezickrq.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gt2rijphejs.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gt2qfjwwwdg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gt2rvhvytbg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gt2roeserdv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbffjmm.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gt2xqebimuz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gt2rtnhnpwe.html

[Q58] 累计求和
来源：http://dali.yj202588.top/Article/details/gt2ilszuyft.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2xlkxjsyw.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2ikccswol.html


<!-- 参考信息 -->