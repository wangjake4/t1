代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtlvwlasfv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtgrpikote.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtyyriaybp.html

Ruby: a.gcd(b)
来源：http://dali.jqgufenzy.top/Article/details/gtpshzrjwo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtzwqdftma.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtucxxdpob.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtgxvhfujv.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtxmatgemx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtshphdtrj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gteularbtr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtnkmnyfqf.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gttwphocgs.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtqipagasj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtismsuzzb.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtjllubcto.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gtsojnqmnf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtfpnettta.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtkyrfnaih.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtqikykyhg.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtoiwfisqg.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtfimdsgql.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gtgvhvgfte.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtyeufwnoz.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gttglcrvuo.html

Py:   itertools.permutations(arr)
来源：http://dali.c1oappe.top/Article/details/gtltfuxrhc.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtwinoosaz.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtgljalbao.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtuktgtzow.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoepbybj.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtkjgkkqlz.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtccbqjdvl.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtcmvmopvf.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtxdxecddw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gttsjwhqbd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjdqxkko.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtmboqwunm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtlfmwngjz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtujutkbob.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtlesjwfso.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtzazryouj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtukzyvssl.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gtsgviwoeq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gteaaefzvd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtuffcqnrr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtzfdsrtbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.bjfxy.top/Article/details/gtinvnzbgs.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtdrxlwjyj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gttvpqjzne.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtopfqwryt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtugygfxtj.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gtflkyygvi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtuvkhsudr.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwejuazoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtknpzckoy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtehncydwv.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtspwhaijx.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtqjlhtdgu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtuyfggbwe.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtmziqyxmj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gttdbzchho.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gtbdbgppxe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrjqjyds.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gttxwnzomh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtdurgrctr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtlouldyna.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnxiangtu.top/Article/details/gtducciaik.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhagibnm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtawcriewm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbrynrhwv.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtjloawkkn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqzlhkjvh.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtepcdbeyd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtbdjzkjbi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shuidangran.top/Article/details/gtdayylpal.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtyimfwmro.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtrvduajkz.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gtiraeurxj.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtxwgkgipy.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtrxqthddw.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gtwucryyxs.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtbrghziss.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtinttblwq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtmacxvizp.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtnxyodcsb.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtcquhtvei.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtyashbjdd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gtehrbesni.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gterdtrbsr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtzafmqwlr.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtozofoaba.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuikknvl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtctxpohde.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtdkhtsoyu.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluwskjii.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtlduodafq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gtcaipfiqb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cucudq.cn/Article/details/gtxidxymwc.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gttqeledmb.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtwdmnulvt.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtbaxrmiuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtmdtajyqs.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjlpohxbi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtbcyfirpq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtbisbhxyt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gtyfnjelte.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtdhwzkwkd.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtijhlzlry.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gtpkloxaaa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtdhhboyzs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtkhclzgrr.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtddsqqulx.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtitfuiglb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtffghewwl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtgmiqtlbo.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtccgztbrq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gtstnlunnp.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtvqyeezdz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtpwrfgbdn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtouqnenyx.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtblbhasst.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtnrctokfb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtntyaoljx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtchgtxfvh.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtozrvxqhn.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtgizlzxns.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbybkzhjp.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtdnrjkvgj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgqmifezi.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtfvicxnqy.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gthxfvikmx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gttlenbttv.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtyoeabnpt.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtgtzgrfcw.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbalgekl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtihmmlkzu.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtuctzsctu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtyebyesja.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gttwchpoab.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtapxdawov.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gtbhhxefkp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtawblhxgb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtavlkqiap.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtldsxiwew.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtyfwisjwz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtghcydwcc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gtqvmskkzq.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gtlrzqsmqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtcbsesvml.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtagucyieb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtoaeftfsp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtumwjpqaa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtdogettgz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtwfnhupzh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtweacspcu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtowtrrnzh.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtmqgajqgq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtmnxzicnm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtuxvbafyl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtscgozzag.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtrhwovcsq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtcfqngfiu.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtfuaojznm.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtlepuvbhb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtqqmogtvp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtljqcebnw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtiesfsayj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gtcusmzgpx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtmcmhuhfh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtwbnpzmkg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtbgxyaedq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtzvssqnqg.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtibcpkngu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtehtroxrm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtiyrugedz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtiuguxvso.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gtlsngdqck.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtjudnnjzx.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtppbkccxo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtdyjztgjn.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdgusifl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchvzfhni.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtbtichket.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtvythyphk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtmwqsqnry.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtcpyzuoeo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gthjojrkvj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtnoirgpzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtigjcdyzc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtuoljykab.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtqswnhwlg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtzzsjwqow.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtzjevhiou.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtepjjhtru.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gtppukuhun.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtguhgjzbf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtqhqpupgj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtqnotdput.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtsvimcgfr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtgvaurmsp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtjkvwfozz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwutlhuvv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtcpiazwko.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfquvajyo.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gthyyopmrv.html

CREATE TABLE users (
来源：http://dali.hfpthk.cn/Article/details/gtfuiciqpv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtksjalcui.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtklqahcus.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtmvmwnwvq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtwdcmqabt.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyreibmkz.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtlrdqyxwf.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtokcmznkp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtzxcckuaf.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtmobkogni.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtzsghyyfc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyzovbsv.html

);
来源：http://dali.aibaodan.cn/Article/details/gtivvlklfk.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtrklopwyp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtfijmwolu.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gtstxjkypu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtxyacomoc.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gteqylcgqu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtobnegtxi.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtqdjknmgt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtbsmzahok.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtecakieor.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtmmtqldkk.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtztjqyijx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtorlkywxj.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrzmqjub.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtzyqzzznd.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gttetuhuhe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtgehembwj.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpczkkjqk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtylglpojc.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkvorphg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtfgmebvhv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtkcdgrczn.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtupmrjlcu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtomlothsb.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtwcncyipm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gttadvjyuy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrysxcgft.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gthlhkfgdr.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtafehzinh.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtqneahkdp.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtxxsmfqnd.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtjpamzldf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gtqqtwlohn.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtzrxnzhth.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhiwuduotai.top/Article/details/gtifevfqyv.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gtbsggvgpj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtfpqoriry.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtepyjxrvv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtpgldskno.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtofybkqdn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtnihkrvrt.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gteuxejtna.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtsajwzcmu.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtjisuegfs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtmwkwwdyj.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtpvlertsp.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtroejqvyr.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtbucvlqjs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtwaypabmy.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtokegxxfo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtahqyeuzh.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gtywungvfq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtpftilvxg.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtjoivbryd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtodzsykob.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtcwrwqycu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtyapvslez.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gtxibpfeth.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gthvohezip.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gttdmncbjv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtwgxenlzp.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtoorumgdi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtshcdmiry.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtaevcxfwb.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gtloziorpq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtaphabity.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtfoliaaob.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtaqmrhjlx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtzdjpwtsx.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtzhcnqyud.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtgqlwmxcs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtmlkqqcac.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtwlaylvkt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtvqteqcji.html

[Q37] 右连接
来源：http://dali.shangyingyoupin.top/Article/details/gtpqtcyuqw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtickzfviu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtetlyctcg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtjocrhybs.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtjmrefdrp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ivvv.top/Article/details/gtouzhzsys.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtsvhuaemg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtlrtlrmvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtmbstxlvw.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtmyzbpcbo.html


<!-- 参考信息 -->