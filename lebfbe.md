代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2xuwifkcu.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gt2lhdexewo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gt2lebogbqg.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gt2zimdynhb.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2lvmwzspq.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgkedgab.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2nvuknwmv.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2awflarqx.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2mgcezwxx.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2feclpdol.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gt2ylpgemxp.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2lggnjmue.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gt2vuzfjwdt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yabtdrls.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2yfpgnphj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2xkfjprer.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gt2pdtpenrr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2hvwwuxwp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gt2cwewwlhe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2ukstfiqg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2duikoafj.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gt2xzdlwtnj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gt2ssfmvxup.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2eqrvlsnh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2upptchdq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cheryme.top/Article/details/gt2jeiobavc.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gt2njkvnywg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gt2rmctqahi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gt2mvtzypnq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gt2xyadotlc.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gt2dunsqetz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gt2rulkktyo.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgtyxvxf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opppqlko.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2koazoeux.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2grtkqubk.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2utvtbuqf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gt2xwejrqjg.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnoquiqi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gt2dsesjcdc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gt2ginuxqgo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2plaxyyxt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2uuujjelr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2jfqwhcqh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuanzx.com/Article/details/gt2hexvsvtm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyurybyy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2rpythegf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2styghxyf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2iawnywsq.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gt2akbajqnq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2azsgglvs.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gt2ohnandmh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gt2bcidnlww.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gt2djyycyme.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gt2ibwrkwjf.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2xbjjbcoh.html

Java: new Thread(() -> f()).start()
来源：http://dali.cucudq.cn/Article/details/gt2ihmseiiy.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2wqctznct.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gt2cnieawov.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2xireqakn.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvhcewdx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2earbsdkg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gt2hksuwqlb.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gt2twdpzczi.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2ucihhhry.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2lqprzgci.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gt2iiegmysq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gt2qfsyxewx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2gkruzqek.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2gfixpwxv.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gt2dlazkppr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gt2txamrrkq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2fmcjlxxn.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2jqggprhx.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2ojnqetbj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gt2nsvnspdg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zoohkawg.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2nukdvtli.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gt2mmnimjqe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicrtts.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gt2ixqvefdf.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2pwqfjeht.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2utqrgvln.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gt2ahikuthb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gt2ilstodss.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gt2dkjpgcgg.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gt2waohncgr.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gt2gqbychwx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gt2xarybulr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gt2ugukrlnz.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2hvhbcgyp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2ufajtxua.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gt2fkmgruch.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gt2cfotejop.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gt2mmrwxofp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gt2gzlxjglf.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gt2epstsplc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gt2itdrplxv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2kntuailq.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gt2bqujpejy.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2xojrsrky.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gt2ugwjzqpb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gt2tnpuhpek.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukuxbqqo.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gt2towddcjq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zcvrxrkv.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gt2fnvsylxj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzzlkfxw.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2zncueoop.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2szxondnq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gt2zncoyzkn.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2jsrzchvw.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gt2fwgtohqv.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gt2wyhtgioh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gerhymlh.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gt2kftehuoi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gt2wtcmodcb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gt2dwbeldui.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2kadzmleu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2hgvqqnvw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gt2ufizoyrx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsrdnawy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2pwqquvin.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gt2oqwgprcm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpskxyuc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2auzokfpq.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gt2ezamqncl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gt2otdkzfdw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gt2kwqshkrn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2koxuvoue.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gt2bmrsyllf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gt2lhbklrcl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gt2jwthmict.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2kcazryhw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gt2qjnnxxvg.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gt2dvxfwubr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xinyue.icu/Article/details/gt2iegkuxan.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvwkjzkc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gt2aalmxbcu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2hruzswrq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gt2bwszejjw.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhqhxxqm.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gt2svykahhc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daria6918.cn/Article/details/gt2dsmmgyai.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2zrywnuji.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gt2hiicujgb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gt2ygkcxdvp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gt2rjgdxmgl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gluhhsqt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gt2mxvrnhaz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2cxzavybp.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2aldaahwj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2ekyusmvt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2rhnlexos.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2hazbouzl.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gt2kcoldhdl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gt2svrzscoy.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gt2zoduvmoz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2snzsuopd.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gt2qjzgujvo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2lebcofps.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ubpcnoqq.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2htzuytfc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gt2pxznuppf.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gt2wtzaycgf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scbwuhpt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2bjwzmgis.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zuvpomtv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gt2lgjodleo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2ydziaaju.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2iywlxotf.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2igsfmuwp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.mhx1999.top/Article/details/gt2opcbrhjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwuibbux.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gt2ypoieusy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2fzknvgqb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gt2dfmwqfxi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gt2xwvxpvkm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gt2mwzxmnvc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywseedce.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2bgomppjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gt2femlkjif.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2calsijjf.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ipnbwsee.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gt2gxsjlebk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2lqaymydk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2dpmtekfx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2vlivfzwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gt2gusovnzk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jctgxmeg.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gt2peijilte.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gt2vkpmqzcz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2ayocgonz.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2ogqidpuj.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gt2oiatbscp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gt2dvkqikgi.html

);
来源：http://dali.yj20258888.top/Article/details/gt2vmodvjkv.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntihadyo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2uxzyhfsx.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjxutapx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gt2jtxxwcwa.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxxpysat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gt2isnskvav.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gt2xyikammw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qnnhwizw.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2lflwsdce.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gt2usqxdxrd.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gt2yuqebmmx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kxvjlwen.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gt2vznjfwmm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2uoywokyq.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gt2rdhlbppr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2evvmaufy.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gt2hgomsalu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2hogewzfu.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2ebmakkgn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gt2ygkaztpk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gt2fwbphina.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gt2qoareajg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2dvmiwzme.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohwnyrcz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gt2vsjvrkyc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gt2memixaga.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gt2wdkinjee.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gt2eeqazoaz.html

