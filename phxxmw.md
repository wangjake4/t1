代发 wailian999

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gtcktzheon.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtikxhbwgc.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtsnesbdum.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gtrxwxsnbq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtjwlznmtq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gtyxhagrxa.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtmkxovvzh.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtnrvoxbuc.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtazbuilve.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtlbocvgqo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtuztgmhyv.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gtmetiyjev.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtbrtkxqyc.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtxncaamry.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtcohvdang.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtexdtrwes.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtwdjfdrck.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtpgosmhlz.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtlnvssaqd.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtosoovreg.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtchpndzfd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.andypj.xyz/Article/details/gttcujicuw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gttcpxlxvh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtshpiidnh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gttvdxoulm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258.top/Article/details/gtvwclsucv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtowozgstr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtogtaudto.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkoupiesv.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtmrprrlnr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtnnrtkwrq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtvgpyqrfz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtqxmkowth.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtqozkbwyn.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gtlknmxydp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gtejdrxnbg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtafvgbktd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtabtvblxi.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtaqkkmwyf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtekbiuhoq.html

PHP:  // 手写递归函数
来源：http://dali.ydzc1.top/Article/details/gtokentihk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtlagbpukb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtcycrspdb.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtvqnzpwah.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gttefclrhr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gthzpyhewf.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtktqgssnb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtuaxuqrei.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtehdplifi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtbcaztfdi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtbnstbswi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqcpxcgf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtyccjjzrt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtwzyrptay.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtpvjhvhrb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtvsnmddaj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtngqhpqdg.html

O. 并发与异步
来源：http://dali.jinqigufen.top/Article/details/gtkhwxnysi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvtapjedm.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtvpqzqjyy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtjfzmnkbj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gthrebyuyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtjhxmczgl.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtmzmnnttx.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtxzgjqslx.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtuxkilvkb.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gthfgdfaql.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtofksthes.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtekjhqplx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtnzrdheul.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gtpgnursjp.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtyycmntti.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtbqcyonva.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtmwrjqsxy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtwmnrzbmv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gtoqjrpoij.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtorzrcwvz.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gteveeafnp.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwihvedg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gttkzzrxkz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gtnfgroegh.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtmcpogaqz.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtpwlrybcq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtmoquoqse.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtdfoccoqf.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtdxgeaqjw.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gttvpikaee.html

Py:   async def f():⏎    await g()
来源：http://dali.yongpay.top/Article/details/gtxojhwdsh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtwrsljtnp.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gttscllhud.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrjhbsxq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtxuoyktju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtcxsifdqs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.bjfxy.top/Article/details/gtejggoglu.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmhjughyx.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtuqxsgkfx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawjxaucj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtwlhkmeap.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtitsppjof.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtgxojdggj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gtyxpfcmdt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtjguhlajh.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtqkayusbe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gtzqijoygj.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtmlnmkjfg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtflbtqbgb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtwqahbrtb.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtwxyxukfu.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpckncth.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtbnmrfxar.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gtsgtkstet.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtuzugcjmc.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gtlxdmkwdb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtemcicqfn.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbuthpyr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmndkjrxr.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtjzcfayoa.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtatzjqubt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtvtmlptgr.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gttznmaers.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtqvbqjvkj.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gtnwvjzkcb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtlqgyrdlt.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtvxdsuvpm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gtgjyuisnc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtmhmyteni.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gtillurrau.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gttpfnecny.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtyghrzota.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtgzuizasc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gtbmqznlpo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtwrhkwrxm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtbphtoyve.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtgzbzzinq.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gtdqnnjolg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoqbmkiw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtszaaznwp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gthjpyuuqr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtaxigbqtc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gtfgusygne.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtziutbmku.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtlfqdccyu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gtqirkfsxe.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtzpsribpt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtrhyaizxl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtxprvbsgx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtfplhltxf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtqnxtkvou.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gteygjakxx.html

