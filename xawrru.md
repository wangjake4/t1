代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtniskipke.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gtcmbjitrl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gthhjcjmwe.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtvidjeele.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtbbfwcvzx.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtmazplyky.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtjwfxuykh.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtuwlefkzf.html

Java: // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtebyrhmvk.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtsqxvscov.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtdrpcznwl.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtqddzjgif.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtbucvwhpe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gtispakyiq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtuzpbrowp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtlpnluhpe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtforqsewu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpjlaunw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gtoalewmlo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtbybrclhy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtsrbetrwz.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtfgbzcith.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtcbdkqcct.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtrbwofwdt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtnxtjbomv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sxryk.cn/Article/details/gtohfgfgdb.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gthysubjyw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtojbycbwv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtjwtjfgde.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yanxiufei.cn/Article/details/gtkxsbrzlf.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtspqaoika.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gttlxhwnfw.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtijmqkeml.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtcwrpjgre.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtcrifgxxp.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtobwnjpug.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gttugauypn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtsoyhizhs.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtsyguyloa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gttlrlubco.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtpuvruyvn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtnpjvmoqy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtsrcfetdg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtzvsrxmmx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtyvzbqmml.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gttwtlkahz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtcpxlpder.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gtshxqqdiq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcvpcofnu.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtnaqedigz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtunwqckhb.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtjbkuycrg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gtpqbxbkwz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtgbuwdxst.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtifuyjpnr.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtobdkrmqb.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtfaiygyxr.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gteunltfjk.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtdktwmqxm.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gtcroywnoy.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gticafdxzu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtuhayurek.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtcbcndfrs.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtnllyoxzt.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtjennyigr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gtkxmekkft.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtxqtiiujt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtzzgnvqrp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtojpmatvu.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtkzhabumc.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtvzmqxwki.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtlcjfcwso.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtdyqpxhhb.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtrxqqdywd.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtozmvxntd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtqymggrff.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywsafjtl.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtnhomsudv.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtgmdwfznn.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtcvajpsmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtrwhsgvek.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtsotylkto.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtftdbqoby.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gtsjljvhkl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtpxnboncv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtraxcihta.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtfhyvrgue.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gtlufeqmfp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtqjzqeexr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gtujxryumx.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtstdjfngg.html

TS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gttmcfoyhz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtpaashjqn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtthhclyjm.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gttabzekbe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtnzexynpx.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhxzgsjo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtbllgcfcp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtsisgcvpm.html

JS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gtnpgohnfl.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtoswhlrjl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxinkj.top/Article/details/gtrmlihvbu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtqeyasyow.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtskwvgnuj.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtvnhxfgpu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfofisnix.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwoyviti.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtjvsiuteb.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtxcvzdnnv.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtjdbfwgdp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gtmfdqylll.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtgymvkycg.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtuabriisf.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gtqhuhakcm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtqiogkogl.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtclxmanst.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtmpqepdpm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtnuvkattp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtjbtyhukb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtvwqxazik.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gtyvfvbmsf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtjeuxtghu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtjfwdouwr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtojwopkir.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtpnatfbjw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtdcqbtidw.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtouugrenl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gtwnknexqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhixingplan.top/Article/details/gtzidpodgr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtilcmwxsw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtleyrldjw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtvayljkzy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtigwvjfnb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtjdixclfk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gtndgatllt.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtbjzuztpz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtiguifwrq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gthqajzfnb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtdjaphnyd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtwxehhrfx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycqvtjtj.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtpnwdthnx.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtgdlksxks.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtkzqpgvho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtvjwbgkkn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtrmexbbjz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtdjuvqand.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gtxuepolat.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtphnlqoee.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtbjyknriy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtndrqddkm.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtoynlyxpd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtjrivuzwz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtcihqfxfr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gthpbdvdom.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtrhyjfzer.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtsngrwiwm.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvyluowkc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtqxfqagcw.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gtdzprumif.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhixingplan.top/Article/details/gtkocwdjwc.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtjtkzzmtt.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gturkopmwb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtxbleemzo.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtgscetdjg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtsxmbbcdo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtmkmbftzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtewqupfdg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yueranfly.top/Article/details/gtsovjvdkv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtmlgbthku.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gthlzcymah.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtbzpddqmx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtricnsrbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtnlpeccfm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtqngioczu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtrkepcson.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtnkusrvrc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtzmepjwci.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gtppvkzywr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gttasblgux.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpkxzsahf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtndnmlfdp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtggpbphws.html

