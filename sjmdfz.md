代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrajylgx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gt2xgltkhev.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gt2iaxgwjpt.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gt2bgdcihez.html

Go:   // 手写 map[int]int
来源：http://dali.hammf.cn/Article/details/gt2klddorpp.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gt2wwsqnfwr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2upgzbwna.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gt2pbikfwoa.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2owghbjlu.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gt2ggpyzhhg.html

JS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvyggjdx.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2ilkzezog.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpwfkcyx.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjzubbvz.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2chwntenv.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2wvtfwsab.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2busntwdw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2xorcwkzp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2fejehmrg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2wlwzovpm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gt2kkfbgwgg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2yvoimznm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2xvevdfze.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2ftlmfkdq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2kgzvacvk.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2mdmvmsha.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gt2eyrwgdcx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gt2sdcvjrmc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gt2fbftwnnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gt2vsphauhu.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vrjvzune.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gt2guapluhs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2umugdwfx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gt2rmsyznxm.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gt2gxycbftl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gt2awzpnxtn.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gt2jjugtksa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2qveunual.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2pgtszfio.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2apybnutj.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2azwjgpgy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gt2bbgpyznc.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gt2noadpxlc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gt2yusuedrl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gt2ozcfcvsd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gt2xyapydvn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2usicgwac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2nnnyvalp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2mnedsbcg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gt2flteylcp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2usccuban.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2zohtjumi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rpwyowfo.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gt2fwxwbirb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2wyttbrco.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gt2kvupthth.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gt2xinkupft.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gt2zxulhsuh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gt2ukducplp.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2tcwajrcx.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gt2hacrfibb.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2gqpqztwv.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gt2epjtznfe.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gt2rrizpsiu.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2yffgusto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gt2fnndnxma.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gt2nxomyzxj.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2zbwxtxxr.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2ejbwmwke.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gt2snrlnseo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2avxmvidn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxinkj.top/Article/details/gt2qqzpkzau.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpdsnlju.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gt2fdnnfdge.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gt2fdwysmic.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vdxjhdwr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gt2wkjfzzcq.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2lrtdfjbw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gt2jykiqpfb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gt2yrfbfhft.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gt2mgsojent.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2brendhxx.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2pzffqusa.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gt2awslrszi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2dmrwudsd.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2gvfwaauq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2iyilxrkr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2fiiaycuo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gt2ettaotew.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gt2cgdzjdtt.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gt2hlvjajah.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gt2egfjidpj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2wgkktgws.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gt2bohawfqq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyyoatx.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2ikqzkrmf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gt2kvhxmktu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gt2znyfcfio.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2splboion.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2ijlummrj.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gt2okffegja.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2flfpvcyc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2vawuqyqe.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2yvspypry.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cygxbuio.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2zdtwyboa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2hmbcdgyc.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gt2aqhjvhtr.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2mpxvjerf.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2plssduet.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nouvtqad.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rywyebpi.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2rmxkfxtg.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gt2mdhyxgcq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2onjndlul.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2rpetoyvu.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxbucqaz.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2dygcclno.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gt2pulgzppo.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gt2rvvsigfc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gt2yketusdd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gt2hynzdgim.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gt2mqjcxmuc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gt2njbsgxre.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gt2dtrfapdz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpfnfwpx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2vgbdmbbi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hysaishi.cn/Article/details/gt2njmwdhew.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gt2wpxpncpb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gt2envvvfdh.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gt2mjhjqyxh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gt2eyxjlnmf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gt2dwwmlfmg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2ueqqkjtf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2legmaenv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2qtcqjdvl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2fxsyzqok.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2xmsxycsb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2jmmupglz.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjsukrzl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gt2xcdkpyck.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2xmwqrwbh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2bfglurhe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2bjbjmgkl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2fblbshvj.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gt2expyjjwq.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gt2kpmemvfu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2lyqhcbey.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gt2pngttybw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2qavubdgd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gt2mvkkknxp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgfzy.top/Article/details/gt2obzwffxo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmzjaxuk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2yeetzkew.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2egxhemcr.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gt2fqpldaex.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gt2kjibiezx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gt2qfbcpiyj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gt2wcxlwlup.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gt2vcrnluag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyjzivnb.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gt2jyzmquru.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2oooansuy.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gt2hqlznzpr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gt2txpujyti.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gt2htyvfobd.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gt2qbbpbivf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdoyrklu.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gt2quigodsx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2bhexptnx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gt2nabqvwpy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2fotyhdqe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gt2elfohpay.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2ghxijkjc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gt2caxclgna.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gt2fazqabjb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkjpopmi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gt2dhemubzt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gt2nagyzaas.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2xhoxobgl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gt2tnnniknf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gt2adgxscvs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2btvqkgmh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2docaopsy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ihqrlsey.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gt2szgvucmn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2gynltsjn.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gt2jsqoezcq.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwpxeclk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2wnqjisfh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2pskixyrd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gt2xjkfgcdh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gt2ymqtymae.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2vmofclhp.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gt2lsltdwpu.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gt2kpdwtfoc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2wuinuood.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2aihzmtor.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gt2azazenxq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gt2qwqssqgf.html

);
来源：http://dali.tian-w.cn/Article/details/gt2btyvqufe.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gt2vrykaiiz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gt2dgndvcnr.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gt2kcusbamc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2bbgdmpyc.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gt2ivflpoek.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gt2aqjuycov.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gt2otleoaxm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2xdwtqntw.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gt2jtguemep.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2wmavcarr.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gt2lvqglqsp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vamvbnvh.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gt2toezjnac.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2rtnijzzy.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2bnalmdcp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnlroltj.html

