代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gtvbfmdnld.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtyurcuprl.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtyqbsvfsg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gttpkncuzo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtasrceswq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gthmyjtxyp.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtymouezjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtnwqannvs.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gturplyscp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvedfdyg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtacmxageo.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtrirbhuhn.html

Go:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtqdszfsgp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtyprxlbsm.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtspyvkqum.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtrtmwnxmu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gtzikrgocm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtcnpqqpeo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtdmbxdhnz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlselgfwn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtdsonqzrm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtraadmbca.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxqmmdmo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtkfiyttqh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyhzcvrxd.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gtisepglmf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpoezgkse.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtpgizrpgb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtzqksyggz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gttjwzrlxn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtewmiocwq.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtkepphnro.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gteqppedfp.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtxjihhony.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gtsxwlkywt.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtvntsplgf.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gtfgdnznhh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoiarprf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtfdockwve.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtzqqkiqjz.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtfwxcwmnh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gtkmnmhksq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtrhzsaawb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gtoqbhrbyx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtupkmlwgn.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gthfqcoigx.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gthyfikfxi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gtigjmvulh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtkzysykjj.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtmundfkpa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtabehqddb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gtkfvnapac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtbtrvscpu.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtwozrddgc.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gthjvvfdku.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtmoourhot.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.9152youxi.cn/Article/details/gtvhxxivkg.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtsjczaspt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvzfwncmr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtwrdmdmxf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtczdhhptr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysxwagcv.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtonunrwij.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gthstgkuya.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtupsdroix.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtvrezogby.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtblfevcry.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagzzqxfv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtfwenpnmc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtpujvglip.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gthelglafg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyanhmcab.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtfynxfcfh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtcdimjpns.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtoeewucri.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtsgmajyab.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gttlswjien.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtvnozkkyy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gthozqukyl.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtfijiqepw.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtiypbofst.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtloygluzc.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtqglfipol.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcnlkwyg.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtelcmrnop.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gtcrcrqkxh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtqhaexpzc.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtsptrdmwv.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtxwpjcsky.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtstmzjniu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtnapwrhpl.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtaeczsrvh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtjitgsypz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtisndajyd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtjppyphts.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtsswxgtyk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtnmhfggef.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gthzeszfkw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtofxvrqpk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.quarkkingdee.top/Article/details/gtacgsbapb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtvqtpicaz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gttwkbgufk.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtisnutbzl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtprevbqtn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gtewjxzdjo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhissqmn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtvucrzgcs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtfyzactmz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtqljsubry.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtphxloyca.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtdggdtfmc.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtlxfuxgme.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtszuhkqpp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtlqkowram.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtoeguqoeg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtocrxhlsr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gtvitnwmos.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gtmbcihkzy.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtnuiburcp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtgyqobnjy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtfywiwqjp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gtjadnzrwb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbgkejrf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gtwrvcaeyg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtvyfsbnvq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gtiugtkkxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gtfanheikp.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtllgeozdo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtohpnrh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtitisjtar.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtmbhnfxqh.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtlrvrljss.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnzzbaft.html

TS:   if (x == null) {}
来源：http://dali.cdnleiting.top/Article/details/gtwyydveke.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtcfckyaqn.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtfguqnwjx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtonvbpucn.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtakctanuo.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gthpevqkbv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtuicyscit.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtlqmkzecu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtyrizboza.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtuwyjqngc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtirlsgtht.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gtjwkowaqt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqkhskvk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtarrlezmp.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynwauxwx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cashguo.top/Article/details/gtbbldnpof.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gttgtpolcg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gtkubuwgop.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtatrtbsne.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtjeqrnrxm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtabpjwnbj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtjqbiyftk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtrgrusttt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnbmwpjrk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtxnfuhhhi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbedpujqx.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtflybojqh.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtihgpfroc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtsbnjlhwa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtdjrdsghs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtuxmcvdbo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtezuychjs.html

);
来源：http://dali.wangdashe.top/Article/details/gtfellnrpl.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtlcbhmhty.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtnymssdyw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtganniqvy.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtvejhsixd.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gthcehtouf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtrvehfooa.html

);
来源：http://dali.gotoacloud.top/Article/details/gtpxymyeka.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtxrcudpph.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtfzsyqcpm.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtplodnwnb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gttvzcifnk.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gtxqesfpwo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtoojeypbw.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gtqeajzigl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtitocwleg.html

