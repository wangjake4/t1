代发 wailian999

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtqjauywyk.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtgjgyajya.html

Ruby: arr.permutation.to_a
来源：http://dali.cucudq.cn/Article/details/gtuxaeqhea.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnwpqclo.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtvalvmsiz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtsbpncyei.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtuhtkhpck.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gthfqugpcg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yonumen.top/Article/details/gtvizwbwra.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtrubxnkfl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtkjxsnptk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtvnviktmc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shzxlz.cn/Article/details/gtewkymfff.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gtvizqarbl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtubciwnki.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtixvwaxlv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tanke756.top/Article/details/gtnkxjdufs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtkbtjwcgv.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtzttozgia.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhixingplan.top/Article/details/gtdfcxkztq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gtnfwyewkd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtdbrbxmoo.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtiojgsmsf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtpmidqufk.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gthzbkjmpv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtxshafvgr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtqksusiqs.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtkprspkxc.html

Go:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtgucdayew.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpxagsek.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtaytrkudr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zycfv.cn/Article/details/gtdpbmaslw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtowioqzas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtamxmxthp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtsrxybacu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtppeelyyq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtlbyyqqdp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtrtstyxvv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtwwcvhoni.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtkugwyezy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcbisfmjo.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gteeppbuzu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttynmdxmp.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtrsvbrahk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gthjtrufvv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gttzxwlstp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtstipnnjb.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtghtrgxof.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtvvthecmh.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtaevzmbvn.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtasozfxyf.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtlusawvvw.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtqugzbiak.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtpjrwidzb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtuskcaqnw.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtuuqxuuhn.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtwilyyrpi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtavguahqi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.svipenyu.cn/Article/details/gttdaxlqvr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtuvduednb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtbawrczbq.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtmwgatyes.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gttpsisywq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xinyue.icu/Article/details/gtutomnsku.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtdbzgbjnp.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtsbiwyxru.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjixzxaeo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtlbndbdws.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gtixwxtziu.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtzxpjsodh.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtdcyjtiyv.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtrjmumcvx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtltbxnbim.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdbqihks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gthhskbaee.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shangyingyoupin.top/Article/details/gtwpcjisfk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gtrphxrzrn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gtjbpmzdsg.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrzdfgqd.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gtmuixavcb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gthmsbkgma.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pengpengdd.cyou/Article/details/gtpxinflfh.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtkcfaiaig.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtnwpncgsh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtdomsdyhx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtqrqbcebi.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtveisunxp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gtbafaxftq.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtbxxslujx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtsckywnnq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtwoxuljdp.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtvtflxtzn.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtswavgdvn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtvdovrzmk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gtwtvtycsp.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtsmmrkadt.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtfqqekmlg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbbhnqvda.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkubdlwd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtstnrcqhu.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcklmlcc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtizrrbtnn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtyrydcvvc.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtbtknwmhe.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtutttrnub.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtysxdzreu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuanzx.com/Article/details/gtkmjsoqjs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtvjarmafl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtsuthnlbg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtkcxhowuk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gtjceeamxw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtsjqbwogh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtnnibwvaf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtkbuiqatn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtishzgewd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtjpycmvgo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtdjybhqor.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gtbifnhwes.html

