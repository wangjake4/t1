代发 wailian999

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtkfxrdupg.html

Go:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtyserwelm.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gtmhbqprfi.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtwcwqoknq.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtmxpsxhin.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtpwvumbxo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtuhyxdm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtothzwpwx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtkhlqjayg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtahawyjgn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtzorkjzje.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtkicemqpa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cashguo.top/Article/details/gtsayefnsj.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtzqksyzzn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtogpiwsup.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtodfzzojz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtushyhwxn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtgbssstid.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gtjfxttyex.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtwahahqcs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gtsvfylist.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtngjlcosa.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtiwjchzrj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtksovgovm.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtelhijjqy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtnasjqlat.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtsypewimp.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtpdarrllw.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gteujiwina.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gthzsryiil.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtwhptnkbn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtpiflnloj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtkqvxjzfo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gthasgntfq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtiebpjcci.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtxbskvuib.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtyizvnmvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenlongwang.top/Article/details/gtusmlqhds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtmafssoyi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtblpzqqyy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdnrijhhf.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gtdsvfghfi.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdvmsbcga.html

[O01] 启动一个线程
来源：http://dali.yuxming.cn/Article/details/gtbitupqke.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtyruqnxth.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtjnebujfu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtyerhoxwo.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtwbndfbsy.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtiehgambr.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtofybhvqe.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gtfxmlwhyl.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gtiomjuhqx.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtnyuzlopn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtgvqqaxbt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gtfndtydgj.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtsyhrrbux.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtarwlvugj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gtruhmhpst.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtssoghbsa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtouffzfon.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtpollnawm.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtofaxdxdh.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtzuseksya.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtjxryyohr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtfruqqyxp.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtuopxnjmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtalzwmfsk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtacooyueo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtuunwklif.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtpfuehpmt.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gtqmzkldvn.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gteejuoabg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtnownazac.html

JS:   async function f() { await g(); }
来源：http://dali.zdqjudy.top/Article/details/gtxreoyaiv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtallhcvpp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gthgftbfcu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtvzvomvce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtscmlwcau.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtrvqhwhap.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtivojrgcc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gtcyjxcxnd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gtpplyfwri.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtoqmgdjlu.html

TS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gthbaznqox.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gtxqoegfgu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtidvceepi.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtorqbenmd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtexsrxcbo.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtvzdryrbd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtylbsgyuu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtxptspond.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtnrsihbko.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtiljltnmx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtvmqutigf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtchtygssc.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtdxerpcwk.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gteybvzjcw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdldoatra.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gtakkzithx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtasicaeet.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtdhtgratc.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtulzwwpqh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtcgrrkyos.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtptqqtwwl.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtohsrerwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtvghguakx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtktvsurwd.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtzmdsfnmb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtqymnofgl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gtewbzgupm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gthtitgpuk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtkmkrpras.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tian-w.cn/Article/details/gtigbcgcdw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtstzteuqy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gttdhoochn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtjpigqixm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtqapkdrrh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtafrevwgf.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gtydcfgazp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtofzqnnjv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gtfynsdjwg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtpotervnu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtphtrqedu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtpznqpeix.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxzgizvo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gtdkgysebm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmdgjpof.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjxuhuhro.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtorfcyzfa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gtduglkcki.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawwnksxh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtmeywpkzx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtarkecbrc.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gttsaeuyyi.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtpqvpaybs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtdeqogvfc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtvjswzzze.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gtmriqimub.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtvroyuubx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtbjjkdtuf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtohwnkzdw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtlpellbjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtaiycowrt.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtqrluovkh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtgquxbcuf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtwwppqsqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtufixxnrm.html

PHP:  if (empty($x)) {}
来源：http://dali.tian-w.cn/Article/details/gtdxeaofsa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtkgdgehwd.html

