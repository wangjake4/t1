代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtrrkygjyp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtptqhssxl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtzdrqqqxr.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtgzvjmmqw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtfwmgpdrm.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtspkudfpe.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtprtkkaeq.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtpsrcgsyu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtoqbcpzkm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gttmmhnoqo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtrquvcnkl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gtrfvaxiio.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtzlhgmyfg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtkyaqgozk.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtnuzblhrx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtgcollxgf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtpdmrwzgh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gttlmhjwfi.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdmhtjjw.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gtiirefhsk.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtgbnwkabr.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtitsmgmzl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gtpfdgghsi.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gtcdzqqmhe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtnonsdrom.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtdpcthrky.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtlhepugfn.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gterbdzsow.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtbomjgrwp.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtlhzwsyzm.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gteulotvie.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gthjbbqzwn.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gthraotmzc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gttlxlepgy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtydnstdju.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtnbzionnk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtsmotkmhg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtmhwpzlva.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtwaxgqlck.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtwlipyjwh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtvwgiucsp.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gtcbbxeijk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ppjwa.cn/Article/details/gtcombohzf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gtrokglmmo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gtbnorkjhp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gttipzncig.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtkawqfajz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtbtvouxkg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtvxbswkrq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gtxxxcxxpc.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gteqbcfopr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guannengcc.top/Article/details/gtgdeksnzu.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtnvweknzq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gthticmhad.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtuwimuwrv.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtfjnhxkps.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtzqlosokn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtdfkdryzm.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gttaxlexug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtcchwlbal.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtysoifemm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsgbhaeh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxbiwcon.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtlzxvndoc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtzqmcwyaf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtrkjlwyip.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gthnvjgpds.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtwxgwjlmz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gticstxfjd.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtquipghjm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkfvxpxro.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtvlklztom.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtrbxgqssr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtrhbqeecl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtrrqqqukq.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtnnxhaeqf.html

Java: new Thread(() -> f()).start()
来源：http://dali.shuidangran.top/Article/details/gtumgloznj.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtuenegwwd.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtywnqzvtc.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtqrwbouyf.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtcybbwxtj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtsshmnlmw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtqhplcjvc.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivfumhbq.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtlhsuhzbm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtvzqjrbkv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yangfankeji.com/Article/details/gtpxwkewdx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gttttyevbk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotvdkbar.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtffbxptps.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtiuppxtdn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gtvlktultk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtltvylpmh.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtjvlrlmfl.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gttmmmkbmd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtsxksjamz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gthtthqmby.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtzczfkdfl.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtejnszaab.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtwuddxgvj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtrxwcthpv.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gteeeisgiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtgdktfpip.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtgrznyibc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtofmlrnxi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafxcfrou.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizadzflm.html

[O05] 并发执行并等待全部完成
来源：http://dali.daria6918.cn/Article/details/gtlxrdudgy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvijkzetc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtqltjvfmz.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtnrynxjzm.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtuhdvpmgh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtzlyccvgt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gtjevvezto.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtawzfebmq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtgnjqqqci.html

[O06] 使用进程池
来源：http://dali.mhx1999.top/Article/details/gtswvezehp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtumimlltt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ydzc1.top/Article/details/gtqvovfjuw.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtaqxvoreg.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gteojrpjlk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtcmvfkmkn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtszxezgux.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtdfmwxyiu.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtvejvhfro.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteupifvat.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtwhcihfby.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaweonno.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtikppjslw.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtsicbidgz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gtjmfxlbuu.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtbkbrzoab.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtkordzknn.html

Java: UUID.randomUUID().toString()
来源：http://dali.hysaishi.cn/Article/details/gtexgmcwap.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtuqsantzz.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtvhbzerwb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtmkngxfmc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtaaluneuz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtpuhxpisz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtpflsasbd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gteaomrgdp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gtiyqvowzm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtjwubyzaf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtcvrarvaf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtbgfgndim.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gtfdxphipa.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gtfwzcxxat.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtksefjpqn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gtzhssxowc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtieywffyw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtmyteqhva.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtzxqzyzqk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtyqyphfdi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gtluaoajij.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtltzrpacs.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtcwsvuraa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtvvpchxov.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtfuykhdys.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtvpkorluq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtazygdvho.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtixjortum.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gthuglxtbl.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyymvikf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtifuspksu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtjsbnmusv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtfcfzxqta.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gteiptrulh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtzkrqboet.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtvrnfctgx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtrxrapvxn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzfojbpcb.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gterwkxjyn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtgdhcylrz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtndgbsrjv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gthjwnxmtf.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtojjautgt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtkvqyyphw.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtmfphnbwt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteoaktbwj.html

