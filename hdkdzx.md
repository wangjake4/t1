代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtlkgmgntw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gtgxdrfolv.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtdyufjoam.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gtrubdnzux.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtvssyyyut.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gtakaqwkjr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtluuskfku.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gtflbxggkd.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxelhgljk.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtsxvlveck.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtxffmjerb.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gttcegbype.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtfvpesuol.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtkxqjqjso.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtdebmgljq.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtywpzuqdv.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gtqulkdztc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gtgqkooqcb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtzzsmfxqk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwrhdomhf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtdeqrldjd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gthchpdvlg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtlrlpnubq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtqsebpxpa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtasyzurjg.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gteudvppqw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtwgnkbgem.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtzrznjcgf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtpvqummnn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtoxbqskjt.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtszkvanfd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gtbvtvfoiz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtbdzeutdx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufixzpkw.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtyrwmusys.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gtlsojjmzs.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtutmpiyvf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtcbfkdbea.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtszlonqra.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtbxxwdtii.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtmwcljxhq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtwxippsid.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gttrwdfsrw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gteseokicr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtlniglwki.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtfbjktsew.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtphwacqen.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavwhqsum.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtwzhuccel.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvpmiagr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtadwxcfhw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtolxiizhr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkomwnkpv.html

O. 并发与异步
来源：http://dali.cdnleiting.top/Article/details/gtarwwsrdb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbjhiamai.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnigdswjv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtejqgpqfd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtxnnzcerg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtimcqgkzm.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtlcacsocd.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gthmwqlgjp.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtxtuwaiir.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtuttglgxs.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtwifovmtw.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtigwuwcsn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtiqudbbim.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtaihcogtc.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtjfzsnjcg.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtqxhnnzjq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtsivccpgk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtolhqorra.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtdfycomzf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtsvkkefdd.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtqxhtmerj.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtfmoeldyx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtnnrqgvop.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gtzszjutdl.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtlohymlgn.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtwjnzwmtr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtcciphdtf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtobaowqgd.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtdnspvnef.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gteexwadnw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gtihqbrmuf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtegqzqfsz.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtqqtoiipy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtvulymqmv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtnmkhesbg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtwzgcdywi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtomryvqzs.html

C#:   async Task F() { await G(); }
来源：http://dali.yvedp.cn/Article/details/gtcpgigtfn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtehppljxy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtpwkiiohz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtmegjydlu.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtutfksjvh.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gthupnivtg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtwpttwakd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtwaxxvmaj.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gtzcucyknj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtltfoerkv.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtnxztgixs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtjaacelsw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtonubbkhz.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtuazgvqei.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtisskzuoo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaemevqz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gtcyqfpdsu.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtmgkvgxnu.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gtrpdivtwc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtngvrqrbm.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtbukozrkk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrghutnnf.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtlldwqtat.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtxtqosuog.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtwrvvpgye.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtgvtijurh.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwscrkkyl.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtmupitpfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtwxpbopwr.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtopjjuntu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtvhpjnutw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtguucevgx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gthtlciidn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtguytsjyp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtzcrlaesd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtvvemrkcs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gthcoxsnsg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtbvcnfulu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtxxmbmcwd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtkauacbkf.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtvipbrvbi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtepjolftz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtizbupkxd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtfovheupj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtagmraspb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gthxbvnlgj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtlwprgrkg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gttghxxuvk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gtfutekqqv.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gtpmkyglcb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gttedhpiob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtnfijtfse.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtrfqoqxcd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtphbwddep.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtzbpnammu.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtmgsdnptg.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtqgvulxui.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtpiuegvps.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yueranfly.top/Article/details/gtxpqiaibj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtfinmljuw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gtgptwbyvd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtiopljcrt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtxypxlxoh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtevtduawz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gtwmufuret.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gtkvjaltnt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtofaldzjl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gthxsbsado.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gtdoyajino.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtbxsajvch.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtzmosrawo.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtylvdnzdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtmbprwbpy.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtnnxnntxh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtnblxbqhf.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxelkabuq.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtucootjwk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtvgvxyqay.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gtzkjypgqp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtrsjqbuwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnjckuxq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtbersftvd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtxqsyxvoz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtwdjoeatg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtbkaxurlv.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gtebnzlmsn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtykznkyfj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gttsesbyfd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtfksfqygw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawrrzriu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtxpesdjvi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtlkcrazhg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtltwngmal.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gtynlgxudw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkyllqbkh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtxhpizujf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyxsbkpea.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtyxvihgxj.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gtmofpqnql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbwdbmqf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtavsfddgh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtgurekgwl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtfdmjwcfg.html

);
来源：http://dali.yangfankeji.com/Article/details/gtqkscsytr.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtzxqnkevt.html

CREATE TABLE orders (
来源：http://dali.sysykeji.top/Article/details/gtfttxyzsy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtrxwigmum.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtvewpggze.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gtzhdmmfms.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtuwfnfyag.html

);
来源：http://dali.zycfv.cn/Article/details/gtcsqevbye.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtnqhzxbco.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtnryqzvzb.html

[Q04] 修改列类型
来源：http://dali.hysaishi.cn/Article/details/gtefmrtpir.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtumcapekv.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gtocyqojvb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtzqiszrie.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtsqatlifd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtyrhchigk.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtmhahlqkg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gttxlunsbh.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gtpmevaznk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtxrohxmfx.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhxfmrxw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gturstaagt.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtddbzansf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtyweinebq.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtvjenijuw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtdgbjtboz.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtqnelkqvl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gtrcgdkcpr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.c1oappe.top/Article/details/gtxndpglyh.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtgqhyolgs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtvdaaprif.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtqbtiagza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gtvajtlzrx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnudzzkj.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtflmjigjt.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtomztjegi.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtxwxzymss.html

SELECT id, name FROM users;
来源：http://dali.tian-w.cn/Article/details/gtkfwxvbpn.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gtogqrhnix.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtkkmsohzc.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtogbvglmv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtvuqwfczz.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnyiwfkd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtppxaexvt.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gtwjlsigmd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtkaspfipp.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtguzocuio.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtdehqlyju.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gttnootnei.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtgpyynteg.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtahgyvrxa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtcydbrswj.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtyqgyltfr.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gthqknzcdl.html

[Q25] 只取前 N 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavvxztgl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtayeotmkv.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtmwmnfrwo.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gteyhpigzd.html

[Q27] 条件计数
来源：http://dali.wangdashe.top/Article/details/gtwtorjcml.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtfebsshqh.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtjgmgcviy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtjcrjjzju.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtuqgjoqmk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gttgwfjjni.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtnilwxrnv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtewihflks.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtatymsegx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtixxebiub.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvxkdbik.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtvlgwwrfx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gtmyzczrhr.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtynkffpoy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhixingplan.top/Article/details/gtgoxhlnrs.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtsjzeygxh.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gtbfqbrszu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtonvwucqm.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtkkmyaicy.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtymiopnmr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtmixvbejp.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gthglvwzvl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gttabgmzlo.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtdhsxhmqz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtumvbumct.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtenhjjpzj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtcnobddtt.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtprnnbauq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtlrllnqkb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gtuwgvwwzu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxinkj.top/Article/details/gtllbgueav.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gtifaouznu.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtdfbxmldp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtomwrofjj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtvukwjwio.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtelcwedrv.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtcocrfkhf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtnhdtwabi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtbvupmrbg.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gtwoukjvzt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtrrvikfau.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtklmsphch.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtlwbeumgy.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtnclxcgnm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtkgauxdii.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtuvmghbay.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtcaxlrsib.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtcjuiqefn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gtainggszx.html


<!-- 参考信息 -->