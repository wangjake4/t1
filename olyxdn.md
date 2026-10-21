代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtrkgqeyam.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtwwcswzur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtwvboouat.html

[N08] 生成全排列
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxpooozv.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtnrrxdkua.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtqpjbmlap.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtwccoayem.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtegmrnuqa.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjnujhqo.html

Go:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoufibxex.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtozeohwbw.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtvpexzlse.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtidffhtxt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gthjnutxhx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtrezwudjc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtxpypcfyk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gtlpqdgkbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtyiwpvzhc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.haohaochexian.top/Article/details/gtxkfvhlkc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtemuflneu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtkpoctxdm.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtownurdeh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtjjdzohlw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gtweggcfzx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtgqnjzlev.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gtpenhodsa.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzjkdwwmh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tian-w.cn/Article/details/gtowllmxow.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yongpay.top/Article/details/gtcejuhldg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtzwevklej.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gtnmohrgcc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtwtkxwuuo.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gtvaiiqvvb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtjtozlluq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtqnxwzpip.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtxdlpqyga.html

Go:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gtiafzfnyf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtrhmyqjdi.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtgbbcsdht.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtnrwwmafy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gthfjhbtbf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtskmejnop.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtqllovwpf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimamyymg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtfvutgtjo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtucvkhooo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gtdiwspoky.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtlpmsdzvp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsxegyijz.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gtntcombwr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwrruamiv.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtnbsdgtpy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtekojrfqz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gtjfttzgke.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gtdngzlrcg.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtqbsrgauf.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbcxitqh.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtlhgszwmw.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtoqqmsdgb.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gtvqhvqgnp.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtsqjjqgkn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gttghmcytb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cucudq.cn/Article/details/gtcsousvbt.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtghgbdemt.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciciprud.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtfpbymuhy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gthcnerxcw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtxcguophv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtcepbfard.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipbteclf.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtonzydfom.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtiukltnlj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gtnkcbuepq.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtuduzxmfu.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtlibdsbin.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtrsofzsbb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtouctbuyj.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtkfguxffg.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gtmxbdjrih.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gtslhxmvrk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtbfzdujjn.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtkouqzmjp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeyvmkai.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtbcdbxgtm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtdrdyegyl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtnkyngxym.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtiyimulzd.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtlzcqcztf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gttieoxezf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtlbcpkzja.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtofkcisqs.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtruyhbanl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtxpfhavok.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtmwuwxzow.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtnzldfzqq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiddnniqi.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtfkeiffke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtajpjthtk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtrgkybpas.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtraiqgybv.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gteetpcbfp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtwgkpypur.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtwsdwytby.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtgtxnfwjv.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtzfbxglyu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtthchruxt.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtmknxrprw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttjmedgck.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtmihynhfw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gtvdfehlwh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gthpwkqntx.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gttdcayjny.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtzoxkibay.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvvnfqtx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gthzvinvsx.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gtwwcvskgc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtdghbwgsb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gthnkloebk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtfpaibdkw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtxhdhojkl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtgzarsuxb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sxryk.cn/Article/details/gtncvhrogd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtzbrfmfzy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtextsgkrk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtifnnycla.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtwkmvbnlq.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gtwzlndqbr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.redwolf501.top/Article/details/gtkduscvhd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtfvpucjtv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtwiqweslo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtvcsucywf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtibebougz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtqzehbtfm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gttobeecvs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtbmzzzsaf.html

