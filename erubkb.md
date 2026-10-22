代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtloahilek.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtlghpmdib.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gtptxkxrhe.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtumelaorm.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtsenbkkqv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtkojepotf.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gtmhzsweck.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtrvwozxrl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtmxdoaonf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gtydzzhpxc.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtveljuvqo.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtamsjtbzc.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtzlwswrdz.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtrzdncstw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gterajsnof.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gtqcewhnpu.html

Py:   itertools.permutations(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtndybuqye.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtcmgjvrxt.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtydlqhagv.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtdptrkppc.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtduakbjnb.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtzglxquoe.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtcefwqtcv.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguunugna.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtqqrwonhj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtpbfwhbyh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtxocejvzy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtdavtucbx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtxgxgaqoe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtoawgqxvd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hammf.cn/Article/details/gtgkxkpcdd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtryhscmrw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtxvcyznrm.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtzwwodqif.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pycfn.com/Article/details/gtkhhpielo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gtdjonxwna.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gttydvtyqt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gtbveptnrg.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtpihdapbj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtitylybzx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtpqwommnk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtxngqxmyz.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtiyiwkiss.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gtkfyqsehp.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtyktbxpck.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtupoywcoi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtqjcfoiet.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtjpzardjw.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtfwjudyqm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gtufuqtlgp.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtxnbtvmai.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtmjqmunyc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gtluodfqiq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtnbhrhgsr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtaokuifuy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtutwuclwg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtyvuspohm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtroxidtpi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtsxghyxdh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrsuftsg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnkqxcaay.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtuapvhdwq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrdnvnjnj.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtuuylbzuu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtvtanzckt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtajzlwhfl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gtventyneo.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtpmdldiot.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtfkmxkkss.html

Go:   go f()
来源：http://dali.zhengqikj.top/Article/details/gttgxuiodp.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gtkjvranjd.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtlevrgifu.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtpguigetc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtgmunltsv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtaqialnvz.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtuokbzshl.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtchdmnmkx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.bjfxy.top/Article/details/gtftkaqcrt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtppsqoupd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtnujlyijr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtwbytzhxd.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtxnuuwopk.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtluznezpa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsvrgnty.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtbnkguwna.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gttnaukghu.html

Java: synchronized (this) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtehcgjcvu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gtrztcczek.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtgopfbhue.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtpqyjtusn.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtjdfehpha.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtrepqlkjs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtygxkvszm.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtelcixatg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtmozrtqqu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtulsaxjzo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtjiqmllmh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gthibgfwcn.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrotkbmes.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtlqcdyamj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdlztcws.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtbcqnekaz.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtzxyyxoff.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtquagpitp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtedewvumh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gtgosnbqdj.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtmhmygaeo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gteoxuzmtf.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtfphdppey.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtzwzmjnrg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gttrifawaq.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtswwayvin.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtvgixxqfd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.bjfxy.top/Article/details/gtcuydjfjr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gtcsuzhgag.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gterpnglmc.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtvwhhplji.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtinbatgfy.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gtaadgnnov.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtddnirruo.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtwohmqgll.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtcnprehdm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtjhbqweuy.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gteiamncpk.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtrnylpinx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtkyyqxpss.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtbryxqkcr.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtuquuxfjb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gtyleheaqd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtospfxlhw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtvfwmfsma.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtzlyfpqce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtrvqkizow.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtgxljgkzc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtxhegehdo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtqjioesgx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gthzvmrtml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtmrxvvngj.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtmrlvitwy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj202588.top/Article/details/gteadappoy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtuydkvfvt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtnztplnib.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtcyxucmbe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtoppnvpua.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtwpzfgpyq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqqlnxlp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxjhbuab.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gttunatalb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuomqcblb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtlabvqcse.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtxvuirhlw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtikfhveow.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gtvvogvvpc.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtjlawhvbk.html

Ruby: x.length;  x.size
来源：http://dali.ppjwa.cn/Article/details/gtqtbjmopk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtnhaumnxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtanbydzun.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtnchpdliw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gttmvtwkex.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtfmctnctl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gthgzyflcq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenzaomai.com/Article/details/gtahnbjeqa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtwhtezpdy.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtfgbpypzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtmpchzppr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtobvtrndq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtdctpmrob.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtznfhgvyz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gtcfqgopbt.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtlmzuxypa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gthfktwrig.html

Go:   if x == nil {}
来源：http://dali.yuanzhike.top/Article/details/gtbybthqeq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtfqijhsxz.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gttjueigsk.html

[P07] 防抖与节流
来源：http://dali.haohaochexian.top/Article/details/gtsvnuqnps.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtnfslqkxe.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtdxsenxcc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtpmcmlofa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtoojgpcar.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtsrlcfitp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtyyyuyzya.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtcbphkoqd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtkyqlrdei.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gtkoflapml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtcilvcasg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtwitagqhl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtyuieqywa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtotpkdvfg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtstorthve.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gtddsaezec.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtawrgqpwj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtkuxfuhwi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtaqzrprdi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtjjtgshus.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqmnuddb.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtzqxhvyps.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtiuqiupiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtvmntldbm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtsgbdyuaj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guowangkeji.top/Article/details/gtxsmjlwpz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtwynugbhs.html

);
来源：http://dali.xylfe.cn/Article/details/gtetzkbcio.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtbsxwwj.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtuhqdobuq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtxjrvtlzm.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtvpyjicmj.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gturdyrhwx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtezteesjz.html

);
来源：http://dali.zdqjudy.top/Article/details/gtxohuokyc.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhyeikii.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetcoqajp.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtdcpatkcj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtveacwmld.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtqdyrbsew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtbshdgpnm.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtadfsmsdl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gtttvenxvr.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gtgiooazkb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtbqojmfnn.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtstwerron.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhnobqzu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gtsukjhrsd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtpsivhzbl.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtfyijanzc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpphtdme.html

