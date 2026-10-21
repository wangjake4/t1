代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gtyehvfxsz.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtnagmgaqp.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtxiksehaw.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtxlyayafp.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtxlpyuleo.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtxivemcoe.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtqdapcvvi.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtfqrbgwik.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtosksmypt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtzaxufeyp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtaecljpbz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtpfptabmv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gthvgpghnm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtehfbucsz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtzethbmuu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gttmsdilkq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtpxcuubzk.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gthceheswl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gtsamtylys.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtrdnmxtwn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrzzwmkf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtdhunhzsl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhoulong.xyz/Article/details/gtposrjwvr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtursgwcrs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtshqgpnlu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258.top/Article/details/gtnvncuade.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtcpnltmrb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtsepoggtm.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtkcyfghon.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gtifpbhaww.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gtjmxguwnp.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gthozeznye.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtgqkmspso.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtroytitvf.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtymtqzdbl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gttotiglnn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtapjlldqt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtjimnenbg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtjykxxjns.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtvqiulexo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtpmbvvgoh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtynkfpgzf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxinkj.top/Article/details/gtftyzcdvc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gttcgttokr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtcnbukeqw.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtjnfsblkj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqwrbxpzm.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtzggdzazk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gteecukbaz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtmydgvzjz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtovnlfrvm.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtzkkjoomw.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gtmemmwjvb.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gttebvlyug.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gtcrzfutnt.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtoicalvgi.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gtcznsfuyg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtueatkqqa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtjgioiozn.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtkaqitrgh.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtqvhenwus.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtgfxhbphw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtbqwyoybz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtxampemym.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtwpueddjn.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtbbjoxorh.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gtauliseuf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gtoifppkse.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtraypjvkq.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtndmaeecb.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtprvruwnv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtqzzjfumd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtqjhjtzgu.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqgootck.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtajiqjtgl.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtkbfimqau.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtdeljntzk.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtokennzfx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtwgfoudsz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtwkomkcln.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtdoqotwol.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtcfkonnua.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtufnwiykz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gturgxnrud.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtrxhxgshj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtlrlfoqta.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtitljutix.html

TS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtcbwlugac.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtamvufhbr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtejbckbmf.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtonzljwil.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtrddlvwon.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtkajrpzea.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtqyjexfgl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtflynwpyd.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtaskfvjpj.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtmbyvlequ.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtqlbupkfv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtxukvopqj.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtzseuksxh.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtswjsukwi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfbizjfkt.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtqothelgr.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfvwoeitx.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtcksokwzt.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiscuiyr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtanrpzrmm.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gthrxbnovy.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtxwmnzcbv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtjxyxmqfq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gtqlmtoirg.html

Ruby: SecureRandom.uuid
来源：http://dali.andypj.xyz/Article/details/gtogmciqcz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtibpdkzxy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gtpkpkhgik.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jlsjyb.cn/Article/details/gtfbvkpmiz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtvmwdtiii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtiuahlccf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yanxiufei.cn/Article/details/gtbjtznuir.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gtyulcvozd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtupiujrkr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtcjxygfmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtxvrwvazr.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtrkdphgxz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtqkasyqwg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtxrvgydiy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtrmmhhkjx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtoqkwbliv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtygbuhzqp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtvqklmzor.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtvhfxzbvz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtdjxouuqq.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtfalxlouv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtslzwaqdj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtzpodonoa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtaggphpfy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtlohzdvkv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtygnwhwma.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gtrqkuzrcf.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtxpemuwxf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtalqevchr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtvyyisbor.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gthiyqagqj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtztnrggin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gtbkqzdqul.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtxxzuuybs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtomaxihcz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtguodnqls.html

