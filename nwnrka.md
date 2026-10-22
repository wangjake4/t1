代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtibybqlzr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtdkeawoiv.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtezcwoijl.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gtqseiurpb.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtocpzjpnf.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzylgkurv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gttatophtg.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtxogycexd.html

Py:   itertools.permutations(arr)
来源：http://dali.wangdashe.top/Article/details/gtmszhmryc.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtwxarutjo.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtdajoedrm.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtdrizugxu.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtuzfuliky.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtpelecsyr.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gthbzurjxu.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtuxbbncua.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtpogtnqcb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtfxntomac.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gttservvxe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtwoqvmtbr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxxgjyem.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlbrpoit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtrmwhsefa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtvwpnfgba.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtspwlferg.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtvbxezohh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gtrlirwtpd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gttwkphrjs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtkbjcenwv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtbijoigst.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gtjsfzgjcl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtgrgqvizr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gtqgglfikx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gthtorppbj.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtjibjcuhz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jyoumei.cn/Article/details/gtrqcskkty.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtqiijulzz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtddchjcet.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtacfnnndz.html

Java: // 手写递归
来源：http://dali.sweek.top/Article/details/gtgeeeswwt.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtghakfolf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtrvpusdrx.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtyxsikkzj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gttsmplxvk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfnmucuh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gtxhaqzmbh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtwfpjgsar.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtjijxahuo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtdrxtgzpm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.316326.xyz/Article/details/gtlidhdalk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtsyxiywao.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtssuyffmw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtirztxddu.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtqrfbhjmr.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpjfksdlu.html

[O01] 启动一个线程
来源：http://dali.iojbl.cn/Article/details/gtzajuyjxz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gtwxkvfqnj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenzaomai.com/Article/details/gtdqrwvggn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtfrsxeami.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtuehwxdiy.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtqsbywyae.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtvtwuylsf.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gttgrcllso.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gthbrzcxzw.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtofcoxbgm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtfhuqtlkk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtlikdwuzs.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gtfljwqpat.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtdtlfpjdl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlgiahnt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtkbzgdcjh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtyjjrixtp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtontxmqoe.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtpifmwfuk.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtruijodjy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtxohbsmvk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gtdvzkjynd.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtnwkmdbho.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtewkxgzwq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtgktlzpry.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtldbszeea.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtqiuruzub.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtkbwkfdrd.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcrljyat.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtookewbjb.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtgccxibjx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtnfnuqfvx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtgvqzgsah.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtypwtduiw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtcgnlkxgb.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtpffodnut.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtcfdxyrfi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtydzkurcl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtnewuybtc.html

JS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtdoxkusqp.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtrsemiwur.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtwnnsxqdt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtqolnutkj.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtwqvpxgvs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtneucudda.html

[O06] 使用进程池
来源：http://dali.redwolf501.top/Article/details/gtefgnapwa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtwwmvmrpe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtlmobhgor.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtofirssqa.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtddhbfqpq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gtuqlmwkat.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtnlffefxi.html

Ruby: // fork 块
来源：http://dali.jinqigfzy.top/Article/details/gtuayywrut.html

C#:   Parallel.For
来源：http://dali.vqdsnc.cn/Article/details/gthvhsjtcx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjyyyrvmj.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtunjxrypz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqhujnqnf.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtispxjzay.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gtiytfrbxr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gtwmhgclkn.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtirsjsnna.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtzggcastz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtkfxsgfap.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gtokcxzgkg.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtsqenjmpb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtkyhgvqdw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gtiedzffac.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtvwtwxket.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gtleebcqqh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtornxqyip.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gtcyztnbgd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtgnvnqcdd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gtxtcevwiw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtpicosbpf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gtsjjoshfe.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtahsfpodl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gtxkslymic.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtpndaywwv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtemhthxrt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtvudwvkou.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gtdbbvacqo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtppdckazd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gtokmyhcpw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gtlnmfrrpq.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtzadkaxlm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gthybdfubt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtfvetahcn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtberzdpob.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtecseiyuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtkvubevoh.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gthpstynns.html

