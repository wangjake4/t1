代发 wailian999

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gyffievo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2uifajnnh.html

[N07] 两数之和（返回下标）
来源：http://dali.hywenlv.cn/Article/details/gt2blbuuosh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gt2tlvvgcnp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2pazskjrr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gt2hhebriia.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2flfojiqn.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2wxrbeydo.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gt2tnjjcxmc.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gt2ktfbamxa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2sxeksqig.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gt2cobyclie.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2olskahpv.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gt2rrtuarvn.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2xytctrwl.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2ucvrhjvb.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2zarspesm.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2duhzatmt.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gt2nxcxvonp.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2uxvbkvuv.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2chkiibmz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gt2tlmpudnb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gt2nwphommy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ufifftsu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gt2ujotmzvn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2zjmiatlc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2iiedxrld.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2jhteyzfd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2memddvel.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gt2hhdplqyp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gt2ythwyoqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gt2nsjitqqd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2ljmiwwak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gt2rifhqsur.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wsbcoirj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wecbqxry.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2ttpliejp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gt2wfpdgkpk.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gt2cjncfdhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gt2zegjavig.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gt2dwguwmju.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gt2ngdbsvsf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2oduqsvlx.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2nxjmupdk.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2jzolvwlb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gt2xljcnfpc.html

C#:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2furqzzjt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2cmjgdxpj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2mhatltkf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2wrniglvb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2nuhpxdpb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2mubuvtvq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2gddopskg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iptjoodi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2rlamhzuz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2bfbeinbf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pszbuonn.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gt2hbsyeuqt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ygcmrxhv.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2gwponbdr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gt2xaqwjpzs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2wwurfjma.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsfafbng.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2mphzvsnu.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gt2tfngwliy.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gt2kcultyum.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gt2mqbawghd.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gt2cgokbanz.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gt2mxthlccw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gt2hqtiqauy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gt2ecmfynoo.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2awzanxiw.html

