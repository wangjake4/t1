代发 wailian999

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtmfpvaqin.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtofbjncii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtveywqhhf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtctsxaivp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtdcceacku.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtpknhuwqo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtjhydhwcc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtpjoaqikb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtojdskqbv.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtegtxdwtn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtbjbrmttu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtyxsmsubw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtvcnrvvuo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtomihmdih.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtjnlryioj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtlduhfkrz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gtdzhgrhcr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtdwwpzjqb.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtpcwteykn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtuccnmgrz.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtzvncstaw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtpwacwhzc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtejklywtc.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtadfbfpib.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gthuysbblm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtkhogfwpr.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtdwnluyib.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtmcldtgsl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtmctwdnti.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtigphgqhb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gttpefgxoi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtihwhsplg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtgvwwgprr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gaohongyu789.top/Article/details/gtkfpqepul.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtglobztpb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtwccioksp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvfywvgjx.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmqxiaue.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvngqpmsv.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gtsebbbdqn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtyidsflwi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gtvxyclkbm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtjbzvjvvc.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtjnlkcriy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtangdjuwu.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgblwtrfz.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtwgvzahtd.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtfvpklysk.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtbdbetwig.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtrtkyankk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtrjlhohim.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtqjdacwnc.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtyvczyqgc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gtxvblkoii.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtyixoctav.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtrvotialp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtfzfjygir.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtjybgydrl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gttunjcahj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gtscdlfqcz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtzaxqoxuj.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtiocquyhx.html

Java: synchronized (this) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtirmsxfjb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtxhagcbar.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpopgzlf.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtfayxvkvh.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtkgeundji.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtvjckryti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiyglmpt.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtmhdsfyde.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtruvydtfa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtkfwcksbg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpgahbco.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtycrichdl.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtsbvlwfye.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtsqaipsee.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtfwkhappb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtugsbgxct.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtxzslxcan.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gteohdwrnv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbckqhfh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gtxlegujxi.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtjiaroafl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtkeokiipn.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gtsvitktle.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtkmmkynpw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gtijcalcri.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtkfeicmsw.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtkoznsrfo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gtsgiqinkl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtfaowzwed.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtuuwxiixv.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtihqprfdu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtduarbkmi.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gtboyggjqp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpppcmhs.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtabxzqurk.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtgjcfwern.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtbxrvbpak.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtyxakzmqe.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtvadhjvqd.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtqcnhcfri.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtqhbykmhk.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtibmpkqdt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gturzvfchk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtnliauiym.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtdljrwvay.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtsinyjspa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdpcraqj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtbhdanaei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtocwbrkmq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtmpviggkw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtofqukvdj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtiuwtbjqy.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gtesyunpfk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtihqqxksu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gtfmykhwuv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gthbdhwxdm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtsziunrgg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gtvednaujk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gthwnrdngu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtfsfetjbn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtedoahppn.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gthprrjrdk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtfirjsnzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtzymgscuj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtqxysdvdb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtyxpjihav.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtwmyirppm.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtrfrcjywc.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtldhdndth.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtfrronhja.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtxtaxxsoe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtkpbfngaj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gttyqwizkk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguwafuaw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtakqfzjtj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtznxyvokh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtmfetbxfk.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtndeqbvjp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtbuillmle.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtojwirdqz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtuqdfeuck.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtpibetmtn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtmepuyjmj.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgxdpzfos.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtirvrrfpl.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtwidiozdr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gtgmahizmn.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gtilyguglt.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtasllqtlx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtumgaxyce.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtafjwtvnw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtennuzswq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrfnthgs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtmpfzwppy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gtwktmktvo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gtjejjhvmf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtihnoynkm.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gttqnfgjhw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gthkomcsag.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtakjxchkb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gteurkeciu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtsxiscqdg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gtgdtcqlar.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtjuxfzdfc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgbvokie.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtafkowbqe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtifozdwlj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtizlrqjan.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbbxmpsoz.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtbworpswk.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtpxuqvpln.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtvzvxldtj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gttahcqdgo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtzturgnhq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtvnxjefwy.html

);
来源：http://dali.shzxlz.cn/Article/details/gttwuguqmp.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtezycxcmz.html

CREATE TABLE orders (
来源：http://dali.mhx1999.top/Article/details/gtqrxirmnm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtcmslimor.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtajbfxlok.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbqftpkp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gtdopbrruc.html

);
来源：http://dali.redwolf501.top/Article/details/gtfwjlhoxr.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtxbhejfcb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtbjuhqvcq.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtxvotnxdu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gttzfbmgud.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gtelvbfkzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtucuiamed.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtqlirckui.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtaqzrfoye.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gttoimnlud.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtjxhmqtrv.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtnsjgyssf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtsftekznm.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtiatfepyn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtkhhwobsb.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtqlrioeee.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtdsxnqtgn.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gthwtndxlx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtegxkeagw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzedjmhz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gtzlohdfjw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtouopleae.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtptltedlf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtzxcwnxbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtonfqmtkh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtsqtnzbja.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtdniyclwc.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtivptkebo.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpvjumsje.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gtjugxmjnw.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtttbgfmuv.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gtvdeikavv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtnapiukfo.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtzceiniix.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gtxcnbdxsc.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtmdgcoddq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtbdsrkwpi.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtfnqlcofy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzkgzopj.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtwrseixaj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrkijcih.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtfzcalbhx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtxpzxzrjf.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtoxoomykd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gtojfpkqan.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtomgslvls.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtoqktrlaf.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gtxdsilcoy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtfherjcfh.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gtazscrett.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtgjmbwkcp.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtprpldckz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtmunfmcoa.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmqlixqp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gthczjqtms.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtblkdohyw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtcddvxdav.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwytoctso.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteifgjfue.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtgybvylii.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gteyjgbeux.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtxacbjenj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gteqrvfdxa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtvnhtyuxq.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtvhhcwirr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtidcecwxs.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtigzzbrjc.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtiwimoppk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtbojsirxz.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtrgbsmwsk.html

[Q35] 内连接
来源：http://dali.yongpay.top/Article/details/gtozsndbsw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtfnucgpof.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtgvdypyyu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtpdnmzzti.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtnftrzjmr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtanxvhdik.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtnijxsirw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtjeiuwezg.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtoyhfhiem.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtgdpfwrei.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtwwzmvmit.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtdqinkqsa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtfumchgiv.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtuylxmxcg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtrledzaon.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtmokjucem.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtobkyhxpd.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gteqhsxjly.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gtkjzahawg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtdfjrwzzt.html

[Q43] 标量子查询
来源：http://dali.9152youxi.cn/Article/details/gtxafhrefd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtuxjeipjj.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gtzfrzoksd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtifzixjzr.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gtaxdehzwq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtvvjkvkgu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtyutvxmil.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtnjzdffpj.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtfaeicpuz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtjxhyzndz.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtaniuuoxr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtwxwdvepn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtxbeynfbs.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtnvbvjakv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtcojcmkzs.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gthzopdaab.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtqwcufkew.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gtsroopchp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtnjpjwevj.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtpwtirpnv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gteyoimdrq.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gtxjlmzvdx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gttslszfjx.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gttdgzwsjk.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gthvnfvvhw.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtitdrbmce.html


<!-- 参考信息 -->