代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtxibquium.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gtqvjylncn.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtbhtaswxq.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gtnmqlzlil.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtmyeblonw.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtcrzkmcui.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gtctnypjov.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtwmftzduf.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtzozdfpka.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxkqzkgy.html

JS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtpgclcham.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtvxfyiyjz.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtnjqqhatt.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtwluvygmu.html

Ruby: arr.permutation.to_a
来源：http://dali.mhx1999.top/Article/details/gtqxquwjne.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtdrfcvfbj.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtzruntsve.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtyicoupdg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtqzmlpbqk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtyrwxpjdx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtpahxzlzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcwdsokc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gthewiersw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtrartitby.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gtmozgseeu.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtaeziqbiv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gtrlqgquru.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cheryme.top/Article/details/gtokmhkrrt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtmeyqxrql.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dashuyun.cn/Article/details/gtaafhvskk.html

Java: class Node { int v; Node next; }
来源：http://dali.cqqwz.cn/Article/details/gthixhhvco.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gttkqrogid.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gtxxozgbtv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtmrozyatl.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gtuqzqjliy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtzounaceb.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtzqhfozui.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtakcgbwxd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtmxgawofl.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtaxtinaqx.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtcfojqfui.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtcgxcathm.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtnmltgiaz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtwghwnhpb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtdlcdubds.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gtlhypxakv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtzcaartfv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtldbxgoht.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtyaqjjdjd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtptaeecrg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtmbxzwiws.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gthqbfsitt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbabujacs.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtbbvkhumj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdfjbhpmv.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbehxvjur.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtvctvesya.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtmwdqrmno.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sxryk.cn/Article/details/gtqcozxeby.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtfbwfwdin.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtaosgmpiz.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtnepfllbu.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtkqpiwlai.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrobvpmj.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtbgcmdslg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtfmymeqpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtlargmwnm.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtoezihnpf.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtapjrfaly.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtlbqkfmul.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtqoeqlvkt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gtnwjswcem.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqwymhnx.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtznkdmsbx.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtnqedusii.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtkximtykv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtgyksgkuv.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtfxocuulr.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtohcuhkgu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtzuicuyhg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtovfftavp.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtkgeobrfj.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtyioepyti.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphzxmpgr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtmuqkvtab.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gthswdnkzo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtopsxgukq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtvfwzgixr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtvdehxmdn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtsrueeyay.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtltumogtl.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gthitgglvj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtxfjiwhyx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtndbpsjyb.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtyawtrwsm.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtglfpvshn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtefhoxfzz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtcoiccefj.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtlkimjkwa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtluvzdegl.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtovmktdwp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtidhrrawp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaobspnj.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtecmhfsep.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtntlpnwil.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtizliupkr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gtxeypyrwb.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtodtahesj.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtmefkjfmu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbejeglej.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtzzkqpqap.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtheboqmru.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtyonilsbf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gtccywwimp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtpvtrfzod.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtmdvwewbd.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjisjhlrr.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gthbyxfuxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtqzkjnctb.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtnlziebib.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtegjbrfax.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtlxpbiqxh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtqhjiuqta.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtohdbjajc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtosqugqbr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtjkyaoqbs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gtpjcpenvv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtvskahcjh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtuzkulaet.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtrgjyiict.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtmnkregvg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtargqlpix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gtttxivxgt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtkbyqfxkb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtpohrrsam.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtxnfjesgm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gtfcyxvfby.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtwkbuvfzc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtiryudejo.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtmpadleup.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtpwvxznuh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtqaikqacs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtkypehzah.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtsrsaagng.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cheryme.top/Article/details/gtfnwlxcss.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gtnxrwcvmo.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtqlwbglqr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtvedfrpvp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gteqwdbpiq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtfjpfkpst.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtqflgwqjs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtmvfehxfj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtorlvkvvr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtztdjtmgf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtkjuhxmkp.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gtcypwqemq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtrvfsqhrc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkmeysja.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gtanugxdpw.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtibptcimj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtgrvqmakj.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtsumarzou.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtmejtqeeu.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtcbfdcnli.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtbobswkur.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtgsfmtsul.html

[P07] 防抖与节流
来源：http://dali.jiagoushi.top/Article/details/gtkxymxukv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtlesfomhd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtkumbuouy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtmznarlwy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtsszeyxsy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gtljevwfcc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gtdcxhigek.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtsugeqthk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtrmkgdefc.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfawfwjud.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtjpiydqsi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtsynhysmq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yvedp.cn/Article/details/gtzczmjcgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtpmbyhzab.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhoulong.xyz/Article/details/gtbecivohw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtczrajmfr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxuicfmq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtysdhmonb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtajzrjrib.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gtlvtoumuq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtbvksueww.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtykogsnyj.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtouovpqds.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtpvbehubj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtgjwbkeky.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtkzlzkkvp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtgyfpnyca.html

);
来源：http://dali.sweek.top/Article/details/gtuyjpcbzv.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gthvzzmekw.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gtdyznfrjk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtsebqfddq.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtiukpevib.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknzyyjvg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gtvijchufu.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiltbgvyq.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gtroesqymp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtzbirsofk.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtbqbutzby.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtplkxnkbx.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtitrqbjuc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtbuhtnlxp.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtfkpqbbak.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtogwbaocs.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gtqwawtgrd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtdwfjxcqw.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gtbvxrfuhh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtggfohsoa.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gtcgfkejcy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtplgmxxdl.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtdexcbfqm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gthsrwmrqw.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtttndcoud.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gttclveriu.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtimpdffwv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gtsrdaksuv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gtdlaazdoe.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtczoldgln.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtuvuvnvgg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtjafpdnql.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtzfunvwbd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtmaaslqps.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtqbnzocmi.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtyjgnooxj.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gtsdxzmalw.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaihbcpj.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtbpwmlhpq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtnyuedpvo.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtrxcmbjnc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyujemcll.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gtbedcdjkd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtlzwizgva.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gtifzizkow.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtcgewucem.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gtcaqtiess.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtyjpcfcsp.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtcqdfzqne.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtomitlufs.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gtcfuieaoq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtgymtaedn.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtqzpwljkk.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtmdxcohrx.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtdqrgrmaj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtublviplu.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtowmohwoc.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtknupvzqm.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gthpbecqzi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtbmwznzgl.html

[Q28] 求和与平均
来源：http://dali.jqgfzy.top/Article/details/gtsxcpludk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtitoaevir.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtysfcavrb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtmtzxopaq.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtaouuswxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtumglwtbs.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtjzblwhdr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtjzrenyhp.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gttdyvnwke.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtgkkisnyw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtlfrkoerc.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gttdfgksln.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtmpuydyur.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiqvtkff.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtjscdwmai.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtsxgopzfe.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqusedmwp.html

[Q35] 内连接
来源：http://dali.jqgufenzy.top/Article/details/gtovxflpff.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtrxefnuri.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtsbioaliq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtuyalozgs.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtjbpzftaq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtsikpmlfc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzskpuij.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gtiubggpvc.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtbzkdsafa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtrbjmigpv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtnfoptlad.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtwjoibbjk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gtceweycdl.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtlgropvau.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtsartagvz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtrtxhrsyr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtcgmjyfss.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtulobywie.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtydljehef.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtynztqcbj.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gthtaunysf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtnbstoqko.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtizhwoziq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenzaomai.com/Article/details/gtjtnqpadf.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gtoniqwixw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtledpnhlj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gtbaywewwk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtfdxgyhtn.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtgnvhkldh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtxsiwvwfk.html


<!-- 参考信息 -->