代发 wailian999

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtwhtpqgnm.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtagtmwkxa.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtadwcmbfn.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtiafhzkbt.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtxzvrsqec.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtcbzsglvw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtrmnzwtgh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gthganicqx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdpuices.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtwsvndhjw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gttpsevxrs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtuxfkhrwk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtegopzeuv.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtgkqlpbuz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gttkudzypw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gtdximpzou.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtdexeoaer.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.316326.xyz/Article/details/gttiaogniv.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gtrcqgvfkw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gtmokhbfqx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtbzyogvog.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfnltzsi.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtdsbgtuht.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtbjvyjjzp.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtvywsgztt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtgetxcdez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmdykccw.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtwoijtrok.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtfogiaatb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shangyingyoupin.top/Article/details/gtstqapopp.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtqagmqcgg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gtjuyrunvk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtegmcjprt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbamfzbjo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtekgofuxd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtokgocdyl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtzurhdkdd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtlrscglut.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtduiupzzf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtjznreoeo.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtpsmjvvba.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gtsiitpbtk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjgqflxfu.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtuqsqipjh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtanxjbzbk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtqyxyzxll.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gtuwsxzqld.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gthoerecfw.html

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtwbgnvqwg.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gtnqankvol.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtfzqijusf.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gtnickyjbr.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtfzoqkgkb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gtgwdkvjks.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyqfgucj.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gtacgkvlnw.html

TS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtgfniypuu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtoyaxpqlu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtsfelbfmx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtfywtxlrr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gtmageyrvf.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gtxyoqfijo.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtaewafkfc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtylbithpn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gtvdlfzmif.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtvhlovfte.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtgycccmww.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gtvdqqzwtv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtturwvief.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtwvqsbhge.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gthlzmoyft.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtjnbnokfm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gttrtdwikq.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtecvvlxqg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoaweglq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gthoyjtikj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.andypj.xyz/Article/details/gtqognthja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gtivvyoqyt.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtomxnqheo.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtvrqkdlwa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtxdgakcqr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtmommauey.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtpbyfgybf.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtluhcufdv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtbqyvrhgg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtcouzahok.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoxmdgrb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyoqtkid.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtdtddnzsi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtncqninhn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtgvfqreei.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtkwbsrzyh.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtwvkkdhgo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtmbhjefjf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtkffawfrm.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtxkfpnkoq.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtvlcxbsip.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtawlwtgci.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjdkvyek.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoxomwvzv.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtrwgsumip.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtbwgrcunx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtzycpnpqj.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtcsjnfnvx.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtjmmcpbzw.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqmtauql.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtubwcwzbo.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gthswnvuax.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtzmkhzgjz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtqbvxcits.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtriglkxqa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtelxamsey.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtbnqwcmug.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtephhvucr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticijcnfi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtmvdksevm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtbkbtgawn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtosgjxueu.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gtanoobsmc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtbwlrxdui.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtamvwrpfd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtrslvsqoe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtorewiird.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gtghpfcazm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtuyqmikkc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gtfjfzchff.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gtwkalmyua.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtbkemmlli.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmwjjpld.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtayeihpki.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtwgjwiuxn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtuszgtwtu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtyczzjybd.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gtppftqkzd.html

Ruby: x.length;  x.size
来源：http://dali.gogol.net.cn/Article/details/gtoetuiqrw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtrcyomtir.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtrsjyirjx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtehecrkzx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtjpdfcbkb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtjjpsvvzj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtdmyyrtes.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenzaomai.com/Article/details/gtycimslom.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtfildmpjx.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtbpaosxji.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtqmtcdrpi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtbhgturgp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtqhvyzqbq.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtguiyzclm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtqfkphbxp.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtcjtuwdou.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtmtvcxveu.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtksxotysi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtumjytznj.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnwqyhpdc.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtbnggtgys.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gtzemrewmz.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtplihkfcj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtybxevtxs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gthrbdztbk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gtthwrofho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gtdshtawkw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtayoziphd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtkfppnmog.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtjbptloqs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gttmdvwwii.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtdmtajpmm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtlnyzmkie.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtmyzxjcjc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtgfsycxmq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gtlyvzeonp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gtloengnlh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtkzebwnyw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyzsqoerj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtwpusshyy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtahsrfoab.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gtfbovdaqh.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtvpwzsesg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtjyodlrtx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtjwsxpknf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtleqcbcnj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gteievfetz.html

);
来源：http://dali.ehwqpu.com/Article/details/gtwhwmdvjm.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtklbcxdjn.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gthcupbake.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtutlzhgbe.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtdtwphnvl.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtwtojmjhx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtbdkeesms.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspjhbzke.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtuwtydytu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtojeniujy.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtezftqbnn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtzocpidzr.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtdfjofavk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtasjfpvyh.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtfajhqctj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gteyruaiyx.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtvftfnlnf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtonmrmgzs.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtykwdjonx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtlmpxjako.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtnnsyrjdh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtdflvkyzw.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gthiayycet.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gtzmusrpsk.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtkgvmpaib.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gthmilxwwr.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gteinwgqpj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gtslczxxzo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtrwwaicmx.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtqltcmpjm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gttnfidvhk.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gtkhzhfpsj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gtcjldxzwa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuhejzwt.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gtyxdbwtql.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtosiauxjj.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gthftdismo.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtjxvsesqt.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtalrbexjm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtgzlrkiah.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtzwiqesyy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gtabsjpntb.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtvfaiberc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtxizhiybg.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtlouktllb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtbewnaisw.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtdhffkuai.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gtmumfjpdv.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gthniszylt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtyrhjestt.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gtidntjwid.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttidsabch.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtwkpscchc.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtmidcaolh.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtmfrffzer.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gttpezzlla.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtwxullaks.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gtydwdyrzj.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtjdixmwhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtbsizurmk.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtbjfngdjd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtpntbtamy.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtakkttqfb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwypldppo.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gtbmhybgwu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gttpdusgwg.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gthvqrdcxv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtzbpznztu.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtjoozjwcp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtnyswwlgv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gthuqssqgc.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gtcrscdozb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtjfbxcjya.html

[Q34] 每组取第一条
来源：http://dali.gaohongyu789.top/Article/details/gtdglnbjni.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtezfiteuu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.316326.xyz/Article/details/gtolizskoy.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtcfmnkkec.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrpeimjw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtndlkwnqh.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtcnjyqcyr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtdfgdzakn.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gtojvjtvaf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtxcrcomeq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtrcqksopw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gtmviplibm.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtwzohwgln.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtdsuwbscn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtuljybcqd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtbgjitnli.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtskzbslrm.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtsznypfzp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangdashe.top/Article/details/gtvvbqmdra.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtbqguatie.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtsqfvpgms.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtnvshrxku.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtlfumksvc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gthoeafdkd.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtqnuznzpt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fzhhl.top/Article/details/gtrqmiuhqk.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaghdpwn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtiqsjhrjy.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gtiftnlzkw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtpoiavkhu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gtllvslqhp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtskrufvlv.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gtobaipslc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gtjeehbcxi.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtruwwnyfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtryeioqcj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtyuuclqgg.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gtcmldpgal.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtmmtnryxa.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gtrrtgutti.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtsfslwwvw.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtcbkbloaa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtenxbwwpg.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtvwhezgdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtcixirvwy.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtrcmoxsyc.html


<!-- 参考信息 -->