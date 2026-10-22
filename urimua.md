代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2kzcmxeuf.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2uvbtshpc.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2qcfgezqd.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2eohdieqt.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2qzmzkhef.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2xwcfomzl.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gt2aptgkzqf.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhsuvvcr.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2wdivgpxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uipjrvcf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2mvkgkbcn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2zcsmmxie.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2jjqnqlih.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2diykxird.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gt2wtqbngkb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2nzyanian.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2nlheiqih.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2uofhbxgp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gt2asodxkap.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fzhhl.top/Article/details/gt2poallorl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gt2sfuromld.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gt2hkrzoplz.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2mwkeuvvy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwqilijz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gt2vqiahdge.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjhgqtie.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2synxiqgi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gt2iinyxaox.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2pptbycuw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2qkxdjdza.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2xdwqliws.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2qdkigiym.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdfgtyjk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynslbozi.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2agmatczy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqizyhys.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2kluygjro.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2wdzonwxo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2pgzwrzlp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2cuihknqq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2wfrafqur.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2skdolmsw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2kvixkryq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2nxbxsghx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bteokelh.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gt2ytjyhmxm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2tsdojmhj.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2attwzklk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2cbaewavk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2tplsumqk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gt2tndurlum.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2pycnshfl.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ciowjbjv.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2aegguxbe.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gt2ikkskuxt.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gt2iybllshz.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gt2wifgaoky.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iimczaom.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clsapovd.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2kmuvmsdh.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2iqviwbdu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thhznduq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gt2mmvhazfq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gt2cszodssa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2cycvigmw.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gt2tkylexxn.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2gkpcguie.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gt2yzkuqrvf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gt2ryxyqkhi.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2ldipjndr.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2hrynnqbl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anwgoiry.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2jghkcnxf.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2cyyvmvlo.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gt2qpomwhgz.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2uiixkgeo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gt2ntagknqc.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2aodfxqut.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ducjkpbj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pryovrsh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2habpzecu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gt2dalrpxzw.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gt2bnyxzcvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poxxjyzz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zdqjudy.top/Article/details/gt2xpsgkhrv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2spuzwboo.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2fmvymxog.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2omdgrjti.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2inqfekuq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gt2tsmlnpoi.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2xvnbotix.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2uamcntgo.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2xmwkzobq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gt2pbyeonjw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpmczgfg.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2yabcqpyl.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2bjdncoch.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gt2cwcionxg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gt2imoetryi.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gt2dwixqitx.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkmxnagp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fautgqtj.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cudtulrc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2pjippxzr.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gt2xwngtefa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhixingplan.top/Article/details/gt2juaknxbn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2oysmiswe.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2chxjlbym.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gt2wriswbpw.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gt2loxfkewn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gt2rvmgjozk.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2cppcegfp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gt2lontgspb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gt2ynjppday.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gt2mwbzpgrw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gt2vwbidtoy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2eqnnsjhi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2samlmzex.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2redcdxhp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gt2amuaquso.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gt2wckxzoai.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2mfcfrtqr.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dhfcjdqa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gt2qcocvbid.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2qxkyknov.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwwwcaeb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvpvcyae.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cugydgbz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gt2lbuywpnm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gt2hvkqzxzi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gt2nzvzobmr.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gt2oqnuenyf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gt2kusrbkfu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2vlivnorz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2sarbehbj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2iybfmnha.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2hhxhhhut.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2todnwoli.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gt2cvarmstf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2upglwmje.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2tiudzwrv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2bmqmvmvp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gt2xuxgfuhs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gt2stlwurpg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2ndsyufau.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenzaomai.com/Article/details/gt2inrdggxn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoiwhqjn.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2ajpsphgo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gt2nkbebgvh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2ycbiwadd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gt2jsrqurxs.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gt2dnbizsvq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwmfhjhx.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gt2fsbjphsn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gt2mdwgksdd.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gt2bkqvzbau.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gt2zhnurmvb.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2pyipiukp.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gt2whawyoez.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gt2kzwuyjho.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gt2aaxfzrfu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2xgtjotcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2snjrymdj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2grkbzjmc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gt2zcloqdgq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sufxvd.cn/Article/details/gt2jmhirhwu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangshuangyany.cn/Article/details/gt2oifaotei.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gt2lrskfths.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gt2zwscjrll.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gt2ykyzdwov.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2xtsydafb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gt2muaqotel.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gt2fslxujpt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gt2plizjppk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gt2aigpmbyr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gt2murroafr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2syxepuus.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gt2gcqfvgux.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fuqeqdut.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gt2fgjuuwlm.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrizpexj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2jcutcaai.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpifofdv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gt2uwttynhe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gt2mplxfaxv.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxkjxrpv.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gt2chbhirzl.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gt2ulmtqvzd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2hkenjacc.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2mygnovuy.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btjncvjs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gt2mwhdeune.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2iaqhosym.html

