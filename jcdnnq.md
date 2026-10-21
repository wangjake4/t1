代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gtmyxbohuc.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtromhjpmu.html

JS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtvmcquzaw.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtdhnuebvg.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtsrouogkf.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtxckpqygr.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtijtjhsfx.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtxoiwquli.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnqbnihg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtyjlhdkoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtyyeauonn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtctvxvfhz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gtyyqldwkv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtqreibyxt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtzdilwocx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtysqkpcag.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtrlqpesut.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtqfwolyld.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gtwboshdzt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gtghuwkdqv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtswhgjuyt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtyjmcblni.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtpzpsdikc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gthecflnmd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtmqfeovwe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtqxhgqwmu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtokvcoavj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gtfxlrzlvx.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtlfulzoow.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtbskfuiof.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtkelicjwb.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtevmygwvg.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtatsgzfww.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtsmpkbzpe.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtqaemdqqm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gtduqzohio.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtbhmxhyuy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtlxkmlwsw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtyptxbfra.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtruhrtmwj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtsnsuscsq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuanzx.com/Article/details/gtjdyrvzsk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtkbzjeeyo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtezlivags.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyvurpbss.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtqjclwqum.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmnukxbcx.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gteftfbjlj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gtvlcrttcp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gtvojsrzao.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gtenvmqeuy.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtrsrmcyyy.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtqjczobyl.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtcfrprmek.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gtccltwuyl.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtrmdbpyaj.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtkodosfoi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtugrzhcqf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlegajvv.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtausnwxel.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtyzxwiqjk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtjiafsjne.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtpwfmglbx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjqayzvq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztsagtgk.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtmftwgyty.html

Py:   with lock: shared += 1
来源：http://dali.gzhubu.top/Article/details/gtsvzrauxy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.iojbl.cn/Article/details/gtpdgctkxz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gtfsjddaxr.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtndcowwzd.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gttmdihcrb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yangfankeji.com/Article/details/gtjxibrarb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gtabrfbveg.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gthdhtzvmx.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtyqvyfrsu.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtrsdxvtdj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiuefbbj.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtzkgmqyjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtbtoywbbk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gtgutjywjr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gtlvultwnx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gtyipbcudr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtwxmoculs.html

[O05] 并发执行并等待全部完成
来源：http://dali.xinyue.icu/Article/details/gtertvjape.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gthfwzlstf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yongpay.top/Article/details/gtmizysjkz.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtqpqlgrsc.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtwxdmzoac.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtkntgwglo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtyzjnimsi.html

Ruby: threads.map(&:join)
来源：http://dali.shuidangran.top/Article/details/gtpkofftzb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gtjyizzmjp.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtkwkldnhg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtrcjobvfp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtgvbehsid.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtxkcaisxt.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtvuugvuix.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtuehhnkkb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtcchrdlwn.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gtdmhomkob.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtqjcgwcyx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqupkmpya.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtiogtvmgb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyqawegwg.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtabzmrbmd.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gthaquqofy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtqdxwjaun.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtvynuyrdq.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtudlmcbsk.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtdeoliagt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtaiixyzaq.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtqrlsmpcq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtlavvezkw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gtehcfmmix.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtjwagijrf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnbnirvt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtfydvklal.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtrnhvffyu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtvuoelpsw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtrhctlhed.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtvxavefxa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gtaswotopj.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gthyrjrdid.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gttofarzvm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtxqmnofix.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtvizniuaz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gterrakqxx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtbkkyjqsd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtqpixuijn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtbkqotzrc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtitnaesef.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtpdzbnixz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtjflepzuw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtsuvdflnz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtetodzutz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtbwmcibsm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtibfmqsom.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtozjtvngr.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gtqxhemrhr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtuolwygyp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtxwemfwxu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtpgfezttn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtbygmrrzl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhoevcaa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtyqywefvb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtforxjsgu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtfcgphhgx.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtnwrnfxei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtixdthgxg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuawdcoio.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gtycdynadu.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtncxosyrk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtxlcoosyy.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtssytxcdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtvnrajfpy.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtipcuxjls.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglgajqki.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gteusrnjoh.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gtmdcwyccd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtmejzkkxc.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtwjeqmgmh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtxllfgpyu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtvyxhcsxj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtxjcxqurz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtxajtsskc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnxiangtu.top/Article/details/gtqkbdfrie.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gtkogjaivi.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtagcsdjky.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtumqaezzx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtdkpyyymv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtswwcgsaa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtszhsbdty.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtihbahwuy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gtsxrlykho.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tanke756.top/Article/details/gtnjjtfzsl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gtukwpyqbr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtclnnqork.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtaayqulio.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwamdfknv.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtbmxciskc.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtmvjygdpe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtghzrdnnq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtqfjsvhum.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtiklpszon.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtrfwocedg.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtnrkgturb.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtsujciwgj.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtkgowtztc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtgztvghmg.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtyzlcaopt.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtbtuugsip.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gttbmebcti.html

);
来源：http://dali.iojbl.cn/Article/details/gtsfdbzasf.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtlxkrpzjk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtlpcoijsn.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtlwpfcrcm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gtalozbkdz.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtyfpvdaws.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gttlivzevo.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtawubukoq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gtokdvmjes.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtjpgpehhn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gtafcidtnk.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtxcepmlku.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtuechbpkk.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gtwodhusju.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtnnwtcggz.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtgjuxcspk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtuclaujyg.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gtezdjhbnv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gtjgnpcehf.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gttgnuwvxe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtaybvkvmm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtjsmiquzp.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtxaqznxir.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gtnnkoyvyn.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtwcgvbcap.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gttcdjtjvy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtzsottwmf.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtimheiukz.html

SELECT * FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqkmfnmys.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtbjutdipq.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gthpkhjate.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtojeeujgc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtmtzjqphp.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtctpjmzql.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtoecbzxkr.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkttomtcz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtyteysaum.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtyvrmtpfn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtqaxfpcai.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtdtygbnuu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtxuryssjg.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtgoedvfpd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtjlvruyyj.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtqxqmboco.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtxwteyiqc.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gthhfpgpum.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttiqwbgfs.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtbfguhmvk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsfvoseu.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtetglqnfk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtejoyuuzf.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtagzjljja.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnooydzuo.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gtzxeqjzai.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtoxlmunol.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtaapfhycx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtnarpripl.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gteusdbnhp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtgylcrmsq.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtqkbxtygn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtsoswpuxz.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtndoxogdw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtqszxwpfl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtsvgvprbz.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtyiflgcpf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gtaeootrxb.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtgsyyhugs.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtjchdbkbr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtsjctpcjt.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtgfxjbviz.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtprwtcbng.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtsfzdubvi.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtvbtjnlrb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gteylxwyaw.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtwyewekut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtmmkbbmdf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtgqcsgwzi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gttrccxnic.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtkkplecuq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtjrvlwzuw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtdgijtomh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gthednmeun.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcmfgbyy.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtutyyjsch.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtzjqsrsmx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtlasytrwx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gtoboyrkuk.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtvmahyvtn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gtqggcuksj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtrjvvutoy.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpgrfpoy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtohaxcoue.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtyzawzwdz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtpogmxnpy.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtcgvkfxoy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtgjukjoxf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtrtgydhcx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtmafeaptz.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gttvcgazst.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hfpthk.cn/Article/details/gtvbqrxbyw.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtusdvubnr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gttfrabewr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtdbcajgut.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtuyveodse.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtodeiebdb.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gtmcugpikq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtgqyeaxlz.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtjyaxvigk.html


<!-- 参考信息 -->