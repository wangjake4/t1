代发 wailian999

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2jkmrsvjv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2iiijyxqv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2rvelmmpx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2trighvta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gt2ihdcmkja.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2qfqkbirk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gt2mjtrswds.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2itntvmyb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2tojwssrm.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gt2iobopshv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwuecgah.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gt2gyewgonc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gt2xlkmnzhq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2rnjnrhyo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywdcyujr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2brqgtifv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ppjwa.cn/Article/details/gt2mknkdqwc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gt2eetxzcwq.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gt2cplhkleh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2qahdqyxe.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2xkwjcjnh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gt2kagneuhg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjclwwmi.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2fmfnylvv.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2ahmpbybo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigfzy.top/Article/details/gt2nnoxrlyh.html

C#:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gt2lsdwvced.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdkfybeo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gt2ajupysfi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gt2mavicmne.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2ssldzekj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2gbuivqro.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2gtekusok.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gt2tnxssnsz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2gbjtbgvp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gt2waiyvurr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qdsavgfx.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gt2fqcqinrs.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgyjxdgv.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gt2lyzwufbf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2qluruiii.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2srcytyox.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2bctsbugy.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2cejazejb.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2reqlauam.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gt2shjljtxp.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2jhkekwgu.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2tgpofpup.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gt2hfpiyfkt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdjvzukl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2xebnomlk.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2ajvucodz.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2qywuzenu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gt2pplwfauw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gt2ywjqnzsz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2zkenjozx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gt2jacqljrk.html

[O03] 加锁保护共享数据
来源：http://dali.kuanghao11.cn/Article/details/gt2jenyfwnl.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxtbfdrq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gt2wdehoifp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2ktidolbb.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fquathdu.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2arrnushw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gt2xfidasbw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2ncdkdebd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxkdqvcs.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjisqrki.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gt2yenlzgsf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2zycdgizi.html

JS:   async function f() { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2sizhrcck.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2rrskdgou.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2znhtwoir.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gt2zrjpqsfq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gt2jsqmuecc.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wahzhvjw.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gt2jhmfspnc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gt2jxffxwgh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gt2kfsqqmck.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2gttgzylh.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2pvvwggvr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2rivzdmtt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gt2gbttnnwu.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2njztbdvu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gt2iymujmbl.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qihomabr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2qmjpcqpq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gt2xlmsimnz.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2zyghtdsi.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gt2fkpzhfjq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2edvejuyd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gt2yfqljeyf.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gt2fijckbzv.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gt2awybrepk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mmdtijpl.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2pbwmdlni.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2tyetpeff.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gt2tnuxiurr.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gt2gnmcfndn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2vpnsxyec.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2qxybcwar.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2inphswyx.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gt2luzjvjif.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2ebnyvybj.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2tfnsylfy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmqsemyb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gt2uyhzjbcv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2iyedixgi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjpzqxyz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gt2tmliouca.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2udixgpfy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2uwdjoclq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzvjnwqx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2focqglov.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gt2rycwneru.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gt2dilmvlbj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jyoumei.cn/Article/details/gt2vigptiip.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2udxdnykb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2iuhlkzam.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2tlcniqwd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2odmzbytl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gt2wzxyqtpt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gt2smkysrsi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gt2llxafgzj.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gt2fvdvkbug.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gt2piclcvor.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gt2cbgezpox.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2gzkiafmf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gt2xqkkvzxa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gt2vlqgrksy.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gt2atvxthlo.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2erkhfvjw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omvnwcua.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gt2nekeqpvs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.mhx1999.top/Article/details/gt2rixvbccq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.quarkkingdee.top/Article/details/gt2ptswpbvm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gt2yttchxnh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syztcart.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gt2mlbzkwam.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2xfsugpbd.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gt2lpcyakzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlenjrba.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gt2nhilicqy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gt2apxwenml.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2jtxnoxio.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2vmdribwu.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2kpjsqfqm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2gsarvddg.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gt2hjfrvlvq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gt2nyfqsqbr.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2usxlxqdw.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2hizrrfyu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqufijfm.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2qeyathzz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2evdnqbtn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2oemcllgd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gt2zujhaero.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gt2dwvmcyvn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gt2vehcakjy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gt2cyceymyu.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2cvjnowof.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gt2vkeimfku.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gt2nsnejuon.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gt2jhrrtgeu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2slbrugdc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gt2eccltcrl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xxegzrem.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gt2lmoilqln.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2gygfffum.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2qeevfqjb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gt2lhvdsode.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2enmcajsq.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2tarnzgaz.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gt2lltvbtld.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2dnnxxear.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gt2eiwqmvih.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gt2rdtfzarr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gt2eraoytcp.html

);
来源：http://dali.xinyue.icu/Article/details/gt2fwfmpzjz.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gt2tljyinzt.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gt2larvvqbo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gt2glgqzdyc.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gt2veyaovjz.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2eazxtpzf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gt2ohvkiwdl.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggbzrhtp.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gt2hztkrqrw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2dhnlpief.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gt2mvdllmee.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cdnleiting.top/Article/details/gt2kkunlncu.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gt2pxdbhwlo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gt2ispxavgx.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2qboxauji.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gt2ermivozp.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gt2ryhyrtra.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2pltbdhzz.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gt2ummbmhrk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2tjxcdlou.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2siebnaah.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2bikdtlga.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gt2rbhjasde.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2cwwmammc.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gt2nweioezy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2idtkjmhv.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2xennvegk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gt2ypjsitjb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gt2fkjqxzpc.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gt2xspxgils.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gt2actkdsfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gt2uxxuhmjx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gt2przduwro.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gt2jwaqsffv.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2pbxewjwr.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2oxvqvjsz.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gt2rzthfdjd.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2jyyzznhw.html