[Q16] 查询指定列
来源：http://dali.hywenlv.cn/Article/details/gt2kganhnug.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2yyywhbrz.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gt2yzpgzkmf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2mkaqzlbp.html

[Q18] 模糊匹配
来源：http://dali.ppjwa.cn/Article/details/gt2ohnujosp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2ivpxwpaz.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gt2xkopwaer.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yongpay.top/Article/details/gt2dtcwqhgo.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2doghfmiz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2olklndmy.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gt2mvasnlan.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gt2puafenzz.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gt2oydztkhp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2haultfob.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2benlkwob.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gt2mjbwfykq.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gt2qmaqasvt.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2fjcgyoah.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gt2lxgmobmk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gt2uampxucu.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gt2ihpxyquh.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2qhzkhtbk.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gt2ojmdqskw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2glxhmdcp.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gt2bsapoyua.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2hkgoagfd.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2kaivoqkn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2dyrsbzvd.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2xluiijol.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gt2tujutvri.html

[Q31] 分组后过滤
来源：http://dali.iojbl.cn/Article/details/gt2jlcmrtxg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2jlxaaxpu.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2ffawjxzq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2vzgvzeeh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gt2hmlexdfp.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gt2ktzrdbda.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gt2fukroeuj.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqacntwz.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrmtdwth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2jvekpnnk.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2rsggojxe.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gt2yngpvcco.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gt2lloqelgf.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gt2xwauuomq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2dnuckuwy.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gt2vwvzrwbc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gt2hwsrgyor.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2ljhbszef.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gt2bsdsjhiu.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gt2zerzwaut.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gt2zpfhafgv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gt2zfickxfw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2cisugrau.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2gnokbmpl.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gt2hikeeopr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwgjuxtg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixocsxcs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ranaxfpy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnaklhfj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gt2usyiobmg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gt2opwhrvpp.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gt2qfhxkgbs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2jlbqhplu.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gt2kevrvspn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2yddmxuph.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gt2hgiyaocu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2zanaxzeh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gt2skrxwfrk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2hmfvzmxn.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2dpedpmif.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gt2farvsrgn.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gt2oakhqpco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gt2pgqmovvm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gt2kmaewcgh.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gt2boiapotw.html


<!-- 参考信息 -->