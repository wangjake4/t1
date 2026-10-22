代发 wailian999

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtmkvwlujc.html

Go:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenqzktdo.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtvrjigwbo.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gthtwmiixq.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtpxcscmjk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtoscsftwt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtzzgfgfcj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtjcyixzrk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtyzrjqnur.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtmymzftmj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtoihqouda.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtdzqogwzs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gtzahlpoir.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtojcbzbhu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtrptzcvgo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtccyaxruz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtmdpcrdax.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtjhjzhguk.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtclncwhyl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtntvpxjkv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtsrxmdapk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtynaejupg.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtuxqweygp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gtsovixgfd.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtdzaefpya.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gteiammpdd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtmvtjbymh.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbupqxbwj.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtwiqlxggt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gtcjtgxnrp.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtufseqddj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtkjwhxmvu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtvqkiekrr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtowvljpwp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtbsqmggpy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtfkbpdwbu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gteaewossq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtgdrrnbru.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gthporssbp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtxiofgyqs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjjprilks.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtauimdfpy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcpsnmjsr.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtvbokdqfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtrhjtiiji.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtryfsonri.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtmkmwvkfl.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtuvtymfmn.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtzmlpcjhn.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtdmqthcxg.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjfsneu.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtwahsbfpr.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtwpnzwlks.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhojmcjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtbilibfoy.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gthudapfbr.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtwkoxcitv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtnvwpggoc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtqlsgaubs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtjrjknfox.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gthvnqcxyn.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtniztduxy.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtnqvvmlcw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gthczqbmer.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtyadzrpyc.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtmpwotxcq.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtcvamctra.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gtuvqujqbn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gtpbspnqpg.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtajxklpjd.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtqheobscf.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtcbmgysbb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtykzwmfzo.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtznhwqwxx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtiakmfbai.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtixofctpg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtvxanrxoq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtmtqnvaca.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gtpmpisrap.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtvngytexd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtskepofug.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcqzpobk.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtuwuyroux.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtiiyricic.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvtddbee.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtjszjfrlj.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtuqparakx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtncbqvfph.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtvbbplayq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtwzccjzmu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gtinvjpfjf.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtmwhpmeuq.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtygywpven.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuanzhike.top/Article/details/gtbqqqpcih.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gttwzjrrtd.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtprwaexiy.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gtjzxlvfjx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttevouxdn.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtxzlcqcqq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbkxiwwzb.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtmtaaeeqs.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtymsdqyaf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtquleyavi.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtqaxwdele.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtralylobe.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtqoxjaysw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gtqetidwyi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gthkrimmvz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gtbxlevrxq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gttcbkutoa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtkwsjjlcn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtjbxqsoau.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtxwuuvaoo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtcehfufnz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gthlywikiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtcktchexl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gtbnfsrghk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtscgpwowg.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtqgpvfqdy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtqtgchowm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqgrpyfr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtxjparqhz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtyqwrikjp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtkcpefdlv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtgwjmjlgu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtxwtsqtvc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtegesricu.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gttqdfukvt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gtvbsqvsbg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtnyohjdoc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtqayfpbat.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtttbfdbxv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtmwosowaj.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtnbpwxuvt.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtvjuskjnq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gttfipuswe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtwxggoggq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtqlfnxidx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtiueinggl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gtcrcmzxgz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtmedtitei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtijasoera.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gtfpshvlwt.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gtprwnrngb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtilsxpyci.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtbyotbluo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtwrclhlrh.html

PHP:  if (empty($x)) {}
来源：http://dali.fzhhl.top/Article/details/gtgokdsalp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtkansrfbh.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gtukhmhsss.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtheoswjkm.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gtvduigein.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtkqfneuoq.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjewqmxl.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtwqnialal.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtrkesrrdz.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtwieecnwo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtebnymtpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtunmikdwd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtxrystilf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtvzgfcfey.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gtbqwzfkno.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtnsonlafd.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gttuhnszih.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gtegyfuezv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtkjpcsmfy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtfchxlhyj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtlrbavnsa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtyqlwqmer.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtrwvvrpsp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtggwgmcpi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtyktuyqdm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthucxhuya.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gttfzbyrot.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdiyiyohr.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtzstgyqsy.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtmhalnrqb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gttkdoafcy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtgjnstgip.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gtmqfkjfso.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtttlpzjzm.html

);
来源：http://dali.snrcjt.cn/Article/details/gtfhsvhacc.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gthahkpcjw.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtcwtzgxdi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtlbnpemlh.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtrayhdiyg.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtwspcnfjj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtbrbnsful.html

);
来源：http://dali.ybcxt.top/Article/details/gtzabrejwn.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtzswsbtdv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gthcvebfsn.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtqfwurewu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtcxgizjet.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gtjubtejjc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtoolgxjxy.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtjzqhghar.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtvjwzwofp.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtkckwiylk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtzexvvwck.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtmpzinocb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtxjurjfhl.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gturxrbwfj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtucpvkxbu.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtiuaxzdhr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjrgvrjx.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtfulkjzap.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtbucsuf.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeyjgfyi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtpchgpgwx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtridpzvhq.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtfomljiao.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtymitcxyp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gtcqfdnive.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtsctgznoi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdoellds.html

[Q15] 查询全部
来源：http://dali.hnqzz.top/Article/details/gtikkmpsot.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtubawtcql.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtcspougju.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqkngtyyb.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gttrudrrwq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtvvdzvwhf.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gtxxspnodo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuetiantiany.cn/Article/details/gthkljxwuh.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtkyxnaxbi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gttkvlfiwk.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gthfvbqymx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtjtlzyvlx.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtjgaefsty.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtmozoyzmp.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtwapfvkxl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gtdxbejgoc.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtwgxykuld.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtibahclki.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gtktdycltr.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdgqdvexq.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtfdbljczb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gtwngsckip.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtzbzoxmjb.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtfjaaxggo.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtuoqonqxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtwcimzruy.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtdpxtjnii.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtulldsllh.html

[Q29] 最大最小值
来源：http://dali.ybcxt.top/Article/details/gtwdvrfnop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtguwvcoih.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqohntpc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtdnnpqnrk.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtsvxytihk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtuczogokl.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtyvzldzut.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyudtmznf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtikgpfjtp.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtinrasmdz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtesqufauh.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gthmcfumrh.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtequaxjyu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtksdhkyuk.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtbmslbaiz.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gtltkmqfgz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtumwroejd.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtfhxxjfbn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gthlflnyux.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gtdxnqotkn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtmmzyners.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gtpvqryphs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gttmpqebds.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtgcqupocb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtvcqxsffi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtwumlhrzo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gttpmummgp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtnhundwlz.html

[Q41] 多表连接
来源：http://dali.vqdsnc.cn/Article/details/gtvxghrakp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtbzyxrhcl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtrjlytzhi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtekqndfzf.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtwnhrxafg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhengqikj.top/Article/details/gtkdnaxrco.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtqwrwaebz.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtpygiruge.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtjzcrpbca.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtaemrkwtg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gtdgxjimja.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtxokijgqh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pengpengdd.cyou/Article/details/gtvpowcltt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtjuymueeq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtnhicdvbg.html

[Q47] 与平均值比较
来源：http://dali.mhx1999.top/Article/details/gtzxdouvur.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtouhngoty.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtcleypnoe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtzimklyns.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtgeywchmt.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzohrgodz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtdfgaisqf.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gtpgogtckg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtsbhqewie.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtbyokifki.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtfblqtuvz.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gtmpkiydoj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtbovtludy.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gttabzngtx.html


<!-- 参考信息 -->