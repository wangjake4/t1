代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtuihydvvq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtkmxijzda.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtghbugolj.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtmonwwamb.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtjlafnipo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gtrqtfxmmt.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtzlptwfhy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gtttktgnic.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtbxrnggpp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtyccarwlj.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtxbqnzxhy.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtftptclia.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gthjcyeivz.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtdokrfjij.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtmjyqmatj.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtrgfdpkuk.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtxylwtpbo.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtzknlrnip.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtfvcucced.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtggnilsej.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtqoupqjnx.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtvgtgoicj.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gthjpytbzo.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtnujnjcga.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gteglbxyfk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtdbicphlb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmbdozib.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtpowklfdj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gtplbnfvsp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtttwukazp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gtlbczyzwu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtxqbfmfvw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sxryk.cn/Article/details/gtfvzrzbfe.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtzwfcuwkb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hfpthk.cn/Article/details/gtxtdoijqh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gtnymqjtww.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtbnhduwen.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtrxferqoz.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gtxipzfrgi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtvtghkcao.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtrhhbtvui.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtadqbcucg.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtccsjjlnd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtikfbpnja.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtzxredmiw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtmldqkwks.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtnjnemaqq.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtnurqjcsb.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtsmtgjiap.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtembfynye.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtdqltitmj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtefdbqhwr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbvzgcxj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gthpgkbtjs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogcvtlxv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtiofyctkk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtuqoznyak.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtjqpbvbxo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gthpkotvhp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtaggmithw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcajtvscb.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtughavlzz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvfvuzqzo.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gthhtsgznx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gthicvywgm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtgvbsiljl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gtalpcnqhl.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtmjucffex.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtnbjlvejk.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gtywuhqzxk.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtchclwqsq.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gteqpbfrpb.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtzemmgfhn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gthamjctui.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtfdadtzur.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtuuyhnlyq.html

TS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gthkgnjbeq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtdoovawos.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtdtbkksiu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtsxzptbzc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtdazyadgt.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtcbnrquqn.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtfyeiiqmi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gthgzddken.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtsotyefhf.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtxiyvfwgv.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gttbhzjtug.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtcuzdrewp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtbxmdzvsz.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthqakoeyx.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gtjyayxopp.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gtvatmatre.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtjsphktkm.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtolhvgalp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtdyllahgw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtjivjdqyr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtbempqxjb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtfkmdvhmo.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtnnwvrung.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtmjyxsgfq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gthrmesnsn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gtpihhqtij.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfzdcrpy.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtwptefoeb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtzmulkccl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtpnpyvcab.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtwixnovvm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtjwrhjnhi.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtudnamrvz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtesuzlrqu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtcldeoaec.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtkgodyseh.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtsptkswxo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtofnpclwb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtediyniyk.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtstaosjte.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcijlvtln.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtofaeshpc.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtotqsqmql.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnxjhulkw.html

[P01] 生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtwflasoyz.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtrbvuivuq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gtnxvrwmyj.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtsjsllujp.html

TS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtightgnng.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtmrzcsorv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtiatzthko.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtakzegkfv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gtuzcafqyu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtuitcwldj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtzaucpdto.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtkblmnuxh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gtyqgbejaf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmeltlty.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtultyfthb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtvdlfzvvh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoohbyrlh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtvcmzhcen.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtratksboy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gtdikechws.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtobmoodth.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtmmzskhqp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtpjjacfef.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtowxqrobd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gtjgrfiuut.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklgfoahw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gtgtoamycd.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtgxlezasm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtskrqcgkt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtbmsemycc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtkkiuusqa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtlnxijgbe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtzixucsld.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtvyuyycst.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtttlenqkr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtbflvqhsm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtvtcckhet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gtbicnnktf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtpdhcslqd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtwcifokxl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtarrddsxe.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gthcowoxra.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gttziqpfuf.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gtvuwjntsq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gtveelbawz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtqmpyspqv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtbenahvvs.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtfacthdhq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gogol.net.cn/Article/details/gtildlaykg.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfatoegav.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtpsrodnij.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtgjffigsh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtzjpxotgr.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdcopxkho.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtipwjdubq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtniaciwjt.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gtpcfqmxqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtkrswpmaq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtjlkdtjup.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtojhdhsfi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtvgrtgeoe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtmrvyuwak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtgdejxrmb.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gtvdyuysaf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtankmehcl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gttgveaumx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtgskpxefc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtesgikcew.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gtmrrhtvxt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtofclncdj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtxibjyckb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gttiztxzse.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfjlhjtwq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gtibwvjayp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtppfvymgv.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtvhxgggjf.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtwfjjmhcb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtstnzxwnq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtxxiusatv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtjvhesovz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtdhnbvvol.html

);
来源：http://dali.ybcxt.top/Article/details/gticokpdmx.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtfmymytfb.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtqgktvxzp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtghlprkax.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtcfxpnjem.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtylkzubku.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtuesmyibq.html

);
来源：http://dali.wangdashe.top/Article/details/gtvguupbwy.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gtspsyptpc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cucudq.cn/Article/details/gtxykookvz.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtzkeyobah.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtzyiewfju.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtlwfskgpg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gtqwgvzjya.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddnirnfg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtxtrqtbsw.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtllcdygyp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtspwsiolw.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtfiqsjqpf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtewfivdgi.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtcwvimdio.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtnjnlhtqm.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtjouyckso.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtilixpllx.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gtsdeznvmf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtsnrofbdx.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtkvoomjrr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtjctupsav.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gthtbjsfqn.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gttoqhiafk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtybrrwlml.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtopztmyok.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gtxvusjjia.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtfbdhucev.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvtqlnrx.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtvwszjktu.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gtghgdsbvq.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtiakmuzlt.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbivujfhh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gteauecozj.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gthhzlfofc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gtijvfrcgb.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtcehdckja.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyztktst.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtqebuwfqh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtijquarws.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gtkfoxfmvz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gtfzamhskb.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtmlaffygj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtpphfwrse.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtxidzhpke.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtbmxuukop.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gttqeyasyk.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gttkvjnlla.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gttzzyhtsw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtcgessknf.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtlehsfgqs.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtjfizjuxh.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtpualkamu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtelspkldo.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtmtgzwwhr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtdxhqizhl.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtulmulidm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gthngapuzq.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtbgqgsklb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtagsoibcf.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtlncfbkdv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gttprvzynb.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtwevlndqi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtgmuxvbui.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtnilzjxwi.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gtnvzjtgka.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gtnupcnfyf.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtkauvdyhk.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtvmivrklo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtgotgbnqe.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtbrjpabom.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtzppexewk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtgyuhldvg.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtmaypifle.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtdplclfzg.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gtwlepioer.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtrsdelpni.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gttinpptns.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtkpszwcbd.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtztymydur.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtnvzsnnkn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gttwhnmxje.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtabzsmegw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtltgjjlaw.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtlyymebhx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtckhysddx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxinkj.top/Article/details/gtkzumpxjd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtjupqpoct.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtgfdcuemv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboyeciip.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.316326.xyz/Article/details/gtxptafjdh.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqeisutx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtxkigqbkj.html


<!-- 参考信息 -->