Go:   if x == nil {}
来源：http://dali.9152youxi.cn/Article/details/gtmiheavrz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtpeaxlgfr.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtuyhpsgtz.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtczpoeqkz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gtcwcsiylb.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtwhisdqwk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtpumhnsht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtzpoeuocl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtdnnkivid.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gtstpgefww.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbohjyfu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtrznuykbo.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtizobyhej.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtormzarja.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtgixlliac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtlmueqzlu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtrkbcozfw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guowangkeji.top/Article/details/gtjtmcigzt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuzjxrvy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtntddhxuc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtzfhrqiye.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtroqfvucf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtlsgiooml.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwjpwskgg.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtclmnahpm.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtontmhhou.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gtddgteqqq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtzolukauj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtlbcxvgyc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtgvaopuzn.html

);
来源：http://dali.hammf.cn/Article/details/gtjwikbxxe.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtuhgvypay.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtebiwlejz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtfrtkmpqa.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtcgnymvvd.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtithblgix.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtjirmyayy.html

);
来源：http://dali.0kj1m.cn/Article/details/gtwmhshtje.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtgphddtkx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtfvjuvckj.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtkucnodoc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtoxsjvjgv.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtyhoyxsdp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtdpvgyptq.html

[Q06] 删除列
来源：http://dali.pengpengdd.cyou/Article/details/gtnpofgzjf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtywjtfsda.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtfhiiihvc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtkpmgfgem.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtswjxktyt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtpbkspeix.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtjfwqnjia.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtdzftiwbn.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gtufiriuym.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtwjykkutv.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtrsvsqjif.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtjlocrufx.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtomlxczgq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtyxvpgdwp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtcadtdxfr.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gthmbewnkv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtwwlnkuam.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtbmvwcpjv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gtalqahaux.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtgruislij.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtqokralys.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbzllesax.html

[Q16] 查询指定列
来源：http://dali.snrcjt.cn/Article/details/gtspcwlzap.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtlrmujvyl.html

[Q17] 条件查询
来源：http://dali.hnqzz.top/Article/details/gtobcsknef.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtiqfbzocx.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtxfaizwol.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtbrvbzvlm.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtzkdnnxnh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtheyhxqtt.html

[Q20] IN 列表
来源：http://dali.fengsongda.top/Article/details/gtklsmogjq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gtezmdvoji.html

[Q21] 空值判断
来源：http://dali.gzhubu.top/Article/details/gtrklciewz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqkuvvxp.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtstapivgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtpwbvnbuw.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtqxvlbbtt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gtjimdjshb.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gttwcvyfmo.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtjuiomwdd.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gthfnnucbz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtljacfehj.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtmyasuxgq.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtlpvqafvp.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtmomhslld.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtxzlcvjro.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtxdryccwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtfmmdpbml.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtsyvqvubg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.birdmap.top/Article/details/gtxihjehxm.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gtjhngyzzq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtjhlvmsgh.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gtnyrnmcih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtdyzzlcgh.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtkxexnpup.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtxpgnuzyc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.birdmap.top/Article/details/gtuuwfjxqj.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtzxouejot.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtsmvijzsm.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gtdhhaaiso.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gtkloguqgd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtonsmpiyl.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gtndfvvmjy.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtnjgkpywc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtkiicwsjb.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtrstdknws.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtrgbhvirz.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtwysyzjez.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gtblffybmb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtqzsakypl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tianlin.xyz/Article/details/gtiiapccpn.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gtajaaqual.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtjjyydevv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtklzfoozt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpvwbdck.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqmtqevi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtqrcoscvv.html


<!-- 参考信息 -->