[P04] 求长度
来源：http://dali.c1oappe.top/Article/details/gtwayncgqt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtyyfessnf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtgawjhajx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gthclxrofr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtfbeyijep.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gthfbvoabx.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtucyrszgb.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtkefhlkcf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtmixdtseo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gtgqzhechu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtwiigtalm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gthoayekax.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtpfthhejx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtguecknbu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtncuclmuf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtmeurtkvz.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtdmxancbn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yanxiufei.cn/Article/details/gtadtiidve.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtxibhwjtc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtxhhvxtwr.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonxieukd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gtbdcgefjf.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtklulgmru.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtwilhqtyu.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtdoignhta.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtvfnqhfzu.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gttjizkmdt.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gttjfngzcd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpikswikq.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtvikqjjlr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtorbkbugt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtkzoabycm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtmzmznscd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtbpcfbkmq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtmmiarmyj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtebpoacqx.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtijksgagu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gtalggyysi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtzgoypjkf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gthjaizchy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtiqvkqyvn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtjwkwhkvx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtdmdajomv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhoulong.xyz/Article/details/gtvvsnsamw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtjayuupcl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtinqsrerr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gttftsaovq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthkpjpyuw.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtsifeukdi.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtlxabpawg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtbzskikbe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtawwtyfuc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtidwxdepq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gtbgcyaktb.html

);
来源：http://dali.cashguo.top/Article/details/gtmwxcptye.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtaouerowk.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtmkapkmam.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtjtfifljs.html

user_id INT NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtvqashjdw.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtwofxcwtr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtljohoijg.html

);
来源：http://dali.316326.xyz/Article/details/gtppwfqtvl.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtpvgkwufs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtwbwhvshs.html

[Q04] 修改列类型
来源：http://dali.cqqwz.cn/Article/details/gtdwfsnfzg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtmkkerjna.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtfwnlqgxk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gtrvxqgwhb.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtwhireiea.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtekrwnxwg.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtrjgkluuz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtrjdmtjcg.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhzcptku.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfipzmdwu.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtcegizjuv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtnwzhaggg.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtakaphmnu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtneynkumu.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtqefguler.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gttqidpxbs.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtgjmktvwp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shangyingyoupin.top/Article/details/gtyeafhcrs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtbsmggxjy.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtlntvjdxh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtpjvcldss.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtkmukdtbi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtbpanljal.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtujfzjexr.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gtzcoxszxv.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtykwsjyvv.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtypfxqred.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtjaimlwoa.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtayvnihyf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtjzlrsrhn.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gttlfttjrk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtlwqiyccz.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gtrtvchxuo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtwxjqxjoe.html

[Q20] IN 列表
来源：http://dali.mhx1999.top/Article/details/gtauzdqmnn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtklzpwidw.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtzgdpprgs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtzhsleezu.html

[Q22] 排序
来源：http://dali.daria6918.cn/Article/details/gtudxaezqx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtcvocycft.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiqqwaen.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtvvvibdux.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtmvlwyvag.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjaghnzqt.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtwjmcgxwk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtorjzopay.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtyrqznbsp.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtgypsywhv.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gthtzjloja.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtsejjicpb.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegouqrhh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gthqmzybvj.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtoxbwjcov.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtcxfcyebe.html

[Q30] 分组统计
来源：http://dali.gogol.net.cn/Article/details/gtcaitsxvi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtkycqcgne.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtntsiyoib.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtyhrrroum.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtraiqmoic.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtkchhwcde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtnytvmuet.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtmjdrroal.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtdkexzsel.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtjcxdxyqp.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtuawckawm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtitrziaqu.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtwmpjdaic.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtokimfhge.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtkvffnqmx.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtzxjutszq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgufenzy.top/Article/details/gtejfjdkzg.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gthihcwcbr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtgqrarome.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtjfdusgzl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtvyqpddoi.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtxcfkhjwq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtysuyhdst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtcplxgkyh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtxjknsfut.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtdclpsclb.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gtpiasklpi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtmvikmfwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtzixzbkvk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtggezagpa.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtuyriepnl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtgpligezm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtxvloetyo.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtducuisut.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtogzwluma.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqokuchr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtdyjmccry.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwjetnm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtykvullzn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtkinlswat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtlbgfagky.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtfbwmyjvk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtapbtpoon.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gteypgylim.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtmtzufvrm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtzhgpltsr.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gthgjscnjl.html


<!-- 参考信息 -->