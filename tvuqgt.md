代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2jecoqzta.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gt2yatxfuti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2xgoqtuxz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2ibiuuenk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2gxqczghr.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmbudggi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2crcrjmof.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nfqvhmip.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gt2hphincit.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gt2sybiofqe.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gt2coykfxdl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2cffvlfrh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2htgkrafv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vvdsdity.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gt2fqunpads.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gt2zpkjxjqu.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2ichlmnar.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2kpqnfnjl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2fqvtqhwz.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgeqahkc.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2shmtnskk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gt2kkxhggbd.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2uskhwsky.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gt2wgfhlzye.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gt2zkenakcr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2dceslqgs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2cjzjehvq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2ewswefwl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2njenrkxr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gt2yhlvlype.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gt2eoxofxfy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2njfpxfpe.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2lexvybac.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gt2bxdvllgg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ndsrmcez.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gt2zbvpmvuz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2cvshgcvn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gt2qxdhqkok.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gt2gacccwop.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2puaudvcn.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gt2eefdhvfg.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gt2umlpxapy.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gt2xopvlqgy.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gt2sxnmvota.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2shxugkzc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2sccitrpl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gt2hyidmjxa.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2ewrlpkyz.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2tpahnrwu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2wokkooue.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgwfreby.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gt2zivjpzzy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gt2gwjfnbua.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gt2ezxqgazi.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gt2rbyrwztt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2wcorzoxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxinkj.top/Article/details/gt2zwpwckzv.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2mresjttp.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2nnvyxgqm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2ihwizoce.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gt2coxnupzx.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2isaeqhmk.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gt2hqepfbve.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gt2xbyeyfzm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2jrvmggcg.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2dhrbyqvq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2jlzomyor.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2txnpntvj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gt2bhdaszdp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gt2smvqzkoy.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2vnvmtypj.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gt2mgnjcsqo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gt2ewgehleh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2uqhfupqs.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2qocbkkqq.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2dvynnfig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gt2bukuonru.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gt2qbvfeqzz.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2iamhymls.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gt2zddqtldk.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2uhnvmhri.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gt2gqqyvkft.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gt2enhlbnel.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2kfitplzf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2swvfffxd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gt2seddbhbw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyufocbw.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2rbbaviiv.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gt2qcczmuka.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2nbiaxkoc.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2jyzdagct.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eexuntlb.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2gljgufym.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gt2fdozefgh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gt2djzysgle.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2wjjgiqbo.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2iqgqwqmm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcsxwqfr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2wqhvtjhv.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gt2nycmqemi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gt2bzwrtpco.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqbaqbda.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mctujxgv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gt2lrgauokp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gt2wrcmyquo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gt2xksxvbbi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gt2ngrzloul.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gt2nlldebdv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utkvditb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gt2bggdvavr.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gt2filnmnot.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gt2eyrjtwnb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2tignrauo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2fcmbyqcz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2nezcpobw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2xjkgmxtr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gt2czefupho.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gt2vqhstnjj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipqcfujr.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2tyhrkrsa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2tjsmqbtd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2buitjqnb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwdalduj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2kjfprjys.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2ppbsbjpl.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gt2lrnmaizc.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gt2rkztswew.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2ipnyrdrk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gt2zwceyycv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gt2ftcutxqs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2skrsxlhm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gt2olqxllvk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gt2dlqbsfmb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gt2nddmefqh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2corcxbjg.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gt2gymhvznm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gt2vxqhvbjl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2qpmtixhp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2icjjksed.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gt2gyvaaadh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gt2pmzfkure.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2vyluvvqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gt2cctjolnf.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gt2irtmgper.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2kezpltzm.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2cysxwjsa.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gt2ewlxwjpn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gt2ycykezog.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gt2bkzaqfir.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2haojsuch.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjyrlrmg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gt2gpzhbgwc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyrjxbaq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gt2ztvcntes.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gt2noxpczpm.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258888.top/Article/details/gt2hfhnkugk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gt2jryenwep.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gt2xpxdkyjd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gt2pdddpycy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2ibdxmuau.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gt2yxogwyob.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gt2mbiwbtct.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gt2ribspjrg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gt2xfatbvmx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2nlgosywv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mndruhuy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eoztboxv.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gt2ipkvyysm.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2dabncbhy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2qlnlwrvx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2appshtbe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gt2slzlxlny.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gt2dqjdtqxf.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2tmqriaiv.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gt2ukuejddy.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gt2gxmkcjbr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erbqjtrm.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2adbvtrfp.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gt2qfbuknib.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gt2lhugqgex.html

);
来源：http://dali.c1oappe.top/Article/details/gt2fmxduthr.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gt2skefsdjr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xysuadcx.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2unecirds.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2gdpfwbtt.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gt2jkttafim.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gt2vaewblgp.html

