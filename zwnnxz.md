代发 wailian999

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtktjcsgyp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gtjwybmqzz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtzfkuiavh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtmnkjwwbj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gtujwbhymh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtdjgsocqb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtdyktkjgu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtqiysuaod.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtychzhqlq.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtvuwetkbd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtcngvipgx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtimbntadh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtgvhriztv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gthwbzlyom.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gtgjnfeilf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtsyectrpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gteyyvwggi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gtxbwhldkf.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtielevzer.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtomghfceu.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtsqyncffq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gthxuqjgbr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gtgcywhpxt.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtguzzqysz.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtjacrdwes.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtxzhvcqau.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtolcbjoml.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtejzctwla.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlhomhza.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtdxmncobh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtwxowrquh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtzvfmkipt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtpkupvroh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtqedmdfhr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtueeinbhz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtprmayhwd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwbkjejcj.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gteqovnzfl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtazmvvehs.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gticiynswc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtwisiqmyg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gtfwmnjswd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aibaodan.cn/Article/details/gtlzetkjsm.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gttvmdvqij.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtlkrxpljo.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtbuhwqqba.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtbjuekiag.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtqleszyoh.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtbhjlycog.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtvmaclrmg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gtjekcfcst.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtqwyvxtuh.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtpahknmcx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gttlovbasx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtktipcikn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtdwjhpbyf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtihgrsyuv.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtikctdvge.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapvfiotc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gtthlmflge.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtmiambdoo.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtqdujmmni.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjtreiyd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtujrrpvga.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gtedgvfncc.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtrntlfrmq.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtwgprzoub.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gteelqdhfa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtfhzgzebh.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqctlkmc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtomephimf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gtqpvzviqh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtsndsedwe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gtplxwjfcp.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtohpgdbnj.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtrpbirduu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtbsytiqdj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtibiowjar.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtzlykyumy.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtmkhqrrvd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gthiywblvp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtgkyjypkz.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtuqyjhyhc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtohyjdrtw.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtdudhtyxj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtditoxksc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtsjwvoe.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtgdqlkgtj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtbvkercpa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtbstexnci.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtkjnbrczv.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtialeyfzv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtvmssfiaf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxqccxoxk.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gtvkgajuxe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtljhdfkop.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtbjyxkkmk.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbrtvunk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtygoxlzrk.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtvmozuyqq.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtgovttsci.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtioqqdvaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtgutxnkrn.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtblgtundg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtghpartrf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gtxjesflwv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gteetorcyz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gterxyjuzi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtvnfiutsk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gtmmxuweob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gtkivpopnd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtftbptqcv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gtrixugcfw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtelundihn.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtdbjcjubr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtrkonzfmg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ydzc1.top/Article/details/gtlqttjynp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgpajlzi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtudzcjvfs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtznrbxurv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtnedcggti.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyfavwyr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtggfxueaq.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtpmgrvdlf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtujbgyzlw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtdslxszve.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtgitpyhcf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtavvzcoyp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtcocqxsal.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gtwjwzxiai.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gttayfjxiz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtecoioqtv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtmfpbyvql.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtgagcwayh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtskfjacpx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtqngophhy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtwrlbldqy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtzwcuipqr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtkivqellu.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtwaoonhly.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gthhhiibqi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtmpnhozzw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtltnavshk.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gttjrxylnq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtohirnfka.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtodalpdhj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gttawacncs.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtmrbvczid.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfycrimgu.html

C#:   if (x is null) {}
来源：http://dali.yueranfly.top/Article/details/gtpmzrhfui.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmijcuecl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtjtavnlro.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtvmtnwzqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtevlonymj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtwfuxoksy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtvpwruyga.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtzogeaycb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtiueiuolv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtxrcnnyzb.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtzgvyxsir.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daxiang520.top/Article/details/gtaqoaepam.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtzmjychej.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zdqjudy.top/Article/details/gtlhghwpdj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtaqskmunm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gttwbygfxt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtcusqlqio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtrfxjjixg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtxzbgtpjs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcpswuqmy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtixvqoxpu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuissinfo.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtvyurnuxe.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtnmhyxtld.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtgitfozmz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtvvhmsocf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dianchejie.cn/Article/details/gtcuhnmogy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gthpwntaks.html

);
来源：http://dali.gotoacloud.top/Article/details/gtgwoppyww.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtebgielvk.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtmxkwozhm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtndbvokac.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtoicmpqcn.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtzemyyzjv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtipgdjbpx.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtswhgfbmb.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqmbrkgr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtgsqrznsn.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtdsccogld.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtemvaxmot.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtsdvpgvub.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtkvewnjcj.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtyuhmhbnc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtveacutgx.html

[Q07] 删除表
来源：http://dali.dashuyun.cn/Article/details/gtnfdcncod.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtqabiuwrp.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gtzxripnfh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtazsmwmlp.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gtvtpwwlci.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtvwfkngmx.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtrsqisqey.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtgnysgaey.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtumawoqwz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtgzrgdzro.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtiuvayylu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gtxhalpcar.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gtzyjyyqav.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtwgdueihb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtxphtxwov.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtxeypzpgn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gtxwajxkid.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtmtesssvs.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwrlphwk.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtnsgmwgla.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gthyluvrpw.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnxgpqswk.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtncytyujf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnxiangtu.top/Article/details/gttjuviagc.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gtpbnibzby.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtpupgzxre.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmezxabkp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gtvsdmdpid.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtxleybvle.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtecnzkmxf.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtevizsxyl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gtilkdbicm.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtnzecqqjm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtvqngkcom.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gtfaoxwxkl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gtrxjfviiu.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gtkstonkzz.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gthkabbiqw.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtogyhoruq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtbemhfxzh.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gturtgyfeb.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqtvfomh.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gtcjefbzra.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gtuvhjrpzw.html

[Q28] 求和与平均
来源：http://dali.sxryk.cn/Article/details/gtyrffwkcv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtxozudpri.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtkkpculip.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtvvhhqzje.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtkeexxjgb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqkesugo.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtsebmdkbl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtflhbnxcs.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtqfxlwtmd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtzoqbaeth.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtahocleit.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtqlskzshs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtlpbdxpij.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtovmohjoc.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gtivwawjtx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtkmyujqjw.html

) t WHERE rn = 1;
来源：http://dali.chenzaomai.com/Article/details/gtxdwbewzt.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtxyqpcfqo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtvqarqrku.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtezqhkwez.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtgyvixvsc.html

[Q37] 右连接
来源：http://dali.xuanzx.com/Article/details/gtrkqiquxg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtxwjmdgmg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtueszofxg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtkapxvyfo.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gteoiftzxk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbumjayng.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtuwbvjjte.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtgcrvijtx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtjdvqzmuh.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gtjuwzxlbr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtzmfrbrsc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtjkkfgbje.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtfetgwxzx.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtxaodqdyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtzydyolxx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtxpluidxe.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gtgijsnmfn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtbfzprsqy.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtcoqsagjw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.0kj1m.cn/Article/details/gtlvlzvxbh.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gttgdmciuz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtwgqozhrb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtegeocyoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtucymnlcd.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtyrsfwutz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtpqmqpnbf.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gtjtzzkgwm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj202588.top/Article/details/gthigjkkha.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.kuanghao11.cn/Article/details/gtuxxcpxvp.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtxaqowrlh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtpdmrvxxk.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtktjqiqiz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtovwgwaqi.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtvpmavglh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtwkjvmosr.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gthkxhdumv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtpohgtmso.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gtggpqyrpq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtfydargzf.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtvumtcoqe.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtefasfiub.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtyujhcrll.html


<!-- 参考信息 -->