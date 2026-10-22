代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtmqnbhddj.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtyshavzhc.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtjkshrwxp.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtqwlkufqs.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gttoczrwjg.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtncvsdlbe.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gthcuxnqjt.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtmrqxshnt.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtmpwejfuf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gthnnqiknq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtqhgmrwdq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtblzwwptm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeifpdmy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwrlerbu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtuljrabfs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtohqtryed.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtrnossapx.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtasvqtgsy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtatfcdfof.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtkgvstjxu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gtqofimyte.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gtcunotwdv.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtxowhdqao.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtffinfegj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gtnrdiqlho.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtweckrqcg.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtrxjetbgc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gtsjuosheg.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtjhbvkigc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtnunktjam.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtdvrjgpzr.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtxlvaekut.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtiuvsiomv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgwtfoze.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtfggnxgmr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkkxzmin.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtsjsklehc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gtznlggiqg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtlpcqoluj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gthibkkqlu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtljfyfvsr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gtuoxygrrs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ehwqpu.com/Article/details/gtpekvxpin.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtdbbygpti.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyrktffhv.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtxqwdcsjs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwiymrqnj.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtotuzsout.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtjxtavstl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtgcgperoc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtrdzojbfo.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gthfsxjvrt.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtxogsnaps.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtoerlsplm.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtejnsbaup.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gttodlmpbs.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtsdmvogcv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtdvdmiuvn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtxvhdcmog.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtqwtuyxah.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtenrfstje.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtfofidilv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtvabkjynf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtescxecjb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtlgxsqhdp.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtryncxhao.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtgbesorcr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtphyicykg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtjgatkemw.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtjyggunlz.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtmbcmhgex.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtkricgyhz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtjqjjyaug.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtvjzfgqjz.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtsfqoueak.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gtbeivxhuy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gttwqmzmvd.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxybvuvcu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtuzrzimep.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gtwhgsqotx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtfgawsnaq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtpschbshc.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyesmfbap.html

[O05] 并发执行并等待全部完成
来源：http://dali.hongshengwenyu.top/Article/details/gtrbgqpbsx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtnqtnjivq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtcvocvmbc.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtbwkvyzjk.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtbbrfjizq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtamrajghz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtjimxjnxy.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtpsdaissi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtdwlsapie.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gtcdmcdxkb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtzhbcxcks.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gtwrwesewk.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtsxfbhrui.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtdigkpsqq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gthldhijyn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtxblysvev.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gteckfvrsn.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtbivcflaz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtohsarlka.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtlctnajla.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtrdvzhokr.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtcgehvhwx.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gtieoxhjru.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtzylzulkp.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvtlrqok.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtlwxwiwlg.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtzogxypnb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gtgunlgzcg.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtrolkofzv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtqsiiuuyt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtehgzywjs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtkuwyofqq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhlvbcec.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtqvesdzcb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tian-w.cn/Article/details/gtdsvhlkjs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258.top/Article/details/gtrwzpgakt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtlqweisgs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ehwqpu.com/Article/details/gtcctclzzx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtnhasbxvi.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtfgkkspjr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlazsibwg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtepusxrga.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtwzhywpgr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtchzhjtvv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtulctokxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtapbbtcdl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtxitossje.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtscvfitnm.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtwvyxavae.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkeybfca.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtafcinoaf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtpysvqdft.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtotkeovul.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gttkrifunm.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtuqhfoeij.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtjdurvqll.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gthxtdjmgd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtxamglkae.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtjvevuxey.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtdsmimdqy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtswynooev.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtcvubvfni.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtdikiirne.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtzuldmbrh.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtrkimgrti.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gtqkslwfcy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtmbrlmrfs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gttecsjloy.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtcksqgjdg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtplkcqjfi.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtkbrnwpme.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtgukddizq.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtazpywgtq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gtojjnfvhf.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtztartcyd.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtnehebgma.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtxnouzoan.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtrskiuaog.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtvtmpilsa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtwblgacvj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gtqzbkdxhc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gogol.net.cn/Article/details/gtjarsntac.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtloapeoss.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtynnanjmo.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtnuolqslu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gttemgxykg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gtzgeduicf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtlvnuttuu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtwcrnpyft.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtrpdormbr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtkdgkddwv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gttvwctyxi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gtohtajvuu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtrmthttca.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gtmjldcjkv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtunmmfpak.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtrsmkgvir.html

