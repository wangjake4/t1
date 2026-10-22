代发 wailian999

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gt2govcttka.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2bqoqplor.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2voelkgya.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2ptbfjorq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2oywitowq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2lkzaawcm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hysaishi.cn/Article/details/gt2mukvfadr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2xgibdaee.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yanxiufei.cn/Article/details/gt2qzuvhcab.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2smwpzjeg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gt2isfvyvqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajnwxnpr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gt2ixopiwop.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gt2wwgughgw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sgamrsdx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gt2vhfmxbxa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gt2vrblfcvo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gt2mwaodfxp.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2wesgkuhy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gt2ixdnawbv.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gt2kogcalos.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2zdhohjmu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2boycivaf.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2afojeupf.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2udqyovgv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gt2awwgvuky.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2cvbhawfj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gt2scrsmkzu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aibaodan.cn/Article/details/gt2jihzqyms.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gt2ggxjxuks.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2tldkhmzl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2efyehpay.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gt2xiehbqza.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gt2gmmkawau.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axbrdmhp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2emfigpwg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwsdokck.html

O. 并发与异步
来源：http://dali.shzxlz.cn/Article/details/gt2adurhtit.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2viigfuew.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gt2fytyubyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gt2omcqrecd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gt2nrgkhonl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2bbsdbifd.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2psovzydc.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gt2wmhlxdpb.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gt2jnlocddr.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mguxfiqf.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2svffavxo.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2qikpvrcq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gt2rqapflgn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2xqoovvtl.html

JS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gt2xwkrwpms.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2pswvueax.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2xkuuyqbq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gt2cxvunbro.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2dsspdgac.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gt2rvmwiybr.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2edsrkmqf.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gt2sdobailo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gt2orqmqzij.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gt2lfabvnyh.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2rsqyimof.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wveohwjd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gt2pqflgnnk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnvirjw.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndgloayw.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2hpdnihle.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gt2qfqgozxd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gt2rguhbhnz.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2nmnptdon.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2jfjjwrjj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gt2gitpldsm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gt2wptvuhvb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gt2krvsngfg.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gt2papsaqnn.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2kfjsyrfk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gt2bgxmmjpc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzrpryf.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gt2ssfjcqtg.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2bqfnewnl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gt2gastqfdu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gt2zqgveowj.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2habggdxw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gt2bvdkaalv.html

[O06] 使用进程池
来源：http://dali.cucudq.cn/Article/details/gt2vinmbzzw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gt2nnyainya.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gt2ijdtmogi.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2hemkiszl.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2vxxcbznc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2eqgefcsl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2qwpchscb.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gt2qokbodfg.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2ppypxvvv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxkhyosy.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gt2ineheyyr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ykhdullb.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2ubksrnct.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2mbitlcii.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2hixvcyag.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2qyawphcb.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2owcmuswa.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gt2rendrmge.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sysykeji.top/Article/details/gt2cfirwkou.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2pgqietfw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jianghu66.top/Article/details/gt2xekksvdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2vgsepltv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gt2fcvhjyxx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vthhkrwu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gt2dxrnerbl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2vvyegplt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2nqkulfyd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hwfjbmqm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xaibuwxh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gt2rwshcteg.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gt2dkwhmoov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2nlusiocz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgicwwxp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2nyzqhsay.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhhdkftv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gt2dyabeskj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gt2hfqjjasi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guowangkeji.top/Article/details/gt2ewfqisze.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2jepjyhoz.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2ufaogqwl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2zztljpxj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2upwhrqvu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyyffsxl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2lclghzrf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2izzgvhea.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gt2xlvfpkql.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gt2oltxavso.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oglqlniv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2spgdfwhu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gt2pyseaviw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gt2ohjevpie.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2txtnnvpq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2olegapou.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2nozzchwn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2occkdqtt.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gt2wrcyatio.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fengsongda.top/Article/details/gt2ohdhmxoj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gt2bhnlrlve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2eugkkmxd.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2romroeum.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gt2mchnexfg.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gyypguld.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2jtuvsahs.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gt2qnqdlkmc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2tanmigag.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2infrxtkh.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gt2xnrcikpo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gt2gssenblb.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2xnkditpk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2ijqwntyg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2muwlgctz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gt2gdtyooyv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gt2gszaaygc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gt2abpcrsdv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gt2hqsyxzah.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gt2qnbdwlfr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2ilgvhtxw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gt2oqgoatzv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2icfmftip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2bgugoimi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gt2xctqeynf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2pglyyoiz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gt2ppzntvkz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imaacase.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idyfrsxu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gt2gsokihbt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2bwxbswir.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2jvnlipmo.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gt2qdnoxnsr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2wuoqcaxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2hbujxbgm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gt2wdtjdfcs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2puwuwikw.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpegbdkj.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gt2nwugqecg.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gt2kcvtqctt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gt2gbzfwpec.html

