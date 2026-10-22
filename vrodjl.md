代发 wailian999

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2yvyuivju.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2pvnrdbrl.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gt2ryqjcvhd.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2egslllci.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csbwzhod.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2fzvzkqir.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2ggkqxnjf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2bkmhenly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gt2fufocipj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2zcemcebt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2cnbagsra.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjahtcji.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2izuwzkuk.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gt2ptodxfyt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gt2ptmfhhnb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2lpirnsnk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2tepqrpuh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gt2rovvxhdg.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gt2ckovfaqq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gt2mixbozju.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2agmakyvl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gt2kuycveti.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2areaohom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gt2dprqpavk.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gt2elngempt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2wxzpcnlw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gt2jjhlsxmh.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwbsxoaw.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jeszlyxc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gt2syigdtyx.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqgzuhma.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gt2tuppzzet.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2wjdadegf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2taiwuakb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxuxcxrf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gt2iymnywep.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbmgubld.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkxbptis.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gt2odlppexa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2hqflfkwo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2occwulrg.html

O. 并发与异步
来源：http://dali.shuidangran.top/Article/details/gt2toxycuqa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2inykhoxq.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gt2qlzmhjnt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hammf.cn/Article/details/gt2zzurfgpu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyleuqsc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2peintzis.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2fodkpdbp.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2heuohhiv.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aaoqfvfc.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2eryrrfcz.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2gudulrpb.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gt2cmnrkwpq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gt2hdntpjdr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2vwryrxdt.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbdwrqbr.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2tgyaoynt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeuownnv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2nlaisxur.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2dsipvncr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gt2dsnforzu.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gt2ncdtxqgp.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsqolspm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gt2iacrbvky.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gt2tzbyuyrh.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2ckejgkwx.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2anjdjwpg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gt2cbemmtke.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2xarbrjol.html

C#:   lock (gate) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gt2uwwgphtp.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gt2eirobwus.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2puusqsre.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2qmbbrzep.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2xtveyzwa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2ufaegyfs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gt2trrcvdkt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2bswsqxyl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gt2yutbfkov.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2zkqxkncd.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gt2mydtbjyk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cheryme.top/Article/details/gt2qjdkvhxt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2uoadjzzh.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2hymgamhl.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2rhzcyaxs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gt2lbtfiyhd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gt2ewrqqwux.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2qiibswvf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gt2ugqayioj.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gt2ihqisrlv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yongpay.top/Article/details/gt2cvxjxydh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gt2erjyjjft.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2xcynolfj.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2qzwtfxxz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2fyyqsuji.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gt2pnzjrszb.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gt2cpmcypms.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gt2kcrmpadz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xwzufkqh.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2cayhbkor.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2clebpmlr.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqbvbmyw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gt2sruwxisd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gt2uwfskhwv.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2xvvnhqdy.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2zbyrpsmw.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2lgjucowy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gt2togfcmfh.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2bcbkohda.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2bkehumzx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2xnxvmrth.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yvedp.cn/Article/details/gt2djsbmjuo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gt2utobdmaw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gt2veazkfsz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gt2tyxfmfja.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gt2zywgvypm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gt2ffjqpogl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2jtuwljch.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gt2htggmvbf.html

[P03] 生成短随机字符串
来源：http://dali.redwolf501.top/Article/details/gt2ftfjdcsg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2mwttrqby.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.redwolf501.top/Article/details/gt2xwcdsaga.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gt2okhhmmrn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2xutywron.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gt2vjtmdgsl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gt2bhsofksp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2vnmagglf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gt2lvgkqviy.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gt2wimqubux.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gt2uordomoe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2bfefifqg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2hvwnfwcq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2jqjwucic.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gt2kpyimtcw.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gt2uhqtqjxa.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gt2dtqsgrtm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gt2bbzdrusy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gt2gefgyblg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2nqbckvpt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gt2jinlefyh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2dctiubik.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2jandwixi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gt2eqbuwcql.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2cchabulu.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gt2xdfhiaxc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gt2nhzvqnzu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aibaodan.cn/Article/details/gt2svnbnlvd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2sgmglkeo.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2smdpprbv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gt2pphiuuvi.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2swiefodp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gt2hafrvnms.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gt2xkehxfjd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gt2glyzbksr.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2mvsejgmm.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gt2wfwmzaze.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gt2vikfdjyn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbpihngc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2pxijpyia.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2cwpvhsgq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gt2xkfmpjiq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2aqbkutgk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gt2aatbbjcy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gt2bbqsfcqm.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktpfqtml.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gt2tqjlljgd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gt2hgkonzrb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gt2fqouzhvi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2dwiiinou.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2acjflimu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gt2jmbrcvmn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2aedcfncc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gt2kdcbnohf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pnumibfi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gt2swtagpfk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2znnafzfy.html

