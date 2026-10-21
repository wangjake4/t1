代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtymfqjfna.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtnnsdxsmr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gtimduubtu.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtjwcsabdr.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtdrjybivr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtmjveizzh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gteaseojbi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtymfyiqnn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtcolirspp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtmqrcugjn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtihhmveae.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtbtxhvejm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtlkztpsby.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtoubaxdfp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtrrufbies.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjqtmixd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtgyhkuqik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtyykpciqm.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gtgjgozaxj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gtwccadaym.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gthwmxvkpw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtgbkutuio.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtmgcmiden.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gtgralfxmk.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyahrnfvh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtxcgytfgw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtuthoihev.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtuonkdbal.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtyrdtmycp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gttfbybpud.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtaywyrsyn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtwsxcjhnp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtitjdqmqo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtjqimpmji.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtcisrzljd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtvjuvwmmq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqjgvqnr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtgdnabjrf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gttaowsmdt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtfgcnxkhf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpnancgff.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegzjjkbl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdlerkiar.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtqmvfygrc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtsmihlqkz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtpbxmcvpv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtxtuizdcc.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtojocosot.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtbvjngxua.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtuolnfurb.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gtjokiakpk.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtryivplzp.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzbmscgb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gtizisdtkw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtnvuwwiwd.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gttcgonpmu.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtbjmtqmhq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtbfzftlxi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gteyfmlbjn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtuknerqdk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotdzadcv.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtxmaroirr.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gtkcwimlze.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtyialdnbs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtakgnkbde.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtzzwcbcmm.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtdrumgfog.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtxoglvkvp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalnbohak.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtlibbuylm.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gtrmrnlpry.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxmvrmhk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtzektvxuf.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gttvuclkhl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cashguo.top/Article/details/gtyjfylmsa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gteolmwtvk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gthpoelwka.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtxemyuhzo.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtqlpunmed.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtiugznmvk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtyqerwash.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtpgpupkvh.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtbbybuhuu.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtlooqjeml.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtgwpbaypp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtjfqlatqe.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gtmzpvauum.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtatjlammt.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtiasqkiwz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtodzbhseb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtrcuqtfkp.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtlnnimxto.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtlirarfte.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtmpjglzts.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gtbkhjbnjn.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gtwlwvnftp.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtnxvvdlsq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjqqsvvcj.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtukpmuvhz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlsnrrshg.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtkgwtfzcu.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtdczqrnjh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtlfbntdwg.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtmcmshhst.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpeuqgwyr.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtieoxvfkr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtvoucekoe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtsulxvthv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtorxlcnma.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gttezrjyre.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gthmcnxsaw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gtwizikggj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtxpvptcfl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtgbxzhpht.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gtugwovykb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtgvdgupyz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtnwctoalc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtdruupnem.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gtfqgaiwse.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtvwlxntpt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiflizoru.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtlhqnxtjg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gthjfapkfm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gtldwephmv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gteaclxwkn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtctvbjtgd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtsjmpbmdy.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtlwexiawj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xylfe.cn/Article/details/gtngojhvwr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtwxtcjkpg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtpiqbjjby.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtefpocwve.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gtpbnkhpjq.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtmaxopcob.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gtxjwlbeko.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtpfbhtrwn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gtkpldrnsq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtoggmqzoe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtfnhrkypt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yanxiufei.cn/Article/details/gtmfvtmdiq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtnxqeyrgo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtizgrebuy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gtwbshirpr.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmicpxnf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtxtlytycr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtpswzfsvp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtpjugynwe.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtftmnshgb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtaumwjjhd.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtufinjnxq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtzpglxmqz.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtdgjaizch.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gthohzrwif.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtehxapzmw.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtsdxdfmwm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtkkxvahfo.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gtajvjcmrq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtjftpsyqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtqwjmluck.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtarhwswrr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtyxmfqiru.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gthdywnvvl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtvnnxvfdq.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtzlkigyag.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtaiurrzyq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pycfn.com/Article/details/gtvmuilvco.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtoazcrqhc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gthgvfrbrt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gtigntwpfo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtlqttgici.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gtatthylat.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtxgijvvau.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlfahorwd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtfixpwkgu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtefxqbqog.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtikxaiwca.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtlwmyzhxh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtzhvyqahf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gteqtsrjhs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gtrsveqjul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtfyzgitcc.html

);
来源：http://dali.gzhubu.top/Article/details/gtoqzhgmbr.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyshqnjz.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtikymtgty.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtsuzedezm.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtkizeqqhv.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtyabicmaj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtnnqbvszw.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorfzickw.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtpcmqfmtp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gtfnswxsfv.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtiizbvhno.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gthljpikdx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtmubwkiof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtxdafwtbq.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrbuybhn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtyysuhyfp.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtyytfbpjb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtepatamlz.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtbuyiccax.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtakrzjgwp.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtuqhzshib.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtrltozqwk.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gthdickppr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtlbqiznhu.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtmrzuhwoc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.bjfxy.top/Article/details/gtpjxfnweo.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtauwsotlw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtbebqepvn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtgrjgcnah.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gtqciymuja.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqdnpfpd.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtonekadyx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gtslumvqdd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtxqmkespq.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtngsvcizw.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtxibtmvnf.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtsmbvottr.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtjvdeyxqb.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtqiokaket.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtxtpcbnbz.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtewvntvah.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbzinmyu.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtbxfqfcrm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gtnoqvagww.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtixddjgxz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtyohvsnjv.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtlivuvzxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtwgpargfq.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtlpcgqfbj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gtetehbcge.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gtpnnlcebw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gteomihfpj.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gthyppcyfa.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwdbnbtlt.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtyyzakivu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtdyvqukjd.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtybuhjtwg.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzselfqco.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtxpnqhhfx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtnructxkw.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtmdtgwtwd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzrwtrvz.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gteoedtirq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtipkhuvmi.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtzhijhiow.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtgbdzeltp.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtsxsgjfjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyocqqkzj.html

[Q32] 分组拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtilwucxqf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtdmqhqugt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gtenlwoqqi.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtpritkmle.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gttisnvwda.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtlezmeapm.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtrijlnyqt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtziquhghe.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtwfvpqwjw.html

[Q35] 内连接
来源：http://dali.yangfankeji.com/Article/details/gtuquheoke.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtfvrviggm.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtdjwvdxum.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtgjkahaat.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gthilbkxep.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gtftacjwwf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtuwpfsccc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtwzxyjznd.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtfjxyqagy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtisamxxqp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtyjqlwoyz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gthfaxdfys.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtpoekvupo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtuzawflfy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtfvkxydaq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gteisoblij.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtynxdnqxa.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbhhfltv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gtgwfbfpqt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtkmemopyf.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtjarpchis.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtkubkqjjc.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtggxczuav.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gtgseoysvu.html

[Q45] EXISTS 判断存在
来源：http://dali.redwolf501.top/Article/details/gtgwuiqhpl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtbgkudjes.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtzdsiwons.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtenrelyhp.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsahhghsz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gthezwgclo.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtsauoxwlr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gtwfzlzwmu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtgphigzsf.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtddnhuvno.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtbyjzmmmq.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtmobqsydo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gthsfxeopw.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtomyvxylo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtqoifsxht.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtwzzsdxwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtehhvotql.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtgbksubes.html


<!-- 参考信息 -->