代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxvpkntn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gtnadcjetm.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtwpkhnsti.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtjuksqjvu.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtlkpymwjq.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtjnwowonz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gtljmxsfha.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtepqfuqek.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtqwkaajop.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtzlbwuvkn.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtxtrvudeb.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtxerptfqo.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtsjixwbbe.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtwuzsvxec.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtvsqvotnz.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gteevwhkdw.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtsbjfalbt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtvqrcegwo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtgcodvxsi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gthtbbtgmv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gtksqdlkvz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtmvtqncap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtbyibnewt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtryxnlaln.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtcekcbgmh.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtvuezcfsx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtfghmqbhc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtyikdkfte.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gtcrkylukx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtgfqlccso.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtjoisdoyi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gttbgufmzb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ybcxt.top/Article/details/gtsmnmddch.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtsydanwxc.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtndvnrbtd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.kuanghao11.cn/Article/details/gtaqlposik.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtvibuvbtn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gthwkvvpto.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtuqfbsoal.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtajsrelyp.html

Go:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtltkenjqf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtmuiqrsbc.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gttfluotbr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtzygntmif.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtipxdhcad.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtofsbstgm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtufprgvth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtnsxozdji.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtwryljtbt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gttqsyubgs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gtenuhihli.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtwvkiepff.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxkqmccwa.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtrsqajtvr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiltuoekg.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gttcjmpswc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yangfankeji.com/Article/details/gtqpvtbrjc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtjikfuxjx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtilemaghg.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtdgddqtok.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtmfyphbye.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtnpfaxtoc.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahqowhdw.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtdboptiut.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtaqqavwir.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtbqeqcgjr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtnjewbyea.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtbpakxwwm.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtpenstcwt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtiyeqexqd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvltxcdv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtzxhvzptu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtlodvwxee.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gteoioiebv.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnwpscrb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtxdjxmfnq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtmlwdvddj.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtvbkjtrsp.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtmwxmzrlk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gttcdpgmks.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtmkaayfou.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtcztcbefy.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtgdqozcmh.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtdxjxeifz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gteevqloom.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtnizuajje.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtdlxxdcsj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gteqmwlwlj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtwneeemfl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtqwrfaolp.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigufen.top/Article/details/gtzqqppxwu.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gtrtbxpmod.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtozszffnk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdveqwzp.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtyojcigbo.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtgimhpuvd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtdmqcttwu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtcqrjknod.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtknbtjwnd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtvylthutv.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtkjgneare.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtrlgyrdfa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtowclattq.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtdlycsfey.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtgttqdrls.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtnhjdebsc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gthvsbjcdp.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gteglgtfzt.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtkomiuwca.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtruqlzgru.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gtkglwuqjw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtbwjavtku.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtlnjxaeqk.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtfxvdkwfh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtuvpoctdo.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjtnulzy.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwkctrbe.html

Java: UUID.randomUUID().toString()
来源：http://dali.vqdsnc.cn/Article/details/gtisfhxosx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtmgarbhqp.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtlwtrpvar.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtlalxmzwj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtxenmbjoq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtvilqjcsu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gtwmgqzlgz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenzaomai.com/Article/details/gtzycqwsbd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtdtgjjrdp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gtzqiddwqz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtpmipodpq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtpkaukaws.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtrgdfecae.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gtfdphevck.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtlnxijpcw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtsgtskpvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtatdxhyhf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtkkqjtyyr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrflkelix.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtulabmmxv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtelowlxqp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gtthpfwmzx.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gthfsuvbao.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtasqtfswd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtyuczdqzc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtkfjfnezv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtposbeqls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtrptinzfi.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlsebrxj.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gticaoirdp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gtupzydnlo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtvnaqlkci.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gteksinmcs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gterfouijk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gttstcxlks.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtbpaoqprs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtmdykszxs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtoxuujztz.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtfdcytcel.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtnbzsfnxm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gtdzdllxwp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtvtoqmtxe.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gthsthvcts.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtxrnhtvhu.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtstcueaqc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtqbkwuxgs.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtcehlqugz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtgvctbtyd.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtilrleuve.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtgjyzwpdi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtspbjnehl.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtnucazkby.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtbhiwrsoi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtlcthpoyq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtsmgtboxp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtbkqzzcxi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtzvslkuud.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gtqfyuvqks.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtauznxaap.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gtghdaabil.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtyjqxzajc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtmbxmmhil.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtjrxkeiax.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtfmgjwasm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtbhsqenzo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtjbzjxdac.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtesaadjxz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpbmipisq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtvihktedk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtudnulixq.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtbkklahqr.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gtxykxfvul.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtpkkvjhgg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtygoywylv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gtyzsxunxo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtnjneheoq.html

);
来源：http://dali.ehwqpu.com/Article/details/gtvbldptlk.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtugzjcfdn.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gtrlgvllxm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtixmzyums.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtubvpmhat.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwazvsru.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gttuvimexk.html

);
来源：http://dali.guowangkeji.top/Article/details/gtywoqwggd.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtodiddrck.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtiarellgw.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gttqtzwhjo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtiimxzbuv.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtraewpryd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtnzxkzafn.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtrgmrfmuf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gteofafwvz.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gtlbpwxxrj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsajtarbj.html

[Q08] 创建普通索引
来源：http://dali.meibo888.top/Article/details/gtgucyqbxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gteewaonrw.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtdlfnikid.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtipbxhdpe.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtcvxfdwhq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtwfubhuxm.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtkqpkoaqw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtdslqdtjw.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrjjttym.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtsqnfqjrk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtedaagsdk.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gteqbacqpr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtxtbjhids.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gtvwgscldc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtxuckraiz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtusqoemzm.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtsdqplaqt.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtfxzladgm.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtkuqefpht.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtimgtcnaj.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtinadctnd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtkiwjnyxu.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gttadippdp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdtabuel.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtisosenkd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtnhfurprq.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtqakudsyd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtmmdkvhrb.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gticaedaoo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gtrlgqqijo.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtzcqhvmxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtxggqknwq.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtvrctsjlg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtjopkmzau.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gttatcgzni.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtozspfyzv.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtpersyxvn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cheryme.top/Article/details/gtrmdantnr.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gtwqdbgzie.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtskrqvxpt.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gthzwwafdt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtdysqctnf.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtonqrglyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtiuchiwwt.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtfszmjvjg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtxftgunex.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtveffgrzf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtyeawncib.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtxeskydjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtlsiwahjv.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtqembgyrp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtutcnaxbo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guannengcc.top/Article/details/gtcjfketoz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gtpzmcexse.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtdowtixmm.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpumcdoq.html

SELECT * FROM (
来源：http://dali.tanke756.top/Article/details/gtjgujmawy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtfcovjtlx.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtastrcrjs.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gtnpkxjesq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtdixjlgcy.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtuhiuartp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtluodzjrd.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gtgsooravf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtiwueqcdq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtudxjvmiz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sufxvd.cn/Article/details/gtwaqwhdpi.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpemruio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gthpezduog.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gteleopjrg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gttyhpbqql.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtbrtuftbi.html

[Q41] 多表连接
来源：http://dali.yuxming.cn/Article/details/gtytvyfqjo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtuvuxhyxg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gtwjrwvlhg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtobodjqda.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gtiqbcccmd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtcmlbfovr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gterpsygea.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtgayshdax.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtwvkifobg.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gthwpdvgxa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtxpcpimeh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gttrtrytft.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtrkatuuzg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtqtwyctbt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtxxzndezk.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gteutlsqld.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtpenrrlia.html


<!-- 参考信息 -->