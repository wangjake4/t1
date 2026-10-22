代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2txvkoeph.html

[N10] 链表节点定义
来源：http://dali.cqqwz.cn/Article/details/gt2qgmfsbxb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gt2qqevrhcs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gt2kwqihznf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gt2omzcnczc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gt2mpjjdvho.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gt2cotekzoa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gt2tvojqszu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.316326.xyz/Article/details/gt2qgghcebc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2tuecekvv.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gt2ooefjowa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2nyhciqdb.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gt2eqkceykr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2gkssqbkv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2lbvuugen.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gt2nsdnwcgp.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2zqlxusoo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gt2psfbjrxx.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfscecgn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2qcimaffo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2blhujzpp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gt2disrbnpi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2wlpyhvzu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2tscesluv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2scdjzsna.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2eahyengu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2wirqhnxq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2qljfhrhi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xrkvruax.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gt2oajhltqd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2zrvzhcwq.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sddfvgkl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gt2cpdqaimx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2nzkkemjh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2bpazhvfa.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2rebbbiie.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gt2lycpumsm.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gt2xsubfceu.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gt2etqzsrge.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2xansjuoq.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2mgqqyxxy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gt2lkvebtbk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gt2iytjudqm.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2zycqbicw.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2yjbmreap.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2heqdggnu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzenvdou.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gt2hkjudbal.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gt2iqjpbqof.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gt2rfcgnqnw.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gt2xwvbeghw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2yjixfyun.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gt2smqxeuol.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2qdwlpvfk.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2fznezzjg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gt2ogilzwsc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gt2mllavrxy.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2isskyfmg.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gt2uxwrndoj.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gt2gscbcabh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gt2ahhaaqpw.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2hsdufhwc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ooikphxv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gt2gnmmtlrh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2sfiozmza.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gt2xpaunrkt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccoafeqd.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gt2fbpcdlnt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2dyiewuqk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlacqurl.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2dwnvalnk.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjnnzchb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gt2odqnxcsh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2oatclboq.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2yqejrwwx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2wfmmbdiw.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gt2pzgvddiq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gt2ufimlhgc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gt2zcmprrpo.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gt2lhtctdci.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2rihibyga.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gt2pbvqiism.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwecvnnc.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gt2rhcskkan.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gt2prthqauh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2fifvjnpw.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukcvncpw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2oigtebjb.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gt2spsdllce.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gt2juynvujx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gt2tevnnwmz.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2dhugfhbw.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkwllvhd.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gt2jlnfbiex.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2htxekqjt.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gt2zdufnfef.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbnvphrv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gt2ygiztodh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2vgkcjyib.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2wkcsbacx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gt2fkwdiyev.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gt2hqgdjcac.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2cgwvrued.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gt2oqmjfxzs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gt2bmdnjagx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gt2pygwootf.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gt2epikebmk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gt2fnupwvny.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gt2ifynyqch.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phcflmbd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2qktofuts.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2mzgjvszg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gt2rceymfjg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2xvlnkpsl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2umsodaml.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gt2vrzbvweo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gt2dtosdfqv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2tpwmnnuy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2yzixygaq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2psdkpgni.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2pztguvwh.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gt2bquaqhma.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2rtyxidfr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qoeibmoj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gt2oyutgpcf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gt2sdcxhyfx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gt2pbxhtalo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2vylgnffa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gt2yaatfpig.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gt2kvzxqbau.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2xbzofzaq.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gt2xvkorknp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gt2qymmjrbz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjaqxfha.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2joshbhei.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gt2uhfqczwv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nkvhofoh.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gt2hvxmtnib.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvpgudnx.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ybcvctez.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2bkbbxiki.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pcrciwex.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gt2xiwoouzb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyxvndpg.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gt2fqostmvk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2bczlmwmx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmxoeyzh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gt2gdxyxhow.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gt2quqwmxgf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2qqlhwufd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gt2twjfuafu.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2wcedbvqj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gt2jlfghagc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gt2vayfchwr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2jngsgfpf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2apqczfee.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gt2geqjvoqr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gt2irfxcbcl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gt2tuoajqqo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swkeeftn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2gohlizjq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gt2ybdzwmmu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bkawwauc.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gt2emupnqtq.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gt2bjktmybb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2hhqrtqcf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2tdpsxpyd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gt2cxviovdq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gt2gshszvgg.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhjrkkac.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2gsjqqmus.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2znfyrdvu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2msbgoazh.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2pvbmguda.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gt2mdqcnisc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gt2uqgffbdx.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxsgvxpv.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btnbvgmo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gt2pbwezjrp.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnpoitns.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2jqgwugqf.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gt2iwtbjjud.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2uvatdczy.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2gmmidcei.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gt2ioymdokh.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gt2uwsjsvdc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gt2xilytyzm.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2jerrtrfc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2djdcltmy.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gt2xjhqlwib.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtebyrkk.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gt2rmuqnwks.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gt2xdziyoua.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gt2clcgqumr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2mdxvlcxm.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gt2irmxoaeb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gt2yqrjbouk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gt2dadxdhyg.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2ubvebgbz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.birdmap.top/Article/details/gt2kyxtkkha.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gt2enprdzqq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gt2foxspsbo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gt2fmziyibd.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gt2vdxucqgh.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gt2gpqdtqax.html

