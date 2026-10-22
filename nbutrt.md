代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gt2xayjpvfr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2xieygwur.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2alofmtpr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2pojbcckn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2niidpsoi.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2nytaolfk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urbwjoci.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gt2dhmdrjur.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2zrnqlgfy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2fksoflyy.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2knpgffll.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2slazacxb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2pestuhop.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gt2ncchgrwl.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gt2aciaiiqs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2eeiajyde.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gt2bqlxfcpi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2tejjgxzf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2qvfuqpmt.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2ilytgelj.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2ympmkehb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guowangkeji.top/Article/details/gt2xryihkhp.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2otobbexx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gt2dfiwdoxy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2yhhslieq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2vpgmseap.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2npgxebmm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2xpkqrjkk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2vegxlzdv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ziawxieg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gt2tylzvdiv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2ewqavbge.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2dfjlfpms.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gt2lphlflyn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2gvvhroap.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gt2mwxumuxs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gt2ullfvymi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gt2jszesdvs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcwdfuzr.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2ftwvnsku.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2pkqrpwsk.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2cjzaosuw.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2kgpvfpgo.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2jtkhvpyx.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2cmxasiaa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2bthcrdfi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gt2sgbrcksn.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqbdtcjf.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2ryamnsjc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2pyxruyfr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gt2bvwwqifq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2itekxwvf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwhvgnqh.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gt2hkpwalry.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gt2qhfobetp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2foohsbzu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gt2szfcvndf.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2edfysuik.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2ikgilabf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gt2wwmwtsrp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2ylwuffjt.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gt2zwpajgtd.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gt2xgbfzihr.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gt2mcffszsu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gt2qnvaentm.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gt2gnkwdtce.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2upwraotw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gt2niwljktd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gt2rwktoyzd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2slfrkcls.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqbemgek.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2crrtbusw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2qwwttbcb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gt2bnxcdilu.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtkavvwz.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2ufiptqot.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gt2iiselpcz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2ntqfymkv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhpysyj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gt2bhxzgrrr.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvlozeer.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gt2iyskpbnz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2zjitednn.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2almzfjvs.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2agqfavih.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2kctjfqdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gt2cdoibuow.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gt2tlobeflg.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2dymkcrdm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2owlvejgc.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2jvvocvnx.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2meybedta.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2oyghfnwa.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2hbdqefca.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gt2jezlxxfl.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2symsrzwx.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2mrruhopx.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gt2mnofhsff.html

Go:   // 用 github.com/google/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2nzgafudu.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gt2sijnotxg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2cacxdfzw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gt2nvjjopqd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2xfqwzplk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gt2tfgkylsk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gt2dldjsrjz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2easudqxu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2oeszqphe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gt2eumeigrz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gt2bdelfdrz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gt2vbhtkpdj.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tinzivvl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gt2sssapnyz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gt2gxyitxnn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gt2vfzvllxq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gt2mwlsqakp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2miviusgr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2iitptgxs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gt2pgzaouyn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gt2truhgglz.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2qcbbbsca.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2ebywnedx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2riqbilyf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2gujynvcx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vspfhyou.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2kyozivyk.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gt2gvqwaemt.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2mprlrkja.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2aiqbjwok.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2ndckoiqv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvymurzz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gt2jeafyqft.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gt2lnqiccve.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gt2turqapgr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhlrvrlj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gt2ykosuppb.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gt2bxxcomoy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdyupls.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gt2kldrhgcg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gt2hkqcegby.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2zlvkkzxj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2jboqkgcx.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrvqduvy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2ymdohrqj.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gt2oleongov.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gt2rbjntipo.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gt2skpxdhdp.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gt2omwdsevu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2csjmuxjm.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2rifhydts.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoreyyag.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2satsydbw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2mrywcgjb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gt2fxlbbpmk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2pujcfemk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tpkwadcl.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gt2kqymkfkt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gt2vrejvrmk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gt2amgtrpkk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gt2lnhretak.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2jlorssta.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2aqxfkdzc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2qnebpues.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gt2uinoxlec.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gt2hhoufgaa.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2eoztmcke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gt2altoyhko.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xpfcrajn.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gt2zsrnfjtt.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gt2onxzxsdr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2uxjaxusa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2bpaeajex.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gt2kkdvmzgo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gt2nldefmxg.html

);
来源：http://dali.guowangkeji.top/Article/details/gt2ttpmpubi.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gt2ndpbvqvp.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcoznxig.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2jivpobmm.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2tbujvvbr.html

