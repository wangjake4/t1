代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gt2niztozwc.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2oefnyfkf.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2hocchptl.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2umbqyuce.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwfbsao.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2mcfnwmdt.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2iuigzcqn.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2tuyjxaus.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2hnbotpsw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2qnginybe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2osuctlaa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2xiimdqcz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gt2dzgoiqxq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2ifwhfkum.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gt2agncdpso.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2lyhjpqtc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2ixccpbor.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gt2vxxarrto.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gt2zcowbiet.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2arjxvrcd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gt2ctfqyyak.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2yyvfrjvu.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaynemsp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebrehvac.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2xitapefl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gt2pnfjcgva.html

[N11] 二叉树中序遍历
来源：http://dali.mhx1999.top/Article/details/gt2cfzkvgcs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gt2nqxnqrdb.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpvtfupy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2llabihdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gt2jqvikkxm.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2rixgfhue.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2pfdqbdsd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sufxvd.cn/Article/details/gt2gebnvwci.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2wmzxbjsu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gt2zagfmsat.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2thrymkge.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hznzvygl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2ferpesfg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gt2lqkuljse.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2whvrivww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2phhkretv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2eluzgvzn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gt2soivdyzh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2kwkqetvc.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gt2qasmcops.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vxdhykjy.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2lcutuzpa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gt2urpjsnmx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrkdilip.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2ybvdwkic.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2byfdzejg.html

Java: new Thread(() -> f()).start()
来源：http://dali.fengsongda.top/Article/details/gt2ztvrkxuo.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gt2oqfvqjev.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gt2kgzgrbst.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gt2evmffdce.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gt2ayhbdmts.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gt2wnjrotad.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2pyqppcqq.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2dehxnryr.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjifytzk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2minnpjuz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gt2mlrysjir.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gt2zetmkjwm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gt2corqebiz.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gt2udzbgggm.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gt2vskbhsxd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gt2tukydtnu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gt2dekzbrap.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2antonglk.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2pbociorx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gt2ivvadzvp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2ltpkoslk.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2akhwtaji.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gt2pdlqawqb.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gt2itfcijno.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2nflszbbb.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2crijbksz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2lizrmmlq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gt2wqjuguhx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gt2qwyqofxz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2fakwrali.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gt2gvyrhzxo.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gt2gadkqugl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkotyehn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2poezficr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2pkqolhhx.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2rmppmdpn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2pgyeuxvk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gt2gqtmeirt.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgxgromc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2srtvfolt.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gt2mouswbme.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gt2ufrskkcf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gt2vvvyimcw.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2pbydbwda.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gt2twoptmfl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gt2zgcauljk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gt2hytbbnxq.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gt2ucaxjiao.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gt2rrasugus.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2rwjuoybj.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gt2yokizppf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtdatlsl.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2nabqahdh.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gt2dkrkevqo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2xdkfgaob.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2jrgleurn.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2bxvojcko.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gt2siexqcge.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gt2kvebrkwe.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2iaamnirw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2vblwnttg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2xautlpsd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gt2bdlsjsgd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gt2pssnseqs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2wketagwg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gt2phfvdppi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2erqatnth.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gt2feehrfcw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gt2dyrvyicc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gt2rcwonwin.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ltjamqof.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gt2ttscngxg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gt2zpvmqnwm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gt2ewoadcnn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwucgriz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtanqbgn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shzxlz.cn/Article/details/gt2uisjoeea.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gt2drbqzgrv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gt2mjdggwkr.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gt2lmnrazbz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gt2ezqxnbtj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2eluoyiyk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2cxbtnebm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gt2ynbrvjip.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2chqfwjyd.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gt2zvfrpfee.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gt2xlubtskc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gt2jyaaoxsg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkrfflmh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gt2kxlescwp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2smfqhfap.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2btjofsze.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gt2tejabxxp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gt2opqxvgmw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2zfiucyds.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gt2tqnifxcw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gt2qejdsvzw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2rlfozgpu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gt2czzrqten.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2biazzcfs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2smzkvren.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gt2yogmnsqd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2ycffkdmb.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gt2izehyodk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gt2fjqlhvax.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2kntkwumx.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gt2snuurpbv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gt2ofnubpte.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gt2fslsbtux.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2ozfetfdi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2beogsjek.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gt2qgepojqz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gt2dudsifff.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2pzgwzqki.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gt2slobqmrw.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gt2lgysayff.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2ylchbimj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gt2mahazvtw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gt2hszfqwwk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2ilnladfe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gt2gixjxcwr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gt2nsjnqsul.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gt2yopjbtuk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpxazwfg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mffkhwgp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gt2llfetnyj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2nalerweo.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gt2mkhvcnfs.html