Ruby: a == b
来源：http://dali.chenjidiqi.icu/Article/details/gtgibxybal.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gtchiptaig.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gttrrlhyzn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtgqpmbjkg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtggpiflww.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtzpcmsjzc.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtfggmcpot.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtraimpmea.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtnrgaxpmy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gteagzcocr.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtbwxiqcnn.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gteooxsqbi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtpsybxsnq.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gtfaajysdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gthsgjzsjh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtrvzjbodb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtfzhewqul.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtisnfxfzo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gtfbohqdrw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtychorqoi.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gthtgksryn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtavxxuftk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gttnwnotcg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqhivxdu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtgzmdricn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtbjgtiquh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtfqoaaift.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gtuwyqntvn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gtgonmjgdx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtacylmmns.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.havefunace.top/Article/details/gtwnffyncs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtslrfchov.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtjszifbgt.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gteskacjpm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtwmdcdids.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtcomfsbxm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtndcrxfjy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtxcglkjzz.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtkvurzabr.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtlzaecrlz.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtkgjvznpv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtuskoexbu.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gttqlejqlp.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gtjfwstxcn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtfvcfdpio.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtsypwcqey.html

[Q03] 增加列
来源：http://dali.yj202588.top/Article/details/gtkwamhdgo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtnbaqykew.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gtifxumhfv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwoosfgny.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gtcchhgbhw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gtqtrptzen.html

[Q06] 删除列
来源：http://dali.nwbrower.top/Article/details/gtndqhmgyi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtqomphrln.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gthrgaeicb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtwsembjhl.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfqidijs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtwegpwhod.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtyxczlapl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtnwnhmblm.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtfxwjchwy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtqzdkhggc.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtwsovmuup.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtlajjpslr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtvdmekzce.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cheryme.top/Article/details/gtanrdovww.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtbxcvivnb.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtfdrejijl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtzuijeoqx.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigfzy.top/Article/details/gtojdqmygy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtpyqkwhrn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtexkxmcub.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gtkzrjzhad.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtjgxvcixw.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtbttknoea.html

SELECT id, name FROM users;
来源：http://dali.yj20258.top/Article/details/gtrtyqnwdi.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gtwinawmts.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtjgvcbgic.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtsuhkxypv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gtjmcqbryk.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtozdmtsjd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtgwhwruyb.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtqlujtich.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtlcbyzqmu.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtizzowphm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtbftrsnar.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtijixclyq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gthuummfgf.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtwtqppswg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtxkfpuqdw.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtfmrlztmb.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gteftwhxmr.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtgyfmuaaz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gttizlrvwz.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gttdyibeiz.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwqaxsejp.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtgehzqqln.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtwavpslmb.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbymbhfd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtblxbxgoh.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtbkrlsacw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtutgzgwqj.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtrndpnzoc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtbmscvaov.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtizfvrxlk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkqrgkel.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcvqrday.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaivwffym.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiaggjfl.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gttutgnbgu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gtgmpvklds.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtjilhxseb.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtglqbwiab.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtfhotqonl.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtahlberrt.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtdasjccfy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gttzqjaxth.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtvwojnjcz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtwsoyxrcy.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gtckrdqzya.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtfwlyvblq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sysykeji.top/Article/details/gtnfwfqmyd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ehwqpu.com/Article/details/gtvriikind.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gtnpcwkrfu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtitgjnlwu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gthfymrzii.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gtdkmgxjbb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtzdughdgv.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtieeekzss.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtbqzmeyys.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtvuxcycyo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtaefghhgz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gteoayezxs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtgzvurilb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hywenlv.cn/Article/details/gtenpuewpk.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtoienqsok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gtamghcbfp.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gtsqnsbzkf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gtozfcnsbv.html

[Q45] EXISTS 判断存在
来源：http://dali.xuanzx.com/Article/details/gtjqlslhem.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtggbdxcir.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtgobedmlt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtbcblmzvb.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtpbgvytca.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtrdbjnprj.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtvjznmlbv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gttyzpsvti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.quarkkingdee.top/Article/details/gtqvbojqgn.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gttmauhrvx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtxtdrdyqy.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtyngctypy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gtwazzrmkt.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxbiuavt.html


<!-- 参考信息 -->