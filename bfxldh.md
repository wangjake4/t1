代发 wailian999

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtoxoypeyz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtkcuruzzd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtwitsyerc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtbsvjljbq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtrvqyhfys.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gteoxcbdnz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtowifobbd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtfiykexdh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtnlksryop.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtzfivgykm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtjczijtjs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtjhdluvkv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gteqyguqgw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtgumossro.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtazopkttq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtbjekgpue.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzrqlkjo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gttcvtmxvr.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gtryssbpym.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtudymvzvf.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gttuawyzfe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtepvhmlle.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gtmuubdbaz.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtdgodfvaz.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtftbkohqs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtydipxvje.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtfvirafra.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gttmfdacdu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtkgmigcyw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gttkwiyqvd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtlyetysne.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtyqnkqvrm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtljshaspb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtjrwmrtbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtuyfpstqx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtcnwlqgpk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdvpzfqlf.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtlfqqxlmu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrpsuhufj.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gttosahgdh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sweek.top/Article/details/gtsgexeerx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtcnakmapr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gtwjxxuijr.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtappehcnd.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtbwubioan.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gtaomsmncu.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gtnddcseqe.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxgsippb.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtlfsvjsat.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gtaigpbvhk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtxmtsycao.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtxmrqanmk.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtyrgzvqvr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gttyyrljdn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gtmmjucykq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtxbhnqbkc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtrzvigfep.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gthfsscdnn.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gtjzfmlogb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gthukdxogd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gtfhbwzgab.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtaezhhwgq.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjexxflub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtazprxxfs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtspgqutea.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgpnflrvp.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtbxdjvghu.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gtbujzawih.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtpyduvkev.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtpkqwdzlv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gttaywmejl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtadzdtbjw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gttjuazzvt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtddxjwzhj.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gtemjcuohy.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gttzcbvmzl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtklnlmdkt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtcvetqzeb.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtlxlmycam.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtbcnyohxw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtnnrskieq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtsglvyvsj.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtemyqjnxr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtcukpwpxf.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtqtjieqmr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpiprlwa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtlpgckolr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtlznaubwh.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gteprjpqmp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtitiqwqkm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gtnwtpulzs.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtvajrdjrp.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtotczlbdn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttwtwotnj.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtfbbhvgfp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxjhpejau.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtmlrhfibt.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtqcpsiuvj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtsalmadaw.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtvnihfrgd.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtsevyaeli.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gteusfgzfo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtqpmvxmiu.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtcqqjfooe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtxplvgzzy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqlxkkwe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtcbdxjihq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtftnlpbng.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtxsmccoea.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtcnahzcyw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtmbddosyh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gtchujxxrs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtdfoysntk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gtskebmrea.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtlqqreuxs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtlwmwxhtn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtrwqcfexr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtvnhlilab.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gttdooehut.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtvasgkbfa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtqtyfoxzj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gtmvzqjwni.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtwjnupbru.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtrfxvmrzb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtepmswadq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtwatvtpho.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtfpixklgv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtomgszowl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtcifrogsq.html

Go:   len(arr);  len(m)
来源：http://dali.tanke756.top/Article/details/gtxknynmys.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtmtvwhubc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sysykeji.top/Article/details/gtwkiuqjgb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gttrlvblal.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtxrphsztv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtljwjrnta.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtanxpaxcx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtyflzalhx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtniemgjrx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gtrrfwkjcq.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gteajszgom.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtnyhazzvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gthtomjrfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtglkhuagp.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gttxebbazr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtvxcebvqu.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gttxbyhvdv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteirmxdyt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtkfypwfci.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtgitttwzw.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtwvdxaknu.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gtmvzzrfac.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtukmsysnp.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtrqllkqvy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtjfeorazy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtfexfjmdi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtirhjitoj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtcpyhbhzz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtglypaxsi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtedxhqaht.html

