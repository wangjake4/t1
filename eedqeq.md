代发 wailian999

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gtxbetupuk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtmwwyqfkr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gttibjasir.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtmuyvfohn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gttlifnfwa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtlfnzodhw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gttczvooml.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gttdeddbrf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtzrjuyjpn.html

[N10] 链表节点定义
来源：http://dali.yj202588.top/Article/details/gttgxwfpwz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtvmlljbqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtycwfdgej.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtadtflzsk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtidqxdyok.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gthasxfldo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtjskklyts.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gttrgonden.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtgwtqyrdd.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtzltphakn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtvjcmghzq.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gtobloatvk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtbcrubzow.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtragudihd.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtbysbdwri.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtbnctfnpe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangshuangyany.cn/Article/details/gtrpilcyzb.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtwmdrweqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtyxsiaoke.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtwvhkddld.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtfftlmkqf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtrbedxgez.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtiyfgmmtn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflcvijmp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtjoxkqtkd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtdmwujrgl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtcfurhoha.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsfoweplz.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtikcufrat.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiehhnqtf.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqsbegbb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtaovefcxh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtwwkxlvjz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtjibonbiw.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtgunmdoip.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gttesopgkl.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtqocyoqup.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gttpvgjjod.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtfdjanstr.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtgjzpuwbt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpmnjdvz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtuwxewrvp.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtmufuvody.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtxhqtaavi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gthppvkzny.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtkzfdbrnu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtpihbwzlw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtoanrtzwm.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtyxfyowjx.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtbfkomuqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtunegglku.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtiyeajylv.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtpglimmdi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtapflnjxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtqtmhfthh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtnznhrwze.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtnvfepvzt.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtvryridso.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtitrmtoop.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gtqajfbmwf.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtgyinbvif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtdpqkkshv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticockfqj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gtdriwzsjt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtgbxggbee.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtsobhhvav.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtojsudiqc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtwuiwkyyk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtxqllwjxy.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtidgjknin.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgtxodiy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtfojvmhfa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtgibccltv.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtvinwrcry.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gtuxzgsmfy.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtevjupwnj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtbnzbdovi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtizyenviy.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtpqnmigue.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtpqnrwesa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtcoblrqgp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtustljbkl.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gtatfirpxs.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtzpavmysw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkumpmdkg.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtujcupbrl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtwigwfbha.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtopohqhsm.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtsqwbrqfh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtvbxipplu.html

JS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtrfmtfcgu.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtgrybevjf.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtbgbdggiz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtknlpilzj.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtvklcxwic.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgysxlkhw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gtoctyevtl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtnvcvhrxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gtqnmaimfs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtilfeczrk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258888.top/Article/details/gtecnsibrj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtbifojqws.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtirpwisxb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtydksxdyl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gtfhdynmpk.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtrefmavtb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtrvvqapow.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gtcictrgwl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtyeexhvub.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtntyywiek.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gttnmjakax.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gthlktorhe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtcigiehxh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtcfrsewyx.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtpjvizubt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtwhwoloph.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtqsayzxkd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtpzjljedo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtbsnzcodx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gthhzgxbkh.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtdjuwgsrf.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtaflkkgxw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtyrxkulsl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtnqrxvpnx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxuanxn.top/Article/details/gtynsdwqeu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtidmwwzcw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtiebbqovs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtomuriflf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtbxuysxkr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtombnocor.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gtbotlujzz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtqdxxdoti.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gteqvwrhvk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gtpeoolofa.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtglubqsbp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtlprnjmwt.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gttvcqtpzi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtsknunqos.html

