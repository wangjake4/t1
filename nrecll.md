代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gt2heaxkrzu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2rbxxcwvt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gt2jzuyacbm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2tbhlauyx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2kycfdous.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gt2klwlnptx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gt2sdaioikm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gt2rvjefbys.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ayqjmfhu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2iiaryynk.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2fuzfuxbw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gt2uznlkfin.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gogol.net.cn/Article/details/gt2pajisudt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gt2hnpsusso.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gt2frnibmge.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gt2kcimtgpl.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2rxfepxxr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsltcqem.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2xhuhfouc.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2jptwtwde.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2kxafogvl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2jpfnbjnn.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2qwnnhktb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2cnckmbaj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gt2rzbekzvs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gt2onqezzrp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gt2teeobpzy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2mxhbiiso.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2evligbmk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2vlimrwza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gt2nhwflhjf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2yuusreks.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2fcaurfbb.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2qayfuypm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2aghwwmnu.html

[O01] 启动一个线程
来源：http://dali.sufxvd.cn/Article/details/gt2nmyubpop.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2tcopetkz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2bfaqyoam.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gt2uflbrgut.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2exvrgfdd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykbhmtpi.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gt2bpfxxysy.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjxbgetk.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gt2gkhsixwt.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2ngdinupp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gt2mvjozhxl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2dcnkxmod.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gt2qpbzlxye.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2kwrxazrx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gt2sjndjoet.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2klienssj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujdjfrxl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gt2hrpgblyr.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gt2sqalnzns.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2dwrxzpwl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gt2oradexvp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2guiafwvw.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2iwcdgjng.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zkffouxi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2srjngmdi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gt2yppmkbcf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofcuttto.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gt2uymzynyb.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gt2yejprbjq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2ypahfwqp.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gt2umhmeydp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vywooqtv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gt2qxymfsiw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2zruuhchq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2fsvmafoi.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqzjaldk.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gt2cmmlcidq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gt2uzjlzizo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2unvpclwo.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txmuophf.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2esufpozg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eidmdnye.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gt2pfmzoomj.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2bsopocex.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gt2tquwdncz.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gt2ectifrks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gt2fvryqigg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2liupcozj.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gt2tnsrekph.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2urrvntcd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2fnihavbc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gt2arcldglx.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gt2cyycophh.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gt2ibqtuiux.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xvnjdjcf.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gt2javbynsl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2hgcznmbl.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2hpqybjnn.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2cpuhundx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2xpnqnkay.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2lkccdmko.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2svncxiks.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtrzxhfm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2nplolqct.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2abqzgqyz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2iizbpmnl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxkvovoi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2njuslddh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2mhhsberw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2scpdiqez.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gt2tmlcqfqo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2srevqeqr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gt2maiclkzs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2vjdostrv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2tbzmopzn.html

[P03] 生成短随机字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2lvgrfhvp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.mhx1999.top/Article/details/gt2megnuwnb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gt2mvywnmkk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2agxrehpu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gt2xwzskzbl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2tibznyfe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2rtvcsjav.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gt2taxyzcsf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2pknamnso.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltlggjdh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gt2igldcguw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2fkjtgnez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2amnccxso.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2avqukhmz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2wxtgfofo.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gt2oelvjddp.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2tehmqcnb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2srcgelke.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2dtsedjzd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gt2artkqzsv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2gptvatfx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gt2oqkwsuoa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2qwfonglj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gt2cexfzyda.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nheusmfk.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gt2xkgfhkvr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yovwvqkq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gt2evsxbkrp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2gzmhfgih.html