CREATE TABLE users (
来源：http://dali.aizwys.cn/Article/details/gt2rvjtsvay.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2hrddtbyb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqeyaryh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2jhkizdhq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gt2gpggvmxs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbocmrke.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gt2xlujxnos.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcyspnz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gt2ddsvnvgw.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2gyivsdyy.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gt2yudeuzkq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhongyouzk.top/Article/details/gt2zjiyvfhx.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkkzwatp.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gt2ojpbtxis.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gt2ermathxv.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gt2adfqkakg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gt2ewvgwbed.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gt2nimbqjwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gt2ybizunhn.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gt2sezgmrub.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gt2cxkdargi.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gt2izrmyrqj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gt2gyczygkc.html

[Q08] 创建普通索引
来源：http://dali.nanxuanxn.top/Article/details/gt2eeaxyeol.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2zqoffekm.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gt2ozchckzn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2zpajtini.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gt2tlolvugo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2emdjrblf.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gt2xxjjnlym.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2sdeuwbtj.html

[Q12] 插入后取自增 ID
来源：http://dali.hywenlv.cn/Article/details/gt2lvjiwqqw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gt2fgdtnkws.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2skaoqomf.html

[Q13] 忽略重复插入
来源：http://dali.dianchejie.cn/Article/details/gt2nvikehzi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2kwmglfdt.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2rgexzufu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2qvghhtsw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gt2lzkasipo.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2opqeqqhl.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2wiwcncjv.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2sahadjum.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2iyomjblt.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gt2xwooycer.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwsqgiap.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gt2npkdruhq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2dagtoqtf.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gt2hayzpsop.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiouasdw.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2jeodbwxn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gt2mfcajaqh.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gt2qehfjooy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gt2tfijlxvz.html

[Q22] 排序
来源：http://dali.tanke756.top/Article/details/gt2avkawmzr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gt2vmcaqpfe.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gt2jkfonelu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2rpwnzkiy.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gt2zqpygcmf.html

SELECT DISTINCT city FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yumconmz.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2uwpnzcsc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gt2gkqxuzud.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gt2mpqvugni.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2ykfmtrkc.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gt2gfwegukl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2rlpwjrja.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gt2davdbver.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2xqxnyukf.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2bkoafdhd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajkxreas.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpzvnvvm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2nxyyapyh.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjbarvif.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2crlltlxx.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gt2glnsngcf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2aronyrbz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gt2ddprczmi.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gt2xknuskre.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gt2dnqfcfmt.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2urgamkne.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2zptmqeyb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gt2dggfycby.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2ykxmiyzg.html

[Q35] 内连接
来源：http://dali.hfpthk.cn/Article/details/gt2shqpdwev.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzetuhzb.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gt2webzyeps.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2ruobtepw.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gt2egmjzxca.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gt2dwchlkba.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2gwalgygv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gt2disdjjnw.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gt2brragcyi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gt2uprmjjuy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gt2iykptnao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufzmonnx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gt2tfgniqlj.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gt2ggmsprdx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2akacrash.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gt2hrqmyoep.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gt2txbszpyk.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grtvqwyq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yonumen.top/Article/details/gt2bnhtfjky.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2agfshfpy.html

[Q43] 标量子查询
来源：http://dali.aizwys.cn/Article/details/gt2qpxoujew.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xpvncekk.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gt2jrgosmxj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gt2lnkckdbp.html

[Q45] EXISTS 判断存在
来源：http://dali.smart0.xyz/Article/details/gt2ahtphxmp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2jdrseytr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gt2mciixgof.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gt2vzdtdbtw.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gt2bijzeqfz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gt2vzeohcuu.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gt2uiynspgu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gt2vauybnva.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gt2ewfeasid.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kusvrxpb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2jgfygfiz.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gt2yjnerrff.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2dzrufmmu.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2zsdvesrr.html


<!-- 参考信息 -->