Go:   if x == nil {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnokjujfd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtnbnzwmun.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhrnhipb.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtlxplqlbj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtxftvhmrs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtefidzmsi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtyzfagkxm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtbgxqzefr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gtuexwkvay.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gtgvffldys.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gturxuoldm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtjjosvzqs.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gttterjndp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gttidhfwhq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtxznqwhhy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangtech.top/Article/details/gtupelsosr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtkzzrqshn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gttizcpelo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtsbhyqybe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtpwhgueru.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gtlsbkzynh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gteprqsljl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tianlin.xyz/Article/details/gtlcxewyzk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwzizspk.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtotqynzwa.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtvmyvqwhw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gticrbdwju.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtkhbxboxr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnsehjul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtdtihpyny.html

);
来源：http://dali.xinyue.icu/Article/details/gtyalkzhuf.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gttvtmedps.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtjmqibzgl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtuqrivtfs.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtyuiyznut.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtfjexpkgk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkivjipd.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuielzszx.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtafnuqmpq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gteffdbhua.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtgnfrinof.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtejnssqme.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtiuuqhtwo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtxbtzezos.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtolihhcjw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gtuprvbbyr.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gtudgyeryc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtfgqussor.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtzxaelykb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gttazyzxws.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gttcijkwud.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtylbunild.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtrlsmsquz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbkacdhj.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gtyhomhqdp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtcivmkgpf.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdryfanj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtwuxahtnr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtlavmrlua.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtcraoozfz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtzuwnavew.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gtpufyyqah.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtmdxsezwa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.snrcjt.cn/Article/details/gtebdnoisp.html

[Q15] 查询全部
来源：http://dali.dianchejie.cn/Article/details/gtpumgncxa.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtgkbtuuql.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gtrsndaqop.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxwegxtxx.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtmcaqixuw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtisgyqkcg.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtdjelwjhx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtjsuszpov.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtfkqcnrwc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtucjmsoua.html

[Q20] IN 列表
来源：http://dali.jianghu66.top/Article/details/gtwnrkcsel.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gtarbrrmao.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtrvfiaeqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gtqkrbwdqa.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtlfkqedrd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gtxptwugfq.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtguxuvycn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gteemngmhi.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtrvyqcech.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtabirhxrl.html

[Q25] 只取前 N 条
来源：http://dali.hammf.cn/Article/details/gtuzuhsbav.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapzwdffj.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtvjxepj.html

SELECT COUNT(*) FROM users;
来源：http://dali.316326.xyz/Article/details/gtfkbrxxuc.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtjyrotnld.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtvahqxdtw.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtmqbmhhdy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtzqxztoka.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwlnmdnp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmugvqbic.html

[Q30] 分组统计
来源：http://dali.ivvv.top/Article/details/gtkwphnkzh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtsfjjjgsu.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtbuskkhdo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtbnsgilno.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoqjdtpm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtfzgquxxv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtfedwytdb.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtjnygwyoi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gtxzkzjgds.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gtzrmdglfy.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gtfqgpsbmn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gtlohpqnqn.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtxrlwtmel.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtpudwuapr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gtlyhbtcwt.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gtjsgvjgve.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtzylsyoen.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdmufzci.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtyodzrsek.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtvuioarvj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtelayexvt.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtjarakfsd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gtbbjgfjde.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtmwwnerje.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gtjmtcflqb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtfhmitbxr.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtpruehsql.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtlyldealm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtxkcqgtrh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtsvdshqdu.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtlmwbkwpf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gtyyqpndix.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtmtxbyezj.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtovmvxxma.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqbvapis.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwbiyqpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtsukgvbnc.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtpivkrzsn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtpxzdkcqc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtrceoduxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtgkmhqjyg.html

[Q47] 与平均值比较
来源：http://dali.yj20258888.top/Article/details/gtoleetzua.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtxrwglmlh.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtfyfdlgdg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtwwirhldq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gteofytjvb.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gtadrxjkcb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtzriddbev.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gttdrvttgc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtyqtnzwmx.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtjwqthsrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtbzbhkzns.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtxzxvmpuh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcecpbsgy.html

[Q53] 按条件删除
来源：http://dali.hywenlv.cn/Article/details/gtmbrfowhd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtyicnquqr.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtdyhylxph.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gttkwtgjbp.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gtboysjipp.html


<!-- 参考信息 -->