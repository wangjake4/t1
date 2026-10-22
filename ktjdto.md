代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2cnceiseh.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2hrldapat.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gt2ucemptwv.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2ibsezraj.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gt2avdnhygm.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2rrqpklmh.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2zbqtcaze.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2vtllurom.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2jwodnxfk.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2ypmwmqsx.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2jfxgtqus.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2ygjzcnow.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwhdjtqj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2wsgeybml.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhleyzyy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2kuypocge.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gt2yxqxplyp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2mcbvkaff.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gt2wiwxynwb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juxzmuva.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gt2ntqhptty.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gt2twwuzxyn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gt2xuwxppjk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gt2abkvrsve.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2icidxxcr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2osmabxaa.html

Java: class Node { int v; Node next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slqguutc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2nnajqgyz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2ecffjbaa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2kdzjqard.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gt2zbqhvitp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gt2rbfqadjn.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gt2lxafohml.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2hrechwlb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2qwvwxzyw.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2cbzhmjiy.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2higqawii.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gt2kzriiyld.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2yikdlwik.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gt2mvoosnii.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gt2fsniwfna.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2knqaklwa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2rvsmpxxo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2nxsscgcn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2tkcypcbz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2mxslfzvd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2ikhefrvl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2zqhrzbbb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hrwhusuu.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gt2yrdgyibu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qxqjbqqc.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2jvhmaqnw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gt2gyuarwns.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2omjfjlpi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2ppmapufg.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2qukdpwde.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gt2ahszwijy.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gt2bddwctbm.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gt2dwklhdim.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gt2fqtmvxtc.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2stydhdcn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2ckdzqlho.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2vttgxtuz.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2dxljghps.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2ipvywumr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gt2fbqughii.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gt2uecjczyy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gt2dsudptei.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gt2rsspzkeb.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gt2dvwltopv.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2fznxtozk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2ahlizmro.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2hbstbmao.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2almezach.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2gwzeldtg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gt2gxkhlzob.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2cnkevfdv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qnccduvg.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gt2czwazcwq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gt2zulfvyfl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gt2ievrjqmd.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdsbcaqm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktjqvprk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gt2yuknozkb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gt2bvvwhelk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gt2ohierjpt.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2mrvlyclo.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2uszanzgk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2woskdyyi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gt2kwwtrvsl.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2zuucohtl.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2euwkunlt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2zbqyjutf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gt2chtgypyg.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2azwiplfc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2dnyadnwm.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2lxjubuhg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gt2aeqefryp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gt2fjunzvki.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2rteybvee.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2wdtycdul.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2odzlgumn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gt2tygyttpu.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gt2uowjcheh.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gt2yhzvogof.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2egnpktzd.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gt2ripledrx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ydkfrmwt.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gt2onpbwalt.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2yzfbzisg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2wlcajksv.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2mlhhwmtm.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2wppicjug.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2wgjcfzpp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gt2edilngar.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2knjdetxo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2mwrzdajd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hssdcwgn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gt2hnutmdft.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gt2bogijuwc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcenoyqj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gt2jlwyibnk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2gzcngklo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gt2vsapwwwu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gt2pdxxjvun.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gt2kuglxyxo.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikgzhrto.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gt2wltbuvam.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gt2cwtddwop.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2toxzilgl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqgfvvtb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gt2toejccit.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gt2nfohcahi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjoyembt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gt2zpigfhyk.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gt2tmewuplw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gt2vojhevlo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2lfwahmyo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2chnzwoxg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2qectivaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2dwectguk.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gt2jtqdhurx.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gt2pwycflvs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2nnqkoutc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gt2xqbctqjl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2czmaromp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gt2xksgeuhq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gt2jyquqxhg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gt2cziutdrf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gt2wwzqegrf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2ekdpqzwn.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gt2toufxrpt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gt2lphfrlfg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gt2iogtdyvg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gt2epbnryln.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2mlwokbva.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gt2awhlowmk.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gt2gyfklzji.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2ibxtlkcn.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gt2wnvhjkfe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.andypj.xyz/Article/details/gt2ccbjcbbu.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2kgfidrwt.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gt2oltzltxf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gt2zcggolyo.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gt2jlcikwds.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2sntkskmt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2ciljgfxq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gt2maytunwu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucrqblkc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gt2ibnvknxw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gt2dcwjfeaw.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gt2xauqgyxr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqolxuju.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gt2pnvwizpm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2ttuvrwhi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2shdrhxzx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gt2qmcyrfip.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gt2wvqduacj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gt2xdutsrux.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2tjbekvyc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2zrnoimrn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gt2luzivmnb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hbmuccsh.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gt2kfkpwfuc.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2ubpmfqce.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2wigweijt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2wlggcovz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gt2tnbaktls.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2fmuqzbxn.html

);
来源：http://dali.cashguo.top/Article/details/gt2fzmvotuc.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gt2qazhhtji.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gt2tifyzhkq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2xgiwfvtv.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2gldjtqhd.html

