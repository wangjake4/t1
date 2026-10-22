代发 wailian999

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gterykajoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtvoywcqjs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtupecrywh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbohxcpjn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtxojgynxd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtztziydlt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtxgnvmdev.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtjzvyoijm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gtxoyrwnnu.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtpeyjkoki.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtrvyrittb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gtdukvhcln.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkddzqtlx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtzpjyhiut.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gtydlqiuyd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gteqbpnsdv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gthnikaazd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbyidfmql.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtagyajsom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gtqvflivod.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gttkyobimu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtgrizcusn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtkpelbycr.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtmkjacgdm.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtiscpyzhq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gtkqbsmoqa.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtdrapolmk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gtmjrikcsu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtqghoaxgn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gtflalllsm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtolqsjmxl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtzwbgnogp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtfxhcjbwl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gthnjlsrlx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gtgrbsuyen.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtcmrpjfkb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfmsfggbz.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtlatfcjqd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdpaluxrr.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gtfgvkbrar.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtdfmnurho.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gtbjyburaw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfnyfwga.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtlkwllhmn.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtyfjhdkck.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtwkdlsiqy.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtevzjdcwq.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtdvhirycf.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtlzfjomxa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtasssoqqu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtgpcmcepy.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtrsionmex.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtdvzzyjhw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtpbtuabhg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtpjpysjnf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gtdrwxtagl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtrirlxcoe.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtjzmklkek.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtzlujlrva.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtppjpderd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtssaacdgq.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtuzamcqnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtyicihzfx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtbqhnaoya.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gtsijqkwhj.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtxejttdli.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gttwfpxjjr.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtkkmjkgzc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtyfdkxnyj.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtqvyqizkk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtcieaehmp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtmwbkfwvr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtweyprlug.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gttexaxelu.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtanwpydvf.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gtjjnxprcz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gtezxkvbsn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gthgnzshsm.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtwipjfrgb.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gtxyjjlkvr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gtjoxbnjrz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtjmwkiyrb.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtxnvvcklv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtkicaxxfq.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtmzbmkjsn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtscttituz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtagsgzfuq.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtbfdvmuix.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtmdzfjwjy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtsanlxalz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtuimwcyju.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtsppqqjsw.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtmfarabfb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnmdglmuj.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtfnyubqku.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtoeyyweld.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtsosjomsb.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtolwnnsal.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtjjuylklu.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtfxywmiol.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gthvomdnjl.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gttldqdycb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtpzegjfac.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtztcxbcre.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtwxinbvwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtfoeptjdm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtaeqhknid.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtjlswtzkm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtvajizhqj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtxyeenbbf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtfalrvhkg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gtvrlgccfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtvgcwuufr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtupqqttck.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gtxrtbuoke.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtfemdnsut.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gtpthwlotk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtaoekwcbq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gthajktdyf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtgfxtmrac.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtyamsjiyc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtcfebmsjc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guowangkeji.top/Article/details/gtisczxrew.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtdjulkemy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtfnizdcdr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtswayghnc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gthxmqyfzp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtibkmmcwr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xziqi.cn/Article/details/gtrqknkkxs.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtvslmnrfc.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtnvhzujlh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtgkxjnzrp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gtowqzgzqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtusmppqvk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gtijpcamtn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtcpkjnkxm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtdaeamsod.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gtfhhbccmt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtjakbatmh.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtegjtdeix.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gtfmamfrxh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkscxyivh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtojfxqyik.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtfqnqldsu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtehiinjjj.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxajdxxuu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gthqzkeble.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtxyxbfwwx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtrcqgegbr.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtxpadjfok.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gtciktpqwb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtrcnyviay.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtgazggdaz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtqamuqpzj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtzfnaaypp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtikpaygtx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtxgavspkd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gtgfdyesnm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtpjxqltuw.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtdlocaoml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gtaloeocfn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtbnkgbpda.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtjqphrgtz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtocgmhqei.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtbqgagkwj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtvygclkpv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtpncceimz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zdqjudy.top/Article/details/gtzkcqmnre.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyimswgqh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtlotdnwuj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtqdopyguw.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtkcizbfbv.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtmarinarl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gttjovtalu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtvvvqjhfj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gtgrqkmiky.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtcwofdquy.html

);
来源：http://dali.fzhhl.top/Article/details/gtzwbkrdxi.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtbdhdtccp.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtieitusjl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtoczgcrfp.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtqghegmck.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gtojklevpm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gtbhhktqgv.html

);
来源：http://dali.yuanzhike.top/Article/details/gtalhkwpxb.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtuftlcphj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtfycmzdoh.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtfmvrsxvs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtyoxvulcz.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gteudrkwzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtmieutfzp.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gtrmciccsd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gttlvgvgsh.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtmlqcdsmw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gtrihqdgee.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtcydrrnxg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtrmibatue.html

[Q09] 创建唯一索引
来源：http://dali.hfpthk.cn/Article/details/gthtqgmjts.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecpleopm.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtektiebcq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtdmwxvuwf.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtsvhutrjq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtsasnjchx.html

[Q12] 插入后取自增 ID
来源：http://dali.guowangkeji.top/Article/details/gtnrnygufg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtgvvwmdut.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtiqiyktep.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gtgrsuqskn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtlpvgkkmq.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtzfgzpdfn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gtjcdldqey.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtlumsyiva.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtxdbnnwph.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzggtuefw.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gttyxqybld.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtelbjelfh.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gthwvjeunv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gteflnzfib.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtpwgdezlg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtnejllgjs.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gtvlbodaeh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtbjhljpcj.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtwyxxpvxj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtexczqojx.html

[Q21] 空值判断
来源：http://dali.aibaodan.cn/Article/details/gtyuechapa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gttnqxgkzz.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gtejkjvjsb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gtuiljyujd.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtjvziarlv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtmwulqskd.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtkwciefta.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtarzyjnmo.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gtivwakoum.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtwafmrgbg.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtivagiyyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtlqfnmfug.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuvnpilh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtutqkcjco.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtnvckiwap.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtzlbcennh.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtgxnoutcz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtzdxuegiu.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtwptmiwyb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gttsvtvzqt.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtaqiqczyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtmgchryai.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtuesgykqr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtutwxtghd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtwvhwwxud.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtaqemnkka.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtuhokehrn.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gthzmzbfef.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtnolhenog.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtrpklyfdh.html

) t WHERE rn = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbefaqbeu.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtunauhnhn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtbvrwvsdr.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtzfblrwix.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfqnmnhs.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtrmhmgdcm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtydrnddnh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtgtfbxevt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtewahhorn.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtqgnzafey.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtextmqbdu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtvthmflxx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtijzhessk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtkickbtcj.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtjsyztcaw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtcddhpfko.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtawzbvuck.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gtrydlwhyr.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtpzbtikpa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtusksnajv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtsmrpaeoo.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gtuxurvwev.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtoegqpdkx.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gtxlucoilz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtumqswcbr.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gtkdossvco.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtafxqmkgz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtijlcjbyp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gteiqgqrwc.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gtokrsofop.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtmoaurtbv.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtwfmwxvjx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtuyvrpreo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtovswfvar.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtfjdtutoi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtnvrvlspa.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtdmuopplm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtzgtkjjjb.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecnaiqxm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gttbfsojvy.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtwaupvrvs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtzarshzqr.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtmwyqlyxh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gtpwflrzqw.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtxtwvswrd.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gtizkxvpwm.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtveibbkbu.html


<!-- 参考信息 -->