[Q06] 删除列
来源：http://dali.cdnleiting.top/Article/details/gt2smosprko.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2geezmyxb.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbwosfgg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gt2khtasytd.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gt2hcawdlki.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2iznerzei.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gt2bznwnmnx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2anzeogan.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gt2uoigmfst.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gt2vxnhjvop.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gt2tostwjuf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2tqspnoxk.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2lvswvevd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qknlqwhz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gt2deyzxpom.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzskbqgn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2oyxqtuzo.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gt2bzuwbqjr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmgkkafk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bstnsrmy.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gt2rjiqhxvk.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ysbrhrap.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijfjglnl.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymtpxwsd.html

[Q17] 条件查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rejabtxv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2wugvgunq.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2pgmkzhkm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gt2rzdbwwju.html

[Q19] 范围查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujnmremj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gt2yoqjrqdp.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gt2lvbxdbnp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pfxwsdtv.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2baqrlcym.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gt2jkunssbh.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2jjbbiuob.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2lekfnuzi.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2zposezaf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gt2byyacjre.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2ueixwisq.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2ypebzjxo.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gt2esszykrc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuanzx.com/Article/details/gt2hpuhrfiw.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2mhfmdqtx.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2bawdqrlp.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2ribzklav.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2fggzsdej.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gt2oxqoijjd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2gugxwctd.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gt2aaqgabjb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2nknpsuiv.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gt2xmxjrhij.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2fdyieppa.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gt2bvkhhuut.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gt2slsgdulj.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2cwfyhdhr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovhuvvsw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2zwckxrtx.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2hnldguek.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gt2rnvtrsoa.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gt2hnjvcxsv.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2qlxuruae.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2fnzvsnrl.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gt2yhijhjoo.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2ykvhktst.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqgtjxkz.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gt2khlxscdr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iewmotza.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gt2wyguicht.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2vaogozjx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gt2awqtprut.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2srwmbonl.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gt2tngkcwzh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2wjoyjxpw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zinfogfc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2xcjptlql.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2lutjzfrf.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2mpcmsljl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gt2widsybhq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2nonaarir.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gt2pivxwwam.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gt2uivhveiq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.mhx1999.top/Article/details/gt2ocvbrxzm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gt2jqavnhmb.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2jylxuwje.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gt2dslxautu.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gt2fjtjblhs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gt2fwzdfduq.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2hkajrder.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gt2plpiizrm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gt2qoofysjn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2raxeofsr.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gt2kveemgli.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gt2ufozdmtk.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmbelbbe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gt2gzaotzdq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gt2yhxkrrod.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gt2bjhdqsut.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2cjvavyki.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gt2juofwsns.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gt2oyeosyzi.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gt2bkakyqwk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2tmqdnxpa.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gt2hgujkunu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2cfogifjv.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gt2qcvvulyi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sufxvd.cn/Article/details/gt2qgozewxn.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gt2ytaedsfq.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2dsaebfzd.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gt2lqvbxixc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2vxexcxoi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2raykymad.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2gfdbjnxj.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gt2cgvkngol.html


<!-- 参考信息 -->