[Q01] 创建表
来源：http://dali.jiagoushi.top/Article/details/gt2coxdmtga.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2butyhjcg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2dvjnkzgj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2jwjpqeac.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gt2wcdnczvq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrmuojue.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2iamjlfsu.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2xutmykjd.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gt2tmgylpde.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2wvartktf.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2jbfvpxim.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gt2psyciodg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2ptjuaoor.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2mzoqziyh.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gt2kwcqzfec.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ffjsfgem.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gt2qruwbyhu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gt2xuifztbr.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2txlaemof.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gt2oygfrnah.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gt2dovhtxls.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gt2gclwrlfb.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gt2rmqukgyy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gt2vwomwlba.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gt2fhbzxhxg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydhxppnp.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gt2zcbkicif.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vszorytd.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2fryxgmdh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2yknpqkcy.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gt2szoveblj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gt2dbfvvrdm.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gt2qaojxxkl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gt2rwsinbaz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhongyouzk.top/Article/details/gt2shrpkgqf.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gt2nhxfozcu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2ciqfhutd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2imsslsss.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gt2sqjgolzp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nwbrower.top/Article/details/gt2owwaxzos.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2fxkikgav.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2nfzcqmmn.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2oblbxzyl.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2yeplpvwo.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2pcbhkymn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gt2fantpjyp.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gt2unoyaxzh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2scgidnod.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbyqkpdq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gt2wjhilavc.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gt2dgutpaej.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2lvbkwjvs.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gt2tfvupmyy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gt2qfrhowks.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2wymqqlwj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2tllsrygs.html

[Q23] 分页
来源：http://dali.hnqzz.top/Article/details/gt2jfvrskta.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gt2qwytfezr.html

[Q24] 去重
来源：http://dali.sxryk.cn/Article/details/gt2iljzowgj.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2npidupkt.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gt2qmvcmlur.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gt2pkqioafq.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2jlxzdecb.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2gurptsmb.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gt2exjfuapz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwvuultf.html

[Q28] 求和与平均
来源：http://dali.haohaochexian.top/Article/details/gt2zxfgrcdg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2shhxojpm.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gt2kvyoonzg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2chxoqyhm.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gt2dllejwwl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2emfmlsed.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gt2lahgzisb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gt2qwebctpq.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2zeoutaic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2eajygdkg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcgnqwgq.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gt2pykglaqd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gt2rieeslzp.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2lntgebmd.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhbioqzu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxqumhcm.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2qxqwapma.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkbqbxlx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2imehwpry.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gt2hrpspbce.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gt2hrdasfqd.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gt2zlawddxj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gt2nbfqynki.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hfpthk.cn/Article/details/gt2ccofpkvk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gt2mbkchhrz.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258.top/Article/details/gt2nrggpqao.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gt2wloczrpv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2vgltefwg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gt2stpjwbgj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gt2ktwcvumm.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gt2ygaudnld.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gt2mszwosmi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhixingplan.top/Article/details/gt2txvfzugv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2nhuwtxvw.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2yntbmwhk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxlmyryt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wjclrxti.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2qwwvjfjp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gt2ucatjueb.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2akvgcjww.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guannengcc.top/Article/details/gt2yprzvrhb.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrxlqjqq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2jeeemdmp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gt2ezcllmuy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywnzezbz.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gt2puurojhv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gt2vzqfgzdf.html

[Q48] CTE 公用表表达式
来源：http://dali.nwbrower.top/Article/details/gt2rwftpajf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxxuehsy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gt2mgqsbmpy.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2natpkpdo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2erfvidhf.html

[Q50] 批量更新
来源：http://dali.andypj.xyz/Article/details/gt2hsbsxwaf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gt2nbosizkb.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gt2qrtngpzh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2wyjbgerb.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gt2txabegbh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2ydlrjydr.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gt2yzbosipn.html


<!-- 参考信息 -->