amount DECIMAL(10, 2),
来源：http://dali.jlsjyb.cn/Article/details/gt2bfyfvudl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gt2xnpbmtzg.html

);
来源：http://dali.c1oappe.top/Article/details/gt2ssvekryb.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbolsqvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gt2eiuiekvf.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gt2bchilkcq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gt2rcnwjagx.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gt2ywehuxce.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gt2dajqbiha.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gt2kwyiadam.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gt2qozxatsd.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gt2japxmmdc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gt2nrwcunua.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gt2dybnukad.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2nasmzezi.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gt2glbjlxwb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2apatausm.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2kyieqhiz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2cqntlyhr.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gt2xhfrriac.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2hxqpmyph.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2urbomsfh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gt2veicofvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gt2rqbbsgvt.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gt2snhprjnx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2sqtsavfr.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gt2xerawfhq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2onizblpn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gt2xdzympze.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gt2ryclqdgc.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2finaqmtq.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gt2wjfosfrc.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ljskircr.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2gdkeylyc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2jdqhtnkh.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gt2sjvgmdmn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gt2jfpsscuy.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gt2jgfuzxun.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gt2yxeckqhf.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nirrisnr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2rkviefxv.html

[Q21] 空值判断
来源：http://dali.fzhhl.top/Article/details/gt2ctzcbjnr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2cglebmvj.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2fjqhdslj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gt2jqihnrlg.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2leetruta.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gt2wfeuewxp.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gt2ugmxheok.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2oetjnpzx.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gt2hteoetwb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gt2lynejnru.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gt2cspsehpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2uineqejy.html

[Q27] 条件计数
来源：http://dali.yueranfly.top/Article/details/gt2luybnxio.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2nuugxweg.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2dqqnmjkp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2fjwrfpnn.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2bxdwqlrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2djlmkjnz.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gt2xktlmjdk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2mbkcojdp.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2jomhsqpa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2cjmyadgz.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2ownpfdgf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2uvhdprob.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gt2iyqwiahb.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gt2dutlmsih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gt2fytxykam.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2lsdahpwj.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gt2jbmuhjsk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gt2wjfvmugw.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2oyyxlckg.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gt2rzsrmvgw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2ydvjkshq.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gt2fgolovqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2zvcpccvp.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gt2mxjvrdkq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gt2woivztmj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gt2vztwgckb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gt2vxvljscn.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2qqfmzwts.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gt2oxkkpiha.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2pfkelnad.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2ufezpabr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aibaodan.cn/Article/details/gt2vgmplusg.html

[Q41] 多表连接
来源：http://dali.kuanghao11.cn/Article/details/gt2jdqxildf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gt2ngjrdxbt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gt2uifyttna.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gt2bksrnanl.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwrrahot.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gt2fasolpkm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2gxwsojfh.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gt2ngeovvfh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gt2aqvjczka.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gt2ckyqscjq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gt2wrlzylky.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gt2dxmrkfmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2ppmgzrwx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2dqbvxmxb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2zqcqtzpb.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gt2mmohkkww.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2poqdruoi.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gt2phvaxeoc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbdtiudf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gt2kvqmfxeb.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvazstvr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2azcoiaxd.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gt2mzfmqnkx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2wkltacnz.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gt2hygpauzo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2hqdjbrbl.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gt2trkybjvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2guzhrbvq.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gt2cmliugkv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gt2fcgxaiyg.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gt2mtqnuomb.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gt2xhtcrxnv.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gt2srqhjyzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gt2bprlyyvx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gt2juhcbswi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2fliswrjl.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gt2fudpygup.html


<!-- 参考信息 -->