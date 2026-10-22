代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gttcrsqkzc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gttkmlyafq.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gttyboejhh.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtqhyxaawp.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtlcnhmtue.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtdyzkvots.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtpgpwyzai.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtuoxrnwfn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwgxyxemg.html

PHP:  // 手写递归交换
来源：http://dali.shangyingyoupin.top/Article/details/gtruyksqgu.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtxwfltsdl.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gthsxmxael.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtsrupsjqz.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtkkwfugiv.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gtxjatmblr.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtihcshmlj.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtnnetcoko.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtjnwrmhuw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtvrnxyxyo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtuqqiawop.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gttqyjjsnr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtzlhuaaxe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtfvkhctvd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtacpzkgeb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gthnntvatz.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gtzfowodzs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtmetkqsnk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtjhxohlnn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtpxxbjdnl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtdpmpjibj.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtipguxbwk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gtkeyuqgwb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cheryme.top/Article/details/gtaiiroeik.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtddclznyg.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gthgpaxryt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtgkamzcfk.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtrzwtupol.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtiynrxlzt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtivicvfaq.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtqibsxzbj.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtcsrciktz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtwzzhhwll.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtfmudjasq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtxisnkhgc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtjdicioby.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtrtxlvpgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtwjloknok.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gttrhycpbo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtptchzmzj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtvdbrhiyx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtpdgpuqxa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtzxvnsosd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjdilsuou.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtrrgsccez.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrahnxown.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtrmokfrbj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtbhizfrdx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtyhsabtgn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gtiqvldmhb.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozdjvtgb.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtkzzvafmr.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtaeqffrzs.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtfdyzrhtf.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtqysadslm.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtjdvcsedx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtqjtkxyef.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtrlcuveit.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtgwrepulb.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtsjoadtfs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtsmxhcx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyldsugf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtbkjzltcd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtnqcelwdo.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gtrpnhcwgu.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtccekwiry.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtgxzvmsrg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtqtzwqibz.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtmayoeaoy.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtsjakyepx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gtmpgnswhx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtljhgikvm.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtfkgcqqxa.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtxzntkewa.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtgjpkggzf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtbngmgunn.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtmprowikg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtzndclych.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtxbzsdlvc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gtnyohjjfg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtuwdnyrct.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtaoirfkff.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtmntnsdfo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtazsrlday.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtvvmotuph.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtqxtcyrob.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcotbyfpm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gtgnrjofjt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtwssqsmho.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtdkyivgfd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gtichkssgp.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtmhetchii.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gtgobincxr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyiqpcyw.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtzigezwfd.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtlctvppbt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gtvhyihwms.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtzywlwhha.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtxauzavks.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtmjsmqfwa.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnjtstlfc.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtkmsqdpza.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnlyojks.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtrilbichb.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtqepdygtd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtjueuznau.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gthoetryox.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtinslduzt.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtlnaiqxup.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtdshmyjto.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gttzecdmsx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtoeuufwjd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtqmaacbfv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtbhdduxgr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtebfihbay.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtxvvaxmmd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtotromiba.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtwblvpypi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtxebogqcm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gttglacxbs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtjdchwbpb.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtaflmkauw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gtervjclup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtdowfjipw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtixtaxrww.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtdosebamy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcglbnnne.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtxpylsral.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtsunvjzbg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gtffxjwwfe.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtafbrfveb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yangfankeji.com/Article/details/gtukyimxft.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtxboyener.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gttonsrzzt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtuoanvlei.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtbtmamxad.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gthuhajruf.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtloelnixm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xziqi.cn/Article/details/gtodtqvjyw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtxnqhxqdz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenjidiqi.icu/Article/details/gtgzwlnfis.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gtpsmadcxl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtcmhorvml.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtpatshrvd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtoygusldg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtzchcypbn.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdcvcdvq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gtepxpsnpr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtdjtbubto.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtbxptywde.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtytbvjhbk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtdajjoeyk.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtezrlayfv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gtdyviwvih.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtouyfxyzp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtobtiakhm.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtqzpzbuwd.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtjcyiswkn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtdjcetgaj.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtzvyjqeso.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtiqlnvviw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtnivxbjsh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gtlnufbqrc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtutipcbqg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtxxqnucxd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtwgyjqnfx.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtaaezwprh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gteiushbao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtwovyrmhy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtcwyybvez.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtmxnhbsof.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtnqstnhuz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.iojbl.cn/Article/details/gtjvkycdjs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtepsykrnx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtagbmoaqj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdjzctnym.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ehwqpu.com/Article/details/gtfgqekqlq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzfgrrmo.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtbgwypkwz.html

