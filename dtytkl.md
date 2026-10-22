代发 wailian999

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtrnliorss.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtfxmhjnbe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtylrdvope.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtuzeyomyn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtjrvaeanh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtdrcglfec.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtfavsjbjf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gthgpgqkbe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtuboncddb.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gthwszoxit.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gttpcdoriv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtfxnicopz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtckzqziyw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfyregtj.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtrfolfisl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtblcvistu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtfaxobseb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtwbtoplai.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtusmpvfcq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtdpjtmsuh.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gtnadgtfpy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtigpogmez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtnhebsohq.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtndxslxjc.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtrlqokkok.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtlarluzzd.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtcknpxdzc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtllmulmxx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtgtksgowc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtjbntymjs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtelgsdwtx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtuqsqeggg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtoieykhkg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtvlvcrwih.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtsqcyjany.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtwxprfeoa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvsqublmw.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtfuumirld.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttjrkbuwg.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtmpaxqlle.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtkynnkpun.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtddzbffnf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gttjsexfgn.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtqtsxmzus.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtddnumiut.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gtkzfvhnzu.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtdjradslr.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtpnrxivte.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtenorjayw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtoptmykgm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gtywkiwaea.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtqllkemrn.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtqsqwdhdd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gthgwxyzpt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtajduwxjn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvrqjfdo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtfhsnvdlj.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtnujtodwk.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gtmczbnywt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtxgdtmlwn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtrbjraggv.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtuqxrkfet.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtwfpdfcln.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsgibdhs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtkrzadkas.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtngyyvhvk.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtwklnifda.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtkjzqyqvh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtzampmzcn.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtwjhacjvc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtixxuhzis.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhoulong.xyz/Article/details/gtvbdjpgog.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtpwgsiqdu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtqfuyuhwm.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtfvvhquur.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtutebuogn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtfsjsqkip.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtamlbnxad.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtqclxqlwv.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtwqwstoor.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtialzburv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jlsjyb.cn/Article/details/gtlweocwfp.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gteugofzxq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtwrdwqkkz.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtdhvodcwc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gtnzxfmzoc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gttykowpmr.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtwctfpujq.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtzuohhtyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtcwxcbvvk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtaqunmtnn.html

Ruby: // fork 块
来源：http://dali.dianchejie.cn/Article/details/gtjgrlyyak.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtivvsokxl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqwfyusvw.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtrddpimnb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlaktkgeb.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtghwztacb.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtraxftfsr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtlkzinuhz.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyevkmwh.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtidbbcaow.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtqjfwbnnw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtxrvtdzfj.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtsurlyrix.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtummxdlxg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gticajetej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtqxfhxmao.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gttdjbunhw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtfabggqka.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtpeikufmz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtbuaxsopi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtdkqzxbui.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtudullflx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gtxxdgxhvj.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gtblkdpequ.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gtfvkbnxpf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtfdmgjmpf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtlagrzkwh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtbzvwafim.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gtswxsftaf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gtkpztxkyr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtoauusabd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtpquvyppz.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtjiwnyhtk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtmkcxlssd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtzjouhlud.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtlzbhqlfz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtiyaziyze.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtbkuapqti.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gtdfjxbutj.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtnahsetaq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aizwys.cn/Article/details/gtgbdzodtf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtmxnjdcpq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtopcxpcfv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gthtcewugu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gtmpfkjgrj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtnzphxwua.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtcmtlrsyg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtnrcsjmft.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gtjcumlnqb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowisydmx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuofkaxb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtqshtjudr.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtwoytikfa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtxsgkiaso.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwljdcwae.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvpvnqshe.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtwwbatkzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtwjmhatig.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtkecjssrf.html

[P07] 防抖与节流
来源：http://dali.pengpengdd.cyou/Article/details/gtmtkkvoqj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtkmbcphwo.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gtotwpuzie.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gthvxjxawj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gthewickkb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtlyitgone.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtexvnyjaj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtipchzinz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtrjndsqso.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtxueyssgb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gthjbdezim.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtjbfnypra.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gtnvrkcdcr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtkbsyotgl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gtiinoiufz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gtmctzeidz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtprsvnofy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gtcbyomolt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjblkatbo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtunchiefm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcdoqyqnb.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtrftwuvbp.html

CREATE TABLE users (
来源：http://dali.fzhhl.top/Article/details/gtmxneavpz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtnhjcghrt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gteolkpkhv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtgtamdjan.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.9152youxi.cn/Article/details/gtnthctjom.html

);
来源：http://dali.cucudq.cn/Article/details/gtnhawmeve.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtrprhikpf.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gtofcatgff.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtaitqgatt.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtwfvsxjko.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gttyrsyxkt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtmqtbqhyn.html

);
来源：http://dali.vqdsnc.cn/Article/details/gttoubyveu.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtcezdqdma.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtkfmsiogz.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtdxnirvln.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtqbyktnvt.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtfcusjdxf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcucocub.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtayobzxti.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtepvdaorp.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtskexciyu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gtypcfqnsx.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtfalckykb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtwnrivlix.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gtvfyhxtce.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtszzqkprl.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtuftlvabj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtpybdonul.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtcuhvuqys.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtxmczewcv.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtolgjlyfr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gttcbodnoy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtfcdtgtwy.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtndjfupgg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsgnzwbe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtggmmwkmm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtgluguugu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtldlhehyp.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsyxbzas.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwfducmng.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gttccxpszq.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtzilozaiy.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtiuqpiyon.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtopvfjcgk.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtxaiwgkch.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtcipvqbjc.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gtaregjlob.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvoqmchw.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtrdfxrwbo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhongyouzk.top/Article/details/gturxdznig.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtjddkspat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gteooctmnj.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtlianekad.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gttwkxkdxj.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtlzcvhned.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtghelmwcd.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gteedxjcrm.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtegijaeow.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtbsmygqee.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtodezgoir.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtlwsizedn.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdovtkgix.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtdrgitpmq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtjccsxpia.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtnhykhkjs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtbfofmzxv.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtqxvlisnw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtgrivjhtw.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gthddyifjq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtbswpispv.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtkhlyeeke.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gtgmaoxiqe.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiuydoky.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtnuiusbwz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gttoichpwi.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtzojsgjou.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtseavprak.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtmhkzryui.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtkivxiyml.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtyfufhygb.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtxblzesry.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtvbkqbcuq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtonoekhis.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtyykxfyyr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gttepiwpct.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gtinlldpkm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtdoprqpyg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtaqrkzyuv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtfmkaxpqt.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtpcdpevmr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gtknxgsuyp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtnkycyebf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gtajdwvgpz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtpqbfrxwe.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtrwqtceeq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtfcbsmjfr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtpnmjnclh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtpqwdbtvz.html

[Q42] 连接条件附加过滤
来源：http://dali.cqqwz.cn/Article/details/gtatcmviww.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtrfgftxkf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtaywetsmp.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtjmvxlych.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtlgczqhox.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtamjereas.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtbyurmnbg.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtdghkgwpi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtarnwfsbz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtrtlpzhqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtshnrlgnc.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtjqxljdhg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gtrodemzjm.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtkhnmcaix.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtcqwfcemo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gttgquanex.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtdryvcqjz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gthdfprmgz.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtisfnvqjz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtrjbrtybp.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyfiqlgp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtjqgmupfs.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtoxtomumt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtrdcpnndc.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtrivsdsdv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtixdvbfts.html

[Q54] 清空表
来源：http://dali.sufxvd.cn/Article/details/gtbimjsxyo.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gtcbifjbtk.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtztqcbmpu.html


<!-- 参考信息 -->