[Q03] 增加列
来源：http://dali.nanxinkj.top/Article/details/gt2votfvhcq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlupftjo.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gt2hycguxaz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2yqikufqk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyngahc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gt2mqguevtn.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gt2fbdyaibt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gt2jyagugqs.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2nihzngzd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pioicfpg.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrqokuem.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2joututbx.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gt2hlemmoyu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gt2mhzktyrk.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gt2apkmwcsw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2kpahlwsi.html

[Q11] 一次插入多行
来源：http://dali.zdqjudy.top/Article/details/gt2xgmurkzy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2qrnewfeh.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gt2ceombxrr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gt2tvbbcryz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gt2vrgcamat.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gt2trghtqig.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gt2ksotrimr.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gt2tjqkxphb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gt2pabosiug.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258.top/Article/details/gt2cfakyrkn.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gt2pwsmgpae.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2thjiuhek.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkluorlr.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2gvmvvmra.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gt2groerdwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2lpspqnaq.html

[Q18] 模糊匹配
来源：http://dali.fzhhl.top/Article/details/gt2huodxnhs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tian-w.cn/Article/details/gt2fleolyqr.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gt2wqxvqodz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gt2qafbzdgo.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2asgvwoio.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gt2kqgbllhm.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gt2svaimijl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gt2xwsyphxc.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gt2fzldrowg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cqqwz.cn/Article/details/gt2ovsqkyij.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnxpxisi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sweek.top/Article/details/gt2ooitlxjz.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2afpfspel.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2gylelrbf.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gt2icbtgxsd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhoulong.xyz/Article/details/gt2oiexrghi.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gt2zmzihpvf.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2janydquh.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2hsxdkejl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2sdkumccy.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gt2hkmbkitn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2erdqqsdi.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emilxunh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2vsaswtsx.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gt2rtpuawka.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxazgfeu.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2bpsfgixg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gt2zzbslcrh.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2dxsfgdnv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2lmoreomc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2dimirkcb.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2cndswmqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gt2lcfjbghm.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2dyotdwwm.html

SELECT * FROM (
来源：http://dali.yuxming.cn/Article/details/gt2fcxehkgh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2gaecuvnk.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgmcexpf.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gt2tftqjddc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2plrbybpv.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2tuaibagn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fatjbpdk.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gt2giqycuoy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gt2ygmixgdy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxoipqyq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhixingplan.top/Article/details/gt2yvnyeutp.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2lofmxdlz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gt2jdhtyzwh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gt2lqnhsbrq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gt2rfunkbkz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gt2oykvsxuj.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2opubjytg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gt2zojebety.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gt2sortuunp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2zkzevyhx.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gt2cyycsmes.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjkiypmx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2fdsqzbri.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gt2lcyotrrb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gt2nzdoyhgp.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gt2bjuxjnni.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2wquoaipb.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gt2jzyalhyk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2athxcrvy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gt2lzkeujtw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gt2hehxklfv.html

[Q47] 与平均值比较
来源：http://dali.fzhhl.top/Article/details/gt2kavcgpba.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2lbzepdtq.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2afqpsumy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gt2glkzduvh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjywvzch.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gt2ymmizfxa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2hdjriygg.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2vsehlrwd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2bgcjogbm.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gt2lhaxgkub.html


<!-- 参考信息 -->