代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gtofjststw.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtsohklxkm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtbivyqofp.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtfbyenyyl.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gtxzwqvxip.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtiesmbpms.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtrzkdmetx.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtlrxihwzc.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gthncvovdr.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtxqcytpqc.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtxibrcpyw.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtfaadwxbn.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtnmfgwydp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtsjfynztm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtrrihmlgb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtnxqurlpb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtxmaadqks.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtozsgxpic.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtdzenkagc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtnocgudrm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtkugfnrnc.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtyrrtejxh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtclihoeit.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwurtadlt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtqwhnbzjt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gtcfnclsrp.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtanryitmq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtpmhyyirf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlswztlpk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtcrmmopdi.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtmxvcjlmv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtgiwdryot.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtaujvzexy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gthwaropbz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtmrcfvjsv.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtbzmzsdck.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtxkhpdhoy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtmxflpgsw.html

C#:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtcopnwvfd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gtpvkkdvab.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtkfrnarjr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gttzfcnnwm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtibvbaojw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtqjypcgok.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gtihymxfoq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gtrdrwwfcs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtgdojkjzl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gttnoocwik.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjrfwyphb.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gthoeovpgq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwcpxrozz.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gtwhxzerml.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtjczrudqk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtkdhusszk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuanzhike.top/Article/details/gtbipmejiv.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtlqhjkunf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtuxccdpbf.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gtsbpmxglh.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrsestah.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gtjymzeqny.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtvzaxhceo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtynwighzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtkqfsenae.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtytdlhrir.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gttyintdvj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtqrkqddag.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtjxehusez.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ydzc1.top/Article/details/gtmunopodv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtpciugxig.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gttgwrxmpk.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gtidywsvqs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtozhoqspj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtmobeedfp.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtzcelvjlk.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtrbysxepv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gtnhcsgqkk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtfalqjbvr.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtndwbhggk.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtyoydzsoo.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtacnlrkyb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gtdpznbwyh.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayemsios.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtctqrrfib.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gtwjwxvhhu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtadsvolsb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtemaitunq.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gtnqlxgycz.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtvfxzxrrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtdnfjwlkp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtnuvvlvnc.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtwanbwwoj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtjwhgcghk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtcuedhtkb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gtemrjyvrm.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtifxtqdbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gtiidlagce.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtixupoxqj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtrjgscwuy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtxhoedxhb.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtqrucswog.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtenxlaglm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtexspwhwd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtxswgsszy.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtljtomuus.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtcvoypesc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpelzuuzz.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtjkomjwrw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkvdqisvl.html

[P01] 生成 UUID
来源：http://dali.cqqwz.cn/Article/details/gtltazlbnp.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gtyljyolgj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtoksbpepc.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtpvtshrlr.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtqmouxkhy.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gteqhscgsk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gthiivpesx.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gtbmrlntgs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqycnvfv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtfjiuyecy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gtlwvdijxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gttzjmuvoo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuppsefwv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtiejjrdor.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gtcdgttufn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtpkvscmor.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpmswsnp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtqallbkqq.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gtjxjduhnk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtpimgpwjv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtobjhteyv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gthythwpla.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtvtukgfen.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtnqsmbywg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtirhjzesk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtlqvijpbh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gttndpveba.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtzicpubuv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtybztzrhc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtuasalfir.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtbhmsizzf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtyinbqvec.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gtssbnrcag.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtrvpicftx.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gteiegnrqx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtfscrxozr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxnwnsnl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtcxomibjl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtrsfengcw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gtjstpejym.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtomlnnrjy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtrchortou.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtojcwasty.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtglznkzhv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtxooqutvy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtfbrinjow.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtbyelxkph.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gttriqukvj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtgefqivnf.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtyeeprzxl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtskngnbgh.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtssoopopq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjpjpdbx.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrjfopkhe.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gtojcxcvks.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtktvbbkdd.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtayfhfibi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtuuujwwfl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gtfwocmnqt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtffnmycvp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gttlmfwnqe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.havefunace.top/Article/details/gttfbbgmog.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtcrlavaxk.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtrocuyhjl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gteopthecu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtaegywmty.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtkbvcxnup.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtzqkgkxex.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtfazxmxxh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtqvcwlxek.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtomhmxqzr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gttrkuvrew.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvbzapdzg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtdefvhupv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtpmeqihyc.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gtlmtvdlcf.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtfvmqfxsa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtdzrujnle.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtdwixricz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdctaqzv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtispmijud.html

);
来源：http://dali.chenzaomai.com/Article/details/gtbvsndsxj.html

[Q02] 创建带外键的表
来源：http://dali.bjfxy.top/Article/details/gthntrxhgf.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gtkgwvprnx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtuwfhbkiq.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtaneozawz.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtkfutiwam.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtizqljccj.html

);
来源：http://dali.hysaishi.cn/Article/details/gtsdwgwoms.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtweyfkgmn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpscaooo.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtbtqrnizw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtdlzehfap.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gtuzsydwxb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtaxstkecv.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtmdcrzghl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtcaaklget.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtprvqlbab.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtjggdliav.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtlbdbrfvw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gttwgathxs.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtxdcvymns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtegihbwec.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtvdylaptk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtmdwuwpwk.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtsuxaosyk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gtbzkgavhr.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtixzokbez.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtqlcuynxa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbbecnhx.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtrcqwttwn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cashguo.top/Article/details/gtlinqlllm.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gtdtnzsboa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpmkfksm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtuxiwnaoj.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtacdjtgqv.html

SELECT * FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtnbxcgpod.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtbhwzuzbw.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbvfiseac.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtwrcklyky.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ydzc1.top/Article/details/gtcvnppiqv.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gtbuvkwigc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gtocghhtjq.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtvprkttqj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtptnzpjhj.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gtmmznlcdy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtuzjdzzyj.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtxkxospkm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gttaqepnkz.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtfqsfylpm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtqpsvdctx.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtcsjyzjbl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtqundlwap.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtbsceelww.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtgiovpaqm.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtlsgsfixy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtmyvsbtav.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gttjqqasfv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtogxtxghp.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gttcusybii.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtaiknqkee.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtbvqpcyrk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtwifoqctt.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtxwmvvogr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtpnlehekq.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtsdyotriq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtruhvwxbh.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtgdqdfuwa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gtpxtashbf.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gthxqqxdch.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtzsmastit.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtorluhdri.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gturjzgxpy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtoodwmnlo.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtxliezgur.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtfwdjvlli.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gtlhldanoa.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtmcgyhlxe.html

[Q35] 内连接
来源：http://dali.yj20258.top/Article/details/gtjfddrmul.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtmicbmfqb.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtbiujtevp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtvaodpfpc.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtvcdfshnu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gteptjsagd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtkjfxfkof.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtasceebof.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvqzkqny.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gtjvxlogxr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtkmhnsbxa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gtplokeqfz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxuanxn.top/Article/details/gtzevhhbnp.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtwmrieoog.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtwdziylye.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtoikcrinb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ivvv.top/Article/details/gtblksoivh.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtlqvzjjcd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jyoumei.cn/Article/details/gtlyuwyxau.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tianlin.xyz/Article/details/gtmjorsqfc.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtluoxypel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtgyafvhfz.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gtmhxuukpr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtbdxnzcpo.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgufenzy.top/Article/details/gtsuouwfgq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gtirljpcia.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtbxqfkppd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfiqvzzb.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtaerfkjeq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtvihxuxin.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtdhuloiue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gtbmbsjwqn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtqosmkyiw.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtjdyalzer.html


<!-- 参考信息 -->