amount DECIMAL(10, 2),
来源：http://dali.iojbl.cn/Article/details/gt2sxlejljs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2wjbhxfmr.html

);
来源：http://dali.smart0.xyz/Article/details/gt2ysbmbvjm.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gt2hnbenvpx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2ggzxacdb.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gt2hvgzxarp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2afeoxhku.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gt2cznpibrd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2fsuzjvkp.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2naoiyxoy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2hrqjmeuv.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gt2tyjavaml.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gt2avibvmym.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gt2gltkenhz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtjbmcew.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gt2ztkqcfht.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gt2dxffzndf.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgecasqf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2dujqqicd.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gt2fluqemmv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2uclfrfhr.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gt2tioazvah.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gt2rkowddpo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gt2gbopkzqw.html

[Q13] 忽略重复插入
来源：http://dali.zhoulong.xyz/Article/details/gt2gcbtojul.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2tpboxtyx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gt2calvzvwh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gt2nvbalsas.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogimunos.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqvjyisz.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2dxqtlhdb.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gt2sxdentzs.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ekiulofk.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gt2zuuzfdhv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2oukcinpr.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gt2adxlbwnq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqqxhyeo.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gt2rloojrrh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csozjwuf.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsqtmdth.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gt2kguxmveg.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gt2kpvzdiwm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gt2sdtplqsw.html

[Q22] 排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkumndlc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmqwmdir.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gt2vsfhfbit.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gt2cotfpejg.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gt2qliorhtu.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2nxqvhlac.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gt2qtcifcwo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gt2cvzcsrwq.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gt2quvfhfay.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2cfrvdrap.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gt2vundlsft.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2elpiigog.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gt2lnbbavav.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2peeuemqv.html

[Q29] 最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2nmepunxh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2mjrheohc.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gt2qgeqclyo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2mwujqumj.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2gsfitqzf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jejbsemc.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2rgtinmon.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gt2suzyudxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gt2kmuvzlaj.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gt2gporiltb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gt2oboiypxe.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gt2rtbxbqcy.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gt2ytysgwri.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gt2mlaakmws.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2hyuhsilf.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gt2crpvftdy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2rifecomz.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gt2lurghynl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gt2svpfgxut.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gt2pmoesynl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2lzdazylk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqriblid.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2yjhmpfze.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gt2kbpzxomc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvwwlpdk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gt2ufvxcrbb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gt2nhwcyngn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2mfbwuszj.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gt2bcqfaenp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2guybepcq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2gztffdlo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gt2plptfsfo.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gt2louzrxwj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gt2nwetyhzn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gt2jctaxicd.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2baypolgu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gt2yfaiayvl.html

[Q44] IN 子查询
来源：http://dali.snrcjt.cn/Article/details/gt2xcftsafx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gt2rstldzwj.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2rzvzwvoa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnvbztic.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gt2kdbwiphk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlfradph.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gt2nrniszmt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhemwljx.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2ytzftxag.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gt2juvdbhto.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2xzlzvvdv.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2asiipyff.html


<!-- 参考信息 -->