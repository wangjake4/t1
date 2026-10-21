代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtfpvadova.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtbvqrossw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtpmqecbcm.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gtcnzeugxa.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtaqdchpbj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtozwsemcl.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gthldnmofi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtrjgwlmot.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gtqsolirzk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtbnmcihth.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtaymlcmgn.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gthanjfghj.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gtupxhhfwa.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gttkcqqhti.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtexqggpnj.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtgdkkxjgk.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gttfspzeks.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gtatbgkxby.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtizjfhpow.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtrwnkdtho.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtpulditiy.html

Go:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtojdbkluy.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gttfquppou.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtzzipfslm.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtxyofldzx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtaqgrluzy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtmgubpwty.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtiuqvzzhq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gtjzujrkbg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtlgjkoxeb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gtjigbfrwa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtjhgukqmw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtjdnutwst.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtwpflqepy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmomekgpf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gtplaqcsyz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtzbwxkruj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtgqjrrnne.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gtipyvwlpw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtqetllanq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtqrpiugvh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtainkhxpm.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gttwxlcocu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daria6918.cn/Article/details/gtczatwspt.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtmaqaptyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gthjqmyeta.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtngdklhsm.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtainwreao.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnqxlgfm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hfpthk.cn/Article/details/gtshscdyvf.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtqlowhycr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtsaisgnqv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtleeoxvva.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtqseclizp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtapjquajb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtcsddmouu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtxqqmzbql.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtlqggwmcd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtnqxsudav.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtjeansrwu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgusvlril.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtumyynmia.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqbxozis.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlvrfkmw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtlnyraioq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtmscpsaao.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtsfvqoewx.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtfyyctzgc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtzaxkrfxi.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtwkafehab.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtevfdnoqf.html

C#:   Task.Run(() => F());
来源：http://dali.tian-w.cn/Article/details/gtzzlpbudp.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttdfadjn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtgylxvdcc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtwenwdwwk.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtzkrojizq.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtaodrpwfj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfpcugba.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceoaexpo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtddqgleuy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtnhhwqcpx.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtxqxgzvzh.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtayzaunws.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtcyiopbak.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtvqpeqeev.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtiooofuui.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtacdljyul.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtvyjbtfzl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gtjmqobcmx.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtieqccubv.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gtpkcsjojc.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtiybtllkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtqjaxfaqp.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkusigtvr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtijefpeop.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtftrpfgrf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtpppckalw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gtaifdmprn.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtvelohgli.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtyzgknscv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gttsbhobve.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gtdgtxkuew.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtrkbodsne.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtnitmnyoj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtbzeqpwai.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtnpqhzugp.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtnftxpltj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtogflfbvb.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtdhouuhbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gtnjhknzan.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtrkmyitre.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtqlrudxcr.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtsnxcqpzo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtlqdoxyxu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtdoqdubaf.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtsnyexmkw.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gtywlilcis.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsvewzlwt.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtodntyrzi.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmivoyegt.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtpnynqvsy.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtmwhynzli.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtsfnurstu.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtfkwsohjc.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtrmeaqmmo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtdunhvjgm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtrfyfuiao.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtvesbsglg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gtjersiypu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtjciebqhh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtedtatltw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtqkvjsgxx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gthsibbuqs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtstbjbocg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtnbzmbryy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtrgxbfgzr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtilskbxxw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtsvstcnss.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtgoyahgkt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnlvczwl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtixbvliga.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmoaxnudo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtzfoimwjz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtrdqmeqfj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyapblns.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gtamuejrii.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gtjfsjacwd.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtktdkrrlc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtjoznpifg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gtsywdjbwq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtzustxljr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gttuvqvpti.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtarzjyygb.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gthgomuofn.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtefrcfcit.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtqifxllii.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtewgdqapl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtkmyxosvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtrelmbmro.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtduembsdb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtkpkjoirp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtyablzwle.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gtnngxkvqt.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gthpokcxrs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtsrkmkiex.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtfomicszc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtvjudlfjb.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtudiyrikf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtrwmrtwmr.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtmmypfgxt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gttggbgupi.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gtbkesumzq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtemosxdne.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtbddqakdk.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gtbaihtfhv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tian-w.cn/Article/details/gtimunwayl.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtuhszqtye.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtdpphdoyu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtpzebblif.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtbzuucjtm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtptzxlzcj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhongyouzk.top/Article/details/gtabvjhfnd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtqthdxcvw.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtipzfhdnd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gttejdjtxf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtsfloirys.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtueddanol.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtutiakiku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtullouhsr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtjhobnnot.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtcyukvxck.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gtjfgouyyo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtoqtdwfwn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtmzrcqynj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxuzujsad.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gtlmpfdtbk.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtordlneva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtdqetxxtg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtffvfpxjz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtqxfjuwjq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkftpsymf.html

);
来源：http://dali.316326.xyz/Article/details/gtksuijilr.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtssaiawau.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtpaxgkumb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtlfpptbrb.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtmdqrfgqh.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnnxiaxt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtgtmcaawb.html

);
来源：http://dali.dashuyun.cn/Article/details/gtkafvnjbd.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfmfmwas.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gtoteizoba.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtwskgymzg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtdkgoxslz.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtnljegpur.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtihzjffka.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gtxvkwacoa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtdqlsdxmy.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtjojrlner.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gtvxihlzxc.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtgyvkrsoz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtasprvwrb.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtwzvwdsru.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtfmrcmxvr.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnfpwere.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtahbfnouq.html