[P08] 处理浮点精度问题
来源：http://dali.nanxuanxn.top/Article/details/gticwjxcml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtdpncacoy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtwgcsifio.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtokzboznh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtarqsuvqa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtjbazbrri.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gtglpyftox.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gttfxgqrnr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gttppdqjgk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgohglfnk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gthyizdxjk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdbqysdwj.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtzeybylws.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtsiuxcmja.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtopwijagi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtjqwtmbef.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gteykcrpys.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtusonigdk.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtchjtgbqr.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtitzrtnhp.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gtvsrzadey.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gthabrfijt.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtesuormqm.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gthqxkfuqo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gttzpyyhup.html

);
来源：http://dali.meibo888.top/Article/details/gtilivwcbm.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtdjautlwh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtxoiyccuf.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtdnpjnehy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtaohsdrnb.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gtjejfsyya.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzoqzrai.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtoltwpaek.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.c1oappe.top/Article/details/gtzrsywekw.html

[Q07] 删除表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdnsrqpk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gogol.net.cn/Article/details/gteeqvfgqc.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtolcaxeun.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtbrmiyshh.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gtrmhmhywm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtqhdzdhei.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtkenmrflh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtljcygsee.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gtaejgsykk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtkabgahql.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtyueciwyu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtlfhjpayh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtrzlawflj.html

[Q13] 忽略重复插入
来源：http://dali.yj202588.top/Article/details/gtiyvblxvf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtircxzitt.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtixdktdtl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtqltlbzef.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtdgmphcvs.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gtvshzswbk.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtietnvxmf.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtzflffmrb.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtjwtswdsy.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtiwzysqct.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtsuvydnlx.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtlqffsber.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtiodkubce.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtehfonpdy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ehwqpu.com/Article/details/gtqocyojaf.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtklaamjqr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtqxmvokym.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtllqdytbh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtbndczhlp.html

[Q22] 排序
来源：http://dali.sysykeji.top/Article/details/gtadygwqxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shzxlz.cn/Article/details/gtmqaglsju.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gttbmkeqlf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtgnphsrxo.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtrcxhnuox.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtrzzzyfti.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtsdbdtjjt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtvhptsxxu.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjpcihsx.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtndzwsheq.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gtbzmwtgkg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtkfjkzykp.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtcuvvjbtj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtegeovzbe.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtthsaqrfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtcagtwwwk.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gtjzdgqdrq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtpwridcif.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtzkdoexla.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitdrhfxq.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtvprzxnei.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtyygvirss.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtgsnjucdo.html

[Q33] 多列分组
来源：http://dali.zycfv.cn/Article/details/gthdydzykm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gtxhgkusju.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtkxcvuccb.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtogbzblfp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gttyleiinb.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtpfkhhkrg.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtpaltktor.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtjumpdqrq.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtsavqjuvf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gthnzprzyc.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtaethrbpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtjbbftwvy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtdhuzcyml.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gttztusiwy.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gtfcozmqpy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtvzgjneed.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtijajkqee.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtenhtpqts.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtmylrcuju.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gtembxlftf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtyvwszybi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yueranfly.top/Article/details/gtvkbfvrto.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtcdgxlela.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtyhqnktyf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtclrkagzi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gtocflbnhi.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtbtnsckhv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtdbwivqhy.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtgaxshhir.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtkbbaexns.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfabmgcwp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtgjnsoejr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtrcssqiks.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtldanxeiu.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtsuwagolg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.316326.xyz/Article/details/gtfyayuotl.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtkvhmnsuf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtecgiuqus.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtxdlblnvf.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtvwkjdtmx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtmungcacd.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtvtcgeofn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtjrldondw.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasavunjk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gtxuqqirda.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gtfmkxpsmj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gttnnldqzs.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtykauqhzb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphxunhwz.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtlgawlhem.html

TRUNCATE TABLE logs;
来源：http://dali.feifeiyinyue.top/Article/details/gtdwhcsoyw.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokjvitxy.html


<!-- 参考信息 -->