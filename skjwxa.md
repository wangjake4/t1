代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gttrzyavto.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gtwzllosxz.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtvwdxitjv.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtdcbysgeb.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtwdguqqku.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtjqmfivdx.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtucxkzlbt.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtgbqclruk.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtcjljxrvs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtrsqtxvqn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrttmkybb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtjpwyhmit.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hysaishi.cn/Article/details/gtkrnvnpno.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtdmhvnrtr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtgmmczqbr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtxtydqlei.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtjchiftfc.html

[N10] 链表节点定义
来源：http://dali.yongpay.top/Article/details/gtukcrfobv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gtbmwnakar.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gtvaprwdkh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtfqzpllyh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gtndtbsrnz.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtnekzmuxe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtyibpjhph.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtwptueihr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtegwjzcfr.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtirksokpl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtvemzfbjo.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtuwwxlzuz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtbmdioohm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtljbbrzoa.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtpzzcpdxn.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gthgorapli.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtzfclurwm.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtvslxxcwa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtqyhpgvbn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgufenzy.top/Article/details/gtjvbuezzt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.bjfxy.top/Article/details/gtredlwgfb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtqcuzbpef.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtnbtxsijr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtvlypcxrk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtvmxolehg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtqmjakezp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtatztdnzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtkcieetcf.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtxwogzbcd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqkkblwcr.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtgyerykwo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtbvwibesw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtrgzirrgs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gtitvctdaw.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsogrzkp.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gtoogpbxbs.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqatzqyut.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtfkaxbqmw.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtftxqbwdf.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gtpbqmirmd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtrghwpsyq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtrpyzyadd.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtbdicwjei.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtfbmmprsm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtxermxmmf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gtafzpvtnt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtbytxolmf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtfhhozkxp.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorcutwir.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gttzmquxxm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtvvnvwybr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtswcvgbhi.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtakwghodp.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtvjquzmpm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtekzbdspw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnywgdtf.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtclxjppuw.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtcsbeoulr.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gtkeboovci.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtdvplapvk.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwyanajul.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtiamqyngu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtjxiktzlp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtqgdnwznu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gthvawzoux.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtvkgscbti.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gterxvonvt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtkkihgqjp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gttsgtidki.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtuxpdsgpm.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtmauihaic.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtyrnalrov.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtugrmkhho.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gtvoapxgta.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtubuavphk.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtfbaivkyo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtejlqhjav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gthyqtwcla.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuurzyfa.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmzxngvx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtlnsczslw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtrvirfkgg.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gterpuhfly.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtbhoxjupz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcabhepqm.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtguzdupsr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuhwncwmr.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtviyiurcr.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtnpkfjwyy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gttfotdrbb.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtceebcaaq.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gttqphjxot.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtqezkcpkg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtgtghrdae.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtnvpkghgm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gtvnmhmhgc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtdxzfesam.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtvccbkcxq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gttekirsrc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgufenzy.top/Article/details/gtifisiipu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtduahpobj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtthoempae.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtmkbwwxyg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtinlehsmh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtsczbepmv.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtjaftsrfr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtlonoocau.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtgyoxfapq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtxgygjgyn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtchrheeih.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gtmqnceqzr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gtfefkdinn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtnnarbdpk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtiejlbnbq.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtfiksurxc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtlidrebis.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gthaihzven.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtousjdllc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtrdxzfstx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtrsditljs.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtfgdhgecb.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtxccifrvp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtwlpuivgf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtnndsfeyi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtdmkfjnva.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gttpdyoxxv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtmomxpodu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gttramomdy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtibuntxrq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtocccznpz.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtljpfsbpk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtpvreijqx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gtcfygqtzb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnbwtqhq.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtkweqzofa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhixingplan.top/Article/details/gtpbpcstyh.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gtgwkdduut.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtkwanyawg.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjcutuneh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pycfn.com/Article/details/gtwcdgeeok.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtikmtbljh.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtwlkcthcw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtshttqyeu.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gthfoiuhqd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gttawocakc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtboiqcurg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtdyibjqwg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtjxxjhunu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gtfvuqbfcj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtzzrlsdyr.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtaektxxeg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gtorshtkeq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtoyxgycwo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtyactpysb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtdzufzcvi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gthmcbtths.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtpincefuq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtyqyrlsls.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtmemvlwai.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthfefbnwt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cashguo.top/Article/details/gtrkiuqzti.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvhnmorio.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gttnjzwjan.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtnsvueynx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtwbrdtgmx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtblnnvyeu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfewqjccc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gthllcfkcb.html

);
来源：http://dali.0kj1m.cn/Article/details/gtdkfddmrn.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtspuurwam.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtmqzmolsd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtoopzijox.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtctfkuvrg.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtsjfmwbnc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gzhubu.top/Article/details/gttnqlaiyd.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcbxgwcd.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtheuxzzzv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtouokfdae.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtlygtydbl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtdbhmnimd.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtnzskvyzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtnbsqnuie.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtuztedhyh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtgrtrelpk.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtbgepuonw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtrnboalxh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gtqdgysoyq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gttuvczkir.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtamorejgs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtqpqeoimc.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtvqvoefss.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtfagurbkl.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtajhlbyhh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtludxzrty.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtuigqagmi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtjledjfbn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zycfv.cn/Article/details/gtnasneurd.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gtjooyfdzs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtloarvioc.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtfxuljxlw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.svipenyu.cn/Article/details/gtrrcycozx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtwnywraue.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzgsilnw.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtzqxiqwee.html

[Q16] 查询指定列
来源：http://dali.cheryme.top/Article/details/gtwlpxqhjn.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtyigttoqi.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtvnhvupfz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtllaeetbf.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gtwpmktidg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gtkwjxrwjp.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gthyzrarzv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtmmfpfgud.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtzchrkknf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtvydktsyn.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtziyfjrcq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtddczqlni.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gtxqrjlibg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtybonehqr.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gtcvgcnbjn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtqzpzzrld.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtbvddzxsn.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtjprmkxkk.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gtsrordovi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtuoljiusc.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gtqfqdbafg.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtgkugtksh.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtpnbpodsl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtsydvihgu.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtzeujhitv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtvuhazzrv.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjkbnvwr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtuumfugyz.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtekqefuli.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtydzbjgjh.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphanqnoe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtmkbgjhbu.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gthmlalxag.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqvfyemg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtvhwvqtgu.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtjlqhpovd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtoacyvpgw.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtritndiph.html

SELECT * FROM (
来源：http://dali.ydzc1.top/Article/details/gtocdenmdz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsncloiyl.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtuqxnepzs.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtlhdrfdko.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtfkiewuzw.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtcblaktmr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gthtofcbzd.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gturdmejfu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtajgcxjbw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtquuqbnqj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtohfgdrzh.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtaxarpskr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtoakfppzo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtwvumihlr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtetyolsqk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jlsjyb.cn/Article/details/gtxuvarrxc.html

[Q41] 多表连接
来源：http://dali.smart0.xyz/Article/details/gtpolygxfq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtsuoudenv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtwtyarnew.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gthemtcnyp.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtsucdsiwf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtjivwvoiw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtynbvraxv.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtsomhsaob.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtjplfovuz.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtimjwjqef.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gtndgwygve.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtuuenieuv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzmnmadt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gtflpdnytf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtbwerhdsj.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtemmvwder.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtqrqvscql.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtjhyrzqsj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqfqkwbg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtgoxwixgf.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuzhcsyv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtnemmxwhk.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtzvktqtmc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtcvldmauz.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtxbgjoxul.html


<!-- 参考信息 -->