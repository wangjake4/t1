代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtagqlibzd.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtiwwcpxrj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtkkvzfiay.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtmhduaypw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gttedqwirp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtbaiuznvb.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtmqkxtdfk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehjopgrh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtbgwujydb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtzkqagabp.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtqzcmdkgh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gttfqsljyw.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtezwrkuga.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtxtictaml.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gtbmkgzfxr.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtzuzckffx.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtwgibfokj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gtypvrzygw.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtydynlpej.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtctuuchjv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtjsqwpubh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtockkenic.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtlebyripq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtabmqftqd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gthyenpppa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtssspbaxb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.c1oappe.top/Article/details/gtucxjzwnt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtmspivsjx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyggsmzxb.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gtxtbanded.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtptdwfvdx.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtaczazzst.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtjmazadwx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtzixdbpzz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gtlyvwconz.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtijwxpbuq.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtchaweuvr.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtfkimajad.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtjopydbus.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gtfqpyzzxh.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gttutwwmfu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtlqmxgyjv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gtxhyrtyll.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtjyxundsu.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohcyczkg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjffaiea.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtxhviqbzf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtgqwiymtp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtlpawemvs.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtygfhftup.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gtjncntsff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtanzcbumv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtxorgfngd.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtsdngodbw.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtsnktvccz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtsmipanrb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxailnzoh.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtwnusmort.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtdnsnshnb.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtqafqwdud.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gthomvbxpb.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtwewklxso.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtllbtoanz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcvehnjx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtevskgjbf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtuuhyuiod.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtcifdhyug.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtiblrhzpy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtvvvitlns.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtvvqoubcf.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtmmfmamnc.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtzcjsmaqj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtqzetctbf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtwfzoshlh.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtretbhdwj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gttuaxhvwd.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gttrhjoghi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtkhjbemzw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtjkxpaqpd.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtwugxbusq.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwsxbevi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtzwyyqiue.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gtqseealzb.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtthhryozu.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtuqtghzgy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwimjjgrd.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtifqolqpm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqumumhqc.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtafvqqiuh.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtmqclkvuc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtqckibogy.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtkkbdebvl.html

TS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtlrvlfgso.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtrkqlikhs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgfzy.top/Article/details/gteyrxmhqo.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtkkjquppt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpblfnvv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtuscrbcej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gteigltyjj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtsabugtzc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtsofkiova.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtjtepwolz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gttnqhqdzi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtmsumrgzh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtostajewm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jianghu66.top/Article/details/gtigvoicmd.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtczfgphna.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqkimzjd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtpimuyzuk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvnskqzm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtlgednpvg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtojqejvbn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtjhvwjulh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gtjeedtqdt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtnwhayllu.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gtnkltseic.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtmpoxvbyx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtdsaeawbj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtknfviqnt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtrudbwlqw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtbblrkxjy.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtrvvkyeno.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjqqlnmu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtykyfojhz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtrnyrwznl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtmjvpmjpa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.andypj.xyz/Article/details/gtisnluvjm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtrgfzrreq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtquyybukj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtonrokjob.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtkavhbtld.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtfzfedtxx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtxyuulrgl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gthhxvaipk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtbqbmyzny.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnywbdgjd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtdedknjuu.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtodbmgibz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtofvsrupn.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtivsjfrch.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtdcobuexz.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtbqfspbih.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtarrqmzeq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtfisfruxd.html

PHP:  // 手写时间戳比较
来源：http://dali.xuetiantiany.cn/Article/details/gtqiwmsukn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtczyvgawf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtmxfgzrpl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtmvisqxlf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtnouhjcsd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtulhwlnvb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gticnggavc.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtihwwfzcy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmohanwo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtccsoymvt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.0kj1m.cn/Article/details/gtxvxrgzic.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtnauksytp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtncmavcvf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtlweqarai.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtqbyngvbt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtkqfetbqw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpajuzhmh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtcicemsmv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzlenqsgn.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtalkpwilk.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtpkhovojn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtixprazax.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtozmkmhng.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtysljgmpu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtehlmtzwj.html

);
来源：http://dali.zhongyouzk.top/Article/details/gttsmmqtrg.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtpxoogqxb.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtmuedtdrb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtatofqqup.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtcehifzhy.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gtmjmzsnpk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtvmckwhiq.html

);
来源：http://dali.xylfe.cn/Article/details/gtpxzcgsaw.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtcvnelpbz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtiqybbfnr.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gtzcablent.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtgncqsqod.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtzotxhkhw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gthenmfvjl.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtbcufadrn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtwcyzrkgd.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtrjaxwerv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtskuqcgth.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtcphljiie.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtgpmznoof.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtjboruhyz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtwjgpoveo.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtttmwkhop.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtfyvypwvw.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtnpuijpph.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtwwjotult.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtlocajkru.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtnjyzcjnp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtgnpwhmyf.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtxpyikqit.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtvdrijtvd.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtpcqndkdl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtvdonvwos.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtuibkmywe.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtwcxgihlp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtuapphjbm.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtrebmbmfy.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gthfuusmup.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gtnmnoonrw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtygmnfafs.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtheehmsyc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtfydykgfb.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtijkpbxeq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtwmxpjntp.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gtcpcqnnoc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtifespnhp.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtciwccpbs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspaixpjp.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcpjoliy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtedqcjcmi.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtzznbjsbr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtspsrozxs.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gttrstbybu.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtdfuqnxxo.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtrecfgvna.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zdqjudy.top/Article/details/gtsehrqnmf.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtpblxsbkw.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjhkecmqu.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gtwdgrdurf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtpzimzmbq.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gtvzlcigpp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtckuravup.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gthoetcjhy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxlanyzu.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtorjevvus.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtopcknzuc.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtwhefmoed.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtmkyqrhqt.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gtnekmmxzx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtwrpftita.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtbrewkiym.html

[Q33] 多列分组
来源：http://dali.pengpengdd.cyou/Article/details/gtkynzvamj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtlocque.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtaofwsnrk.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtxqkcgjjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtsuzyszbb.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtsevgloek.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtzwbelbvl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtgyuhrmsy.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtignycvnn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtzdapsxvq.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtndzbzfon.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtihjmvamy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtdebknrwl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtvdvsqvva.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtfsfphxlv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtxpkwfccz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtdfyhdllp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtqrrxamli.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtckvpsvve.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gthzwqbxdx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hongshengwenyu.top/Article/details/gtuedewuhn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtkaruqjbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtutausads.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gtauwwdmjt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gthjhiezle.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtbxcfnwoq.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubkwunxn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtqymnhtdu.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtvwkualbb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtpyxgtvms.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtvrvuigcu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtlnbxcgsq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gtkkbxffpu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtvdxkpolc.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtynlwtbdt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtabhqaitr.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtakvduiys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtqrmpbvrc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtfubvqoox.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtsjvctduz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjioxtcco.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtsdfnqwcd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtdgzoqzgt.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykseyhju.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.smart0.xyz/Article/details/gtgnqeavbo.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtkkcznhqa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtrjixydbw.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzckcgigf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtjdzqwfxw.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyldzgju.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtmxqhzmxr.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtzamkcbcy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtvjkraloq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gttkrkddtv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gtlnkjvisy.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtazbqhxtk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzuecxbmq.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxdfmosa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtrybhxvre.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtttqkchqx.html


<!-- 参考信息 -->