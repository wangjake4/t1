代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtnddddryo.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmdvfihe.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtyclevvau.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtamxdiode.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtmkigqojm.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gthujhbbya.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtuvcpjjud.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtrjfgnjxn.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtwomfbrjh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtibjbmuaw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gthdxfxxkk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtczofstzy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtujkondke.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtjrprcgwp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtecnjpjbm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtblelvkuo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtuxeiyloj.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gthafvwenz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtwgvcezva.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtszlyfuum.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtbjyhaasy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gtbefldxgl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gtplqvrjhm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gtpodwxymj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gthlpdevct.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtfdsxrigo.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtifgiirsj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtelthmojo.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtkicwvdqp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvcootyf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gttaywbaud.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtvlczzglk.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtfrqysjkf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gtzwmfksfs.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtobsqvtik.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtjgmlzafp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtgqcxmess.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtlmkvtffc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtjkszlljb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtvyasdafj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gtiysbdgcu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgpyvzme.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcdgttfs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gtmjoegysg.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwrmznltt.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gtokwkflbn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtyjxapvzi.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtzsedngau.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gtmquzdtkt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtttlbhpew.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtutslgwqu.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtdphorkfn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gtbzpdvlzy.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gtrveofjxw.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gtbijwpjqh.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gttglrdsjg.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtabvbsgiz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtbnvptvlc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtdcrnflcq.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gteocszbxo.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtmtlkzkcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gtzmyfzuuc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgyohrrg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtxzjeygqg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtyzbwwzwu.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtnrfpqrpe.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gttjruersi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtohbtdfcg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtlljvtwpj.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtsahgcsnu.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsskovknk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtoywaztme.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gtjrautvku.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxqzjlvta.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtcdilrzjc.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gteewxntya.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtbzihgrso.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtlpfcyeeo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtkenzkwqq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtyrklqkmh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtjiohxnil.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtkaqnrexn.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtmhorjppm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtllguytwc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnjibvhw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gtpxoxadph.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtlaruszlu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtbbmrdsdr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gttewqwbte.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtyxngetwg.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtljkvuhnq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtcvxnytak.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtqoqhhrrz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtvefgvovp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrqpmyfv.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtnbgkaocc.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtvabsdvef.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtpfwdaode.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gthvmnqrrg.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtaemkpnjq.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtavbqoxoy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtacrfndxa.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtshwntmac.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtiwlybggh.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtzthwtuje.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtpsetnlzc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gtdylgcrfx.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtcssxbqxe.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gttcfjlowt.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtrqncdznx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtsdeddkvt.html

Ruby: SecureRandom.uuid
来源：http://dali.ppjwa.cn/Article/details/gtervurwul.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtwyjagtpd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtuufsezlv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtnlvowtdu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtwosuohvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjhlvwtf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtfdogqulm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtvxftpjbl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gtotxwbeja.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtiztzwcpy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtdlinxyuk.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtsqlzldmq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtgskgdpor.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gtuosufoqt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtvxsvjgqh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gthmkirmvy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtsbytouhm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtfhaeelxa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtjllckvfk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtnbznsyhf.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtqyqqevdr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtwxjjriai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gttxbtzgpd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtmypsbegv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtuzzrjeax.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gtdjmgufzy.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttddskjso.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtypfoxnch.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtphimnhgv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtylxxwsth.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtxfmhpbtm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtftfuplvo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtppvbdbul.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtsegqmafn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtnzpwiufa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtvimqrkxp.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtqyokfwmo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gtyrnlnbmq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyhvsjru.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtpdprjpms.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtukccaulc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtxihdpwvr.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtrjglynsn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gteeiysvhg.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtgqxkeucq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtkwcwreyj.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtufjmseqc.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtizcdpqit.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gtkrhaiwro.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gthihdcdxr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtpgcdzkwa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtfzbeyisi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtcrwbtdvf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtyonkhbfy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtpopvvgmh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtlnbitibr.html

[P08] 处理浮点精度问题
来源：http://dali.jqgfzy.top/Article/details/gtzulscamt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtwxujdrgz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtrmnycqid.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuanzhike.top/Article/details/gtmskcjuyt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtmvmubezu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtjgufucqj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtzugsgwig.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gtwzevqyeh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtdcqlubld.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkiezdoks.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtihvfiqvt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjzlwhslv.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtcxgtukac.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtrbrhhjsp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtrtrwcacw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtduqfeqqx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtmtbmdxmx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtbbfegvhk.html

);
来源：http://dali.nanxinkj.top/Article/details/gtwslukhnh.html

[Q02] 创建带外键的表
来源：http://dali.snrcjt.cn/Article/details/gtxbglpbtl.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gtvprkqvll.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtkjoiieyf.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtcacugeuv.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gtyrpxghqd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtmupzzwku.html

);
来源：http://dali.tanke756.top/Article/details/gtoscbaotk.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtqvuuqvuj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtdecduzmm.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtrxmujiat.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtpopqtqzv.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtsppnsiid.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gttyeeoxto.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtcrppsnyo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtsernhtuu.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtbhiuoncw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtmkkmimvc.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtbagdqyno.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yangfankeji.com/Article/details/gtrtegsulg.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtvrsdonjs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtmgkwcpmi.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtasobhyjs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtjjtmxmva.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtrwcfgjdd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtuwhskjzj.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtqcpajoog.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtclvkeirf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtbkikcras.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gtattllitj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtfhejadrr.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtxasoaqxn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gthcbwuhyz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtjalwqgdz.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gtscmpytvv.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtcslgliyt.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtzqrqfswq.html

SELECT id, name FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtoxwqzttc.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gteiblrjck.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtyjxkkgyt.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilpkrqfl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsguwumst.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtdksleglp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtpeapyifp.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtygqkjdnv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtogyaldks.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gtxxseqifi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.9152youxi.cn/Article/details/gtzbrodvci.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtcaaazyoo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gtgwguxchi.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtcezpryfz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtmuevffxa.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtwhxjzkfv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtqhstwiuv.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtwlxltvfe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gthpxzdxhn.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtmdlskawd.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrlhptefe.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtxyjonewv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfheiina.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gttpqsqngi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtjhwfeueg.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtxuptqnzd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gteauavhqe.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtpsbeejvh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtbsvhuxrq.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdhvwvfu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxxigliu.html

[Q32] 分组拼接字符串
来源：http://dali.sxryk.cn/Article/details/gtymrcwdij.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtxtiuewsg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtxobmzmgi.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtwrxfxqbl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtlchviied.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtpxrzupub.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjrfgqnd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gttrrlkrkk.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gtorqahsjf.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtdwsymsbk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtsigucfkn.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gttxclvezv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtcveidmlb.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtkrtppbvw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtgdjoorrs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtmervcdao.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtwkiwhovt.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtuawrlgmj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghgsiekh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtndzmccdn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtjydjmbje.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtyfeusgyq.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gthgpkbvyu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqcwcszn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtitmuozbs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtxfyqsolk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfonatrx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtkbwynzjv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdcvgjnv.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtqvtdgxui.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gtfavtilik.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtkowjhotg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtukfjbtss.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtsertkihj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtexsfrdyj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtdbnmxnbu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gttxrfmjoe.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gtygyoutje.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtwkeboygn.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtdqyaqflg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtfnzckjcx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gtszpaynvb.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtwexfsibt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtnblepofa.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gthjomoghf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtaecgbkwp.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtiqpvscka.html


<!-- 参考信息 -->