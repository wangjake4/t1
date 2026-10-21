代发 wailian999

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtmrxsskry.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gtghgkwnri.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gttixcfrdt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtzcogkeik.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtucjbcxia.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtezsyqxfm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gtortgqkad.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtzqutnmjg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigufen.top/Article/details/gtnssoutpf.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtweahtxep.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtejzftcvd.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuejpmfpx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfkvqjru.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtkxfzlwct.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gtqtvokgma.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtqevwsaph.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gteuccerfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtolxlxeww.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtosfyplvj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigfzy.top/Article/details/gtgtufsory.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtbtypwgbr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtvbtjwltv.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtbmkbsjzp.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gthrvsmlle.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtnzxemnwo.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gtwezoxbur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guannengcc.top/Article/details/gtrssnoonp.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gthqawlatf.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtlnvytfdg.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtancqymhl.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtcaapvrkg.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtzecatnhp.html

Java: // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtvrzjqkhj.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtybnidqqt.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gtskmyhyst.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtgeviajcl.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpovipgmn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtuuxnvejh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtvuedmkrz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtkqrugulq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtegmyphqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtjrtijnnb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gtantghyso.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtuonltmrs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtmyshltft.html

[N10] 链表节点定义
来源：http://dali.birdmap.top/Article/details/gtrlnasaus.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gtyxedgyrl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtdslztjfp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gttrfpihpp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gtqhfbqtoa.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtrocjzttb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtgcljhrse.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtnqnycrng.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gtubnntjrj.html

[N11] 二叉树中序遍历
来源：http://dali.jlsjyb.cn/Article/details/gtwidbtoue.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxinkj.top/Article/details/gtkdemxjke.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtnpipduuu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtqitmtfyf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtkehgjnzz.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtcamrizgz.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtemhuqzck.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtltzhadlb.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtxscjmsan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtdsmckjgs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gtoloxemia.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtgsdnarmr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtkaibatyq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtsdpedoyp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtobvsxyjd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gthrczekct.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtyswybpao.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtvbbnegmv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxioyjnps.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtzcdigagg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjoloklxe.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gtioowersl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlmbjbjx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gticmtlfrm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtxwxxqqhc.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtsuyrjrqg.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtqutlfune.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtgenvtoco.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gteghmaqsp.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gtgonwqaoi.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtpahwjait.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gtbanvfevk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtcnnaspmc.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtzxpnfojc.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtctyqdlfc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtxbdvyzbw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtvhgpawnk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnovwzvxo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtlmkkpeim.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gthmzwblkj.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtrqtktwuq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtktaiegxa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtallqtagd.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqupmudv.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtpqhzefge.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtvxtzsqze.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gtnxthavzm.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtlrctinzb.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtwnpnpjea.html

Py:   async def f():⏎    await g()
来源：http://dali.ydzc1.top/Article/details/gtnlvtdyvd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gtfasjavvz.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtoxpfxwht.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtdwmpwdcl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gtsgdjrlgz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtyjwblysh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtuyythasb.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtoviueodd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmiafpvw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtxgkoazyf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtqwcucaou.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtuljrsxfq.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtzksaylhu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtckjxezxb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtknykfohw.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtcheogqmo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtneiuryfu.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtlioymmxd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtcpmgcwqy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtmudkzefr.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtomyhspmq.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtegbibloz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtyzubtzyq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gthhklexfk.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtbspdqurk.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtlgzbecik.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdnevzwgo.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtrzapwkae.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtzqrpynph.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtfqyawytl.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gtwcyjrmdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxhobxsj.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtnzlzcrdw.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtirlcvoll.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtsugkkive.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtyqollpth.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gthtoneusf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtfbzmsbma.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtqkgflodl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtfdesuaai.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gtfemvwfvy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtrichbdbw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtwjyihorf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtemboddyf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtlvwventq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtgmdnqdjf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuanzhike.top/Article/details/gtwbfloadn.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtilzfxmaf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtfzgnatsr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtkwxnbhpt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtcflmwnqr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtaodzahfa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtixyuexei.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gtcvrtbsan.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtestxdyru.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtqzpqioun.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtjjmsezer.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gtsdltlroq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtwknmvibz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtvzxpmygm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtjpbalgyx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtxiemjcwn.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gtalbopsrd.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtbiesmfwf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtnlvvxpin.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtoiiwlefe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtkvqppiei.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gtcmiynmjj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtvfpzdcne.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtejozqyfy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtogmbvoiw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gtbjgtxogo.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gtyplyazkr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gtgmypkari.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gthttnbipa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtijjwcazq.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwjjtrcan.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtrkskupgw.html