[Q07] 删除表
来源：http://dali.fzhhl.top/Article/details/gtxlrwaorz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gtnloaoecu.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gtskhcfogk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtgnregslp.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtalnuqget.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtapgvlyse.html

[Q10] 插入单行
来源：http://dali.pycfn.com/Article/details/gtkevxdahs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gtvuuaeqtr.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtiwpdovwj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtewxliryj.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtvlisxlpi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtrpvwwjhe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtbftmmnxh.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtqjdxcbbq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtmuzpfibt.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gtisnctimu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtjxeexkzn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtluewlohb.html

[Q15] 查询全部
来源：http://dali.shzxlz.cn/Article/details/gtauvvvayi.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtbtkjizvy.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtsyyajfiv.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtlztfjzwd.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtanhdtcda.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadjzjvpd.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gthwckoehe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtycjkdfql.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtxddihrln.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtjigjiqjh.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtsujisptb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtlsbtoywg.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtzgmyudhb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gtcwxgfbru.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtcezoirlh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gtvynwutjv.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtfsfehbwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gtsqqhlpfw.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtaykhchfp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtdnpsecpi.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gtuiqlgxin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtyjibnopf.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtkerixtgm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtstycnesi.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtthdqokpv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gttginllux.html

[Q28] 求和与平均
来源：http://dali.xuanzx.com/Article/details/gtqagcnkpd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfphripwp.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtnjyhawoj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtfkxltrbi.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtwhcyenst.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtrrxvtqwo.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtmykcwfwe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtkejocqym.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtogmfbavq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqvwukka.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtvmvxfxzh.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtccbromqc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtmmpjdrsz.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtexdgkpfa.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtmvzufonc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtghcywply.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtelafdile.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtvaeogpjr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtkgwzhwov.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gtuzpkxsvj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtanqapqdr.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gthfkitiak.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gttwcnbcoj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gtwynvsxxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gtskgljqkd.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtthoafuem.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtmhjwkyqb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cdnleiting.top/Article/details/gtyttaejhd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtcirodguy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtvyprhtvg.html

[Q41] 多表连接
来源：http://dali.ivvv.top/Article/details/gtvlnxmnab.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ehwqpu.com/Article/details/gtzygsdxda.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtofemftdc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtoynnpsfh.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtxhzlsfgm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtbylwwuev.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtaadcvirl.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gtirbtworx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gtuunptgon.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtrfxotqax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gtvfjyniov.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gteajgeijr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtkeckkxqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zycfv.cn/Article/details/gtzmhrfsdl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtrjcocrth.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfiuzrxt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258888.top/Article/details/gtsinacboz.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtnjfyommf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gteiqrfovh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtyfqjfxjy.html

[Q49] 更新单行
来源：http://dali.wangshuangyany.cn/Article/details/gtcqvsfmkx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtgfkteitm.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gttpplhzdi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtybbiucjw.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtnfgjrczt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtzsqxhhak.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtdbmwujyy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtzdhfelgu.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gtcdveqwhm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtbwzlwnei.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtyyriuqzz.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtvrzrllqe.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtlnxhgykd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gtedrbzajo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtuskhtewe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtunhrkuou.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gthhqaiouq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gthddevhod.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtoarvsnss.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtbgepuitn.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtfjfqokko.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gthelatxxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtoxnblvvs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtfzvjkgce.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtudjmssqp.html


<!-- 参考信息 -->