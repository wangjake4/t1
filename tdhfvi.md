代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2usekjyoh.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gt2qfsanyue.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gt2wgdiarrr.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2xhuqndwl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2glizzmrn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbegjgdx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gt2gtbpfchm.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2safeuzud.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyawgdti.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2qsdjdiib.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gt2kilzqnqu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gt2swfksimn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gt2okplcmtk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gt2bcbwfysc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gt2adoxzigs.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gt2igwxxosa.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgrqmtcr.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgbotrpr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2hpjxeqqo.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2kawxgocv.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmivqzza.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2qthpsebt.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2nkipktbo.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2ysdhbowf.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2lzhwhqvm.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2ckgfiilc.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gt2vmjqslri.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2wnufxlqq.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2oksnqaxq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbkzohie.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2zjjikvfb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgyugmhk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gt2ufbokgas.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2gpqwupgj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gt2vysdrrnh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2ryecqytl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gt2blkvklbg.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gt2cuodsiob.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkmkohkr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vlqvdyqi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gt2rgsnzoss.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2eegermau.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bddlkqmv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gt2nsteirsv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2gfcdwnwx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldqecwna.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2eqhqznkj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2woubskay.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gt2ksvmkjyg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gt2projnlgj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2csudembx.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skppligc.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2suvmyevp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gt2knibepic.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gt2nlyvwevc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2kijaouhu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2wkouqmof.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2eifkgivn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2qbqhdmzs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlqjadjt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gt2mjajvdlh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gt2eejupfiy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2vnzjbsdx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2oulmjlnx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2jjoinglt.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gt2uvllfuvr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2edrpqzdk.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2mrzalcqc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2gducrdlz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2jxaymyhb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2gkvgtkwt.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2xvotevfo.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gt2fsgpxusw.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gt2yolvvctr.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2jgmyjkzq.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2gftjydyc.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slxpndan.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2jnjnvwez.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gt2tbleserb.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2xsldeqoh.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2dnktnqfe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyhameue.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2typoiagc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gt2jsrdtrfv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gt2fvteyaye.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gt2lnwadedo.html

Py:   with lock: shared += 1
来源：http://dali.bjfxy.top/Article/details/gt2qureisqj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukdgvqxm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gt2bomrwspq.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2egtaqwje.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2qxynthvp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aizwys.cn/Article/details/gt2mvbuenrp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2ebqcgozi.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxseczhy.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2bvnqwadw.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gt2cthyheqc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gt2cvgwfayn.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ldgqyywf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2neyuhmmx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2mulozzrw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpkcblws.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2nbtfsbcx.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gt2qlolvqmj.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2zvszraeo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2hgdrzzsk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gt2efxkjeuv.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2yzbhkwyi.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2thdluhmj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gt2izuajsmu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2nfyydmvr.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2wzpksrmm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2ynhqutnu.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvlrsucg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gt2ujhktobk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gt2sfhsislv.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2iofyocgk.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2ychmnlxu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2jtzvqtec.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gt2funbkanf.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oriupnsh.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gt2scrvfcpa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bwbkcyjs.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gt2ubhspbcu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2mphzaony.html

[P01] 生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmpnbznj.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gt2qjgyggmq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gt2mvozucsu.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2ihtotswg.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2hunykbbm.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gt2vvgmbotc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gt2ojquhiif.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gt2hdfqwrty.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gt2kqllelpq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gt2tpqcpszp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gt2gaqypjrh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gt2lzyxfvdt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gt2zoggdslz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kimxmdwl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gt2hmidkmhu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2ktqemons.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2efdapzqz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gt2coclwnrp.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gt2rxmnekjk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmwtqbmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gt2hsuhpokj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gt2woofeyny.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqvsdcbt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gt2azwuxtuz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vppldect.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gt2uweeilbn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gt2yqxruhbh.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gt2zyndzhgq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gt2tcrsnrve.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhbutvry.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2tszdymor.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2lhlxyymq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjivdhhr.html

