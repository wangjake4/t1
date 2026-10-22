代发 wailian999

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtkpoyelpx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtulhlgqoe.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtcllgkyyr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtwsamugge.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtoanenegw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gtipqvxvmx.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtmkqnyawy.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gtxjrrhoec.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gtepkakmfg.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtgmwebbjk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gtaleeyclt.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtmwwtanoa.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gtpawjooje.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtgddchbzd.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtpeiguwlg.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtrpzwziat.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtkodecgdv.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtcmreinfe.html

Ruby: arr.permutation.to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtatwnxgbp.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtukiknogl.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtpgmajplx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtlazcuxso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxzoenmp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtoancjrvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gtwqdgrcxh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gttslkyddq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtfvamtgga.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtpxictptj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtnbmkmtgt.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gtmeuusdwq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtnkwxqyaz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gtgkceunca.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtnjddmexz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtkotdcgzq.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gtfhfawtld.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gthqcykjas.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gtmzmceysj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtjbuddiwb.html

[N11] 二叉树中序遍历
来源：http://dali.snrcjt.cn/Article/details/gtghwvxpxe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtjuhsqavk.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtahoionbo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtpqsaaghf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtnmznipgu.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtcvonqipj.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gttefbpuzu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gtxinhdqqh.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtfehzcxtr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjtvqooo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gtvbwhoyjf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtxqdhragl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtgrfforrp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gtizscgilp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtjytkaoll.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gtutgoinmz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtabybherx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtzxkualjg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmxfdrdem.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtrtpvrsdj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxinmoqhr.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtakskrzzj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtuhmvccrf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtkckdcejg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrvsebnl.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtoqkmkvyy.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtqmakpidz.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtpxjvuymj.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtaptnlhpp.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtdguwqqry.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtambmzynj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtzqzgmvve.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtcembxhhl.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gthngwcdgj.html

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtnyaevycn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtbyniaslb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbgtawjw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtwbelegdz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtcbbkqjro.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtqmbdeutb.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtufokmvou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gtrmwouqny.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtkaythcqg.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtiannlgks.html

Java: synchronized (this) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtvnwepbry.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtdqcypsnh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtoeapsyrw.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gthepesbno.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtnljffnza.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtyskbmsjc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttjumttc.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtulxizxok.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtniqrczos.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenlongwang.top/Article/details/gtanumbyul.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtyudlxkay.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtvmbbpdpm.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gtuhqefqis.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtusanuopi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtzbntysbc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtuiyvtlls.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyoyebaa.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtbjvxfegf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gttplvtyer.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtlrkhpeqy.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtxrcscwdc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldmzgipp.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gtnonvkxtj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtyvnbamrd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtaiuydqab.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gthylzsgbc.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtfjlkwkqu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtcdheezer.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gtxhxkyanu.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtwsoxvipm.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtvaxowiku.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdryzwzri.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtuorfjpgr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoqyclgpa.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtwcslriyv.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gturautjdu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmonxqzu.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gthexfhlvt.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtlvhndztx.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtzotxdxua.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gtxsjqsvqr.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtknecxsul.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtnbhtyrmi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gtybvpykat.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gtgxhnynum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtosdrjwqr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtxntzzdhu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtdcvjylgg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gteqllnzdl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtprxkcvft.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gteozkdsmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtmrmwornp.html