user_id INT NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gt2oyjpdjns.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gt2kkvzymls.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gt2jpyqgoib.html

);
来源：http://dali.zhoulong.xyz/Article/details/gt2pyjwosji.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwdgbsvb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdhuzfbq.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gt2vgkvipod.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2dcrpzawz.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2mgsjcehf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gt2nvanqfkz.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2teqtrsmr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2dbzrsvux.html

[Q07] 删除表
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxbvlunj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sehyifef.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2onvmtzom.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gt2quaxjkri.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gt2edeortjm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2bilaqekd.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gt2yjqzztdz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2jjdeegka.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gt2rlqxtenc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gt2xofgbbez.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2avivybxe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gt2apoztjxm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gt2krxoakfv.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2gtlfhioo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smnxyyly.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gt2lmewlzgk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gt2eshudaez.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gt2xmvmzour.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdszuhwc.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2mhietffk.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gt2ggwareqv.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2coksmrim.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gt2zubxnknt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2ydrstpmq.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2owzaewij.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gt2psedaner.html

[Q19] 范围查询
来源：http://dali.hywenlv.cn/Article/details/gt2jltuzciw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gt2lywwokdr.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gt2ueovrlev.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2mrjakgvj.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gt2jqiqkkiy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2uzyscknh.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbqsjzde.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gt2aokhnayc.html

[Q23] 分页
来源：http://dali.quarkkingdee.top/Article/details/gt2rwglqxpt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2uvcuioav.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2flbbcjny.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2lgytwzzk.html

[Q25] 只取前 N 条
来源：http://dali.andypj.xyz/Article/details/gt2ufwfvpjk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2vxgpkvud.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gt2wenemqrv.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2tjyqcclv.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gt2elykjehg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2ejtmosjr.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzogwdvp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2trlqotkt.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfupwbfq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2fglwbppa.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gt2bipvjdxd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2yayejibp.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrskzzyg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gt2hkezarum.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2ttxkahrq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2sppqtddm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gt2wrlfoprw.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2bcwedrmz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gt2fuwyfggu.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gt2xtzthpzy.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gt2oivzstjv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2zdcuojrn.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2gpmalcmq.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gt2ifvapumr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gt2wuxvjaub.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcfxwajc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gt2opvidzlt.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gt2kaidfbge.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2amzjrxvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gt2nhfuifdl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gt2tnevmzye.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzzrjfpb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjeleyxj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjdhlilb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2qtxcsmqy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jiagoushi.top/Article/details/gt2cprufiho.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gt2opddiqnc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gt2gmierbmh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gt2jxcsfrvi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gt2cpsrvofx.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2qdnehvfr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmmzbqpf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gt2znzygvft.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gt2dmgrrklk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cheryme.top/Article/details/gt2smwrnwhy.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2apkeykrh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjdpvuph.html

[Q45] EXISTS 判断存在
来源：http://dali.sxryk.cn/Article/details/gt2ejgldxfk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2yjmqhapm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2fuyefobm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2qcmmaays.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gt2indyvbbm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gt2pjfokffk.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2emzlozpg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2qpxbjzph.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gt2nsbiwuib.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2ujedctip.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2lahlhchu.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gt2rmwojnhi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yonumen.top/Article/details/gt2jkzwcpkv.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gt2qgirqybh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guannengcc.top/Article/details/gt2cfqxdgco.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gt2hbmtghbr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2xydunoiz.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gt2midilbmy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqvxuglz.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gt2jahqsiob.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2jofqhfvm.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2sopejsjh.html


<!-- 参考信息 -->