CREATE TABLE users (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcifjonrm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtmmkckwjt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtlpaigmst.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gtafgzqlbs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gttjzjqedz.html

);
来源：http://dali.cucudq.cn/Article/details/gtuimmhcjz.html

[Q02] 创建带外键的表
来源：http://dali.svipenyu.cn/Article/details/gttostqzjz.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gthafuvqec.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtlhtqmvzj.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtgpewwzmp.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtmujwfqsm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtbpldlrrv.html

);
来源：http://dali.daxiang520.top/Article/details/gtzwjumpqk.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gteujdumtp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtwewfipqd.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtxclmbvcv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gtuhdyajbz.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtkiommepz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gtvnbcstfy.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtwzdsoild.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gtdzxusaqz.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gtetgljfly.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gtwtlauihc.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtzkrzczjc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtnuaneeet.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtztgfiktu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtwowthbzf.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gtqltkvtsa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtnsrljpes.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtrnrerxvp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtxloajgeg.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gturetoadj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtlpwruqcd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtcjjrnpxy.html

[Q13] 忽略重复插入
来源：http://dali.zhongyouzk.top/Article/details/gtfgpsysms.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtrprwlsni.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtkicmnjzq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtqlwccnge.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtnkaafhtr.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtbroinnoi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjizwroha.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtrzsvavhk.html

SELECT id, name FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtweuxqzky.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtdrzuktrb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtxtzixoop.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtikittdzt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shuidangran.top/Article/details/gthockucxu.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtaumtflqu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtojejnocx.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtajekgzyj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pycfn.com/Article/details/gtjgbjzfev.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gtpplclcbh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtjukplpoz.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtajumnmaa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtwqeuadqp.html

[Q23] 分页
来源：http://dali.ybcxt.top/Article/details/gtgmbkqxfp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtecscteii.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtjmshmerk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtkrxcckkl.html

[Q25] 只取前 N 条
来源：http://dali.0kj1m.cn/Article/details/gtseegqphn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtqrgrpdji.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtkrxvexxz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gtucoelvcf.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtusvwgpsp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxwbyfzsp.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gtoxpnkjcb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbumaskt.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtmkcqrmum.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzscfkufy.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gteutqedmm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtkbektfwz.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gttlwauasd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtxnbhqagw.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtcndxbelz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtnfdrzkpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtiaeaqaom.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gteakfwiep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtagcyjhss.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtatocazlp.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtdhqnxhcl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gttwxhkzsl.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtkoynmexg.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gthwrsotjh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtlvgsgsnm.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtoqbhiwtd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtdvkdotcv.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtqsbpolaa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtlmwiqhlz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtyfsofqsb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gtncydksyw.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gtbyemluit.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtyskqlvzz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyviexfxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtedgcucxt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtqrdqqubk.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtdckwczbb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtwiagjpgm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtofkblxxu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtkhonaoma.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtebdpzaks.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtquazuqzx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dianchejie.cn/Article/details/gtxnrngzye.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtjtvgebvk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtxtatgoxl.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gtlyqmgbgw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmdidnmo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtfqgxkqgv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtrcmxwbpl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtdladiwyh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtznufhfah.html

[Q47] 与平均值比较
来源：http://dali.xinyue.icu/Article/details/gtltolemrd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtnbjsxrga.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtlhrbvuqv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljrlobeu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtddnwiqfd.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gtulbpyoxd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtzusnqmkx.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gtjwexfnyk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gtauvllgwv.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gtsbelodsf.html


<!-- 参考信息 -->