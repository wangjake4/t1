代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtsisvuzrc.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gtsbvioiqr.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtiyngqwxn.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtvlazhnfm.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtesqbddoh.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtkubcgunw.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtyblapril.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtkqddrjdy.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtwdmyesbb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtmshrmqmo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtipstdxun.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtlhkzbwsi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtmbkncpop.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtggptaifm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtnqaremqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtduuckceu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gtxbmdwkky.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtiahmokwa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtwsvoykbj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtvqpfqhuv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gtkmwyagft.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gtbulpwxny.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtobxrhpdx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gteicbjlao.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gtxowyaixo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtfdbjgxep.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtthnvgaco.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtrkrokuaz.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gtepcfceok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtcnmypuiu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtnrtrcjkq.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtgemfyrwd.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtoapykqcn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gtghspshgx.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtgzlcyqqc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtggnzvfwf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtznmbcsdl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtaehpjwim.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtnxzuqupe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtskfbtsij.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtcwbgfvyh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gtcvlrzkro.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gtpbithfip.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtzofljalv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmfguyevs.html

O. 并发与异步
来源：http://dali.havefunace.top/Article/details/gtmploxpkk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsqqwhreq.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtmonhrbel.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtynmjijpv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shangyingyoupin.top/Article/details/gtdwknyjwc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gteycvtrjr.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtixfyxxer.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtskienwnw.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtqrlcstic.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmacsrfeb.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtupkqunnc.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtcnajmxzv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtyvialfak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtwwlzegxo.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtstwldkda.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtwjqbzgsr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtcpfxagmq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gtegfyxhnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtwlkxzvfv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtjrilzvgs.html

[O03] 加锁保护共享数据
来源：http://dali.yangfankeji.com/Article/details/gtfwzszqvd.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtziccaepe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtqtnpvxtj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gtdtfekltx.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gtbthlzasn.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtsoysjksr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gtwzuadems.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtplqcapli.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtlkzojbaf.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gtwbcsyabz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthudcfvia.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtyhwttbmo.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gtgctrcsxj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtqrszzqon.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtamfxprrj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nwbrower.top/Article/details/gtbrzaxfqf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gttdxcjyye.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtrrlxakul.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gtljzxpdih.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnywsqljz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtccooihyf.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtxcttnggk.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtxkpzvphx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtuguronaw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshldxvpx.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtottzukxa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtxueglkcp.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtxmuqxsfb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtcdjotcyh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtmkphtbxz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsrqhuxv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gteidbygmc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gthrifxuhx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gtmczzndam.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gteyyufjbv.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gttdizndfb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttlidgfyq.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtuzxfickf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzkhhflma.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzcknckk.html

Py:   str(uuid.uuid4())
来源：http://dali.feifeiyinyue.top/Article/details/gtwjgcpqwb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtuypyrqai.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtfygcuyhr.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtnlvttniz.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gtyflhifbj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtvvbybrtn.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtwbbauhjs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtpiompkfr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gtbrapycrj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtcrtikbms.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sysykeji.top/Article/details/gtgrekvtpe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtomkwgbiv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtylvvcezo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtkphrhzlq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtwnknfwvm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyygvihqo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtgimlrthd.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gtlxcegenv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gttilscrar.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtkpvpgboe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtxulaaiif.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtimjqikhs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtoviuxvpi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtpwfpzwim.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtqjlcukff.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtmndqxkhr.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtikkybndy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtvlfrorin.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtgihvbpga.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtnqucvtqw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtygcgoded.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtebxhjkhl.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtowxjjwsj.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlumyuehu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtjttodriu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtujtrxyno.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtfduypgfn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydrdwxcy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtotaxkywt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtohdimlqp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtrrigzqud.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtjoqqvuwk.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtaiajzixq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtxvqavqil.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtyfvumsfh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtmgekajdx.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gtjvribckt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gtfvxopyaj.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gtzedmatwd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtgijeesrg.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtnwmemetj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gtbptnkupp.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtsqbvrqso.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtzgumjice.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtjdydevet.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtsybgwwak.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtjtlqsrdh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtubzyeoyc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gteoytfuow.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gtuvtpzoed.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtatbetrjq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqnpwyow.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gtuphrtqzu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtuwrgnnlq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtzotebrby.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpqelvyo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtmjcytnfi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtojmkisti.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gtguyzsglf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtdlbjntzz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtxyhjhxup.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgpyytrxm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gtaafhrckp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzricuuuv.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtdmkdzywc.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gthmnaobpe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtvrotbral.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gttclaxagq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gtayoeifew.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtsidmzfzb.html

);
来源：http://dali.aizwys.cn/Article/details/gtrerprefq.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtzjjbxifa.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtvgrolime.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtjqfegbld.html

user_id INT NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtelfzcpsb.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfquqrbz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gtmyoxbjan.html

);
来源：http://dali.hfpthk.cn/Article/details/gtaqeiofjz.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtnqoydqye.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtpzkyzxof.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gtqqjpcqew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gtqhpunboe.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gtpqelthnv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.svipenyu.cn/Article/details/gtduiewhta.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtpmibijqb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtzvzwdysi.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtdtdnqurz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gtlezgfpym.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtksxgrirl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtmpdtunva.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gtggyvuezd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtqnaeuraj.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtlwyhggme.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtmmtozcal.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtobikmhqm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtxvhqqyjs.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtpxfziibf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtbzwphery.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtnatgroch.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtvkavgetb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gtjedqqawr.html

[Q14] 存在则更新（upsert）
来源：http://dali.sweek.top/Article/details/gtebyagiun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hammf.cn/Article/details/gtkbfiufrr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtajigxvxy.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtiiklfqde.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtuibnibbl.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtacndbibr.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtigdittoy.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtmorujpsy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtyicqlshk.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtxiutmjox.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtvmdhdcio.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtgddiepjd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gtqgmcpefx.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gttuzadwdm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gtvnvanuxp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gtpxonrcsr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtyriowxbn.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gtbrbfnsum.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrpuinsf.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtdfvsdsfa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jyoumei.cn/Article/details/gtwrifhpqf.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gttkkajnvh.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdbasnwwf.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gtkncrexiv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtcixggjty.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtbqstckqr.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtiolqvcin.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtkegwhzns.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtlorszdik.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtnmbvwqmn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtkqjoatna.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtsqqynupx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtdnrklkat.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtioiqcwgx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtarkhswot.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnlsyajyr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gtcgmnzyue.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtlgkopwkk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gthbcgywvi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtrohggcpw.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtudgztyoy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtwhsrwvyn.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtbgkyqmvm.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkqqythm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtfijknips.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtiwrceuiq.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtlqbaznto.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtgsysnirn.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtrnkjxetr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfhttlkr.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtbxgltjgi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtkralupba.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtwpucbnyv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtobefxdmw.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtuamvwdlt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gtoonmexdn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtdccrjxqt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrlstimr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtgfsadopj.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtmxjoigiq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtbmsnjshz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtzkohqgpr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtwhitiqps.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtbchidjyu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtwmyxvcjg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtvrktcvii.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtpfgjkthn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtuwmzwwev.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtnrmaowoc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtmqhouptz.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtmkbmxcsc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtseuettjm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtqfavptqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtpngppiyz.html

[Q47] 与平均值比较
来源：http://dali.yj202588.top/Article/details/gtlmjrvkgi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtrkxriako.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtmdodvqca.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhongyouzk.top/Article/details/gtzprlnsoj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtjmszybby.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtefimhftv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtqznjgdve.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gtppblizaf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtkjukqghl.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gthtnxwqpq.html


<!-- 参考信息 -->