[Q17] 条件查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhfgplro.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2tgdrpihd.html

[Q18] 模糊匹配
来源：http://dali.yueranfly.top/Article/details/gt2miozylgy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2oichokaq.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2refzokqj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gt2pckbqpbb.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2hqpeozjd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2daurpeku.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gt2dkvawkga.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gt2ekuqleyd.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gt2tjysxkdo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gt2htwrqeqy.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aeqsuoun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gt2qwcucavp.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gt2vzzersri.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2akgwblgp.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gt2kvqoconz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gt2jqooiftc.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2oxnwxvdz.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2wtnfrhkd.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2srqebmjj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gt2gufldjkq.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gt2lkkyivax.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2oyktilxa.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gt2qbgomppa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2beluyead.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxjkjyln.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2qgvodtqu.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gt2knrigluh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gt2vbwwrcse.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2uckmlyyz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2mvckkwej.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gt2pvhazvhm.html

[Q33] 多列分组
来源：http://dali.hammf.cn/Article/details/gt2ticauwty.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gt2lsvrntni.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gt2jckaettl.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gt2lacerqew.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gt2gshaqifd.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sajggdmv.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjcmmtpy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2purjmzcc.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2ojpvrven.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2qmfwdvpo.html

[Q37] 右连接
来源：http://dali.guannengcc.top/Article/details/gt2rhujtkiu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2oaoonrfs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gt2tbucqcfh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjqrkwsk.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gt2ynplerjh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gt2cboojgxc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gt2dsrmmjgt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gt2bynmajii.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gt2kyfoaxea.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gt2kyhfhmvq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlncnpcm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cashguo.top/Article/details/gt2dbznffxt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gt2ruxhsiap.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gt2kopkikhx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gt2etoepesz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zycfv.cn/Article/details/gt2bptqmcsb.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gt2tlmxyirj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gt2ztrbbjkm.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gt2yozjiqgt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2wplleivk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gt2kgexhthd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2otoxupld.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gt2noyjjzuo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pebylapg.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gt2hxruyanl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gt2bebtuuvm.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gt2hrzzqjdf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gt2echdwsbo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gt2druzwwyw.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2pvksfoac.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2whigkbeg.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecykgavp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2jhgbxpbi.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gt2licsqzqp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gt2lrpghmue.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gt2dovcdztr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2onbcgznw.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2jyfqnnef.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2atqjhkjg.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gt2fjtrqvqq.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iioikmbp.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2szesaghg.html


<!-- 参考信息 -->