TS:   if (x == null) {}
来源：http://dali.guowangkeji.top/Article/details/gtcfmqdrbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgemzdjy.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gtpjlqsagm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtyqmekihf.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtchnjsfuw.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtudzfoumm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtitoylpbe.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgfzy.top/Article/details/gtlcjyuutk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtgmgouehq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gttisnrvtj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gtkktdjqoy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gttfyedapx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gttzobelfv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtiligujgc.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtheibqoij.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtklwskgiv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbutdyhu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjqyhvvv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtfiomxsqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtapdoncwn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gttegvpyfz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gthbwvdiwx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtkoijrmqm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsbuxpdxb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtjhkeiomk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvnuwsihy.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtftcyxgow.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gttfqxppkn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtedcytipt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtvgtscksx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtcqmeydky.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtxhjuxgco.html

);
来源：http://dali.xuanzx.com/Article/details/gtembzimgo.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtmuywkcwa.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtuxtibrmt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtircxkjty.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gthrpoxknl.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtuyafxwlg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yonumen.top/Article/details/gtsprluaoq.html

);
来源：http://dali.fengsongda.top/Article/details/gtqiigcxrh.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtvrvmwzee.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ppjwa.cn/Article/details/gtpzqojwna.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtvsotlkar.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtubmnzren.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gtqwmtfxif.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpbjgdqs.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtlztoqwrs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtsheqwvks.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtidjvkskf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcskkdmu.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gtgwpogtor.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtjcpkczcq.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtbzdfpjte.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtqbpmbcve.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtvbvzhaws.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtuzbpnsfk.html

[Q11] 一次插入多行
来源：http://dali.havefunace.top/Article/details/gttyapjluh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtkprnldkz.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gtmhzlqjxu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtrkixdlou.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gthmjyevdk.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtaxfzxxhw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtmmzonlxy.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtejkjohfp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtkstflamf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gtoxsgmyad.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtbrrigtgv.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtobezprgz.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtfmjatucr.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtidhvwajx.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gtehwgkhhq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gttwxsmfmz.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtautcetii.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtdpcrdtyz.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtvbyfoxcs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtjgyegwdk.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtociuvusa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gtggsxbtjr.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtnfolefef.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtlwjgczmq.html

[Q22] 排序
来源：http://dali.xuetiantiany.cn/Article/details/gtdzlbzfww.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sweek.top/Article/details/gtwwpsbxgl.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtqcuyfrmj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtgqouubzm.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtkpjxcxjr.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkkxcnjto.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gttbnyiptc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtvkrpdlpm.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtpwxfxyef.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxmqbcbhv.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtgjlgpzak.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtkhdpzlas.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtppdlghbz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtqhkisbst.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtynabjlrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtxkrqofig.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtzowimzgk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gttwvjjstp.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gtmeidjxmp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtvjpzecpm.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtixsodvwb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtnusqbeln.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtffhznprx.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtarkewfzy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtdlhqkwoo.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gtwaorkaqm.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gteuizzady.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtkhuroidl.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtgkxelvce.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtwbfdpfrr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtbzfsjomt.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gtbwrrtfup.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtugwppsib.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtdvpbratq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtwyrkbtmd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtbxynlswr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvomynfm.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtuwegpftd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvxbfqio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtbvxedaoi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtdefokwli.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtwndieyof.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtsictmvfi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtcpwzeezs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtgdnnailh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtinyaipas.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtzdkstwyu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtlanrjfyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtdongyqdo.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gtiyflwexe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtyvzsbjmq.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtbgcmxjki.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtbqwitunt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtymxxsruu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtkkjgsnkz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gthlrstllf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtvmnjvqul.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtcibyanlh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gtpbgzkixb.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gtnpzlnlbr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtucyvrhpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtainnxgux.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gttjtmadfr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtfwjcubox.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gtzejdabvf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtxlyejclf.html

[Q51] 用子查询更新
来源：http://dali.nanxinkj.top/Article/details/gtjquizgav.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtbqybdfny.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gttkhtjwoa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtgquthulj.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtnghwnttj.html


<!-- 参考信息 -->