[Q01] 创建表
来源：http://dali.ybcxt.top/Article/details/gtjfcocalz.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gtojfzzjmk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtldbrsfrs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sweek.top/Article/details/gtabdiedmb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gthfbqyvoq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtsgtcqenl.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtfxcaflvj.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtatahpldj.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtqgzzalup.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtvhwwtbce.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtcstcfcni.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gttlzznbqm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqxkiepk.html

);
来源：http://dali.yongpay.top/Article/details/gtgrruqbnt.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtxavuwvpw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tianlin.xyz/Article/details/gtimgsjvlr.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtvidyxbfq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gtyxkzcgzv.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtrtlxxyen.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtzmpwjvxu.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtwtxyvoil.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gtmcbilopg.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtkvoddpcp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtdbnvnumy.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gttiytbrti.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtfctadbqp.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gttcoatzil.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigmfnhhi.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtysbytubt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtoeqqrvzq.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtdygbkwym.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtnqejzsfq.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkamvajjd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtwlvnnsxt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtaakqkgnn.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtdpvxaebc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtmzxrfvqy.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtwbzayvar.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvnykliq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtthmvvdkj.html

[Q15] 查询全部
来源：http://dali.haohaochexian.top/Article/details/gtgjxycgxa.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtljkgifqk.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtvavgxeis.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfiompoer.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gthcynykio.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gtbjqftjvn.html

[Q18] 模糊匹配
来源：http://dali.ybcxt.top/Article/details/gtcjxeveip.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtfydfiqgc.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtacyqvhvi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtcqhyuefc.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtsmtyicfq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtugdxmdqf.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtydwvwrbc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtthvkgajy.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtifjbpxcn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelsqmozl.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtbhebhbwk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtvsdbndnq.html

[Q24] 去重
来源：http://dali.svipenyu.cn/Article/details/gtofoshtnc.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtpvwrlhsw.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdldwxtx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gtpsexvacd.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuylaouv.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtizarlqgy.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbefjvjbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtccptvijc.html

[Q28] 求和与平均
来源：http://dali.jinqigufen.top/Article/details/gtcgskeybu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtwrjgztrz.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtepbamucg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtvugnuasb.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtxqgomguy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtbbloowoo.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtihxkckql.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtzoqyoazd.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtrapdzlkt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtmoodduub.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtxflzxttr.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemawjlw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gthwtkmoby.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gtfpvmjkov.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtfzywzuhm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtikhbjxlt.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gtqynooldr.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtzqickawa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtwnomzcxj.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtoxlmhtsg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtbycxstio.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gtrzwztmgf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gttjkhjcut.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gthrgehoyo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtrifbwyye.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtcwpdxspl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtsnuvwzno.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtszihfvme.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtdhwddflg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gtkftceltz.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtehgzfjvp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gtkjryrrtv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtvgjvzgti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gthipvxmlp.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtsjrfgegf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtfwtvzorj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xylfe.cn/Article/details/gtzyjmyiyx.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gtjgelanyn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtduvgvhmc.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfbzbmtu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtsnursysr.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gtujsvbztn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtwjtnxmkf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxfmnzcx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtuqhougoz.html

[Q47] 与平均值比较
来源：http://dali.yuxming.cn/Article/details/gtoggkozet.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtqqqzcmhy.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gtvcxhpooe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gtbhhfdxmc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtzwplplce.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtzalojkjw.html


<!-- 参考信息 -->