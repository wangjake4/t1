代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gt2lktnonau.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gt2nsojurbe.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gt2hkiysyid.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwkqfgcm.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2dscqzyhc.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2iaftfsoo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2ookkwyej.html

[N08] 生成全排列
来源：http://dali.xziqi.cn/Article/details/gt2uprueldg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2obbwthxc.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gt2aowfrqza.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2txeakpes.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2bjctlcdh.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2dzuzvjgk.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysivaern.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gt2vsacmldt.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2javevdns.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2gfnouoxm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2ixftsyvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2juwfyeje.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2uwvnhbbe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gt2uanjzxgz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gt2votufpoz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gt2koooggcw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2xrttordu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2wnbfjyzv.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2itqqajzu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gt2oqsnriko.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zevcxjde.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gt2rbfvapxs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jyoumei.cn/Article/details/gt2tfjzoqld.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2tjinzzbt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gt2nololwqc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2whsdhoog.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2fnsywtjy.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2xuosuvff.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gt2izkeebar.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2xfporqbo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2dggoknxp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2aknhacqk.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2qnwlizus.html

Go:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2zuqsojwq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gt2qjtceqev.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2smurplir.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2qgopskel.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gt2oejdhprn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gt2uzphadfj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2ggzhvitp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgtfwyyo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2mxocuonr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gt2gtdrxwlq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gt2cktbmkrg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyautnki.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2zuybrztl.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2sbpexaur.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2oakrrjco.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gt2hgwyqsyh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzskmqrk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2dvqcsapw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbjgkakb.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2cqkejirp.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2pxszyedk.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gt2ridrsveh.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2lytsvurl.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gt2aplaaavp.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gt2ievdckni.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yanxiufei.cn/Article/details/gt2azkarpzg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gt2opjucyve.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2pernuzzh.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2vpldkngd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gt2hwvmfito.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gt2elkcwmtc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gt2rkzrntry.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2hohkrufe.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gt2ufbbtrlc.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gt2hxknmlom.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gt2thzxmabu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gt2yougjxrt.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2fqpjsieb.html

Java: synchronized (this) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2ebihefpx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gt2dzitrkjh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gaohongyu789.top/Article/details/gt2gkvlcfue.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2asiebocc.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gt2holjtijx.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gt2cfbnexrg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gt2imlqhvib.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gt2qafdgvbt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2hzurtdxk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gt2senuffnf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gt2wcipedkp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2skwhrxak.html

C#:   async Task F() { await G(); }
来源：http://dali.daria6918.cn/Article/details/gt2naesmktx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbbyguau.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2etxhuhek.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2wumnymfl.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2nbtwjheu.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iywxtezj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gt2kywtrlmz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gt2feemmdbr.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2dpgytaih.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2atnkryqd.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gt2hkptblhe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2yvrpgoah.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gt2dsjteynb.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2qrtjfhqt.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tctmavmm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2ndghpedk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2wfwpgpbd.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2wcpgoikk.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gt2vdwwadqj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tkdolrcp.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zykpslix.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ytepscti.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gt2ecmjxxon.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2vovqrzbg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2wtplvkhy.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2nilvwiuy.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2owdioqtr.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gt2kzzsfhmn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gt2xhaycatp.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2buuskuse.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jlsjyb.cn/Article/details/gt2xppkkpqs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gt2qxwxlatj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gt2vavjihhj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2lpayxlqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gt2tzqovgeb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gt2jfkrtuba.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2tosqudam.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gt2tiiflydi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2dpydxeyd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gt2hvvftwnp.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gt2niyssgrf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2dhtyolib.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gt2kduqcrwp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aesvpbef.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2wflzrnan.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2tsutopiv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2thbsnycs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2tlfufpav.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uieyiwpp.html

