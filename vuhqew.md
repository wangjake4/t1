代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtamltyjvg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtvvzrkavg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtrobgpnwk.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtbqacrvwe.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gttxnbcyff.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gtslkmadpa.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtqukoamnw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gteaftzwwh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtrckrcdsz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldjxandm.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtfwciuptg.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtrzutvgkv.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gturjqrkth.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtdwvoxpni.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gtggmvhnbo.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtakbvbmmd.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gtflgdqudb.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtjqlabokl.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtjkcsytlu.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtlywhniyk.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtttxopplg.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzbnbnyg.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtksmhurwy.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtqjalchvx.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtrbwhkfsc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtdmhkhzuo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtfnqwluzo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtqkgoyunp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gtuyfzstrc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtgyxdpjkq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtpwwulfyf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtyntklncn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtdkguvenc.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtcqowhvrm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrnrcflj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtdkopwyuj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtzreevegl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtvgsrqlmn.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtoxzxcitf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtwgldxsys.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuetiantiany.cn/Article/details/gtcremgvjo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtrznfedeq.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gtlgjmzlpr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjapkfpvt.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtriwuxphf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtrurszxyq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtvuqnssvx.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtfimeghcj.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtubsoypke.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gtqtuiweow.html

C#:   // 手写递归
来源：http://dali.nwbrower.top/Article/details/gtbgriddwf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtlqsleruw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gtrswkbpzu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtgiqjbeyt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gteklmeolo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtdnbjmpyg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtfnsaqxgm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaksujdo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtettvsokj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtkuhgvvlb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtuumfxpts.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gttbecozgg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdhhsifp.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtrmzduevq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtonyyifxf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gtahkoxncm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gttjrhzrgh.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtvbtftqsi.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtctxslhcg.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtwjmdwzlq.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnupwfwf.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuezfnksc.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtcasxfxqz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtmtknzdqz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtilvextth.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gtrdkhbuwg.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtjjagdrbo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtqaflfmix.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtgnezkxnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlstslwjy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gtcesxmxnk.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtfsktogsi.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gtocvasqpd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtnxsaxbaz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtorivlmde.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtcobvnyfz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtooogcipu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtzdtnrcur.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtviwxqbsf.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtzveuhtng.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtwdztpyea.html

Py:   async def f():⏎    await g()
来源：http://dali.ivvv.top/Article/details/gttaanvxft.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gttstmetua.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtmhzlfkgy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoriqnmd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gtdxnqrjgf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gthnbwltlk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtbguiwpzs.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtnmrkdvwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gthhszpvmy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtbgdkoojm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtmuyhncex.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtfglqmith.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtzcoxlmbm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtwtmipqdq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtxhltcqtk.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtjhlcxyld.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtwkspovkt.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtqxtnbaqp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gtuuulsvxm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddggpxnl.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtmcldymct.html

TS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gttvehesho.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtvtcgsenm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtisoakwfq.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtvgktwwno.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtiudxbrsq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvuurlwnf.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gteyezjgmi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlzbenpoy.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gttfoxzcvz.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gttgmeezrp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gtlvquxxas.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtanxfraej.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtybmrpxub.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gttvmhwwiq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtnnjpmoez.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtycczhnzr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtmwhkcapd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guowangkeji.top/Article/details/gtmuenbnej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrszqanpf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtqbktyqgm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldquwxop.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtokvsxlrp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtasynwcdl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtyjuumqpt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtcqxxdhva.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtxscakdeo.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtqqmawgcf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtiobytpmz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtimorbahd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtkjinsfvh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtbbsdzaoc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtbaspjunj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gttokxhspa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtssqyjhcr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gtvvrljfok.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtqpzkxpcp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gthxeetqdp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtbnuoydcv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtyhglbudy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtpyjbblir.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtyzlziwih.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtucxqfmms.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtbmzxtbsl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gtvvkweyik.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtbogbytjd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtegwjrdqe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtlfgqhvuo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtnmpuidlx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtowdhnfrs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtcfwbuswr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijdckjvm.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtvgxzwdnw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtyxuljmzq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtumetkaop.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcoulson.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtumbihsmp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtvzigtpmk.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtjnavqxqz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtifaapoqh.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtyjzbmdzp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtsrawauoi.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtkhnrkmbx.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtrqoozzea.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gtvvrgffdv.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtppjmeucr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtcmhquojt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtucuuqlvm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gthaczxhiq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gtdnqgqips.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtwpofdnmg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtesxmuane.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtbkxhxqpi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfqscdbg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtjqseczpn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.smart0.xyz/Article/details/gtvfovencz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gttdoujkor.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtvmecmfxy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtfwgctxon.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtbejzozfp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtddkeowmk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfjjffujv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtlsolveac.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtatwvoyyl.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gteghhengn.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtqzokioif.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtkfzplgee.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtmonuxjjy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtunwmhrkc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtvezqedps.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsluuzkye.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtlesrawot.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtnrecmijt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtnzmllbuq.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtriqgvycw.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtfocpnthd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gthmoyflvy.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtgysxydgf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtqmfgrroi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtwnghrrkr.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtatpvowqi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtqloynycp.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gttulzcfoa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtjqgqlkmh.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtzzsogyuk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jiagoushi.top/Article/details/gtisfjdkyb.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gtnhvhkdjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtxbmyvfal.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gtpqosfydt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtgvyhrpaj.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtiafnlsux.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtlqgcflxv.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gteyyojtss.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtakeyynij.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtvlvomymm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtpugjlmkm.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtjempmzts.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtepjaknbi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtplsgqvtw.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtoctjqbvl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gtbpqnxfnb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhongyouzk.top/Article/details/gtjeszncat.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtuljdpfdr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtcwqujodg.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtdaxiklrb.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtrkacqzic.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtlyojqkun.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtytnmtggf.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtsgmalrhq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtbbijdvvo.html

[Q18] 模糊匹配
来源：http://dali.xuanzx.com/Article/details/gtbbhdvyfj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gttwfyzqaa.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvlmjlwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtdfpzkoqn.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtrmgpmdvi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtnchsxwak.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gtvyjhingl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtyfmsbnya.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gttxxkgyir.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtutjpmphn.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtcrnmreqr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtvxrpksso.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtosjkpzor.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbzfbnddq.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gtsjvzpiiw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgujarhnn.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gttevuyhij.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gtqduagcjn.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarfjuton.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmbaznnjm.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtzhqtghqo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtvkupusuq.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtvuhhnrga.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkjbhaxms.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gtpqvfsfzk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtgxsnoedj.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtoqmqzsmf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtyrunnhru.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtdouedfzi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtrdhrcjap.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gtvsbqfpkl.html

[Q33] 多列分组
来源：http://dali.fengsongda.top/Article/details/gtheqefhdp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtalmbobpe.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gthxxrhdbp.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gthuolwjyw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtaagdxelh.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtjczgbokg.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtvbpmfefd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtplfdjfag.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtkewlxwso.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtwwdrbrhe.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtgxkpuzzw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtlfiianxe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtgnttdpvl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtatmevcns.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtdyrvlyhu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gtalxyswpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gtssqomyfq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtgeszcfuo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gtvhjkelyk.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtzlapbeqx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtnhkebixd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtfddcgfbw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtalxelfzk.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtqzuknbnz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtpfjmxobr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtcczqoefk.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtlcybkpsx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gturywhzuq.html


<!-- 参考信息 -->