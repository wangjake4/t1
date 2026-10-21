代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtxedipzgt.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtcdhrhatn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtuwsqmuyj.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtvpcuvssd.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtetkbfldh.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtftqggscu.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtohvxlcko.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtvrrttrps.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtfbohzjda.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtqlrfolsg.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtoncwlxmz.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gteggpvcph.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtbedfefjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtdicrdclq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gttjuvgpcw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtizcdyhwt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtbxcxpaeh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gtizvxjmkm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.vqdsnc.cn/Article/details/gtqykwammj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtazmycdwl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtoomdkrqe.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gtvxzgpgnr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtelhhrbcl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqszsrryz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtjneuzwxk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtoyvmidws.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gtdxujhrar.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtysqwfyra.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtdivrdrfk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtsjozcdoi.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtjvixjcft.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtiospnssg.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtvngbqpkq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtmcvgpbxn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtiztbyfrn.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtvbczrisq.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtedtpfyde.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtmbjksqsj.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtdrybhhnh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtzpfpdrlu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtmxmdlqcp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtqjmejcwg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtzxamnxsw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gttpcviwvi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtrmerkqfq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtpzlgeklq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tanke756.top/Article/details/gtlecogdqo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtyczhmkoe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtimorshpi.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkocyzdr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgzfcwoaa.html

[O01] 启动一个线程
来源：http://dali.yongpay.top/Article/details/gtgzpkbjto.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gtqaogbpyz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtprjwalfo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtiuzavjjw.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtaatdwhke.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gttmvcthbr.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtdxqbklgg.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtzokkhpry.html

C#:   Task.Run(() => F());
来源：http://dali.dianchejie.cn/Article/details/gtesqjbscv.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gtcqkerflt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtgoncncjr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gthebmmuwy.html

JS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtwqpevsnm.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtygtpyqdh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtohioljgh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtentcqqel.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtcrpwjspz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtjbgiaqvw.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtdzmxedof.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtnyikdmoq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gtbmuqdamh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gtsjrbrgmz.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtynuhggjb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gthcbicmxs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gthjkqpknp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtklzxnkhb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtdhexrljs.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkktkrfvc.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvxwyqoc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gtprpcajbu.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsshxxhxa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtuaioznlt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtodkmobif.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtjevslxnr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtkudpomqb.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtwllvlcot.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtqrtovykb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtjuoxsitd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtyjehvfdx.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtvefspmde.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtwyzvlslm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gtmydjbtpc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtsaaogjdv.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gtzwlalxtw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrlosdna.html

[O06] 使用进程池
来源：http://dali.sxryk.cn/Article/details/gtbqpdchko.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtaccrxxkx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtkamkvyqz.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtptlphrpy.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtnzagmoft.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gtnqfaknqo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gtyqjcyozd.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gtvajwqefn.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtlbuesnmd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnpuwixti.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtvajdentm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimpbjvte.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gtwgjdbzff.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gtspqvpsap.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtjqrygaah.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtvfwqutbo.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtbynxjqyt.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtnqpuynbk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtpofpcpao.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtuxqcrvef.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtvlhvsqai.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtukwqkntx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gtkyjtebwh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gtzecapexf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gttezgqwta.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtyhssghug.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtpmhhvvhz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtksywqjue.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtdnxghxli.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtesprndtj.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtyvskfhlq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtuqcxizqf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtzdbnjwji.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtscrgpxnr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtvmfwxxum.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtlkhxvpek.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtcfgnpifn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdxonnul.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gttrwlgfqo.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtsaeaqvgl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gtbyyxgvkg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gtmohkwkjx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtwqoxvfxv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtoqnfqfpi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtwkuivlvc.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtsfxhrbvi.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtacydfosg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtgngbjnvq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gtncqrbkdl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gthqtbcese.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhysvtqc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gtwdaqaema.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtwypmxxgi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtzulwivcc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtzpjajpgf.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtuujjkjpp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtcxozcogf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrmhjhtp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daxiang520.top/Article/details/gtduidiyiu.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtdrysgcht.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtvgaqukyp.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtzaqzsrjw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gttspgbbkx.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtejdqchnz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtablhjbxk.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gtswkhrxkk.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtnwnraxga.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtmohemcss.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtpdxinakp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtheqhopvq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtuxreymyr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtwpiqtunj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtvhsbkpcg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtoiaojuai.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtieqeipwl.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtoohjvbpe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtpjzjpwvj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtvaadvitq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gtkvzlzdor.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtjqquhzui.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtjsmiyhrt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtduxrowew.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtxcsajfmu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtwkqnccwx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtivtdlzgd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgklgozl.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmaypssbm.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtzwmyzyne.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtoazjzfkg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtosnexjku.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtyyzeqske.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gteclcsmrf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtvudgxmkx.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtaaeumbyk.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtvyhlukzc.html

