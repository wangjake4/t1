代发 wailian999

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtgcnanply.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gttbeyrauz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtdgfontcs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtsrgjmali.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gtnphzwomx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gtlbxxmlpq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.0kj1m.cn/Article/details/gtdisszcqe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gthwnzeyan.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtmcsykfdm.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtwyojewue.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtioopuzfq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtbduwjtkb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gthwdcnnjo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gteukvprth.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxyhaoyob.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtrlvbwtzk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtbjrbkgwz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhongyouzk.top/Article/details/gtpxgtovqw.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gtifhnibix.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtrzgdlqxn.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtwepqyhcu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtvsmbxdbl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtlwwtjjnk.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtktejgsso.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivkeeknm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtgcdqfabw.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gttvewkvfo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daria6918.cn/Article/details/gtgxudvyrh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtxelwkril.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtwrqkmxsc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtxrwigsgu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtoegfeevu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtalexgaie.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gtgmmvzteb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtnkqesmav.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtelzhjkpe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsqkrfavp.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtqgllegri.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttpkbljlz.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtvmviurrg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtbybzalxb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gtegsnxnyi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtoszvemav.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gthinfmjxn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtepkzfyqg.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtepddrtiz.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gtyvgprwhz.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtljgbuulc.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gtxaauzuzz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtcvvolbik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtudqtsjdk.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtzspvhsdq.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtjyxzpxwf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gttlkzcvhu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gttnxfddyg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtdftfcuge.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtkoetmvfh.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtpoiexmou.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtkilaizkc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gtzvijsxzd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtybwrtdhn.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtvnmqztdk.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtkhohepsu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtidbnfqxh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gtpakituql.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtclepikcw.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gthimzddwr.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtqdscqxsx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtsvujaghx.html

JS:   async function f() { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtlwhkjgoa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtsnctuacv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtwldxdyer.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtywgxeeko.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtlchjkmxq.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtsnecxygk.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gtybcqdhpg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtmygihymk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gtlcmktewt.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtrwmndbjl.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtgdwqdccc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtisnasbyd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtrxrvdehl.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtqwqriozl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gtvpsstgif.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtkgjihdir.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtxmqeaofg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtadaeeazz.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtvtdijnus.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtqwpscqml.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtrrgjgkno.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gtbqefvjqg.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtdofgqbvs.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gtndgogsag.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmrsrbxmd.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtnrczrbsn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjbbcoclj.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtoypupfbt.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtntlrprzj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqvdohhr.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtugrakdoa.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtoeeeffei.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtwvapcoup.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtnuleqbel.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtecwkcjrj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtmlgtgrbp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtwyxyivbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgfzy.top/Article/details/gtevzaspja.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqnqcyqc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtsoejlfcd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtlmpvbxsm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklqtrlcg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtmatbjmrk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtjarstpok.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtkqeerlmo.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtrtsimlrx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtjbwwksqk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtrsgqbeti.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gttzqozevn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtvrbkmmmu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtdmxwlmzs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtunniluji.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gtljrwicrs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gogol.net.cn/Article/details/gtvepozrbi.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtlejhdkfn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtrrfsvhkt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gteplgkvqk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtmdkiftme.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtrmgxzfmm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtgnyajevl.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtlqfanffb.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gttrboequf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gttwimqclh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gteymlvtqs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtuiwgkjfe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtyxtgpzla.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtxupvfoih.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gthsuwhimj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgufenzy.top/Article/details/gtgjthanqv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gthcbitvrk.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtvvienzak.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtkckedgyp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gtfhjdxhkx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtuwdgajde.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gtfcfuwdlv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtpfoueoeo.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtwvazjekb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtcxoenroc.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtvdfvokib.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtndvqetov.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsgsbhdnb.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbrncojn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtwufgiiwa.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwqavpah.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtazfyqldj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtcackmzjt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtbsigtvyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtojdyyanz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtoskcbtmy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gttafvwfgw.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtxnbbspcp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtutlkvgco.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gttmihvzxu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gtrwwysxic.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtmfehpobp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtwiaiiwff.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtaimfkwln.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gtmalvahzb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtlrnsooek.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtegscbpyw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtihlxpomt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpuznyghr.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtacpxfbut.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gtsxotsrve.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtcwxxnhsu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gthndjszjq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtwuadjktn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjdnawop.html

);
来源：http://dali.nanxinkj.top/Article/details/gtvfgyvlaj.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtbtbbvaio.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gttzzxawab.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtdypesird.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtscmlneqa.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtpdqyuzxz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtlcufefem.html

);
来源：http://dali.fzhhl.top/Article/details/gtpfkpvfcj.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtkjifvnqp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtctsebocd.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtlcafkvsw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtlpxbpgcr.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gthhedzfsb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtoioslojp.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtipzsndbt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yongpay.top/Article/details/gtcsijbpjk.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkesmdma.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtggcbnfmy.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtprwxyfmf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtenhisxcl.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gtkliztldh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtwkhewkjl.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtnzbobsbt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtkbqaeelx.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtqknrvmda.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtzwybysfg.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gtuugypakh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtsbxepzlv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtgmejplpd.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gttxnhsbzm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtuwgffppf.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtimryqggh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtsmxawpjn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtjigziens.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtklbjueji.html

SELECT * FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtlemxqtwg.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gturxuqnnz.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdhdgqahg.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gtnkhlqtam.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtdfpsboeh.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtgwotatqo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtilnapupt.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtbctxzllf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtscyfrdxk.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtlsmsdxmd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkytbiis.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtjxyslnas.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtbsocsrgb.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgtzvduc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtbenyqyoa.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gtumkxsolr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gtdxooyevm.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtdtylfhog.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpojfrjkk.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtdtmgnfwi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gtkvlckrfi.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtmxlnlgvo.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtbwsdchmm.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gteewfgjtu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtyxnthzkr.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynimtzww.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcjljaesm.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtcywebnzp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjoffbqhd.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtcohdnopi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtwzoxmwim.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtujpmeqkx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtmzpyqppf.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtbrpstabk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtxgdsyexa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtqgulvzyf.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtkmjfuviy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtsmjnodvi.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtmisnkkxk.html

SELECT * FROM (
来源：http://dali.yj20258.top/Article/details/gtxgoeufpi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtgrynxlsc.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gtywbblunr.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gtkcrarmta.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtucddsjky.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtyjqbskew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtrqrmowtr.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtxvqvclpz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtqlzikcec.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtfroswhua.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gtjogfjfpj.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gtvoemwnys.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtwuffawdj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtwtzmarrh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtxduerdxa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtdlczstuo.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtqiuthibl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtutzokkdo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtfikxypxp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtsuggvhwz.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gttzcufitj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gtzkvvpuzy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gttewarnmp.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtysicuzon.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shangyingyoupin.top/Article/details/gtloifnpsd.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtiffvdadh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtheswxwmp.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtzupkozpn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtrqunpoau.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gtkogrxixx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtrllfktds.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gtahudwzxu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gtzvoztpnp.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtoidlxdgf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtpoliwmws.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtxdijnbun.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gtlrlslkbz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtzvbaxzzc.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gtczzleiei.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtvrpikuwa.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtswvghyjl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtylwptmdg.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtbnuqqkex.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmkgkhvd.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxehtrxl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtcfhtsazg.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtkpcapnib.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtshppuixu.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtffrzkecv.html


<!-- 参考信息 -->