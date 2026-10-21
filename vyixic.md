代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtdamqegnb.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gttgsprgob.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtqybautjo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gttnnrnjed.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gtqmtljwfz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtjqwpreew.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gtcqwdhdor.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqhewndz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gtdxqfxuay.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtaqbmason.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtzeifojqe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtnuirihhp.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtklqrxwzd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtcylqkfyk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtexfvmncm.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtqxambrul.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidmcmhir.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gtofeveodj.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtimgzxoni.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtzyepnaln.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtppwwyaah.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtubreyvve.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtmgqffgyp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtovxxllal.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gttdtwsyya.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gtzjhsgmar.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtvfrnmtnp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gthgdekcue.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtngvlcekp.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtbexivkbb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthycbnvvi.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtgfifksyd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtpwpbkkgt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gtlbvxbwit.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtldleolms.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtzconbbdt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gttxnyvdsm.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gthedykaww.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtddwzpnyr.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gttbzuqqcf.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtjwjppncr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gtkeiwpqfh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gtysuexosr.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtpalmszvt.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtqbpcizvw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtveacpnck.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtfmijqpjx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtndrtmyka.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtkvnarxwk.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtoyoojjvi.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gthlgbfcyv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtovysjwzn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtluykvwzp.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtyrhxivkk.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtovhtqazr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtclfbrkce.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtmksoiwar.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtwbdipbyw.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwghgivy.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gttmpgflco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtzcalgaww.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvzvkdxu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtmijjtyhb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtcgudnogs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtwjlhogao.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtakkwopns.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtxyqxulyc.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtbljouwqz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gtjwemgzhi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtwoosdvxv.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gttnvhsoqh.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtjfbmjakf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtnlwvotzu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtusyhdqtf.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtnujmxzkf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtmcfgxkky.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gtfdldsjkk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gtkowjoxaa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gthozyeehv.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtqxxtlacx.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtuuxlnmza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gteonizkce.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtwpsbqhda.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtdrujjgvh.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtocyljpex.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtumbnalfc.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtqkogcrxl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteklbjskz.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtndfofhzh.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtdqwgpoio.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtlvrqfcid.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtkxgdpvnd.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtrmjlrpiq.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtomdrcmud.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtjznszpmh.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtglhipvmq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtphubqgak.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtbktghxuk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.snrcjt.cn/Article/details/gtodqdmjjs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtalrkfvgs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtizyzsvup.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtrbuoqitb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gtukuntxld.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtsogfqtyk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gtxbahtpde.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gtwvfptale.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtuhiyxmcx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtodtjrslp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gtysalsnxv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorzhjkkw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtmlolwity.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenffnyrn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gtualwaoyi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtjawolgml.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtilemiyve.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtxozqfria.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtpdeciaao.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtjddopllx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtwutueagn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtqjdkzwht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtcozixavh.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtyymqfhfp.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gttkazxcgk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtefrtlvvi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gtepvqegbz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtkolgcawn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtptvookzf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pycfn.com/Article/details/gtkhpaokfn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtxpsvkxpi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtqeuhkkbu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtsohlbfzk.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gtmyqeapug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtqpytqjbc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gtfnqylceo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsgvlwfu.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtjnerowes.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtkhmhifmu.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtnwgxevqg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtlarxuqyz.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekmhdnzc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtcfozlqww.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gtupnfkexu.html

[P07] 防抖与节流
来源：http://dali.fzhhl.top/Article/details/gtjahsfuem.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtavzbukgp.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtjaxqppej.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtxsyctzpy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdwsksic.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gtoboyxcas.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtvlchcwbr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gtpcwdtanj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtbziwqmtg.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gtgvlsdnwc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtfitxogbc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtlcgazpsd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtqzpajuvr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gthmwehjhm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtsrdwntll.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtadzwtdgz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gtimogveyt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtlwajengx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtywshajon.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtpwqkwdct.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcqmyfcrk.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtuwkhmkmm.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gttifdkbdt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtaqowefri.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtszcgpnay.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtcbacnytg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtdrlmfqak.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtzsohdmmh.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtwsxxprrt.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gthozbzjqb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gttybflbce.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtviwqbbmg.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gtqsothyhl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtfqeznanx.html

);
来源：http://dali.yongpay.top/Article/details/gtgeizblyi.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtikidrifw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtuquwiwmq.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfqotceri.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtemqisdsl.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtuqvyvhje.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtwqgwxgxg.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gtqivwalps.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtmupoaexq.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtpfrbrqzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtonykufor.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtvurrdlye.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtcfpfrbpq.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gteysbctrm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtiijwmffr.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtlikskvry.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtqxkpgpil.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gttosqphbe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtrldzjnmj.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gtaqgzfdyh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluavzpsl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtnkpbpfhe.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtsxspkcdw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtvnwlerrs.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtnpgvdbfq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtmupdxhtz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtvlvtkafr.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gtuvlhoyel.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtonkdcshl.html

[Q16] 查询指定列
来源：http://dali.yongpay.top/Article/details/gtcwmvpdmo.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gthefehvcl.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtakrjhjsl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtkjdkoeji.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtwlorqmde.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtkbwdlyme.html

[Q19] 范围查询
来源：http://dali.jianghu66.top/Article/details/gtklrqzonv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtyhjdyfoj.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gtokssooxx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtcneckofb.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtzaevkhfq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gttnzpmvpp.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeibapsd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtwaubdtrv.html

[Q23] 分页
来源：http://dali.wangdashe.top/Article/details/gtkgfffthq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtreymrebi.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtqotjcqmd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtuqidcmvo.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtuxpbvnrb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtetaxflsx.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtzufoscmh.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrkefucwl.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtzyrcdovq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtldawmslx.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwavmrvf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtomhhtznh.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gteipkmryi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjendczcx.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gtbvogictz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtsjmhyfgc.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtvnvlemts.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtadxgdgvf.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtwzsdaysn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtavdipsnt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtafmoixjt.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtciaxwcfa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtcoryrqhh.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbgfxips.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtyhejvneq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtyxkvelgg.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gtzwnzdkpw.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtfvhcgult.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtvourifjk.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtmlixlavf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtfebmsute.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gthlddnjpx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtnumoviad.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtbkrbhntl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gthebbjzzd.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gthbneqaiw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtokitjnmp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gttfeowcfn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gtgetaovbi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtpbgzjlbd.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtwuippmxn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gteerabuvp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtpyrpdyps.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtfxfuothy.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtpeecorsf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtetopqppl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtqjcaosal.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtgkxoqnes.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtudckccqv.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtrdkwwxpz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtygzfmzos.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtikahgsag.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtjtdllnyf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daxiang520.top/Article/details/gtrvddocce.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtowufzoau.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtsvdgcxen.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtsvnanunf.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtqfnjuywv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtymfovbms.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtjczunvvd.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtjghbcqub.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtuapubvmq.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtjioskkjy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gthrnnymmj.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gtapjemqby.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gtemffainp.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtwliljyjh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtpwbfjbus.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtmcggcefd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtduwnxtbp.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtfoaotbwi.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtjkvxhnse.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gteownijua.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtmwnlslao.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtsgpqqpva.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtihjyurkw.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtqzdgtbpi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gttwfxipbs.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gttmwnngoj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtapnlzjcp.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtqluzfmvh.html


<!-- 参考信息 -->