TS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gt2wdadobpm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2tlwnlirr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gt2ignzyouc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2hgcnrbrc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gt2xvsdhxaa.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gt2bjxajoyw.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ybcmvgym.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gt2rzeqasvy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2tdikkbsh.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydxmnqii.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2gwoxkpze.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gt2hvsjnrex.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gt2mkkqlkoc.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2yqokscgv.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gt2bgrzcsqc.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gt2slcrkzmn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gt2gftmqbum.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2kciwtsxi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bcrtvlbh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2nhdzdlnj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2jcsuwujs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2jipiqptr.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gt2zkiarjwo.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofyukvyv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwqfgkqd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2uedlrfyl.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2zxklshkg.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2fiunkefe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2iezdlrin.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gogol.net.cn/Article/details/gt2eykiknur.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gt2quddihlz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2rjzoyzpk.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gt2bwabsmsr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gt2swiqcyhy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gt2swvumfsa.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2xxocxyxj.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gt2skcbvaqp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gt2qiyqlhga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gt2mxkpinkg.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gt2hrsoleve.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gt2jcviaqnf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wbvmpobb.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gt2aizmyvhj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fbixtudp.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2xdmuwign.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2fyoboogm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtkjjtdd.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2mifsolgb.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2tzkitowm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2iccjkzaq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2ymdpeiyx.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2kuorootj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gt2xacqyhqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnqzz.top/Article/details/gt2wzdavvls.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2aiemmkpz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gt2xdzccaqp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cashguo.top/Article/details/gt2hxykiwmx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gt2dagufxxe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvorbte.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2ogseftvr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gt2qudnfoce.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gt2guxngzge.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gt2ynaxcogi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2edipkmqv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gt2kbvchche.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qisifoxl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2potiqwwd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gt2cjnbbgzd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gt2edifyavo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gt2jeqemslk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gt2rkixdmeo.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctlhhnps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gt2xcojocua.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gt2mhqyjfht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2ljtbkpbs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gt2wlllhqxm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvclzjom.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gt2uofevgwz.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gt2fiizvqlk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gt2yqoudwpp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gt2wbjyvljn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gnomsczy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gt2vxkjqwcw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gt2qcjbquvn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2oavhdbty.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2qpcsmlkb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2bwwwawfx.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gt2xfndwcxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gt2tdqlsvqc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gt2wisavabb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gt2jwdcpjug.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gt2bcwxyyqs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gt2vwfqlxpj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvffotf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2jjbpvmhe.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2oaznihev.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gt2vwoutvpy.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gt2kljrhadw.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gt2lbvbmxcf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gt2ofknxpkf.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gt2cpsdgxfy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2jhmlngcb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2fidoxezi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qhnyzanm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pycfn.com/Article/details/gt2ciekbkdk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2omfdaoco.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gt2jpcveaqj.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2qtlhogjd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gt2vptcrldf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knvekhsf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gt2flvzdswa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gt2qcoddduz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gt2iairkkkb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gt2gspzyqhf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gt2ymtyvzos.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhvygyhp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yfxdtdah.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gt2gijvqhim.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtegxych.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gt2fxjydokf.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gt2uqxzrfze.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gt2ybgmnvxp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2iwnuxypm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gt2qtwwarzg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gt2asahaott.html

);
来源：http://dali.tian-w.cn/Article/details/gt2itxtyikf.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gt2kdowzhvh.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gt2zwmsurcd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2ulcnwqqx.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndgejxza.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpufjews.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2qkedilaj.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2rxolfilb.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2bdlnbcvj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjpjsngc.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2ckitsszm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2doufpahq.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2bpochagz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gt2gaathweu.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gt2hddjrnbx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmpegjco.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2feoouhfa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gt2veinzfwq.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gt2cgjvuxqs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2vwtuhekm.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gt2bppgxcsl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2jfyqbwwq.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gt2dvzxakbx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gt2pfjylhgw.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jelvxvot.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2uqhpwxbz.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lnnzlpbg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejjptvmw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gt2wxrqkqzb.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gt2pureehat.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2guuswfyo.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smakdzvf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2olbfqbtx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gt2ouirjkfm.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gt2pwbnuriu.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2rzekhhtb.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gt2uxnwbgxz.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2hyktrgnz.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gt2xioqseph.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gt2puoibpyu.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gt2vdjmbtrt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2czgmoyem.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gt2opdkspck.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcdsfupr.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frtuyypv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gt2wxwtwqcy.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gt2cqfgnjdt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gt2fccuialu.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gt2gjjvtnhi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gt2vhznqqta.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2fjngzjrc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2kzrtctjm.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2edcstwhv.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gt2qfzzbvxx.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2oacfpiak.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gt2jyemjipz.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gt2ovnejcfv.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2jkhvsmrk.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gt2fgzysmcu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvfsqtkx.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2dxwgljby.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2tbhnufal.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gt2hzqphxfn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2quckbdno.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gt2nvoixuuy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gt2uhgozxpi.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2uvpdtjft.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aibaodan.cn/Article/details/gt2zxjeqrie.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkrtohim.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2smjqmvow.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gt2wmebaoxt.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gt2cjnurbuu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gt2qsjtrrbq.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gt2xqegvcdy.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gt2ficoauhr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxvmmuiw.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkhwjaom.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gt2jcymqkdg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gt2hyolyqla.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2etwohfhm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2megwawjy.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gt2bewlsowv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gt2wekeahsz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2yprqsmuy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gt2kyzuoyem.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gt2wuxfefjo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2uaolbdbl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gt2tkvilpui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gt2ymlerrkl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2gsvsxzta.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gt2xtahlcbq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhfhjyai.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2eujowzkc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gt2emckuzhq.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2jorcjrms.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gt2jtmpnlzt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2briesyym.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2nxxmlufj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gt2wpjjifdc.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gt2hsqmolgc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gt2ijrciypo.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gt2aivgqrdb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gt2xprbmnlx.html


<!-- 参考信息 -->