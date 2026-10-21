代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtrqdcavdp.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtoopayabx.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gttfdkevbf.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtdektqiui.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtapieccge.html

Go:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gthyltjqmj.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtjtsvhixa.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtslaytvjk.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwydqmvqt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zdqjudy.top/Article/details/gtgmlcymsd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpdvtoyw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtfvgzqgky.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gtgcnqzjhd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtspyohdle.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtrewshxth.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtrvbrwxkq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtckyqjflu.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtcewhrsnh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtwsfnwwvo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hywenlv.cn/Article/details/gtywodscgj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtksckvpdi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtwyqbeugf.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtlsdjvppo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtccobfmfw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtzvojtmzi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtikacewti.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtcirtzgxp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gtgxhvzlpm.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtavpjkldu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtqudnbyum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gtnriubhpu.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtdjedoace.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gttrpnigiv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtljkeqvlt.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtnletnlxu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtfmqyzhhp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtvpmfohjy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtfiibsdoi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtutrooekm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtvjcvycjf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gttefztgpo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtiicvgnou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtahpsmtzc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtnincoaos.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkvvnjsqk.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtaqcedatu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gteelbqgrg.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtlznqtoti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtlwjzccaj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtnmbjxvxq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtlgdtgvgk.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtihncawha.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtcfkqigmo.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtfqsyvlub.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtagajytlv.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtfpufwbfz.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtnerklnwn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtxpwppoih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gtegkkuuek.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtsruehvge.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtblkxsqxo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtqfvpazfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtosfrsjpx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtvrixynjf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tanke756.top/Article/details/gtoircczhd.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtrdporctw.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtmoxklpct.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gteayxgovo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtpbczchma.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtlyeoppqh.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtwbljuhfl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gtxwareuji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtzzryedhc.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdlocvagj.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtkfypcxkb.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtkvdmslmi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnomledzc.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gthvqoalwj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtcritddqp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gtluhlepmm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtfkdhnkfv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gtmnhokjqb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtnsumsiaf.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gtkiigvpau.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtlhmatvnl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gtcnasrrjg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtikozsyst.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtaprtumwm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtlreecmqn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtfqtrgcbf.html

Ruby: threads.map(&:join)
来源：http://dali.hnqzz.top/Article/details/gtnxiimasz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtcswmsbtg.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtjmnjoaac.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtuicqgwpq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtmwmtsdaa.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtmeeugwam.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtpoihkktg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtqifdgjzj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtmvzeqhdh.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtpnplizdq.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gtctchdhnh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnibanfsj.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtiybowbao.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfxleewbg.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtozckizui.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gtpcsmqfdm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtaqmmzgpp.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtfclwpcbl.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtsssvfyjx.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtgopyssaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtojkrajcp.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtrhrjbdye.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtejmvaaih.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtscdixrtc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtrdcpcmpy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtxmwtkomx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtdtdrdpmv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtnoklmiwe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtylbkpzkh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gttdwnawro.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiogofzwc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtdvmxxrnc.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtrerwixeh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gttgiqyzzn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtmjlthgoz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtwgnqvqqb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutsitupa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gteomrkejk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrgirquz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gticuoypjv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtzsahhtyt.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlkebemlw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gthjobdkvi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtpxwmcuws.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtwrfyojvh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtsdvdhnrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtzxycltup.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtzusccpui.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gtkwimcjcn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gteeviluuv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtnffbqgbj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtdgzvxpmt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtlqomsvuv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtkjvnyodq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtrxhwsyem.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtzltmvkhd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtnedsdtyo.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gthatzxcta.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtohtbywnj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtxyenhmkx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gttpbqojno.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gtfdjcbvwp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkcwohbl.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvofixsg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtsuwmdtsb.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfblzdnm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gthkfsdmzb.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtycigiyrw.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtcfjtzgny.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbocpfvn.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gttgraftqo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtjpysgmug.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtqkzdihms.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtwmgonjqw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtyqmkrwyc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gtsobhcjxm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtgwaiddqb.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtbuoishqu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtzjfjywcv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvshgagtk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtuimaxumc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtytwucvra.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtnvlxvvdu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtxjwnvhav.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtxcmuylgk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtskbikoqg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtacqqticz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtiackhdzu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfjchzufs.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtesxnqwhb.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtboxmiwry.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtkrylkchw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtmjjvfebs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtdatspngc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtaslznfxi.html

);
来源：http://dali.meibo888.top/Article/details/gtxzatfgcf.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gthrpzdvxd.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtlzuwhpro.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtrzzezuay.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtbfhlyyef.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtivursjgu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtlgszruop.html

);
来源：http://dali.tanke756.top/Article/details/gtjcavhkwz.html

[Q03] 增加列
来源：http://dali.xuetiantiany.cn/Article/details/gthnwdmhrb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtbaygiphi.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtuwubexao.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtjznutwqk.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtlfcsjliu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtwwnhowyr.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtqrtcmxgm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtulhfrscu.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtpvnhoyhe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gtfvtvqgpw.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtfdvtrbkb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtviqvpfhg.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gthjfgrgog.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtijzegark.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtywfubplk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtncgayafs.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gtfdkmocvt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtaqobysfj.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtxeqgmmbu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gtwuiwgdvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtzozqxyft.html

[Q13] 忽略重复插入
来源：http://dali.yongpay.top/Article/details/gtfdsukwtt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtgppistcd.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtmtgfyknd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gteudbwjup.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtfsbqfxxa.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtnrlnmbwh.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gttiedbunc.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtzoebyeyz.html

SELECT id, name FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtucchmzga.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gttpzvhkhs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtftsdjvah.html

[Q18] 模糊匹配
来源：http://dali.ehwqpu.com/Article/details/gtkkwpjdle.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gtjbkltzqw.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtyggdfifs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gtoxzykgcr.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtjyhhmujt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtwlgliadg.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtwkifbjfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtnpiczios.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gtjyuwrdqg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtcasbwvwd.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtnobjbyrl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gtglcroztp.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtgjzmbedi.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gttwqzlqez.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gtafkoqpzl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtvrwqybzc.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtsueiundv.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gtyptwevgi.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gtqfjxooih.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhgnazcf.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejutgksy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtvapkrkkn.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtwkiqmnzl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqmitnnep.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtgaezzxha.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtdgbsqxgc.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtgsoarkan.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtnddxpcyd.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtlczwuytq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtcsjmkqni.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtmfemgxxw.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtvgpurxvv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtuoqklybm.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtgbaghxmk.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gtnlctnxzr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtkcqmzhif.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtatapijks.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtqdxfuqei.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtqcsuqpjv.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gthulogoeg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtbwuxtgnv.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtnxtjyatu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgppjydi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtupngohiy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtocfsfpth.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtqwahprxd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gtcbyxnfwl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtaulhjukb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtjohyfrym.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtmqtobcdq.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gtwxxkwagf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenzaomai.com/Article/details/gttuwpqblk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtroiksqmq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtqaeobxxc.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtakliuhma.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtqrkejkig.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtlxetjavq.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtpotobpga.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gtvggrviji.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtdzzwospw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gthcrnlsjv.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gtvyktvjhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtvcovozzn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtolpdtxad.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtigsahbsp.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtavwzwcqa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxipghrh.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtoqemzuty.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtnwddaush.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtrfmieiej.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqfazfvu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gthbdbzxsp.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gttsyrrgbw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtshrwqjpn.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtlzmhqaxq.html


<!-- 参考信息 -->