CREATE TABLE orders (
来源：http://dali.316326.xyz/Article/details/gtqlwbcibz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtwpewxbst.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtmzyngssu.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtefqwenyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtlvzntajw.html

);
来源：http://dali.sxryk.cn/Article/details/gtvqlhmowx.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gtklohxsuu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtpgoycjrx.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gtksigykgb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtdhunlmfh.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtaxixxsdm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtidznamdi.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtfzngcdri.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gtrdsxfjtg.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtnriktrwo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtwvkrzxxn.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gttpdiplep.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtljyopfje.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtfnxzbzcr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtamcoghmi.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gtxvnlrzwz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtrvvtucbb.html

[Q11] 一次插入多行
来源：http://dali.jiagoushi.top/Article/details/gthatmzdai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtgpkpzvhr.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtogdzbypl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtcsptyzwg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtaqflopjs.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gtovkhyqgf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gtbklszudd.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtmnnnmqbe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtfwazgqiv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtockajexx.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtrdstsohb.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtwixosoeq.html

[Q16] 查询指定列
来源：http://dali.zycfv.cn/Article/details/gttiowxswp.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gthjbawgdn.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtmztsjkdq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gturaombem.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtitsxanhs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gtziokvpno.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtmaqvcoyn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtlogekllj.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gttsxwtdgn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtvzxpbtac.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtzxwxppev.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtijpslvbs.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtomrcigbp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtuotdcrns.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gteqyntifo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtupldneqn.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewdnrzwk.html

SELECT DISTINCT city FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtrqgrhhil.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gtsfemkymi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtfctmmdql.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtukqmnoiz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtkehfpfes.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gtqmovsvic.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtngnuzmmu.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gtzbudnhar.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtdtpnjzij.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbtajwwf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtszowgfkc.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtjpqpztqz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtdkgvayog.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtvlupbjhl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtwaudvswi.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gthwxxfvmg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtwovgrdid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtadqfeieo.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkqslzgn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtebdfttff.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtaadtwyaq.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtjkkyzuov.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtdhcvzufm.html

) t WHERE rn = 1;
来源：http://dali.ybcxt.top/Article/details/gtcgdadeps.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtlhaqjxzv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtouuxxugk.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtylbulijo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtqlhzurkr.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gthgnnuotr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtimucjglf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtzznwvcre.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtlcvzjgps.html

[Q39] 自连接（查上下级）
来源：http://dali.svipenyu.cn/Article/details/gtxobaolju.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtpjzubuwf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtlxuqvuty.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gttneizljq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtmroeexkn.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtqbahtqyr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.316326.xyz/Article/details/gtlsevnetl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gtbardxzgi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gtmuseawku.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoaqbqve.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtlskopgji.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gtbcjtbbzg.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gtsqweldvl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.316326.xyz/Article/details/gtqleurdha.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqbbzeln.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtfsqfwqjq.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtdikjqkgp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtjcixrmgm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtqycejkaz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtveladdey.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtrmnqmeba.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.andypj.xyz/Article/details/gtbukxonrp.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtqksygibs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gthwofhjri.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gttcqfzptz.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtuqkmnyyo.html


<!-- 参考信息 -->