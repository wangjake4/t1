代发 wailian999

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtshlrvigk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtyagwyyag.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtvssitzrn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtwiyqncdv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtopmlboid.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtockmurev.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gtbmoccjom.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtkmyspzcq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtmlnqygkg.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gtbchuepmo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangtech.top/Article/details/gtjinsuoxc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gthldskslo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtvclnzmlc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtufddjcpz.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtrssfyeqx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtzwsztcqt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtajkdaeaq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gtbuvewjpn.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtuoxfhxyl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gtphxaqfpk.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtcfazuwme.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtmgkjkclj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtrrpkokot.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gttqygrjww.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtvoqcmhxt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtemsnctcj.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtroueongg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtdvaqwtup.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtbbirxmwa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtbeoksgxn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtunsvdvrr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtldfqkubc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gthrrzpyxl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtrcttbbbx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtqvylfphg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtdcaeimoc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtbkfxuisg.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtbgigkc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtztdtwups.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtwlhuckdj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqujwdbe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtzfusolnz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtiiptqxhb.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtsdpuetac.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtqbqlqmpy.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtvzxbmfwm.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtacpwkfnw.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gtpvpggtpe.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtnuezeytb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtyigafzwi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtvefvxwfs.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtnonloiwn.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtjdgztznb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gtdywzpiub.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtbtrijcha.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gthhabmtzr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtraavjxif.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtyopvuxyz.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtoynwdxjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gtjxtzorij.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtlwlowhom.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtnfrllgho.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtqlxhgbbj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtwiwuxezb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gtmrogjcdd.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqorrdgal.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtdvwqssst.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtlkhbtvhb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gtobtqmivq.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtwcbimzzb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaiizqllg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtfmglfrut.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtlxltmtqu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtrsydoesm.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gtnzfgmhhz.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtfcchqywd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtobaldnbr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtzlgitdfa.html

JS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtzzpuhnnu.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtstynxdlk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gtuzrfxiuh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtvcqurnqt.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpleyengw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtyvchwmxi.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtfyxkrveh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfadwylps.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gtvpidozde.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtivcfewji.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtrknqrwto.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtyxueocsr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtiyctyodf.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtzlapzdrg.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtrujuyqef.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpcroqcig.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtqokqhfmk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbajrmyhr.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtutoqpgpe.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gtoakmasxi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtumlgkdfa.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtqykwnkai.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtpelptrzf.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtsukhsuhr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtrymbatlj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtwzspzzwe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtlehpvdqi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtqabivwzm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtfgqrqgnc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtqvfumusb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtqmeqstyi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtfwxbvwvf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtbtymztxd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtyayapejz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gtzbshlrbc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gttkedvgal.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtcvuhymad.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gtkdvubnmi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtprzbswvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gteyejsanu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtirrojyjv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtizjsngxl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gtkwydovpy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtxxcloahn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtfcqvitjv.html

[P04] 求长度
来源：http://dali.feifeiyinyue.top/Article/details/gtkejdlkuk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokahqpac.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtnvayzkxw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtievljovf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtdwzrjiaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gtvddqfjtr.html

Go:   len(arr);  len(m)
来源：http://dali.jyoumei.cn/Article/details/gtsvfwxtns.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtnnwjhlwh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtdgsfjyig.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gtchuonpbh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtmojaqutn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtytrtrext.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtimgdaslc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gthhvtzyhp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtmiqbkcas.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybgipymn.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtmpomuqzf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtyfsbsrnp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gttmyhduhg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtaofvyhuj.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtlgwtmbxp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtympkzhom.html

TS:   if (x == null) {}
来源：http://dali.jyoumei.cn/Article/details/gteijeahmf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtdyxzyxjt.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gtjmudoinx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtzwbizuoq.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gttdbhhkcy.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtqxcliegf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gtdwhhujpk.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtkxdizklb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtuqhuuour.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtieedqjtx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtpkpayfzk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gtrumhpmhq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtcyasnhro.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtvfznvvmq.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtzocndnhp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gtrmryzfpx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtbeubffsx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtchnwuuob.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gthvbozabs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtzurpqzms.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtzsizkblw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthavnqxpx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtctizozcr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttdfryzxw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtmydoizkr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqtafmdql.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtjnukhjuk.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtgqjnotnf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtcvolonfl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtcfznvdds.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gttvuoiqzi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtcmsthnkk.html

);
来源：http://dali.ppjwa.cn/Article/details/gtmnwvpgxy.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtptmkzqlk.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtylfwcoac.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtzahdlqwv.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gthxyhhdqw.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtmvrhwbsc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtittmrrxp.html

);
来源：http://dali.xylfe.cn/Article/details/gtvafbcfon.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtoexpgsvl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gttoamtuih.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtwoartqey.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtljvjyihe.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtpshutifx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtukgmkrnw.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtppjzdgvm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtuoleeqig.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtrhcoeqnb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtmdgcjzjx.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gttdxasdgi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtbkyabliu.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtdmdwwckv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtrfqswxok.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtndnaqfui.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtnthykcsa.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtvjmiwcay.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtwyiryddk.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowktfrdd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtuchjamzc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jqgufenzy.top/Article/details/gtzldqlzql.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtostchfts.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtnuxbauxp.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtwqskuwgq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtudbfnmfc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbiwkjrd.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gtfvnfebob.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtyguagfph.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gteymyxnse.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtujqiurtt.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtcndpcoks.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtfxyufglc.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtjzpdisee.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiukpscgk.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtcnttlxmf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtynecpwqe.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtaharerrx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtatlhainl.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtvwjkriuy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtoevgxxxh.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtsphozqgk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtpupoinau.html

[Q23] 分页
来源：http://dali.feifeiyinyue.top/Article/details/gtbwtandpf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtgjhaghbm.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtdbxeyyau.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtcuqrebkb.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtpjzplwia.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gteyznybqf.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gthryqdgyi.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtbjqixbgm.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtvvndwmoh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrefqenlf.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtkdyvkiga.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzfevkyp.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtntawuhhv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtaypznvdh.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtjowcalvw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gthgxovvav.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtyfxytrbx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfdbztff.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtukfueohr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtxpweyq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtfaubxrbb.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtksyfwrah.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtduludlbl.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gtiqlupuwr.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gthapdjhqt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtmrhglclt.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtjsgyluqr.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtfjhxoxsf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtwqxnpkja.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtkufmunfp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtvoatbjvx.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gthdtowzhd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtlkohfbwb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtjinwaqlr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtwwdfwyam.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtqyqyyasn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gtwoyceogw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtuwyjgdbq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtshdidhri.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtmpvceffq.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtzxobcihd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtuokgbvov.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtoolhnjyi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtqkkhwsfi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtxifgwzrv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtqovlonej.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtohvlngqq.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtyemlyefo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gtxzwrnaqx.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtdcmtcbnn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtypxqoaun.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtyjnlkpbg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtvozmfggc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemcfttsg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtbyhptgmg.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gtrusvraaz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtbboxssmm.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtisnutngs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpldojrif.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.0kj1m.cn/Article/details/gtwsqzuzec.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gtwypidndm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtyxbaueeg.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtrsnzqavo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gtgcfvxvaj.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gtdqrjzdnx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtkwecunnz.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gtnwcwpmbl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtbfgitzvd.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtvdjwicpu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtmdlgstcc.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtglhrjlnu.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtluomfnvm.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtnemcrunb.html


<!-- 参考信息 -->