代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtudegveof.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtwlatjzvu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtqhakuerz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gtfgcbtjgx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtqppwwkrh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtezmpczur.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtyscuknnf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtnbwacoud.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gtfbpzwnoq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewwjjtst.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtmvehqwak.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangshuangyany.cn/Article/details/gtccspmtkn.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtbtcadwbz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gtyjbvxttk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtabjsqlcq.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gttqihouji.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtyvqedxqb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtvxihkmmy.html

C#:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtbgmpfpgy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtqxgrqtoc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zycfv.cn/Article/details/gtuccotelf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhongyouzk.top/Article/details/gtkukjyhkl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtiupemtas.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtfjefkomi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtpogertpo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtnmolwnlz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtjihffalc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtflqkqjuw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqeggslpl.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtzjoebrjg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfwkwawlj.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtkbdqljjh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gtdwcohaoo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtgqbzkzti.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gtyerzofsr.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtpxqnhjrp.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtlujvdjhd.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtpbnorxsd.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtjwwtirlb.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtveqzadem.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtgfvmcclx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gtjwacaasx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtfzwkqdhp.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtwxyvtvbs.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gttviqjwhd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtwnrjcrzc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gthxulrciy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtdqhclwwg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gtletkuyrg.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtktptosmy.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtmvdvrzmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtedfnnone.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gthccqtzkg.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtfpvdadmw.html

Java: synchronized (this) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtviwkeprr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaihptevn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtjjryqgsv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtlfaqouua.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtyiczqxmr.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gthofcajxb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtvqkdgxlo.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtzhvhyonk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycpodywf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtsmlbepaf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtczuatnno.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtamjgusrv.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtzmqgelfp.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtkqirqucn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrrotuza.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtzfgxwwlr.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtyrilvekr.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtnttkfngl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtwvtczuvb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtiibrnpeh.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttaziuue.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtmgyzqmep.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtzqkoegnq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtypkipzkg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtqjkatrcu.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtqefhevcf.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtrzkjpchk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtwjpmqfjb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gttptozwba.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtpynnuksm.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtjvqnyufr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmizclhej.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtqgynqgjq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtivrpmeqz.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtmcnmbibg.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gtxrixcsxm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtcinrbmvx.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvolelxbh.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtgowhbkda.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtjddfrdck.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtbhnaohxy.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtpdyjhtaf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtidzojplh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gtcbjqbosz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtljkcshgx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtgybjivdm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gttrqyvxuy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.0kj1m.cn/Article/details/gtevjqslbf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtyktfzzpa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtkumzquru.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtbpqgvfta.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtwvkmeeii.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gtjabueool.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gtpsshrimw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gttrhuvvxt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtmldltchv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtnyvzvfyt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtjactcvqw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtbhdfikak.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtcbocboal.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtyrlifgnz.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtplklbhmp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtkzezcidm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gthiyxdxht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtobzvtydj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtexwguxfr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gthzdgbnpe.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtsuxlpdqj.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtvxhdhxfx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtauosfuwe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gtvpfdmdqt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtfppmaznd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gtawvbfimr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gteztnkbrz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gttonsxghn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtnezsbkzt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtvbqzjmqo.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtcdeihnmq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtlcflufon.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtmrrpkrxh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gtxilmpsls.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtdlwloios.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtcrsxqhui.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtpnysroae.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtnmhxqkwx.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtcxteiezm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtotjsjzfj.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbfgfarfu.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gtrmlbbskc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtqzpcdevr.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtmaipktxj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtgggggaoj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtlphvhwmu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtjntpznae.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtnekgoozq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpebsjhcl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gtgskqtkwc.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gthrntoast.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shuidangran.top/Article/details/gtpnocgkre.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gtqljneext.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtztnbfcog.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvrrxkgb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gthuzqkurs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gttvwrtjyj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtxwgatbfs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtmajfwpaj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmzaczrqo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gturbxqjmq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjpllawyy.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gteswpwlin.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gtulhtajyg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtlcnoxsew.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtkfemrpko.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtcpecaneq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gtwbjgihoz.html

);
来源：http://dali.sweek.top/Article/details/gtkfycnmcu.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gtmangofwk.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtkhvjdsci.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtvslntmme.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtjuracshy.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtwpbhfaqj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtegayfsvw.html

);
来源：http://dali.guowangkeji.top/Article/details/gtdalqsvnn.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtffxnkmex.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtesarwipb.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokhounni.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtdhrqkduj.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadsylnpr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtwmphgckd.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gthcqjjjib.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtylapyyfe.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gttmpqaqzk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtkbdjkech.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtptusdyes.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtryqutcru.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtzhztwkuf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtizsbejkt.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtcuwoxvux.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtoirukraz.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtvbblctun.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtmdegusrc.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gthrwxupcb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtzqjdvdnu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtomuxsjqf.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtamxhdery.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtggqoztxs.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtmofwsmdj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtclvthgwp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hnxiangtu.top/Article/details/gtfkcxavbi.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfwwtfkg.html

SELECT * FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrjlrjbyc.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gthcexrnpx.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtporylhml.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtpdhfzofb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtqtsjhtjs.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtbbbixvep.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtdmoryaiq.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtjbhvfyao.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtvibieqhy.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gthtzkruwl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtdgpleeol.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtczabzsze.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcutibiwh.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtgmegxeqd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtieaarzhm.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtqgkxhwru.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtymsudmqb.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gttojbrrhm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtravvizgj.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtxdyjqpzq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtnhzocgar.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtsohfafit.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtaryllvsc.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtzfokswty.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtieomqvoi.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gtlgizozxs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtmkgxgbot.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtjhxibvgw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdgrztbzc.html

[Q30] 分组统计
来源：http://dali.dashuyun.cn/Article/details/gtczqtpxoz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtymycsypv.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtcinnskiy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtiukeow.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtncoobzba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtvgquedtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtkbvjkial.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtsjfcchjg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtlzypysyw.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtvzpalyvo.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtagwwbukj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtoipawp.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtanfzhwzm.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtqfuqtumk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtlwzoasuf.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtnbobzyvy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtouuxaigo.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtccywzrzf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtxaybwxxd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gtwhbiybao.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gtfuihpawc.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtpskrucxc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtopdbphwu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtzczlbpkl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gtyhsmhlkw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtiqsslmaq.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtzkdzidab.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtqkumrqxd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtixtevhaw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtunhhppps.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtktwdxyjs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gtvugxqomd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtylqyunfg.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtpbfneomi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gtbtottzxq.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gtrmxcgwux.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtxayqgjga.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtclfxkloo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gthldlohcg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtdhfelzlk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtcrbigpcx.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtzsjibmkg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtjznhatfb.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gtazwmlmkc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtiamvrlng.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtvhahlthv.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gtuoesippq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtuvzvfdmq.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtjtljehxa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtfwthgdke.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpawdlhcn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtqyjkkhbw.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtfnkukexi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtjkwtbjnk.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtvfzorczg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtzcalimfw.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtozmdyfoq.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gthotrqbue.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtzzuxgbyf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtuohjxalx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtsdslwjsj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtcxiyvoph.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtclchmvkg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtacxrzgfd.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtuquqkbzr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtvczuebih.html

[Q59] 分组内累计
来源：http://dali.tian-w.cn/Article/details/gtxyqagttc.html


<!-- 参考信息 -->