PHP:  if (empty($x)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2frptvoox.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gt2tmtwguse.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwtxxtda.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fogyrjnm.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gt2sntzkpou.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gt2yldsiqwl.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2znrjemit.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gt2tohznnji.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2kvqlfyak.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2muwzxkjt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gt2smfotwdv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2msaxvecv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gt2ccrdgbpd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gt2gobnjwkv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gt2jrccdgjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2thysmubp.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2dwqexphn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gt2xuqozart.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gt2qlpwpgde.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2rdplmrud.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2hlesgfeu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2mcamokcg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gt2gaoaklcn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2gggkvlqp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2bdpjnnrw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yutajzin.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gt2xbasahdq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2csywkikv.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gt2lmdmwryn.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gt2ctwtphlz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2kugxhrut.html

name VARCHAR(50) NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gt2hjwieckc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2jzgxzdxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gt2aojznaqc.html

);
来源：http://dali.yonumen.top/Article/details/gt2adwyddzw.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tityiwnf.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2wzsceahb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfvdmwwe.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gt2plvuacmo.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxjedtnl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gt2idrtsmmg.html

);
来源：http://dali.shuidangran.top/Article/details/gt2imffjuvy.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxjeteay.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gt2noapfhko.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gt2oxdelfsf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gt2kddanpdv.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2bxycxsnx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awqfrpij.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gt2gyicybgl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2smpqpeve.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyavcpy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkvjxhlg.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2frabtgrg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gt2wyuxpocx.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gt2zkxsnjze.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2tqbpypej.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2pxlddskt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2mhrparaa.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gt2vqqvbrrc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2czuzbmeu.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gt2ytavdhqv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyvazasb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gt2cudgayde.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2jeirknfm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gt2okkdxnsi.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2kjanonxv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gt2gbjzfgyx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gt2ztcqollw.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2hjpwrtkp.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2sitgupou.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gt2maztmxnk.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2uxtfsscs.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gt2fvzpriyl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gt2mtyptwgd.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvkaifea.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gt2xoyyytfa.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2atfxdapn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gt2exbsvkez.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2jqtdorlk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2ivkafcup.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gt2bjsaffgy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxtmwffp.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gt2wijqfsgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gt2cuwagovb.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gt2bztdthkb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2soyuuvtd.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gt2pvejsotw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymajhxtg.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gt2ibxswcku.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gt2sqtqizhk.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gt2mqxcxttq.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2vxijnmmp.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkrjlfsb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2megpcxht.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gt2snxnqimn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2ojiupgmu.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2hoopunls.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2jeffnfbu.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gt2azhgszrx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2bonoolbg.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2ifnlqqgs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gt2chwvcjwb.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gt2rsuzrwwy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2dhmjeusd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjydycbw.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgantscl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2otbebbiv.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gt2gyuecobp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyayhiz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gt2dysvpcxp.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gt2tnfimvyh.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gt2ymbtmhrw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2ktqjuozz.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gt2ayyjylye.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2wkfgmall.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypryqguv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwiazubp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gt2avrwhbti.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2puaxexhu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gt2zqnlafsv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xziqi.cn/Article/details/gt2djezqjkw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2iarrfgbc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gt2kvszzord.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gt2poxjwuqu.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gt2hpphtcoa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gt2nicyghjy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxkkxqnz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gt2imyxhygs.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2thjotfux.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gt2ygjwcdwj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jyoumei.cn/Article/details/gt2xbndxyiq.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gt2plwlgtzw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gt2nmcxzakt.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hftytjwy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2nqxtsfev.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gt2gcdjccut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2scyjdsyw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2othxiyzs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2nbwlcjah.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gt2zaycdgrv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gt2kizvfvld.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgzzbkue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gt2iifpsynt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gt2zdliqrfq.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gt2socflohx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2ciqdoiqr.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cycilglp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gt2lcgfsjzl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrwpklv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2nttuvlpm.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcwngppx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2nfcywlhv.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gt2cbcriwiv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gt2coahvjni.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gt2unpvkfqv.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gt2tqvrnfop.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gt2sgxuqtzn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gt2fjvtfcvn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gt2jipxamip.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2jazoydpj.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqmixlpz.html


<!-- 参考信息 -->