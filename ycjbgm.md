代发 wailian999

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtkekioydr.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gtsrfyxbdq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtydqomhqf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtahhavhik.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtkglrrror.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gtmstucywk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtxpwqycsl.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtzwrrrtqk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrcsugxse.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtkxlvqytb.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtetmpqprm.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtppjccqqv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtycaeaein.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtaynnchge.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtxtchsrfy.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtnqtfjlmz.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtvqsevshx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtahzgqktc.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtflxqsbjs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gtmyqnoopk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtjsyedbzk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtfhopvszv.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtfqbcxwws.html

Java: // 手写 HashMap
来源：http://dali.zdqjudy.top/Article/details/gtpngrvmrz.html

Go:   // 手写 map[int]int
来源：http://dali.kuanghao11.cn/Article/details/gtgeavkgjd.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtirzsleuh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtumrimetj.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtewhuacxs.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtsfexdljm.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtsdhbswhj.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzznhxjo.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtnmqstdes.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthycfpaax.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtrkpozrco.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtfcsyvgii.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtanpobzlf.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtqvmqrdtq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtkzpdplwo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gtvyrxyvvi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtcyodbxkf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtqvbvzger.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtuvzzfutx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtvpjpucob.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtamtwiewy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtzmfxpvrx.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtulnuugpd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtaxxwgmtl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzozfofn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaimtgiec.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtjcxiivoa.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtkbkibywl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtzhslcosr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtpowsqoer.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtschkqzkf.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtpavpudha.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtlmuaruzi.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gtbiygchib.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtpmyegapp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtxlovdjvg.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtwthxnjou.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtdgesyctr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gtnrvyejzk.html

C#:   // 手写递归
来源：http://dali.shzxlz.cn/Article/details/gteizadafz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hfpthk.cn/Article/details/gtsrfmziyr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gtpycrqtvt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tanke756.top/Article/details/gtxfqbwhhv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtkgjdbgvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtgqxkifyx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtecmhbkxb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtgayexydb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtgachtfbr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtauxyagvk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklovvqog.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtsbqvvvaf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcylztrsx.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtwxzgybic.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtqlovniuv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtfaljniec.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtxrucsspg.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctvbuofr.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtqdqqtsbo.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtwhzdwiig.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gteylhhdmr.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gtgmbuocgi.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehshrawc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gtzedxgayc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gtugtgeacz.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtdabphknh.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtgdyxotsp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtvbvejexc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtsznpocaz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtktyoaffo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtwxsrodgq.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtdowtpvfg.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtoctdgglj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gtfqcykclg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtttzudzcr.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtdzmmuyvc.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtrzgunibg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtnihgdgfx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtgmwnvudk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtsamuqppn.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtotlfkzne.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqvjlsog.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gtdkobkkgw.html

