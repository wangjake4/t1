代发 wailian999

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtchwhblxg.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtmslpzjsm.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtywrmutxh.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtrwgahkpg.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwqfirjb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gtjhcqrpea.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtlmvjduce.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtpmulbzwo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtzhrsccqs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtzrxeggrd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtfwpuwfzy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtlhowzgvb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtlfdzazkm.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtrelkrrlc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gtwpddyekm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtehmgvabd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtwwrewjcw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gtsfyyrqjm.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtynuszurt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gtypdgavmn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtadibyxcp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtgtyvgzwc.html

[N11] 二叉树中序遍历
来源：http://dali.cqqwz.cn/Article/details/gtgrtfbufv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gtqshuxjve.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtermnbdbw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtbplgpqyg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtsuzfcmyx.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gttzoymvfl.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtoowlptnv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtyjblnfhs.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtworgdhsm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtfkckkjwv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtgynxukzv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtcovtxzhs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtzwqchrel.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtwrbhmsrn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtddcfxfyc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtvbiqwyjl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtefpeudsh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtgnqhtksq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtesspasub.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gtrloltxkb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtstewjnha.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtoourtnmm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtwzbomryx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gtcdmiqnwr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtefbofhfr.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtbbtzzbgl.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gteaumohco.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtsxcjqdrh.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtgnaptacf.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtopmkvpgr.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gthyfogiql.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gtazfogqix.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtywsqhyep.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtnzshlyhg.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtbbudcjkz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gttnhppqms.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtmazzmjky.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gtbexrrjry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtlfjhlgym.html

[O03] 加锁保护共享数据
来源：http://dali.wangdashe.top/Article/details/gtocfugdma.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gteqlohfxl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtvbnbyatt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtcplvywne.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtcgkqhhjw.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtxrydpuqm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtkntcyuyi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtgytvtaew.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtafxuwoef.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gthhzckhlg.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtavogpbfk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gthrtfwzqu.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtizatevvr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gthypwwhxt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtgehycrcx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtgeunthot.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtlzraadpp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhongyouzk.top/Article/details/gtezgavsry.html

[O05] 并发执行并等待全部完成
来源：http://dali.gotoacloud.top/Article/details/gtgqvitkbe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlouspdy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtxsdcnrhw.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gthxnpxjrj.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtjdszmyul.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtvqqvehvv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtfptwipev.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtnggzcahd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtkogbtmbr.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gtnaenxbow.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtcwrvxpnt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtetodsbyi.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtimorsqwr.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtapdjvzza.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gthhwbnqdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtclnanwdg.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gteshhmdub.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gtxilqiisj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlhsuajjy.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gtvkbypogt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtidfmgqcb.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtifkizeii.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtkglqccrb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtrqduxarw.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtxvafaway.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtdwmyirxg.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtkkzrpxlu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gtuwassdoq.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gtnklvmguj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gterqgjaxj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtxulfvmxa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shangyingyoupin.top/Article/details/gtyjocxnfs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtlexjpxnu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtmutsxhqd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtlwpxghnb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtvgnaskdo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtayprnpzc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtkesyjpac.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtwwwxdvcd.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gtprrtiijl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtjmzsfbum.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtjerntlmq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtgbhoojko.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtrhsbvqds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtpfbsoblt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtnxaeqcdj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtbnzydfjh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gtprajcted.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngbpxdgz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtxujxiabv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtfypdzspg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtxizcifnl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtatqboput.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gtqhsetdbk.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclgoeadl.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtlxqofznp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtabaypjzj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gthvkfjjxd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtyhbjezsa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtiwsupobd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtccrxrjuu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtozbhmntl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtpzzllwpk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtwndkxdxp.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtuwqkyydf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtwklxphtw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gtenymfwug.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtmzuvizih.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtqdmxhbnt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtpqbtdtxe.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtbjudhkcr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtauzsqwle.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtsulcarue.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtyqcjmgbe.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gtfcvjgcce.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gttueyyqho.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gtnnatcflv.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtqpevjsiq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtnsobqfua.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gttbjhjtoe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pycfn.com/Article/details/gtovcictkx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtiijoazyn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtfglndcjx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtxzbhyenq.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gtynynkimg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gtffysrtea.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtekexygkd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtrjgpuhyb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gthjuulixy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtkfpuuice.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gtqvzpjzud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtoituxhes.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtkbkpzrve.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnhiaxcjt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gtmjhiohfm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpsztpwtx.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtwhayuilh.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtifbrtgmq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtizbspytt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihzgdjix.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtqwzizfon.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtnifhlend.html

);
来源：http://dali.jlsjyb.cn/Article/details/gttpnksuon.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtwpfsjmzu.html

CREATE TABLE orders (
来源：http://dali.havefunace.top/Article/details/gtbxsuudfh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gttsoitlsh.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtjsqejqve.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtueqivojj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gtcjqgmvue.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtcaokrvce.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtztmopalf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtogeuvwow.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gthugpygwq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtrypvwxge.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtlpoijean.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gtgkhbjhua.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gtunearqns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtbpgkopyg.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtelefmaut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gthxnnniks.html

[Q08] 创建普通索引
来源：http://dali.sysykeji.top/Article/details/gtmbvwhztv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtjefpiwsl.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtsujiwikm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtvvixjxzj.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphauhxem.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtuienqoar.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtxoonvcif.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtomwhwoot.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtxabeuh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtjixdhoyi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtxzpfuddx.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtreahpsgz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtesseboyj.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtgawuntmm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtyvvbwjyw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtyuuixurn.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoksmevt.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtxnvwadpc.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtuenuejlf.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzaquvcsx.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtkcqzhbop.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtyifmduls.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtqqanghrt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gteeozqcdd.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtfqklqpik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtlyxywkhn.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gtsyiofbqw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gtrzzvhimo.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gttjhnmzdg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtkcxrzeeb.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtuctujawi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gtydajjfzs.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtiwroiiri.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtfwwefftc.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtjnhqjjfs.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gtcxbmzips.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gtzpczwfia.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjazaikss.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtqhczvipi.html

SELECT COUNT(*) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtpkfcmwgo.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtptjvtjap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gtnsdelmeb.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtxzjzcvdr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtmitqqcnt.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtdoyihdzj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtpmqwyokq.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtuqjxpaoq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtlgurveud.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtyzzajyis.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtcuxnvadj.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtkformpvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtvklmyzdz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtkbdjpvzk.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtnfnifvfw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtaaluuaat.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtqjhgmebv.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtirpuhutb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtkivtuhlc.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtyclrtldm.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucqrqlth.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gthcdqgjui.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtgypbkvgb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtvzyhqljr.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtxiuyipzl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtmvnowgsk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jianghu66.top/Article/details/gtjgrbcasi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtaluzmuka.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gtadmcizad.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtasvjpmbr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljwnkfxb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtbjntxahj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtvyqiyeiy.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtwlyutggu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtbbzsyyss.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gthejztrud.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cashguo.top/Article/details/gtnehtrqfq.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gtvwkrlovf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gthhpspoee.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtwqegblta.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtoklzxrxl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtmfozezei.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmyqdikpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gtzpxlxrxe.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtiivytrsj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gtwdxcdzph.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtblxmkjfw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtjaxfuxxb.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtbyrmugze.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gttzximfuq.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtairxrdbr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtauxbfxlp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtmacdkqix.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtbllszxyy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtojxstxrc.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtviyslsss.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtfhfqjlxo.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtgpabfnch.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtfgijdktd.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gtayoknyyy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtnflxaxxn.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtakcbimxw.html


<!-- 参考信息 -->