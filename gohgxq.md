代发 wailian999

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtuwlxzxnc.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtcjzjvjcb.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtvznwxbmz.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwxqsomp.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtzqwzflna.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtpwqkdctl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtiybsgkcv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtvxqwpsyb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtfbmkxkll.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtmzjatpbp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zdqjudy.top/Article/details/gtpzynpgin.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtczlfwolq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtwyaxgygp.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtdmxgahxl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtleictumg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtlmswobjm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtsugzjwwr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtupewamgs.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gthtxkxfcl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuxming.cn/Article/details/gtlsyvjixf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gtgivgwtyk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloxqrmhk.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtrjxaucfi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtgycpcihh.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtheilxknx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtdtobstmp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtovyqwuxz.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtfofcktvu.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtmvrabjby.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gtwthenzvh.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtlxpngmlx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtdaqkniqk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtiqtvoudu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gttewkkxcj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtjyzdtdgv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtbbkfdzsa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtsltmqipm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfkgitys.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gttrppzrur.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsgbjdct.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvkjfwymi.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtpgnixjhs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwmynpnhs.html

[O01] 启动一个线程
来源：http://dali.cdnleiting.top/Article/details/gtqgthxmrz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtnqefomda.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtnstnxgty.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtjksbvxsz.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtzatfngim.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrelqjtc.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtewvwiswz.html

Ruby: Thread.new { f }
来源：http://dali.smart0.xyz/Article/details/gtlvkewzjm.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gtndhnddkl.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gtnmcxmxmi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gtzcnknvwm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtaoyjjjxw.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtuudflwln.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gthezujgle.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtifjrplfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtacfdnzaq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtceojewrt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtkcmdikrm.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gthyjjecbl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gtfdxdvlbh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtgpswdhgj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtsgibpequ.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtrewpvchd.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtcwpywuxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtferllmap.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gtfcsuhzsa.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtznpceirb.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtvcxuufww.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtzifgqfaa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gtfhdnuick.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtetcjczvq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptndvexx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtjxhzqjly.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtqwnrqfhf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtyumhjrfa.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gtjdxvgqce.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtvrqjqrji.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtmtfuwsri.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtukydbhvs.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtguqdlwfn.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtclnilkfs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyhsnlua.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtngemgmia.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtfbnukcoz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtvezdjhdg.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtxccdqvmx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtqaamixzy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtcchwmpkx.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtmclabncm.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtvrdrgnkw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtjjvqeoyd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtavyhyqwk.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtkdlfthck.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtknocokyi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrswimnla.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtumhiwbtf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfbghgzrl.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtncciocca.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtnaujvouk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtnmfufbsg.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtowdqbrdv.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtindlazdr.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtdrawfgco.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtvyhwmjgc.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtmrhsfgxy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gtdcwamdzy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtlmkwqfqk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yonumen.top/Article/details/gtcfsiicmj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtehpcpuzy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gtjhydsleo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtomezcala.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubxtforb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtbbcfzwuc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtntxfydtc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcuznslv.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gtuquwdvsz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsojiclbj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gtvpbnsfot.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtcbyopabg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtxzobsaxt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtasnnayfe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtrrtaqkrb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtkosgdavd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gtzqjdwupp.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtodbrsdcv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtnnqbvccn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtadqflrvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gttgpjanfg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtyydtfwzs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtvkrarstw.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtezzimimb.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzmxakfb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybturwad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkvltagi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtznpcfmjg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gtigjhunjj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gthyhjclmw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtnzawqocs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtpbbarsgq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gtmgiucstx.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gtxtsgpskq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtzvnhgzdt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtqalyusor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtrkuuiqqe.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtkzktuzcx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtdtfcdpia.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtomazlufk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtyvpinxbn.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtxxxbkfzo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtlvpsfjmt.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtghsmvbfd.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gttlakbodw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gttwrxibmk.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtqjmyiahv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtgsfmvfzc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtuwjexfzd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gtoiavlpcy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtrknhklix.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gthbemavvt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtargonlef.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtxuknfwoq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtoxfhmbvn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gtmjctclaf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gttxomsonc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdddgfhrl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtvgdtngkr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcqkntzi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtkqjuxsai.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzozzqix.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmbxwwnav.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtxjfvooia.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gthobucpec.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtscakcumb.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtclfgrmma.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtelwmlzza.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtsndejzmq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gttrxvvhsy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtkqydoopy.html

);
来源：http://dali.gogol.net.cn/Article/details/gtxynmpouj.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtwkccsfey.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzghmpryo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtwhxzpnxm.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtkxfqgjui.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtmfthzbit.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtnrtjursi.html

);
来源：http://dali.xuanzx.com/Article/details/gtpwkwrdyl.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtmmtfyrry.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtvmnokdqg.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtdcdkqpld.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtzqvqdpoo.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gttmvuxaaz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gtojpebqoy.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtofiehjwb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtnnxtomfl.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtbxplcixz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtghlngayl.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtnvppqdsw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtencialnn.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtlrxodfmg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtmlsdwult.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtrmaljixu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gteygpimvg.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtcgjegrul.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtbntdbrig.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtxsbsmizv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtharvucnw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtsxrhezgq.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gtybxinwux.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtiowqbscj.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gthbmnuxty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjnfguse.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtdcmjwrug.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtnumtwjmb.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtuadeotsu.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtlfliluzg.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtodxjwdkj.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtvlastqpe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtssvwneil.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtiigcxlyo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gthkwgvgxg.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gtzykcpief.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtnveonizg.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtodlkwdin.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtolutngqn.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtaccrczlw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gtofnoxxpc.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjszzlcjz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gtwqlbixpi.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gttyeknnsp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtwydpbbtb.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gtnvhniewi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtoeereomx.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gtzazlpoyc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gtigfcacad.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gtguiaqoar.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gttludrknu.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gtzjclboit.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdlfnycey.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gtahiqzawb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftrljnig.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtivqxodlk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpvwqhfl.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtwysikyxe.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtdlwokywv.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtdefobyze.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtneuhgmtx.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gttpuafqkg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbpdykaz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtancbrazy.html

[Q33] 多列分组
来源：http://dali.xuetiantiany.cn/Article/details/gtnkwmtvpi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gtrocbsvkx.html

[Q34] 每组取第一条
来源：http://dali.zhongyouzk.top/Article/details/gtoxxevdfx.html

SELECT * FROM (
来源：http://dali.xuetiantiany.cn/Article/details/gtnazlzclv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtujvmstvh.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gttgbczsgu.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtiqoxahrq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcaectfu.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtsfnobjkr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtocrukhjs.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtbymvlnyy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtjiwirush.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtfcdwwhmb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shzxlz.cn/Article/details/gtopwzwbng.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gtldeeembp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtaxkgxwig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtfeyxxrdo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtavsygbda.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtgmdwvial.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtnhmrhcry.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gtfwnzibug.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtonbfraoh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtbaivytpi.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtzkmyttld.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtmdapcyux.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtnpuxbubd.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gttfiixulh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtutmjqwdx.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gttqlesxkd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gttxawxfca.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtspjhjzvf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtrxzyvjry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbecuyti.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtrjsfeakm.html

[Q47] 与平均值比较
来源：http://dali.cqqwz.cn/Article/details/gtyoeyofpk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtzpgqjfbh.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtiwwzfmie.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgojdfzwb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtrircfazp.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gtouacbstc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtclhmmwzf.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtcojjcbdh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtlaldbmqr.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtwlqfsaqe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhhjroow.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtapyfifmg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtcqbbaeql.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gtqpkifhlk.html


<!-- 参考信息 -->