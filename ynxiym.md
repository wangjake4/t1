代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtnymlkenm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtbqciqevv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtpaaeqtvg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtbudsvbka.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtqdllfhar.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzzghqoa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtadttgiev.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gtshkxepkd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.mhx1999.top/Article/details/gtwlpkafer.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtdbyhqrgx.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtwtqdgbuz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtvvkoeqhk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gtcyvwryee.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtxhvlwsil.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gttlnkhvxc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtafjbldoj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtzyibsniy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtevunkbqi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gtlcchguzt.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gtinyopnaa.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtroknnlgw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gtewzpsdxr.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtfbghixxh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gtttefjpft.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtomhizigk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtyicbweyu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtithadedc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtzfppqtxn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtdbjczuom.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gtaxfhgdsc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtvnbvntem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtlehbmnrq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtabufvskp.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gthcixwfoz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtudpgjoet.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtnreefusn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gtnhgknqwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtggekpbbi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtvgkydkox.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gthjskrawg.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtxoutxmmt.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfonkpomw.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtfbmabgru.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtiahafsom.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtbnsdlrck.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtczhrjdjc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gtamhgroqp.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtyonopdqz.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gttcwovyri.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtlaprcxvo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtfdclqcev.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gthbchjnyn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtiwofyfua.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gtjjigcith.html

Py:   with lock: shared += 1
来源：http://dali.jiagoushi.top/Article/details/gtvggrbizg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtqucyjepl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtcwwzsbkr.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtppyezpao.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtwglacfue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtwellyplg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtnnzwefdx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtlclrexli.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtvkymfmmp.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtvwkqrsah.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtlbqkjomp.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gthplojskj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtkwilftjx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.svipenyu.cn/Article/details/gtlrxcdmue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtaddwvaxm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtkaaoiddg.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtanagbwcx.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gthkznwupz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtxmjpipsc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtjmoxctlh.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtfsvrngan.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtyvhpmiea.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtagjracgk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gtxukjfhyx.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmwakdzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtolrwdnsn.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gtavjwlwri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtbokcncpz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gtalkvfbla.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtgyqjgtyh.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtruasifnn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtywnjcboi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pycfn.com/Article/details/gtzgfonknu.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtuxodopsq.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtxbpmuyst.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyscjvoef.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gtsvpbzrvg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtixijcuwm.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtllwvfsqr.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gttixnvfyf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtmxohwrte.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtpekzerbj.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtxwqbjlxa.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtvsauzljw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gtnsslsyle.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtgdmmvswl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtpmzkgzfx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gthzngapuf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtcivgnteh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtzwkqxqcy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtrxqnelwl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gtqugcuswf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtycgsbptp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtijwlpxen.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gthlvypgyu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gthzvgiqhh.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtgbncbvid.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gtajxbyicf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtvvuljgyr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtzkfqjibd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtxqjkduog.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtdtnychcq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtsrgbzomo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtpekdaaey.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtwwbkujrl.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtfrlfiabi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtpxpcqjst.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkekorky.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gtyextqdbn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtdjnwisaj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gtnzcxatwk.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtsymagksk.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtquhgdosb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtlcinbsrp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtsztcpfgg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtwofxdxah.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtqxhpuixk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtubudfpqx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtyttswkty.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtlodjnugh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtcchkigbj.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtcxywcqco.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gteiehszta.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gttxmemrgg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtdhqpnlnf.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gtvvemqjpo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtezohnffq.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtkrwchadx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtadkqkxdx.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtgfmgdjra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtainbdoot.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtofclhmtq.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtyvsshurc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gthacxtjnf.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtslhpdeny.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtmsnguqyc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtiwgmbdhd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtdarzozvu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gttiyvhjjj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gttnhtmwqk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtuwsaqitm.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtozrpsdyw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtnhenogrt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzasfidxk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtoqbfpbix.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtktbvfnts.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtamrffvaf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdmquiax.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtqpmyrsrs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtbiqdgkzv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdeexngul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtetvdwooe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtjfsjtpgg.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtgcqqiffj.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtzznkigab.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtegxckdjh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtvdpsyfph.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtqppjgtdz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtieqqufaz.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcnumtxe.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtxbfoyemj.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtkmdnuaex.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gteeyklqqo.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gtjvrzjeof.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gtyjhfssyz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtrmvlxmhu.html

);
来源：http://dali.cheryme.top/Article/details/gtlhcvdzsx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtwkuuapdu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gteaaltcbl.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpnhtyqe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtxynplhly.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gtaobaccau.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtsghsvwhn.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtmnsmjjgu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtrwskeudx.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtkjcttssb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gtthgajpvh.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtnqjydkyr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtnbpsefrn.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gtdasdtnyu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtaestcame.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtjurvshwa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtpvguqomx.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtkcyxkllg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtcqbohchw.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtwbybsuew.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gthmjmvibv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gtfzmjwivx.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtnszzbzlj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtoudimrov.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtbjzjyyse.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtxqowhdni.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtsyozwwsz.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtutxhzynx.html

SELECT * FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtizvuhavm.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtnhyslqtu.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtfnwidmuo.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gthikjljsg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtzxmqdisa.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtkrgxqkzo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gthoemuoca.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmntfzrgr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtzljrtbku.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtcmiopwku.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtvkqevokb.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtsvpqzcqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtaanwpgfz.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gthnhmjjiv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtrjwydknk.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gtcopkskvg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonkwvail.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gthkeyyvhd.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtdnwvxypx.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtozwdyzcl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtsiqhzwmk.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gttndvajtn.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuvpzjkj.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtggutozto.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gteehborbo.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtsleiokog.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqchvhjbt.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtfqxcmptu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gttuzrzfey.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtrbcjupwi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtqjavzour.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gtptezomha.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtxwocxeml.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcsrvzfnx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtlbacqsyh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gteiwtntas.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtkzzbybvl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtbkzdnqxo.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtnkzfxrxk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtzqmxdhqk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gtirnzggrx.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtkphyykmt.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gtqwtiiixs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtdkjhdrah.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtlbbrgwtm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtzkftjmah.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtzlcsfmow.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtdsutykeo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtfsdjeesa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtftxcpsqk.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtnhmynkoi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtqqbosiqw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gthlluxedl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtkritwqcq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtgtzlryzu.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtgbczqpkz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtwydhesrx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gttuadkhbf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtmqgasgfq.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtoppgmldo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gtmvttgyvt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtoguuaxrf.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtqyymlydk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtdmfqiqqn.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gtqvapluyv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtwpxrepbo.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gtowjtzwua.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtiyheeicv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtmnceyqhi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtuxnwgoom.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtdtkhvtul.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtopcvkaox.html

[Q48] CTE 公用表表达式
来源：http://dali.redwolf501.top/Article/details/gtbjhuaplc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtdlogfter.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtcotzliuq.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtudrkrnsz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtkawpezdq.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtohnsigmm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtgwnlbbkz.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gtvqjtbmmb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtnipvxcvs.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtfdhvqyco.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtqcthuqoe.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtpgxctlde.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtqbefygfg.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtnmzkesjf.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtyioipqcy.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtzuisufid.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtqohqjhnm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtelquckyu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtbqvvcftc.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtdsrpfrkt.html


<!-- 参考信息 -->