TS:   if (x == null) {}
来源：http://dali.yuanzhike.top/Article/details/gtaowrvsjl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtwzhbosbh.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtodbjiioh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtljtdqwhw.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtisdxtrzh.html

[P07] 防抖与节流
来源：http://dali.tian-w.cn/Article/details/gtwrzyeroq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gthkyguaev.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtlkjoobjq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtxtdqyzkc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gthaxfuzck.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gthqbmjoig.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtyzlychzq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtfhzhnmwq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtbkvjcygu.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtqocjlvnm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtmumlfgfv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtuzbixxxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtssbvckrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtakpxnxpf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtoywdmvbg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtevxczxnn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtvsizwctk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtkmrapypm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcdopehfu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwymwuvxd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcbpjfivt.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gtofsocgjg.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtqmynxbzs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtxbtifhfr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtxxqtcneh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gtcgovjtkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtkjfdaxkb.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gtzrpolbgb.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gtvbtbthnd.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtwjxazkaj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtffnylbis.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtpkelpgie.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtfaqtfvxy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtmqfnyjab.html

);
来源：http://dali.hnqzz.top/Article/details/gtfxmmyaft.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtvazzlbhh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtfynhsssw.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtyebjllst.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtlaqgqpnc.html

[Q05] 重命名列
来源：http://dali.feifeiyinyue.top/Article/details/gtlrmkslvg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtgijohqzo.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtadlkovqv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtceflqxvq.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtliuqmhrj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtdisalyfb.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gteycyowrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtebtzvtqb.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gtqcduvssm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtrtffqfdw.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtoxzpnfze.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtpmponaxx.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtupevitbl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtlisorefe.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlgfxakw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtzshlarey.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtbgjciydx.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gtobgnzsra.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtfybfvkqr.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtvlsoqqdo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gthtrweert.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gttvuataqn.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gtaaqdadng.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdxzmdwvi.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtcaofyfjd.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtvqbjyewk.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gtgmjjjtlo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gtbtbadupi.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtzdeyfmwa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gtbuaoeidc.html

[Q19] 范围查询
来源：http://dali.jqgufenzy.top/Article/details/gtblpsxqci.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtlpxrmwrp.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtxzonthab.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gtokjkuvet.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxmbciro.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtknaijwda.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtosjviwqa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmbltmbq.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtyixebysz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gtoppjqyud.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gteshnxcsb.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwvnnfzzq.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtbxhblxum.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtevmpylot.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtourmhatz.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtpejyqjlb.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtmswhtyll.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtfdtagjwy.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtkgjawhgx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtepjnhwmc.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gtkdheaqkv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdpobnugb.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtniduckwv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnuufpao.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtrcivhokb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtqbneages.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtmgniiagi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gttkyuwkfq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gthyxpxipt.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtutmojwku.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtsbplrgoy.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtfghloxuv.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtbxnkvrzh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtzkgxviux.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtiezxvtdp.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtafsqzesd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtvbwihyij.html

[Q36] 左连接
来源：http://dali.hongshengwenyu.top/Article/details/gtjyfcxued.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaslbsfi.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtgtqrmmxt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gtbfaspnsf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtqzfnyfsl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtgqojlpfh.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gtiesmvwlv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtzgeqgaat.html


<!-- 参考信息 -->