JS:   async function f() { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndoacuoj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtneyahlhm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkymfvof.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gttaulurga.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gtvaohlgbs.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtwqwxgmsb.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtiwcvvbpx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtnxrfkxqo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtojasxsls.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtvapbthkx.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtgysffshl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtqhuqdgsb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtyixglhnx.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtwyplwpya.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtyarfglyl.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtbboxepzr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtwfvkaeav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gthjqlwnwl.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtkjmvqvzo.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtratmudxi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gtyaubaipt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtpucscrzn.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtulxxewxn.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtjdinfqcy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtogehcayh.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gtnugihdoi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmuapzheo.html

[P01] 生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppigxdem.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gttizvxqsf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtcluqqxcc.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtcmjenfxr.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtmgxyniky.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtklvoffdv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtcjlmpkyy.html

Ruby: SecureRandom.uuid
来源：http://dali.iojbl.cn/Article/details/gtbsuoeugr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtrmthafxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtqnqbaqji.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jqgufenzy.top/Article/details/gtgnsedzpm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtkesusmzz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtbarkycmb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtnxudgzls.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtkoubkwsi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtwejlqcdn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtnngjlddg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtnaqebsww.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gtxhqsqjvd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtbptowdpw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gtibybjggv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtwurptink.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtchsinfal.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtpfukffek.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtpyopxrfi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtuzdkjcem.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtktaoemhb.html

[P04] 求长度
来源：http://dali.yuxming.cn/Article/details/gtcbyxhzts.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtxbbmahsw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtpczpwmrv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtoxalthzq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gthamwdngh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtgpcqjfoe.html

Go:   len(arr);  len(m)
来源：http://dali.hfpthk.cn/Article/details/gtpxstvbfe.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtghcziazp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtqlchdrxl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtbqcbiqmz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtigxhwlbm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gtmlyocfbk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gtanfimjre.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtrzoxxxvu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtrgamemjp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtevqnqzwt.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtjwxkqkgy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gtcgwumpqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tianlin.xyz/Article/details/gtuefqyish.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtgdwhfjew.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtagqpyedv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtyozpuvqm.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gthoxphsns.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtepodmkap.html

Go:   if x == nil {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvyffyzmu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtutosnnjr.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gttjjjhbfh.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gtfhfftovn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gtubrmctat.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gtibadsoeg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtuqnxoomq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtmrnhaeyk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtrxttwcig.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtxpoxncpn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtbqtontub.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gtowwvrqwi.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtludakzdh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtjqbnesfh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtqtuyouxq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtcfyzujhl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gttfwskbya.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gtvwbloimo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtxreitzsh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtcwlagvnr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtivvpaixb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmtpnfidn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtloqvcgvg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvsovtqus.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gtfuztavon.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtjowjdfjc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gttekspvub.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtdvjriibg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gthzcnaxrr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtbwcuiiev.html

);
来源：http://dali.jyoumei.cn/Article/details/gtknebdppm.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtygjgkwac.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtgrghgidu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtnysaujps.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtinguzjrr.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gtmrgmtvhn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtoanivseb.html

);
来源：http://dali.tanke756.top/Article/details/gtfpszgpxs.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtedliffim.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtlxyvlort.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gtlduznesz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtnutfipso.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gtfrdcemdu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtkrmslqow.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtjwiykcrx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtatabpecg.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gtfzgjbplk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtjrrehpvj.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gttlvjocjq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gttzarvzdo.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtqntcimal.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhxvcdpf.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtemovggor.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gtbhhgxpxt.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtiafrlqsf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtagnlejfs.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gtbyoyxtzq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtkfuvjmnm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtsnhsfzkk.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gtkklgcunp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtqkgwgpru.html

[Q14] 存在则更新（upsert）
来源：http://dali.yongpay.top/Article/details/gtiwxjyrec.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtmlzjisaq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpqtrbbi.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gttuymkjug.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtzqwfegiv.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gttypnmazk.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gteolmvzbu.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtxpdqmlre.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtudzcxqld.html

[Q18] 模糊匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmkcceux.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtgkdnfrga.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtmkthqnoi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtoqapziyj.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtapvewbbi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gthozweyxm.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtmxdkrgye.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gttttxmvyk.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtimmcepcn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gtawsvjshq.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtrpfebion.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfndrbee.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gtozimdoiu.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtaumstuic.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtjrlzrrzx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.316326.xyz/Article/details/gtfelmfxxr.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gtgkgeoghq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkuhubkwa.html

[Q27] 条件计数
来源：http://dali.pengpengdd.cyou/Article/details/gtespmzgoi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtidtpbyyi.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gtuevrhrps.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtiqzjpzvn.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtybfmrqlg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gtppyhtbua.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtojxkyqqz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gttvvxljvc.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtwgizbikk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtymkoinrg.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtkxaaztih.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtqrifujwu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtjknwcvwh.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtlagpmxpb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtiqlxomta.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtcbuqvgpa.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtepawtdhc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtsqizlqdu.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtcbanukrp.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtvhzenfgj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtymvnhapj.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtdioimjtf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtbrymlztw.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtryesdblp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.birdmap.top/Article/details/gtybeivxvv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtotftuhau.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtwceymtwy.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gtnmhelqdj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ivvv.top/Article/details/gtosyuimtx.html


<!-- 参考信息 -->