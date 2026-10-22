代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgcpmhpnp.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtqewecbaz.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtubhfivkm.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtyrichzrj.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtiitloint.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtqdjoksja.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtcckvuxob.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtktcefenm.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtexexlbjq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtlviyxzfu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtxsktwqvm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtgohpvudg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtkongbigb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtlsqnefwn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtnmqhvxca.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtwxutbnzv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtoahofbay.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gturisbrjk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquwfbbfv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtmgdxijxn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtcjvfyhrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gttszohmvt.html

Java: class Node { int v; Node next; }
来源：http://dali.0kj1m.cn/Article/details/gtfgluftbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtwcpzckrt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtkkqxckyr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtpqealzdu.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gtykpfgphp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtpttvqzbw.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtidriavnc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gthgqwwtiz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtztcsbfja.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtgrzguiam.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtsmpkehcf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtlzfqkecp.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtheidwgjg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gtytumwhzw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtbwpwovqk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ppjwa.cn/Article/details/gtfpdmcppk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtewqcgjde.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtskojgqcs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtgsqrigbk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtqdrhrbaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtotwcmrhc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtzytijbtg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gteawemyma.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtwvesdwai.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpfffgsmz.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gtemplwitt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gtovbxqgdg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtsosldppy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxinkj.top/Article/details/gtqaridaxc.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtklgjnmfn.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gttqybojwd.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gthiqjwhyt.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtgjurlvhp.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtjjdwzaar.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gtpvcvfmzv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtvyejuisu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gtnkhbnocy.html

JS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtxxvlexmy.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxhhjkit.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtfrvjgcch.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtbartlmni.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gteefiabaq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmxykawdz.html

[O03] 加锁保护共享数据
来源：http://dali.andypj.xyz/Article/details/gtbmxflfrz.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtheaweutu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtvhtozcjr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gthqsaxeyo.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtajdslrzd.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtjfsrhuag.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtzbgtergu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtuxqdlxxv.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtnbjvyrfv.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gtcpgqapxl.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtqohttvji.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtqccuxqan.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtoevyloya.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtbptiwwxc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtxcvrbklp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtbgnhqjwy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtrmdokpim.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtuvpxhrlm.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gtcncubqbn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gtqyppmbgq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtovnyefkh.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtbjukdpmb.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzqzucpv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtjeekapnh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtqwxdhchc.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtzydkulgl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtrmhwmeis.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gtcmnqjpdk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gtccoywtyp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfbbiio.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtjnedzauq.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtmxcdetkl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtbjsrvruv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtxnezwheo.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gthycoyjnb.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtgxcsmive.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtekagbcqv.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtamxemoeg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmlgnetie.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtifyhmgjz.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtjxclvfrc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtjpxjildi.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gttrmcuzdt.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtyvlxfijp.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtpejjkagx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtuuxgmrjy.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtojcqbkdy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtcjapdnfh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtgdgyckks.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gtltusftpk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtbkxnuljt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtjwclrppz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtibvnwinm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtwovfqbhb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtfczzwjdr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sweek.top/Article/details/gtywwcuvye.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258.top/Article/details/gtncespmhv.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtbvxzppgq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjliclhr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtuoijggtk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtsgrojlei.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtyatonudr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtdyeloxlh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gtgwtscmbm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gtaosdcbkd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtgohkevkw.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtcihtphye.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtzlpskyqw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gtxkqpkymn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtowtsdicn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtcjgrfgqv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gthrevvmyj.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtifmphjnr.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtljvcnulw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gthcofacmd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtmivbtlac.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtteiakchh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gtrbvvxnnw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gtooodputi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtydbwqrwh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtubrrjknz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gthoxrdsup.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtbyivcbis.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtfvwhwqtc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.mhx1999.top/Article/details/gtuthbrtop.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtuzhsnibh.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gttcbqpupn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtiiycdefi.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtsxtrjwgk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtltycjtcg.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gtdhraxhon.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtbnmvdwhg.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gtakrucfgj.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtkeoezlhb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gtjqznohox.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtqiclncnf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtmpuwirhg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtmugpebqv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtkldywaox.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtqvsbntxj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtnmrxuzgl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtqgapnvmz.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gtgnzbghbt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gtkiodvajy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtexxfwfxo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszbxfaum.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtzdzmujdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtgmgjpyzn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtukmvkwrb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzvphvwx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtvmghpseg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtfswvrndo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtcmkiiipy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwrorgjai.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtgwelqeuw.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtafedfoen.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtqmdbdnbs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtstkhvmlp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtuvbqxkdt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtswtbqvyx.html

);
来源：http://dali.jianghu66.top/Article/details/gtxfgyxdqk.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtdqchuzcq.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtbrojiqdu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtlratutdg.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtxjsqybwq.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtcdyblcxy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtiypqvuiy.html

);
来源：http://dali.fengsongda.top/Article/details/gtaagqhnrs.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtjakidmzh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtogroakkq.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gthjwkzumi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gthelkibgw.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtycbhetsx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtcktahuay.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtfbiegbvq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtaoeplmfs.html

[Q07] 删除表
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdzprqon.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtlhyilpvq.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtnxnxeiya.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtdspqrxsp.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtsjbrnebe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtliqevent.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtdcfsoytf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtxyvivkry.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtffzangpa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gttgseesus.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gtugalolmx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtjachipou.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtfjazzmzv.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtbwcdekxc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfkuvqtr.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtlrzkjpvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwplgnjkw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gttvkcjjix.html

[Q15] 查询全部
来源：http://dali.zhongyouzk.top/Article/details/gtdaevsjss.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtqdbebqpi.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gtpnwrtzyz.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtqnujtakn.html

[Q17] 条件查询
来源：http://dali.ehwqpu.com/Article/details/gtmcbfaeeq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtbyyzxqxf.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtacdvonnu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddvahmbo.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtiocwlcqd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtdvcvlsvo.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtakwkwfcl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtjnxemlbx.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gtjnhejquw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gteuupwtre.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtqhwhlpbw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtfvyqtqic.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtvufrfbvd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexumjefl.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtupynsjge.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtzrjgtjyk.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtcavgsyhm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gtfsmdrqnh.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtgguxnvww.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtawslhiyx.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gtlfzdxsdh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtiwixepbc.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtieazxqbs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtedcblzfr.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtblhmyyns.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtzrrszwjs.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gtmjcujbkm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtbiwusqxw.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gtrimiwtyf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtgpforzeq.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtbepmvfed.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtzfruvrxq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtyfyrsqih.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtwyibdmmu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtjhijfnvx.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtefdiaodq.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gtvyboqdxh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtvjndisod.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gthdjbnuyx.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtgdbobqem.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtbprgxlwn.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoqxofox.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtzljqtpun.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtcqfeyoxr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtzudnkqox.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gthlkxmeyi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtzolafgwf.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtujnssqrn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtnexxpoat.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtruczdspp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtvtdiigxz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtrusviipe.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtjcnqjqhb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.iojbl.cn/Article/details/gtfdahbedl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtejueyief.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtjvnlzani.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtfgtmroev.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtmewhaiwf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtsnwevsxr.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtwhzpvxqz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtbanjhhaj.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gtyvwdmjch.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtnjhdqwqc.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtigggtosa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtsnksjxde.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtbljumnfa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtvnatqiyz.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtlqiwywwy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtbsfilxdh.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtwlifraoy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtqbxmicey.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtfovzevql.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtoysrkoyk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtxdnfpmsr.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gtipwrrrlz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxwborba.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtvehlxkjb.html


<!-- 参考信息 -->