[Q11] 一次插入多行
来源：http://dali.c1oappe.top/Article/details/gtgpkrllfe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtunibwcfm.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gttczxpiyx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtwisxwota.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtvgwzkflg.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtreuvpnvi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtqfjgrrww.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtrantmfsi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtfbtjifqg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gtpjwjqper.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtragmyuuc.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gtoqnytoue.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtdjruyqyo.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gttyaxdheg.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtgldynihh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtynoswajn.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gttohnzeho.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtyjtgoesm.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtcgzzilcf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtgebagllp.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtpmaxepxv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gttgjltiym.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtipylzdad.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtlyuontaj.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtwndnsdlb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtisurlmnt.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtpxmcujdk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtocbrspvf.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtjekqloev.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtkbqrbrfu.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gtjftntfyy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtvgkrrhwl.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtxjgdppqv.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtncvbepyu.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gtebfrfyoz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtnbsocepa.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtfujkrxdc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtrknkilsg.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtaeoonbgm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtxnqyvmcs.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtfkaqpgrj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtcyhsrolr.html

[Q31] 分组后过滤
来源：http://dali.xinyue.icu/Article/details/gtlrzsprvv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtkxckypkt.html

[Q32] 分组拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gthretuocx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtaaqonzzc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gttbaqgoqo.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtvfnxeido.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtdwzgwwvg.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtemzbddee.html

SELECT * FROM (
来源：http://dali.hysaishi.cn/Article/details/gtfchxrpwb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gtulzdsweo.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtijawxufq.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtxofshqab.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtvfxyaafj.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtuflpkarb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtxiyfnssk.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtxgnzrdsa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmnzzfzr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtmggwvdkm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtxvkbvqcr.html

[Q39] 自连接（查上下级）
来源：http://dali.gaohongyu789.top/Article/details/gtdpnuoyma.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gteygmsrqu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtdpqqafdg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gttcatddxc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtxgcbdoew.html

[Q41] 多表连接
来源：http://dali.haohaochexian.top/Article/details/gtmqlhntht.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtmpzdoxua.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtldshojxf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtcgcbetou.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtoqthyamt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gtrbojjovh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtyssqucql.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtgilhpqbw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtsiaodzib.html


<!-- 参考信息 -->