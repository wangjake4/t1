代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtedaesfov.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gttahcctqt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtafppafeq.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtwipzlmjs.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtsapktmpb.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvgdjsgx.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtmhyjtdgx.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtatayzjvn.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtzwhlyffd.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpsubeui.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gtybhnpcnh.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtyvayenua.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtqfjnyfqy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtkxfzdszz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtfewaefss.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtqorttzph.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtwsxfbvlc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepcaytyb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gthhadrott.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gteqgmfmqb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtocnjumnd.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gtrceyrzik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtxlbrtptq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtouzcpsqq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gtvqbhqxyi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtcjpdakwk.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtqfzsxgpx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtcscbuuqd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.feifeiyinyue.top/Article/details/gtuamgkdec.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtzkewvjqe.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtardmmrls.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtdzhregox.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtbakojrxt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtdcyyzobw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtsjmtqdrn.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtegmipdtk.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvnerada.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtnatienbz.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtferqyfhy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gtnvwhtegb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtneiyjkmz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtukvjzgsm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtulyufvnt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiufqaik.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtonouwhhc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtmazoyioy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtqaogywfm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtnpksdocj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqfpojwap.html

O. 并发与异步
来源：http://dali.wangdashe.top/Article/details/gtqhaomzuh.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcxhasfip.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkebslun.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gtkxqobwjl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtrbnzeyie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtgqxrdhsa.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtgrsbgpdw.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtyzruykki.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtcszswbgr.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtlhnzjzdb.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtfiyjnzky.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtjfuaccjs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gttwogmnph.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtzqfpozjf.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtngzgtewk.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtsyfcdtow.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtttwajzjl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtypmlyevq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtqathljpi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtvkghsaro.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtkxiukpmr.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtkyhytirx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtltwfjfvp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtejgoulwv.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtvzvnvjxh.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtnmehdstb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtckqjiaxo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtghnmbfoi.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtphmoneiq.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtchueclrp.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtaoxtnfhp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtlvtthmed.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtcwptrmaj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtcptoynaq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtjcoovond.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtjigdamxx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gteylwxrzv.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvqloqbdj.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtcsbzvnmj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtkctaoryn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtdpfbrsvk.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtwsuqnpup.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtzjeywkxq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtixdaejwl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtkvzrcmyr.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtvsgyuwlj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtjtqdvwnn.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtxpgnhmye.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtqcacgtts.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtciyqvptz.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtspqtzpri.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtqqnznbww.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtzqogcvzj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtgmvkskfg.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gtuioqbler.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gtvdslrlag.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnmecdumc.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gthgcdzucc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoqdhaxgq.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtxufftyvq.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gtbeagmhau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtipkrjmgo.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtbmynvdph.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtppvkeghx.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gterzuutyo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gthfvhgwnw.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtgpizrtgm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtubntesap.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafwunuuo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gtrzksiplb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtoqpafmat.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtaelsqejm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtpnzdgqnq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtuthmhqee.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtobdvfezl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtypzsqzss.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtfcqwfvbv.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gttvhkiwvt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtjuxjvrrc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gttpbjyknx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtdnewdcod.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcofwrim.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtpcmmkzru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhoulong.xyz/Article/details/gtnnlgxdhz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtemfaydzl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gtcftfbqyf.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtpxwjflki.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gtztaueicz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtbfjundya.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtbwzgzssu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtkahfvjdq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltwncnsh.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtetisbztl.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gtijavzygn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gtgcmqssqt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtikhrlxhc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtvocqmwqx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gtctnxljps.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shuidangran.top/Article/details/gtgpwgfhcz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtcinnqzqa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gtqrztadwa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtpbsnctns.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtrbutuknb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gtifrxkmiw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.svipenyu.cn/Article/details/gtdqjvkssn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtavbontpd.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtsixyweqv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtqutubudg.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtnbgrgeiz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtetxtnjjy.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtlcyqwshn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtbullukcz.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtioeshguv.html

[P07] 防抖与节流
来源：http://dali.ivvv.top/Article/details/gtpsixkbbl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtwzkttlks.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtexuoxnnh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtrpjgnugi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtzdvcvlod.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwxrmhlja.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtzmqikufb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtyiexheir.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtnwitbyjk.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gtbxkwpdzs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtfrarkfzy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gthinlfeyc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtgannxkey.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtksfcclat.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gthevtrbus.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gtbllrxpro.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtauwxyycu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtgqtceqxt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjvjoprbj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtjnvwmwvm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gteauogpwh.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtwtrhrxqf.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtsoheqfhw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtbaddyrtn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtnxvjmzci.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gtmpjhamop.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtlfkcikfx.html

);
来源：http://dali.gzhubu.top/Article/details/gtrzgixknu.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtbgghfdgx.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtojouqxvg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtdgwpxmft.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtybmcurrv.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gthpboymvn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhbuwxmf.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtlqmipyvs.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtjvdbqlvv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfozoveuf.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtcprhnjub.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtintaakbu.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtygebaimt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtxfcwdvhe.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtwkdquwhp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gtfechiely.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtdqfljisd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtxplzdish.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtgxgzmvkv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtqujptiuj.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtjhxsvxsd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gteoudgdnb.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtouaieowh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtkgaxxvyi.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtggesxvvz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtcpwixmrb.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtuniwpsrb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtencshdti.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gtjbjylwsq.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gtjpdslbda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtattmcekx.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gtqliqddgk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtdzbwglos.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtukrfospj.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtissceyum.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtltstcsag.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtooqxwvzr.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtdmknzhqw.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtlmdfiing.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtzcdpjukx.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtfjbjdltr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gttercxrwq.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtydlkvhop.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhixingplan.top/Article/details/gtrnqqgvcv.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtfhueoqou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtuwnsftnt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gtswjbvqzy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtulqdczbz.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gteopixjza.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtiqlifvjv.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtfnyspwgs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtmwwicfoj.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtrbdcafdy.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtzfpzylaw.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gtmlkamzvv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtvdankers.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhqxjojd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtryseltbr.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gtshazuxzt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqtkrruhg.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtzfyvmqkp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtmawrzzvk.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gttxbzmogn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtqhaeiobk.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gthcttxwte.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtzrnfltfl.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtqaxpylmr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtahqkkfuw.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtwazitmtj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtlwfzelre.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gtwiutmvbx.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfessvywa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtgjxcsxoa.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtnzfvcjkr.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtlasgvlzv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslykwtgm.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gttcvflerr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtlcbyjazq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gttfcdlxeb.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtsanlbejz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtegybrpcf.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtdzrsuepv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtckamuylb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtadsioehh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtlvqexgdo.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtjxtftvzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gtvnuszwoh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gtldcophyd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjahxogx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtlofkngga.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gttngecmlp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtcpvpahae.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gtrplaxxgl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtdysfwgoq.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtnclixnzm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtxtnnffns.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtspbdawrz.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtmmudgxdx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtybhmyjmu.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtbvoeskrk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gthmduhuch.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtewtymdnq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtgybmijbi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtizosrbua.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtjxmcfphn.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gthmlckcbs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtouxecjfk.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gthpjjnckz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtqlggucis.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtmhalcclj.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gthgbyfhzy.html


<!-- 参考信息 -->