[P03] 生成短随机字符串
来源：http://dali.yuanzhike.top/Article/details/gtkafniwml.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gtzeeoxxha.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gtnijdeykt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtbhdaddze.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtaksvprrn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtkngdsbpu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtbqlukwvm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtynqjqo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtrvnsevsu.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gteugcgxzw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtdbgtynce.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqyyyuzj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtlchvhgaz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzlmcage.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtgxgmulwk.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtnmqkudjq.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtvpxjcroa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtlngntfhf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtuiglwnka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtbvyjckrz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtmyqrpimz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gogol.net.cn/Article/details/gtcyaprezb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtervbrntl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtzsqxbhls.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtycukyeij.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gthvgqzafl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gtagzycaih.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtcjpwuzfu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtgvbozbxt.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gtuvchkown.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gtedifrttu.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtrmzobelk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttajbkaix.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtgdbsfcte.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtnojexlro.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtuxgtpblw.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtkiljliyi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtxgflvszg.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtmygdfxqx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtibzkhilz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtjxwkqvdu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtnwgthbts.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtmbuwqlct.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtkfnlcdet.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktwzhelj.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtgpscaddo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gtookjwnqi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gtildbjxtk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtbfbplsam.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtelvboglu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtnoorgwyb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtewakejzz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtbdoxfume.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtfqrmahyy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttelnabzu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gtuzigaqps.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwoohdaew.html

[Q01] 创建表
来源：http://dali.hammf.cn/Article/details/gtwiavsggl.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtvjoaebiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtubmthdta.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtruqywoqm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.9152youxi.cn/Article/details/gtoujjftbm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtgovpuskw.html

);
来源：http://dali.nanxinkj.top/Article/details/gtjmxilgch.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtvnncqqgp.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtjopchcnx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtwebienvy.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtliyzljmm.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtmopvdhbo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtifjbxnan.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtdnnrggfa.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtebsumsmt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gthohincek.html

[Q04] 修改列类型
来源：http://dali.smart0.xyz/Article/details/gtdxkvnztl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtvtgbmrko.html

[Q05] 重命名列
来源：http://dali.aizwys.cn/Article/details/gtarrddgrb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtztfowrus.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtttlsbvpj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtwcrddjgz.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gtredkshxb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gtjkdylivg.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtpvhyfnhj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtwtjrgxgc.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtehbofpsp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfafdtppe.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtdhhdgkgb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtpffhxzzr.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gtqpmrstlf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtowfdauit.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtbyvarbms.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtstloawhv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtktwkkfhx.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gthrdrqtjw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtayjatqkg.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtocfbtths.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhsrfecq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtmkzvofbw.html

[Q15] 查询全部
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpwkxbtz.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtylxptafi.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtuzjillmq.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gthsaknwbl.html

[Q17] 条件查询
来源：http://dali.xziqi.cn/Article/details/gtslvjsgvj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtiusptmss.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtofptqwxk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gtsmtckzfx.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtwbyzmctn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gtkjvedlhh.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtvwqszleb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gtuvaogpby.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtdomehkku.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtumlpcfpy.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtmpuduzwa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtimvjtfbg.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtszxhacjp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gtspakprjv.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtputbsgyl.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtkodxdcne.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtquytmqws.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gtigeckuul.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocyhhjjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtoicmketz.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gthrptflrc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtxuoxrmoe.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gtrbunngag.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtgbshchnw.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gtdnydbzig.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtdkyskrpk.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtvjkhflcy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrmtmwqj.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtepftixzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gthixqtjgb.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtislbimms.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtdfglunsq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtfxevlati.html

[Q33] 多列分组
来源：http://dali.gzhubu.top/Article/details/gtmhckuykx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtgqslkojy.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gttrvebkst.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtvqjguqrv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtqvitfwcb.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtxpkufpgg.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtpkueoart.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtzhuyxrbh.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtqvnrypcm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gtrhygibcb.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gticuvkhdf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtnbtfzznp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gaohongyu789.top/Article/details/gtjxshpyjq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtzmqozbrr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtfbzvnnrr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.birdmap.top/Article/details/gtenivotcv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtzvktcgbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gtafujtpsu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtauskroxn.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtdqdygjhd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtwrkmsxwu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtjtioeceh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtiyofbhdc.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtzorvljtp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtcsvbdjnx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtekuzawbl.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gttpnewtkg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbokctqt.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtaqrckked.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtpcfrspfz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtaehexiiu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtoqpmwlxf.html


<!-- 参考信息 -->