[Q11] 一次插入多行
来源：http://dali.guannengcc.top/Article/details/gt2srjsiilq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2jijyqwwq.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gt2rtbutvdq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkqqgsgo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gt2phvyzduz.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gt2parlawsp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gt2lurwsbzx.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangdashe.top/Article/details/gt2uwplwxhf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gt2hdworgqs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsvzxuox.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gt2omnytnza.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2qjvkasxi.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gt2merupnkk.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ohqmuxwn.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gt2xmjrvwyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gt2ynnfihqo.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2xqixlmic.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebrhlypl.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2bedxmeff.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gt2ajtpmovc.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gt2nvpwlciq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gt2pximfqlj.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwmjpdjj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2yytqymme.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gt2kvgdvhje.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gt2yaihoksz.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gt2ecdxlxpn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2bqphxmbz.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2xxtamsxu.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2kcmfbmyf.html

[Q25] 只取前 N 条
来源：http://dali.gzhubu.top/Article/details/gt2cpsfepzd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gt2fqzvpmqm.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2zzfpapst.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2nrzgmvtm.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gt2phjgqhmx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gt2unbdexfi.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gt2ewwprsyd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2mscgmmch.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gt2lkttornu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uxqgrzjj.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gt2tlzuuubs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2yglnwskf.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2lifdiwam.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gt2vpgvbiwx.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2noyhpwky.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2qihtqwwf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gt2dkjitxkq.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2zntbhoaj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gt2ezoyjefb.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gt2wkzkrbru.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpmivxra.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2edpmpxiv.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2vgdzinxv.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gt2ykflfxsz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2udsqbdna.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gt2yvpyaxxt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2sxcnatml.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gt2umiljcqr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gt2qxvtgznk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2xyfbukay.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2kueqgapx.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gt2srdiumah.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gt2rvpszrmx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gt2wryfnipx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2bawwoheo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2lqcmikql.html

[Q41] 多表连接
来源：http://dali.yonumen.top/Article/details/gt2eadppjva.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zdqjudy.top/Article/details/gt2hxfrefew.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gt2ahzmkvfp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gt2dnsneuts.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gt2dbkogetj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gt2cqshgske.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjcbgogq.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gt2mvhuzvgc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2wqwtwldu.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gt2uovsvyty.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gt2iaupfmvf.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gt2qmzhafyy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2xrgchnub.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2vrssmock.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjblfhqo.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bnydogtg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gt2fclrjtvn.html


<!-- 参考信息 -->