代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtggqqxclp.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtnnqezpud.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtrjkpfbnc.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtytbwpkgq.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtdontkfhb.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gteiqokhee.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtaoczwyrg.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtdwxbargl.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnfvjpotw.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtnpwxgyqb.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtymbjfvom.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtbkgppjng.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtwugkhdwj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtlcbdftoi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtedqwyphf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtxoarjfzg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtkwrklosj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtqawkqlvb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtnakatwtr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtkgvexfci.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gtglacagbu.html

[N10] 链表节点定义
来源：http://dali.xuanzx.com/Article/details/gticmsetlc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtviildphb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtvxkjryul.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtqgptxiey.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtixbnkjlz.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gtqjjyzbwm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtlssrslwc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtavnfkqyc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gtudxnefqy.html

[N11] 二叉树中序遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxydpuap.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtpwecjigv.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtfsihogho.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtdpahfnug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtlanjbgik.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtmbmgrbdp.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtvoamsidp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtdjmumjxo.html

C#:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtlbttrkro.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtbxlrerab.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtgbjrpdaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtjjeikhoh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtnaqneshs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtjvinugti.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtoakhxwqa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtwnldpusx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtfplpnqkf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdwyhgoh.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthcarcsgq.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtkjmvehjn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjcxnpljf.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtiikvufbn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gtitlccswn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gtlrbbjagw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtmfnbmvis.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtnmrnlmta.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gtdmhybops.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtcbekszbu.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtfbhdrlpf.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtyeomnejo.html

[O02] 使用线程池
来源：http://dali.zdqjudy.top/Article/details/gtkwvkauck.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gtspjorezl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtbhmeggrp.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtyqbhwgjn.html

TS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtqwpiiyus.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtyphtjent.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtcuyqombo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gtqhenzbvn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gtdmariebc.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gttxgpeucl.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtsbqbsxjn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtnwpbzefr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtienbanit.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtlznkktwg.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtrnyuewxa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtgmeuxszk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtwyxlqjoz.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtoelkcgns.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtqkkfgzck.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtrjobhdhv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gthgnkuozk.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtgnqlxkvk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttbafwgxn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtcpaxaowc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gthwffwlib.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtjxcdsfbi.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gtkfbeaotm.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtuyabfqgf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tianlin.xyz/Article/details/gtmqzlwpoh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtndqecize.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmopejpba.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtbkfebwtu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gtmqjwcizg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtwufsabgs.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtuhefoqcb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gtmldyrkur.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gthopglxqc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtcthkpelx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtrlfmjdtr.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gthmwcgdkj.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtsyucjaib.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fengsongda.top/Article/details/gtdmvezjdq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtbyhvfktq.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gteokpqbeo.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gttbcpchrp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtedpvfkey.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gtnxnqwabv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqiacidxw.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtqgaghhyp.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gtbzfcvnfl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtdldazcbh.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtborzcqqw.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtjxzurfjk.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtdhrgbhqe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtopaqqtpg.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtcbmhmxua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtizlcfvvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtyodwuaro.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtnlcjaeti.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtstmemdwx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gtwyjruywx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gtjunjsvmv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtdaoptpbu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtnfyqubgm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmidpfqo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtmirsoveg.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtbtktofri.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtygksxgfi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gtpkkxaeor.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtmjrvtrnr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtcnuqgjdf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtizabhngc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtenkaoslr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtellfgfrn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sweek.top/Article/details/gtpljwsava.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gtztjdwmhe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gtooojssgp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtxdvkvxjd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtvxowbxzf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtrmgxqbww.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtgtpyzkdu.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtokmsavek.html

Ruby: x.length;  x.size
来源：http://dali.aibaodan.cn/Article/details/gtdqwrqbbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtutowrdia.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtbxpxhgvm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtdoeejaex.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtheuuhdsi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtkiytiemd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtumodlnsh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gtuzpgmxsl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtzwwrzlvf.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtqqybahlu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtvbswheoj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdafpbrwt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtxtywgpzh.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gtnfddmkdy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gttoepoxkw.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtjeupyrox.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtpygyuhis.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtmtgtqvwl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gtolhtbusj.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtqhykdgky.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtetquesap.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtbnnglmhz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gttelylirl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtblhzftsg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gttfyhgfaw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwfenrnuc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuetiantiany.cn/Article/details/gtgzjiqinx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtfzhmtabw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtgdzwemqt.html