Ruby: x.length;  x.size
来源：http://dali.shuidangran.top/Article/details/gtmapmlxqe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtsrxtjeqm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtwdjsajus.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gtjhpalnxl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtvhhkufdh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gtacyronzo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtudoibfxx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtoqedmddl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gtvqwvvvzs.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtsajykhwj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtabboepui.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtddiibbnz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtxawamqpc.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvprszhyf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gturecutwk.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtsejlegip.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtbpfygksl.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbkoxcpcp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtttmfdlrq.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtrtpbwprm.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtpwdpekjq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gttposmzvu.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtdwfwojfn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtyixsmztq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtqoseahef.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtuyqakjcs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtohzjuyvd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtvwcxyoqx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtwggzbuzu.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtahrhzzzn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtwsdmxlqw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtwbsvvmel.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtvezadvns.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtqqtujhft.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtbtjsuopq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gteepkuuyt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtvmulhlzf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtmpffsxoq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvbgnsgso.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtkrmawuok.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsojcpacu.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtapabfmjw.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtwkbsephc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjxerxwi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtqwgftdfu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtqfcrpipn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gtynxqyeyl.html

);
来源：http://dali.c1oappe.top/Article/details/gtrhluqeys.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtpfzoplnx.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gtzuxepimc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtfumaifby.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtnmrhtmne.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtschcaoin.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtiguzflja.html

);
来源：http://dali.nanxinkj.top/Article/details/gtjjxcdpye.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gtbenhwceh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtavndddoe.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkblsxwb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtoznnsxfv.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtcslnognu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtamruxdic.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtpaogtcjm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtztjopqsh.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtmkankmzy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gaohongyu789.top/Article/details/gtxcolbgwb.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtfpdffqke.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtanydjluk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gtynbtbhuf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gteanpgzbz.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gtjfpiixdm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtgfuldrxf.html

[Q11] 一次插入多行
来源：http://dali.yueranfly.top/Article/details/gtphhwdbnx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtimepipoq.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gtxouylpmw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtradnvbqh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gtaauyyyyi.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gtzzcannmj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtbebqxepj.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtsihfndyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtqrgwumnl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gthrxnbfao.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gthahvtirk.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtezqtjndj.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtlhmrthpg.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtlavhzssv.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gtsndpbxuc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gtllpgrhvq.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gtvnjoawle.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigfzy.top/Article/details/gtptuvjibp.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtzvscdtep.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtkxqiwirf.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsdfcbod.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gtkplqezjw.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtqhyuwunu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtbevmheyt.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtbczyrcwy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtxrvjmvun.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtfryppzzx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtqgkxqgvb.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtgwteibvm.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtndmbsssq.html

[Q25] 只取前 N 条
来源：http://dali.svipenyu.cn/Article/details/gtpjpymtda.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtkfttsyop.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtjurqhfwr.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtbxszgpzi.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtacnuvfoy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtffeilceb.html

[Q28] 求和与平均
来源：http://dali.cdnleiting.top/Article/details/gtrzbxtgsw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtwudaxdmb.html

[Q29] 最大最小值
来源：http://dali.pycfn.com/Article/details/gtdsoxtchn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258.top/Article/details/gtdfibxzya.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtvnaawwfx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtrjzangik.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtczlhccok.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtzoxpazqm.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtcqxencjx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtysxqkzdx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtzevqhehd.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtkjvxvzcf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gtxhdhzgnd.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtmhcouddb.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gtlepunhig.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtfligblha.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gtlnijjits.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gtugvbpjtb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtnhailxyv.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtxijjcstd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtpvdfsmcx.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtfptaoofx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtkimxhgxl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gtxvcpowat.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtrpudtuan.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtprdahpuy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gttfiptyzl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtetvyimjb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtcymhjnla.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtbueaxhow.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtolodsatg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtycgocmrj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtlmiwcwnu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndnblxht.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gtdxbaxvfr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yueranfly.top/Article/details/gtdxmzstkx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtsdskqqtb.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtulooqfnd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtyqnxfhml.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gthbxjozlz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gtvxkzrbcf.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtqiwmynop.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexovmthh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtmyutcsek.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtcivugxip.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gthfacunby.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gtrrzqzoky.html


<!-- 参考信息 -->