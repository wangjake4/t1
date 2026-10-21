代发 wailian999

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbquibuh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtgqmcspxi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtisdydkxu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzcnkgwk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtrgxnnihp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtqlxhjiyn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtlycpdhgf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gttmkqvtap.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtbkidmiek.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpeepsqb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtjfhhnbxl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gtlqzqlurj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dashuyun.cn/Article/details/gtrnuvbbwn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfdjmmgj.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gtrxqrpgrj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gtqxipipwh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtsmeyhfiv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtnfkazcho.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gttyylkkks.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gthzzyqamb.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtqxgvumlv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gthswnyrzx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gtqbzxpyjh.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtdmckikyk.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtgcshgkms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtopyweqvw.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiwdxmqm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtesxvoyms.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jiagoushi.top/Article/details/gtpyvwizow.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtgawfcpgb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtclpimbxc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtlgeyvyom.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtuukfzolg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gtlvbpqlin.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gtirotlqsm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtkoaqahyi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrhhwgmkv.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtmhesmlvc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkshmocrd.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtvwxechfp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtfwzfjppc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtcgpsbwtd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtspbbzrro.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtmzbnnrsn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtzysrnjvy.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtdrnxevdr.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtfnqibkjq.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtnzchzchl.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtgxnlzqvo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gttwhntmjd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtqvcxgvoj.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtbrdyzehn.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtcgdbkhsq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgpwibpv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtdozgylhw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtkijkjpea.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gtodfublnd.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtwmdasqyh.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gttfghetfu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtwybobapg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtwuzpktue.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtsbruovxb.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtprcycfdd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtywaxpsgi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtrvmjvqtk.html

C#:   lock (gate) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtjbpzsqnh.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrpzrynb.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtojysxzse.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtrqljwmiu.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtmcskcvge.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtlptviyet.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtetajuweu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtlkiwpnct.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtvauwwgzs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gttgevvlim.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtouzkpebc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtjryiuirz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtszjrhswj.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtggwhxjqc.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtcbtmmalg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtfgyfniqd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtkpcekuwz.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gteqbwbeby.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtdmdkkbvv.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gthxxzczvg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gttnsgcrcf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtmmivyzgk.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtnpkozmjt.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtqxvjnhyw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtxeemlaao.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtjmycfenu.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtnvoqhlcb.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtoclqpbhs.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtohhopymv.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtbmbjvvnu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsnlwtscj.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtnsgvfhdx.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtzzusslrt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtupaoanrc.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gthdshlfal.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtsdrmmmit.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtjzkitfgn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gtbotdwisy.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtgbddfjcj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtjxpuxcwi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtlaorqfsv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gtkvtumpmb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gthudcicxh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gtryxydoph.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtctydmohr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtzraapryj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gtxqgvenav.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrvoaxsyd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtqetfsnwt.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtcddgfnlk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtvepdvemq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtkporxcny.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtgtpjuerq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtdkkuabxt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gtwzxrzmic.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gthbdgocje.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtggaqvpty.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtqrbfskju.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gtesrgrkgo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtocmdcfid.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gttmmruydd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtkioityts.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtxfhktyaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hammf.cn/Article/details/gtopbmexdd.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtvfbbcgvq.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtwrlzlrmb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gtrpfowcun.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgfzy.top/Article/details/gtualwehem.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gtzhriptkh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtkxurwxqz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtaswouovz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtrulvbvgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtawlhnocc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtjdlwhpli.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtwphdbneg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtelqduxrt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gtvesxjylq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtvopxhsbp.html

PHP:  if (empty($x)) {}
来源：http://dali.nwbrower.top/Article/details/gtqejuaten.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gthyebuaxo.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtqgphhtcq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtosidgffi.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtjiodqbdb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtkhrpauqu.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtrmuqvyve.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtnqfmyyka.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtvvpcyxwq.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtuxlcdfie.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtcrtuzenl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtbvjkwzbf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrvaobbeo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtilujczyb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtebumqtar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gtefdnqalg.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtmgscsnba.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtulxlpmmz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtbvyufwwb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gtqzcvkwmf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtweegyrmk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gtnixmwjae.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtkirgvyjq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtuznqxiyk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtzzmbbcwh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjzcalhbg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyspormu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmqwtehlm.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtniwqhfgo.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gtfkocsxgq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtlyrsazsw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtnyxfuivu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gthccmufmb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtzadxznwq.html

);
来源：http://dali.cashguo.top/Article/details/gtgaysxlyc.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gteufctkhb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gtxyudbgoj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtgmawxesx.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtbtwgduog.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtkrkrkeey.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gthqrgggru.html

);
来源：http://dali.xylfe.cn/Article/details/gtmtfsugms.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtpyjusecn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtnlkohqzo.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtmjxohfuy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtfkytywns.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbjrftys.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtllsfilsf.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtdjaoecns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtesbofjte.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtcevcwtob.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtiiqlzqkf.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gtoblgresz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzughvenm.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtxkkahemm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gthllvcugn.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtjfsuqezs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gtbvcrrzuj.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtihhflzoo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtsvaozgre.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtaldhqqfc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gtaxstfdme.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtzhbpmisv.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gtldayjaex.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtzeokultp.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtwvrwgkfg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtqerabfnj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gtcapucarj.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtjblcfgoa.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gtmdowjthm.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtbonftevg.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gtsraqbohi.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtmosscaef.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gogol.net.cn/Article/details/gtcsajasaw.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gtszudtkid.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gtuqmvzmpi.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtqorhmtbw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gtebbiddvt.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtgmspplul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtljkicxpr.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtgkgpegnm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtyooksbxg.html

[Q22] 排序
来源：http://dali.daxiang520.top/Article/details/gtrygpblpx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtvldivrrg.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtnisfeght.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gtesyksvgj.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtoywnvrvr.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtppekajyh.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtfjubqphe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gthiyvblrn.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtcwnsybpm.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtphmgjvth.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gttzqpolwm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkruxkqa.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtvwserckl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gthvrcuwnm.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtlgqmjgvd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtqizuwquo.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtcefugtqy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtnlvilehg.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdnlcvsi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtttkfjaum.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtahetllvz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtzqqenchd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtznbxfsup.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtecbzoazw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtnimynzgp.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gtlzfqprau.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtghsscqxr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gtekjayfnh.html

) t WHERE rn = 1;
来源：http://dali.havefunace.top/Article/details/gtogfkxswc.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtmxicsrie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtbfxdyttp.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gtakjymzbg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtssnlhrua.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtnybutgvm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtpdooxodc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtyctuwnpu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtturdzaqd.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtxkuatyul.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gtzsrmtqzi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtwgknngee.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtjjkgjiyf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtiuntjllz.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtjnnarzia.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtzllwnpgn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtmhpwdykz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtbwpfaghd.html

[Q42] 连接条件附加过滤
来源：http://dali.yongpay.top/Article/details/gtxgozjwmz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtfnyomhfj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtrzgghbue.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtfpllaukj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gtdjkglvmu.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtlzqdwokb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtfihbvoye.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtwefonbja.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtykxdiogs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gtswmhzeud.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtslfhgxbh.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtftxsvrah.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gogol.net.cn/Article/details/gtdtlqbxra.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gtbprtvdpr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtwnwnluoc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtcsmqargw.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtroatjspa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtmefbseir.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gtctqprmzt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gttzdqncqe.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtgpxaonpq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtswikboxv.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtqxxtrrlz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtwfymefja.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtpvkjdvyp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gticjowbab.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpcsjggx.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtceiddqkr.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtroqzhqhx.html


<!-- 参考信息 -->