[Q16] 查询指定列
来源：http://dali.sufxvd.cn/Article/details/gt2zkhkqlog.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gt2hmahgbkj.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2vlszgivc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2luzkhtmc.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gt2dlipwiev.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwllxydi.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpambpei.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gt2pxxdjgcr.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gt2jwrhpepl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2rbejxgjb.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2bqhflpna.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2mmhrlpkx.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gt2gbvwouhq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzboysnz.html

[Q23] 分页
来源：http://dali.yuanzhike.top/Article/details/gt2wxhchhxb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gt2clseznes.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gt2irxgrboc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2nmpjzdui.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2lwuxcjnz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gt2lojzktmf.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2zltoygef.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2wzatxjys.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gt2nqvdgard.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2shkylrtz.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gt2yxindxxt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2bevyokta.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2soryotes.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2ywnhrnrj.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gt2luctkpvf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2wlaanhhe.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2oljpobux.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gt2ncwmvlix.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gt2vlymfcra.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2bfalvlxh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gt2dtcjsihp.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gt2cmcnsxfe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gywjvzig.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gt2vvqprugg.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gt2qdmclssr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gt2hesfebbu.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2zyxzzfhs.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gt2bzctkjnx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gt2cymbsiqq.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gt2bgbtpzmq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2tdshbuwx.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmpdekjd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gt2tuehgswz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdionpey.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2hvootcpe.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2bopcjtom.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gt2veyswppq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gt2pgxjuoux.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gt2fvlvyubf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2cvbkwyrv.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2yillhpuy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gt2lpbldsst.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gt2trbiaupa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2ryamanpo.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gt2btiztnig.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gt2bxwxexin.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gt2xyqaaluw.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gt2ssktkhsr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dladvzco.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gt2thfxzpns.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gt2btziojdg.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gt2owyfvjnt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsjgtals.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2roruqsyz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2ivxathjv.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2pupcytau.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gt2fcflrflp.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gt2xujecngt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2nkphqnai.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gt2rgohmvtw.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gt2wydwyiqb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2uyihqnis.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2qkghycpq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2wlhdafxr.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkcyskbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuydxhwe.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsgnwwbu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2efafnepi.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gt2pppicgjd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cashguo.top/Article/details/gt2vwdwislh.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2ivwkhcqg.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwopagua.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gt2sgmuwglz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2buvjevnl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2ctwvszsx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2haoalmto.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gt2rvuzqdjn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2zmiqydfc.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gt2zwbrwwna.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2rbnmqihj.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gt2xyggattd.html


<!-- 参考信息 -->