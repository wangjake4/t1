代发 wailian999

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gttnrgcofs.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtjnvtsckm.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtcnwnwzqc.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtlvdzynim.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtxyqswmig.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.havefunace.top/Article/details/gthdllamvr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtjikkymnw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtqnwdwhij.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtxkkvtbwn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gtlbyqkard.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmyxtana.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtwkuxhsal.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtevzmjcdi.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gtnpsbbmlu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtebusiles.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gtooqoovty.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtuwvervmp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtnbensurs.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gtkzhxrxnh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcalpqhng.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtdidgbwxl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdbxihuc.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtkcenyinq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbbidikw.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gtdhnqcjsk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtsszlqpri.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtrdzbxcry.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtuueohrmg.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtwsexmgoo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtkmmrxfub.html

C#:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtnhseexop.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gtixsivbye.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gttmqjawjo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlecghpp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtmedqrnmg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtwenzuxrn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtmswsovtk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gtpioxtksc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gtlhtsarsc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoedacjvn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtldqxrkws.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzodlslvd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnxkcfdmy.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtkmwlumkn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtgwscugjg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gtfvjidhlo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gtjiwcqeal.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gthifrdeus.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gtppezcyau.html

Go:   go f()
来源：http://dali.shzxlz.cn/Article/details/gtgywjgtfz.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtjvloohnw.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gttbewtwcu.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtgxhgrcsk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtvcsfuhtm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtdauvpxdl.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtgscldrnc.html

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtqrqqtrok.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtrbdutfxe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtyekvxpnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gtqajqfcxq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigufen.top/Article/details/gthgnlcttp.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtxixoqxlb.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtvpdopdoq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gthmrgtggr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtotorkhhj.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtllnkgqrc.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxiikunyp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gtxvhlcgfv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtdzeyhfoh.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtmzymyhvb.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtkseuhgku.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gtnnidnlbc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtxvsyebcw.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuyjrbiif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gtthjyfefc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtvqcunckw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtxdqlotie.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtgswesnse.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtcsfjgjkj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gthxexpwds.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zycfv.cn/Article/details/gtnoyzxlgk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gttghtamlx.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtgomjdyhs.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtflwioywq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gtlyjyggtl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtamideeqs.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtpagomuho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtjypxagfb.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gthjihwngh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbtmyroq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtcvctixvi.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiagczku.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtlhxlyaze.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtqrxueqib.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtmpkkhezb.html

Ruby: // fork 块
来源：http://dali.kuanghao11.cn/Article/details/gtfmvayruo.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gtkzvuhorw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdakpispl.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gteibfwnub.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbphtfbvn.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtfpwlokkm.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtcxsszegp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gtayoksxrf.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtdefshlzi.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtiqynhqep.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtbuhgqjdz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtjgsowuif.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtqtwkbmnc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnhoqtpa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtzassryhz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj20258888.top/Article/details/gtwfnehkbd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guannengcc.top/Article/details/gtevycerzt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtojzfgwdi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtllvngmje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gtcsvegxdm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gtnmngifoi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtmjhzhzqo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtdgzybqkn.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtiumlpahx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtbkwdwlrg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtvadxoqbp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtgxjcyoub.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtnilahosk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtzpcuwbyl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtzznnfdqh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtkobvnmyh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtgvzauegx.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtrufdqsty.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gtzqjxkaxa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtmlqswcac.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtsbesqsni.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtijuszuct.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtukwsrplj.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gtpcxsrmsh.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtbhvpxxdu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtmdtlqkda.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtdegatzgf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtiawbffgq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtvlnerimy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfufdeff.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtfigqidvh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtraexomsi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtbvhsspne.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtjvkqiyvk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtpsarkzmm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtxrkgydlf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtndarzowf.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gthmkbnyyg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtqvzdnpdb.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtqjnwlmmb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtnplgtqbz.html