[P08] 处理浮点精度问题
来源：http://dali.chenjidiqi.icu/Article/details/gtswdcvnre.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtiglifzgw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gthmclvlks.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtclibrgzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtyhyasdoe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtlafppjyt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtzitzscce.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtldiwpwzz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtqjftppbu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuhqupblm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gtfzifiuyo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteygbmnsr.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gttlegntff.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtzozckivd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtlvkvlydh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtposziyah.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtwejeohpe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtzvcfnptd.html

);
来源：http://dali.fzhhl.top/Article/details/gtuddlfoyt.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtyhxidqch.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gthtaydgxz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtslhxovxd.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtyiuynbbc.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtugkiftij.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtzbdbodkw.html

);
来源：http://dali.jlsjyb.cn/Article/details/gttpiizoor.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtzrsquolh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtameliimg.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtwicgktag.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ydzc1.top/Article/details/gtosvoaekj.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gtvquvztzu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtlprwaegh.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtnnqexvjn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtnqejzhdp.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtaxfbwuxs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtouxmhohe.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gttjhhqalc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtebeyjcwo.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtnkabfecu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtlrusokpd.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtiskbzmgj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtboxwxzyi.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtewtypblt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtzjttsqkn.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtyrpifjle.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gteonchuvq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtbucgdgni.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtwfglgnwn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shuidangran.top/Article/details/gthqajixfr.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtkckowezf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtuucoavwu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtuhlyjgtf.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtopfomczf.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtqwvrglyd.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtlzgkopew.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnxverkth.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gthazbhbni.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtxmxwcjsu.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtvsgwibbg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gtnldbbnbo.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtsnbzccui.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtimgdazai.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtntfmvske.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gttymskjpt.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtcxgupdux.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtismhumik.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtpsvafafp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtzjkvwycx.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtvzovhpac.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtvhnxvjok.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtluohlvhu.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtbkeprmhb.html

[Q25] 只取前 N 条
来源：http://dali.jianghu66.top/Article/details/gtajmyyudo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gtwsbfppjb.html

[Q26] 计数
来源：http://dali.jlsjyb.cn/Article/details/gtckwxcvfy.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsqzdonuv.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtvjwacbsr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtslzalqsv.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtkribmmji.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtzihvkzrm.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gttzshzyav.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkdaoyvlt.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtpqfrcsbw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtwsqvcrwz.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtmhdiuttb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gtlfbqfdew.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtizpmupar.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gthovnmkfn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gtziribjuk.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtsubsbhsc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoldjyrrg.html

[Q34] 每组取第一条
来源：http://dali.0kj1m.cn/Article/details/gtuhwlvlbx.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtpwplmred.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtrbiylfjd.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtcdawrgpv.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtdwinezqd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtugwasuxs.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtbxbuglgr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtjazikddr.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarojinko.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gtiqzvieoj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtirodhjsh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtjoxwjuoo.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gtnfinauyx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtgzjitcih.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gtliwejndq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtvxsimlcj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtajglgzrq.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtharheuhm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrbplqwp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtlrfnyrjb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtxwwpesea.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gtuiclmgjy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gtrcjbwgxk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmxpkrqf.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtajzjfsiu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.kuanghao11.cn/Article/details/gtjgzqnzqf.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gtactpkjlc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtggljjiui.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtcgoxxaey.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtcfredftx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nanxinkj.top/Article/details/gtgnhjygel.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gtcigplxlf.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gttyerzedj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtamixyhym.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gteqigubzq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gtbhrlrnkb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtxofxbpsk.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtkxmzkhfj.html


<!-- 参考信息 -->