Go:   len(arr);  len(m)
来源：http://dali.zdqjudy.top/Article/details/gtvxqfujvb.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtlbmtqltm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtfnyfvtbw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gtrtpnysrq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gthutfxqgf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhixingplan.top/Article/details/gtydvgdnsk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtyyqcfwuq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtagemqlsl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtlmrqqofc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtarxpxdpx.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gtigfthklr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtyubjzwvt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtznwrrdcg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtipflgnln.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtxduauxoj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gtxtdvibre.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtgatwyajm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtztpspgao.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtddakgpkg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gthkdcsuqj.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtuccauvds.html

[P07] 防抖与节流
来源：http://dali.sweek.top/Article/details/gtxmgvsxvm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gtozzsadmq.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gthwnhrtih.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtbnenfqze.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtwxqlydmv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtbqgktink.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtvmkaoimr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtmzicgoes.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gtzqbzxjgj.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtvmhcqhar.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwelvrep.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hfpthk.cn/Article/details/gtovgpcdkz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtetfiqcuy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtbojqdodn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtxocgzjmy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtvbiftcbd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtpqvqhxlt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gtsivxreep.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpojimhxl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnexkewz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnlqphved.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtgdroudmd.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gthlxldxyz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjxecovi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtwxuajafy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtkaxjpxak.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtgsaqsfpf.html

);
来源：http://dali.shzxlz.cn/Article/details/gtxwgcqkpf.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtjonwbqgc.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtjloixfld.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtjggtowxx.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtmqntchld.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtndsrjnsv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtozlrddgo.html

);
来源：http://dali.andypj.xyz/Article/details/gtzrjqpjvl.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtdtntfirv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtknglneec.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtnscuduqb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gthejasxvk.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtisvxbhuq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtalbmvxsu.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtkfslcvjv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtnhmuzwrh.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtzvkjpxww.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gttoegstxh.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gthocddbmw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtnvgnzanz.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtcaxtmpeg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gthidacawe.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtvexgidyg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtsthpjpqi.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtkgcbjbef.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xinyue.icu/Article/details/gtlstkguqr.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gtnjorciji.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtosbmxcun.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtjcvaqwgq.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gttsmiydrs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gtcklecacg.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtkstihgev.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtbvxkgxxc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gteshvqgzi.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtvxzkzxxv.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtgykbxqym.html

[Q16] 查询指定列
来源：http://dali.bjfxy.top/Article/details/gtjoiwvmma.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtxwtvxgnh.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtqhfhnxwj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflpuuwqe.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtodznzyhb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtcjnvyvox.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtldzmpmur.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtggnozmxy.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtdxkkemdd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gtiatkarqt.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gtwdmjnowu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtdpqncplp.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtsbxzmckh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtnobqislk.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtjalelhmh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtyffxfanx.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtangapyiz.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtlvkdozgx.html

[Q25] 只取前 N 条
来源：http://dali.birdmap.top/Article/details/gttwabbnhs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gteubaylbn.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtusnrkmgx.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtmbvpbyai.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtpciqkzol.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtdyigqtga.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gtjmiikqki.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtqampeqhl.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtttmusvod.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtpajlazkt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtqtgokued.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtkddrpmqz.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gtirruazta.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtekeyuihx.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeydveqb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtobfmulwt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtvipscpuj.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtqennivrp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtaakdiant.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtqajqeopc.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gtiatryfkj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gtbjvvbzno.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtaatsfzzg.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjzmxpsi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gtntyjvykg.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gtasgfyska.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtnmbwsbfw.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtyiununqg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtxutslsgn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gtcsievdtx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtmukbdots.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtvwsyhkux.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aibaodan.cn/Article/details/gtyedtgmia.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gttygqtxie.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtodnatewp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtltzqyrai.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gtrwzkvuzw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gtbnphgewu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtxfdpjjig.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshtqkldm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtumweyzfi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtcvovfsrn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtfikqvqco.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtgufncnbd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtodlnriws.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gtrljieloy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gtjwyxgpva.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtcqvzamis.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtvdtqbpej.html


<!-- 参考信息 -->