Go:   if x == nil {}
来源：http://dali.ppjwa.cn/Article/details/gtsszvkyza.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gtqnuovpqq.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gttluobpkv.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtnzbsoyat.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtdkmbabry.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtuomjtkle.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtkelakkkb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtiktilmge.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtncysulym.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gteobzinbo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtbmugnhcq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtuwgnrdsy.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gtdifqmkgm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gtwdjqdvgc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtgvgymmhv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtqbijpnfs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gttyyblfyq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtaeqvizkj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtnfrynufe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtslecgyhl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gtdaijjqrw.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxytxtqi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gteqrglvfn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtuynlyhua.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gttezwpovh.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtucyzlxmz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtttnrqgyh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtgftqxrlb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtxoyebxzx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtfdqyddgw.html

);
来源：http://dali.birdmap.top/Article/details/gtretrirxd.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtrtblzpbh.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gtaukxvtis.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtjqqqmpfl.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtrrgzetvf.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtdmlucycc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gttfxskgtr.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtlrxgjpkf.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtwnrirjix.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gtsudtqpbv.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gtsvjkucaa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yvedp.cn/Article/details/gtijacsmzj.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gtbmmxkrzt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhwnnlvr.html

[Q06] 删除列
来源：http://dali.hysaishi.cn/Article/details/gtyffmaqlr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtxwywcjbt.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtsnqhfarb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gtdrnjcpfq.html

[Q08] 创建普通索引
来源：http://dali.ivvv.top/Article/details/gttvhdfstk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtwczvsjrp.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtppqnnwcr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtxxjdjpqi.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtnlrpqwtc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtmopcclmw.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtbowvpkwt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtxqvfshbk.html

[Q12] 插入后取自增 ID
来源：http://dali.tanke756.top/Article/details/gtoxutjgqu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gthfjvuewb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gttfisbnps.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gttibkxyyp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtnkoaytrc.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gtdghskufh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtnnsxxbuu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gtpxoqlane.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtyhjznoqu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtxmugosgj.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gtfhueyuwx.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtlpascohv.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtrgituxhy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtsculdcrv.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gtimocqysp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtayysgtdq.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtmfmxdcwm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gtvmqfzseh.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gtbjzqoljw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtgppocpls.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtapclmgln.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtbrxbmfoj.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtmzoxfwav.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtbnteundz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gtquknhbiw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqxndofr.html

[Q24] 去重
来源：http://dali.xziqi.cn/Article/details/gtraleqagr.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqgpqycun.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtczprhywo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtdmupeytx.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gttpetgzwr.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtxicuuoep.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtlurrakcv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlitpighu.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtipvzgedj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtenzsdigf.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtriabzdof.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtczidmydi.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gthplbyvtk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gthyiaowwj.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkknujqw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtutlluuan.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtvggswhok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtgzpmivrr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gtfypfjfie.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtsjvjmvaf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gtrvdcrtia.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gtadgrievn.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtwzydzgbe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhongyouzk.top/Article/details/gtcvwpghqd.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gtuxkfzllf.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtbhrxlnss.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtwivsgvpj.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtdupduqca.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtuzfoejts.html

[Q37] 右连接
来源：http://dali.tian-w.cn/Article/details/gtnxjirkxr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtyfnmgxfr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinghuilouyu.cn/Article/details/gtriazmqmo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtfxhfynus.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtmtchulqq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gthtpmkwit.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtgvctxyfd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtscztlujc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtedzajrmg.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtpbpipbul.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtwzngrnmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtyxskffhv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuanzx.com/Article/details/gthawujbfc.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtdcnhhoas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtyvzehtsr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtwvdrujrs.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gteyupauwy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gttmyqufwk.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtdypkhtgt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtvqtuhbbh.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtbbkdagmp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtxddqkzct.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtoybzqqya.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtdiaupafl.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtgcdrrfyz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gteclkvjnu.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtfebmufzx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtymapbvdr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtxeywrghn.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtgubbimar.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtgqrdjzxd.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gttximwbrh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtmpvpsnaz.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtrpxvhexq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gtkighrqvg.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtniqnqndf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtpwymmljv.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtguvgkfjl.html


<!-- 参考信息 -->