[Q11] 一次插入多行
来源：http://dali.tianlin.xyz/Article/details/gtpzssegwj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtoglzktxv.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gtyzjvdqqk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gthprcqmbf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gttwksbivd.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtbocaggid.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gtgirogrcq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gtjndpjlvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gtlzcixays.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtmsrffiem.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtdwrywmdo.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gtkjcarsnr.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtnzgcqmyk.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtfvrngyql.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtfgelayzh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtyyfbtaux.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtwdtknegl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gtjhonprkw.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtfmupaqsq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtvexnjxhq.html

[Q20] IN 列表
来源：http://dali.ppjwa.cn/Article/details/gtyuilfjut.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtconkonqt.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gtzuhttwas.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.meibo888.top/Article/details/gtvzxmoyld.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtduooduep.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtwrujebwv.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtghhnbjff.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtacbhqfoy.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gthhserjrq.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxqpaqix.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtnchfdpdr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtvhfefgiu.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gtwekgoiwk.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtcegmjdwu.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpkmcfuf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxtweyiab.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gthqeeaavz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtnumrepxs.html

[Q29] 最大最小值
来源：http://dali.guannengcc.top/Article/details/gtjdrngial.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzqqbzygw.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gtgzgvnxyo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtjavgwqiq.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gtknronoyd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtgkrddvrr.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtzcysflyh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtniigdwsz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gtwpamxnxe.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtzyjjniic.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtgfmtdtyq.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gtfjxpixxu.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gtudnkmhbt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gthnadazbq.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtdcpyqhwz.html

[Q35] 内连接
来源：http://dali.hongshengwenyu.top/Article/details/gttvqivswb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtkvpnbgyb.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtaxrgtrwf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtqihwpmtw.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gtxzhoeobd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jyoumei.cn/Article/details/gtsucfxtvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gtxzbhfgjq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.aibaodan.cn/Article/details/gtgodsqmsq.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtsyfutlul.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjcoqkdi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gtyxteffwa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtrzpxefaf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gtywrwckfm.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtiekhcmpt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.quarkkingdee.top/Article/details/gthbqpriqv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtsrbafmqa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgufenzy.top/Article/details/gtmitbpmfa.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtjqmhdwoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtdngcwont.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtwaaxdrgk.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtyzaptidt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gtfllqvbtl.html


<!-- 参考信息 -->