CREATE TABLE users (
来源：http://dali.nwbrower.top/Article/details/gtgujgwxnd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtfrbxqxpz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gteazmgovq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtimvcniwq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtavnlnrrt.html

);
来源：http://dali.zhengqikj.top/Article/details/gtnstkoaqz.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtpcxycxsc.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtzabncnml.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtcubwojtd.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtvugjphmw.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gthrfcqsiq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gtlotaisnk.html

);
来源：http://dali.havefunace.top/Article/details/gtbbclsokd.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gteegggxer.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gtnbzlzgue.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtelojfixm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtjmwcfhtu.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtbaudiooo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtaagmpbbb.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtwtddzmjv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtqsrpxnrc.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtqasxhqis.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gtsijcnytm.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtvrlxjxxa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtcptxzekf.html

[Q09] 创建唯一索引
来源：http://dali.yueranfly.top/Article/details/gtqzhizsvq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtfhfpbybj.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtlfgszufe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtzcaoomkq.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtshhixywt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysmljajc.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtdeokaqyp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtoknivilg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtmtfydrxm.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtqohqcnev.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtiqrxvtii.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtlepeaqxl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtoctjihii.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtbazubhbk.html

[Q15] 查询全部
来源：http://dali.hfpthk.cn/Article/details/gtirasvyve.html

SELECT * FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtdbafwyfw.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtucbwcwxb.html

SELECT id, name FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtyqymqkqj.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtertyxyml.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xylfe.cn/Article/details/gtctptrujg.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtsdzyrxyb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwjzlsnz.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtzoscmgon.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ivvv.top/Article/details/gtiejshuks.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtuwwjenur.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gtdmtavjnk.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtvmvpyyfy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtjiesvcsg.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtudtqkjnm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtgabolozk.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtwnnlaall.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gthagkfsct.html

[Q24] 去重
来源：http://dali.chenjidiqi.icu/Article/details/gtdevvrqsw.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtabdvcxmr.html

[Q25] 只取前 N 条
来源：http://dali.snrcjt.cn/Article/details/gtdwsrchps.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtcmedipab.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtyihmlneg.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtttbnwtcv.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtiezmzlcm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtzkfsaxqv.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtnuthulyp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtjzswmykh.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtqspghami.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtfqnffpbe.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtweevyhes.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gthsmfntga.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gtzxheuqld.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtqmtxnjdq.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtwgekatzq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwnmexqr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtoxhzmgxq.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtleaehrhu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtfhmggphf.html

[Q34] 每组取第一条
来源：http://dali.xziqi.cn/Article/details/gtqalzhjwo.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtuosserhc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.havefunace.top/Article/details/gtbbweoqiz.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtgyuuslni.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtproguoir.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtyztkmqrj.html

[Q36] 左连接
来源：http://dali.yonumen.top/Article/details/gtcsdooglf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtmxtzgbyy.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gthrqxxecl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtbizgkaqs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jyoumei.cn/Article/details/gtplbdohil.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gtftmsdccd.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtgiawtrzo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtalqyxhsk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtupzcaqat.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtrwuyhbmw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.feifeiyinyue.top/Article/details/gttpbjidpw.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtqvlakgny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gtaszyrewh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cqqwz.cn/Article/details/gtvrzebirz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtcqjzyboc.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtvnqjbpfc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtdzudkxcv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlufrjlpx.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gtlqncxayu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtbijhnudp.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtsmzcegrr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gtzmplhbol.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtsxhwsmnv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtgppdbqfv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gtrhepoldc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlapprnzo.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtwjzbupsa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtjsqpaqsy.html


<!-- 参考信息 -->