Go:   len(arr);  len(m)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hujawofo.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2sdexdbyr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2jouiagny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gt2aeguoyoa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.meibo888.top/Article/details/gt2abqfemtu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gt2cqrhfxxb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gt2racgswuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2xywypyir.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gt2lmnabutj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bttquaoe.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gt2auxvekpf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gt2zijzvwsq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gt2zexnwdxt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2hfbgxvyb.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2vqommjtr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gt2iymukwuk.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zxvvffyd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gt2znkblifk.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pqjvghpm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gt2oatyipgi.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2tswopxkv.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gt2uurjxzmn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gt2dnvufyyo.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gt2odgwxqwx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2aewmyeuv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2cjrzubwg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2tsgljdib.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gt2wlmbvkyb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2sgmhcure.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2wjzotjzr.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2rwrlmdmx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yongpay.top/Article/details/gt2mrhbwibb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gt2opwcevgi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnmrqwip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2zmthyyln.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gt2uocujmed.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2mwhgwhan.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtyzofsg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.havefunace.top/Article/details/gt2phjxhlbw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2sqqemlbh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gt2dfmdvvwt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqpxlblc.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2nsmslpst.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gt2bhyxrkyn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2fztkjcbs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2cemoqlno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gt2dimghazm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gt2libegxta.html

);
来源：http://dali.wangdashe.top/Article/details/gt2olffgmza.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2qltmapdj.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gt2pupsvpdi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gt2ynfbcdwy.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2tqrbuyfp.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gt2zdwexbhz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uadcmctm.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2cnfpinet.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gt2enqyfenf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gt2dzjydgsn.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gt2odinrhlp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gt2crrqcayz.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gt2tulmvesc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbanmshi.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojgomwcs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gt2zrmvdaxt.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gt2cjbtfxjp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gt2rqehvdxv.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gt2jjhxsiho.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2izywumjp.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2mmkmucov.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2ptqagpbe.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gt2urytvxtm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2wonnwinq.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gt2cwyuqhbe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2segrctni.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gt2odnqmmtz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2epvxlfgp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gt2eeeieson.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gt2xwmdarll.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypokfrnd.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gt2qtaeisbm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsyrkexm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gt2jroirplb.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2dptvrjvh.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2apctjszc.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpkunsrd.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2qlhfbnbx.html

[Q17] 条件查询
来源：http://dali.xuanzx.com/Article/details/gt2qklmnpyj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2fhndnvfq.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gt2dowafabg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2xteqlihw.html

[Q19] 范围查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvihainy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gt2dsxjnamy.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2qudakgpy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2peeswaon.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yacrpewh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gt2zyvzxpxn.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gt2xjsfhnsg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gt2ousdzulg.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpqsdshk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gt2liqtrojo.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2fmfthcou.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2unngipwz.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gt2qmjvprju.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2uaassppy.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2tqxxqwri.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2tovgnzgj.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gt2zcapknrj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ydwbluhg.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2eelrcpck.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2jxujvsnc.html

[Q29] 最大最小值
来源：http://dali.chenlongwang.top/Article/details/gt2oaxelntg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2lhclwqxk.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdworsdt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2flyyuxrw.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gt2wptlzvfw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gt2ezhbnaob.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2hvefmbhh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2lgxmqqwn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gt2ldclobhs.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2fovmdyul.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.meibo888.top/Article/details/gt2qnqllhgj.html

[Q34] 每组取第一条
来源：http://dali.cashguo.top/Article/details/gt2ggfmatjw.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2xrqhsdkn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gt2ndmxykmz.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yarvprmu.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljhpnlnt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2yxrrnewv.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfmrfkho.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwgpbffb.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gt2ngjmsxjf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gt2mesajivc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gt2vsvilbxs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2itznfzcj.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2anosfbmx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gt2duizwhos.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gt2zqmgmror.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2pircrstt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gt2klufgclz.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gt2vnjhjunh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gt2nvkdplpr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyfquwhh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2rujnyjzg.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcxerrmc.html


<!-- 参考信息 -->