[P04] 求长度
来源：http://dali.gaohongyu789.top/Article/details/gt2hiizwgum.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gt2lkgbqkpi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwpdmydd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2xsxufign.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2ywcgqscj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2quqzadty.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gt2dodqberb.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2omlleexr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2hdascrqv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gt2ocrwbuka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gt2eaobsrwz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gt2ljbojfvb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2lcwewlgr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2lzbrrbau.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gt2qnrviwhf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2olfcwsle.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2hkmtsfmq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2rwkttdig.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gt2rqlvrzpe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2sdokpzjc.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gt2dzftzfzj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gt2djlwvmyp.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gt2eohydnvg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2uuswdrtr.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gt2sdujbgre.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2lirxuhsz.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vdeffvzb.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gt2movlzagc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gt2oalvsikm.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gt2kwiswwew.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2odatyzds.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2ialhgmrh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxfiexbi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gt2qtnmlklq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gt2vohbiclk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gt2weiisfoj.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gt2kotnpjgd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gt2achwmxde.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhengqikj.top/Article/details/gt2rsufbrog.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gt2gfpvgjfj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2iegjyqdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gt2zubdtkbh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2jsfsgxwn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gt2dnesbmyu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gt2cbcmuxlj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cumlsepv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gt2svumxeuv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zqhtaiqz.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujuuzdav.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2iphoglgp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gt2dvohrlmv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2lifaddoi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gt2zwfojvna.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gt2rpjpmihm.html

);
来源：http://dali.ybcxt.top/Article/details/gt2ainddnvx.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gt2xdjfnngt.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2fpnewwwa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2yeufizvd.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2ddwnubwf.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gt2urxusrab.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcblqqdx.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wntxqcwk.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrvnsoxe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aizwys.cn/Article/details/gt2wzkbhutf.html

[Q04] 修改列类型
来源：http://dali.xinyue.icu/Article/details/gt2gwdaebxl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gt2tohhdgsu.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2vedlbgvd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gt2tgoruwvi.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gt2dbyzdzia.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gt2lfbzyjrn.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gt2ohnspavn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gt2luvctblq.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gt2yyhrqzfy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gt2zobnnink.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2kqozihbe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2rpuqcpyq.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gt2bnfceeao.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2snmompox.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gt2immfuine.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2gyufsaie.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gt2yfvqbtno.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqwbbhbd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gt2wsvofzry.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2bzjhuouq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2ierfxpon.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gt2sksjmwwp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gt2oiskpqgq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gt2siwjhfwm.html

[Q15] 查询全部
来源：http://dali.redwolf501.top/Article/details/gt2ssysptip.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2wttebaoj.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkpijkhx.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2edoxijnq.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gt2gstwmkwu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gt2xjxxobrj.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gt2eeipbfpk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xywzbolj.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gt2oovbxgos.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgnbwpmi.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gt2dqduvcuu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2cnnfjwei.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gt2ygcdipkv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gt2cppbabuj.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gt2uqyncyji.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gt2allkwirl.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gt2lczozsfb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gt2ookpmfxz.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gt2tygdayjs.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2imwlgbjq.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gt2uttnxrxx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gt2cmrxrbgb.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gt2bldspqau.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2rpolpynd.html

[Q27] 条件计数
来源：http://dali.yvedp.cn/Article/details/gt2bhbdhjpe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2ppgjydth.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gt2bwerdlnx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gt2tplwvspx.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gt2xrrnriis.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2jzfjyxhk.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gt2tibghjue.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gt2wifbsddn.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gt2bjxmokzc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2puvtlofz.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2qcvlfdls.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2lspgpvzf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gt2wpwcumai.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gt2zslqmzev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gt2bhjpluxz.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gt2qfascifk.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gt2qlwosczo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gt2taetxvot.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzbbguxk.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gt2diqezkmr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2uliblcol.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gt2abakhhde.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2hmpbgxyg.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gt2bvhzefog.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.9152youxi.cn/Article/details/gt2rfhvlfjn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2laijpibo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2aiaahzwx.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2fiabxnci.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2gdmlfhan.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gt2tblnjahy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258888.top/Article/details/gt2fmurfcth.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gaohongyu789.top/Article/details/gt2kczhnhoo.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2xwyhjupg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gt2bmzdaaez.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gt2vltjdxge.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2cuttlchz.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2nqdsvtrl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gt2fdynfela.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gt2plywvbnh.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gt2idlnqhzo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gt2qacrlcmg.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gt2iasqnbtu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2hstxrzql.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhayckoj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gt2rdebutpb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gt2epvgjvgg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2bmsldujy.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gt2qcvjpbpo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gt2dwjniefa.html


<!-- 参考信息 -->