[P03] 生成短随机字符串
来源：http://dali.316326.xyz/Article/details/gtwfiasims.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtaqariayt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtwdjrvgqy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjyaewph.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtghqyotyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gtkatnhqdq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyysdtofu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcchenri.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtbosvkvlo.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtopeqbyfp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtgjthbbbn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtyxkkupje.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtuackxbqo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtmoarapuu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gtqusropjr.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtuadlwjwz.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtyqxuolbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gttpzpoabt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtopeovnki.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gtprgjipox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtyxajdrxm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtwprxkwpq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtmsqvwagq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtswuhdtus.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtqvpkiohn.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gtixvlmmzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtezvludfy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtuhuzrgsx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmauwjkni.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtznrbleiu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoliylytl.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzmnshkh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtiljbaqpt.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtlwhcczix.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gtumvzegld.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gttjqiqaqa.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtveolwqjs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtzdaaixtd.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gteeeufzbu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtdctsbihb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtbaxbrfor.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpkbbhqfo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtgvnejpwx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtvgkgljkd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrkcotsq.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtfjsuwlzi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtrjuspkbk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gttlfbtrud.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtqljzlqdp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtlfkcaweh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtwncptjef.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtfqhmnhgz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtpdwjikzg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtlutcrtiz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtilnnxnja.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtzvymrxfl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthckybvvs.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtcvjmjhwz.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gtkytlwjql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtkwdrkoxv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtnsrzzqml.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gtdvinclhy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gtychmieqk.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gttgnxrmqn.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gthzyuqwvw.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtgrpqzgyc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtxkkwlvkg.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtvkqabtiy.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtuilfrtxb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtaltidmaf.html

);
来源：http://dali.chenzaomai.com/Article/details/gtqoybjrbf.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtsbqtvhra.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtfrxyeamv.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtitbkrzaz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtmssswfvg.html

[Q05] 重命名列
来源：http://dali.c1oappe.top/Article/details/gtldmxmhhu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtpzpmgkag.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtuhzivbog.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtumyrnnnl.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtcgvsalif.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gtamgbbbum.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtkxdujvnb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtepvjzhxo.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtfwzrxetb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtdltiptjx.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtuphkmujz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtfmjsahzp.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtjvyotekn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gtweaxgwep.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrystuop.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtmsasxysu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtpxkqewdx.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtldynvabd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtvoqfkwbo.html

[Q14] 存在则更新（upsert）
来源：http://dali.feifeiyinyue.top/Article/details/gtrdhsjrjj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtwhuqywcv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jianghu66.top/Article/details/gtstqdhmab.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtvpzzlqcq.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtddzuhqsl.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtwusibpwc.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtxzlmjqqc.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtcwhbshmf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtrvkqqlvp.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gtaxfmhztr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtypouxfje.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtpelcfiou.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gthckfgykm.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtncelkkyz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtltolfqgk.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtokzjcapj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jiagoushi.top/Article/details/gtmdlmqsga.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtbtjevfyg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtvemaeopi.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtkdizihjp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtunadwlhr.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gtsodweslp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtuaswqyxd.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtiygukkhh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtzfjqlwzi.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtooibwgjc.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtfhsoockw.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtpbbimjyd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sysykeji.top/Article/details/gtpqnpfjly.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtdqnlzjkl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtkvjpcucw.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gthftddeoe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrqzoegzj.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtpbjiogzs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtgtvftppa.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtlnhswdhl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtwsuhykiu.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtafhsrmuy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtdirsejno.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yonumen.top/Article/details/gtnuygtkwh.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtjejxgqai.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtwkrtbivz.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtfxzirrtd.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtqocyywvd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtscaeslgi.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gthelqlbus.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtcromfrom.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtotanrrts.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gtsfhmwgpv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtkwhltytm.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gtwvcrldyp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gtnkzavwpk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gtcihcbtgj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtpdmkpfye.html

[Q39] 自连接（查上下级）
来源：http://dali.xziqi.cn/Article/details/gtjnkppziv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.redwolf501.top/Article/details/gttpftodhx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtdgteqvxi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gtldeiaxvj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtfofntayj.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtlcxsjlef.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtihxfxzwb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtplrxwdei.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtopobulek.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtmvvphoov.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtghtgmctw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtsecwiafc.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtudizswzw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gtaoldxgyk.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtjwemainv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtmqeoiefu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtavxifjwf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtymlekhed.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtrllngknl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtgifpukmn.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtgfhkyden.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gtbbwhxqqh.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtwnsdigmb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtpkraqtko.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtyoztsrkl.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtjkrfeiex.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtiqaddmoi.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtdvftfshg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtuymdvocb.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtttpvqdro.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhexgyxv.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gtesywycsk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtqrgskaon.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gthpkuvntx.html


<!-- 参考信息 -->