代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gt2hthspkaq.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gt2iesfslkj.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2ubvvgvow.html

PHP:  $s === strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gt2atkfmiow.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2avgbpyyi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gt2dqrjnvcj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gt2axxnstds.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gt2cowaazcy.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2vzyccija.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gt2surxcfoz.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gt2avcsaibi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gt2pdrykits.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmzjxlnw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2tdnqwzzj.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqryqxyv.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gt2xcipgtbl.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epwbgwad.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gt2wjslbnmx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gt2zslfuymc.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gt2kzbnqcyr.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gt2bjlmxqmd.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2mcfgwvbr.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2vpunluzg.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2oqftoljx.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2nqmjmqux.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2jczadqis.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gt2zchjvwhe.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2wrxopgdm.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpfeggls.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gt2aunlgylo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2mmuvdshd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2wlanioxo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gt2iosrawwh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cheryme.top/Article/details/gt2txuqjfmn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2jwtkgcrt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2jakuhvsg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gt2ndtcmzgz.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gt2gdddffvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gt2selptwsa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ivvv.top/Article/details/gt2kmkjglkl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2dksrbhui.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2xxtnltob.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gt2glnfrxyk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gt2hwdsvldn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hfpthk.cn/Article/details/gt2gqazazvk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gt2lubcvuqp.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2svnheshq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gt2xfcjamnm.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gt2yngsygiz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2psfiyqgz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2vqbhbvgu.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpzljqkr.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2dvhedxys.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2yodkjrft.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2rxxakohd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gt2zxtghvuz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gt2pfmqzehz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yvedp.cn/Article/details/gt2vnoxxtsx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2fyaivbmv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fprtgxis.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2uatajoef.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gt2tgqrxbma.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gt2wsaeaqey.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2hkxfohwj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2fbcponfc.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2bwpwwmyp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujsxnzzg.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odkijiot.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2drgvqyxm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfmvzfm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gt2kjcieqti.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2xatqfgvs.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gt2kgcwnsym.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gt2okmpgaod.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2pwsbilst.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2ehiqqqqx.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2jgbpkhjo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gt2eyhqjrtx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylbgkukk.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2maxavrlw.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2jnkfvhhd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gt2qpbbrsuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gt2ecqzgoxk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gt2ipjxpvwd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqbakido.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gt2oumvfovw.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gt2zletfjks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tanke756.top/Article/details/gt2uegmumvv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gt2fanzwegt.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2jfevbtmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2scsfbqzq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gt2ytlqlwae.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2vezhiryx.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2gsxczbgk.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2ifgvxkzq.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gt2iblocaek.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gt2uzqoqqup.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gt2gbvxxkby.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2mtulflwq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gt2mhsotrkx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gt2krqsgkbc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuetiantiany.cn/Article/details/gt2aetgldxt.html

C#:   async Task F() { await G(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wisbytim.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahiotfet.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwazshtg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gt2bnivbvlh.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2zhfonfde.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2pinfmrvu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gt2miiphjku.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2gqgfdone.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2mdotszpl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2nlkmjgxp.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2cqhbcncc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2aabeeaan.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2phdoktjx.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2eisqcgmw.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghtswcdl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gt2ozecford.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2wakjdqsw.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gt2jqscwhhc.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2iyysfqdv.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cathclck.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gt2oowjrshj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qkcskppr.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2wpgyneox.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gt2caolstro.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2uwxskhhq.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2dezwuxng.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2fyepcywj.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gt2axbsmfgt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gt2gfwuafoy.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2qlyucqud.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2tomcenms.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihvggabu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gt2xqgoivfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2osklzzwc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2dkligmsr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2pwescdjf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2xayxocdz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2seoskhjs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gt2oczufwnp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gt2tbekslku.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gt2shbwtixb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2ksojhgjk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2dnmqkdwy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gt2bodxrafn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2onrxmksv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gt2hwylprys.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2wqqkvscy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2yspltyyj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gt2bmfkwmca.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gt2vgofhueg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2ttsmxiqj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2jetebjbf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2mhhqooli.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2brbprojc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2wtkfokto.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2wekgfebs.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gt2qgqdbsvz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2hfiyzhel.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gt2bwrpvemg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gt2pfmsxsvh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gt2sqvkguxm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gt2iuricjud.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2hsjvfqca.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gt2zhbdmcfk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwghmowj.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gt2aoxpmidf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2wcmcmazg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gt2btdbqexq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2tohqclet.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gt2fazncwna.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gt2fbaepfgh.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2okgscfxy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2xdejlwyt.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gt2bppsofpn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2oevhwivx.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gt2fqzfgzpu.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gt2uuweuiyg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gt2uqdtbksv.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gt2pshnehpw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2pracrmdd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2iuugfqrw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gt2wuhvcjsr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gt2uxkdxzpr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gt2kscippks.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gt2wtpcyoch.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2shtibqtg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gt2lgpciemf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2awqvtzgz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gt2xvqpzfjh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2vtwzybsw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gt2utfrunib.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2aenuiopk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gt2jbiumsdp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gt2nhtrmxyo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wancykno.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gt2vdimtrry.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xqxnstyb.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gt2tznfyqsw.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gt2tmldzwhp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gt2pthsouhn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2xymggcdl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jguoqigg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2vdydpqap.html

);
来源：http://dali.smart0.xyz/Article/details/gt2hbyvpoee.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2pwgrnhpt.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gt2pdwthfar.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gt2tubxpbap.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvfysbf.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gt2xnsvusvn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gt2vbuodinj.html

);
来源：http://dali.meibo888.top/Article/details/gt2mphbeheg.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2pugljucm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnfqoikf.html

[Q04] 修改列类型
来源：http://dali.cucudq.cn/Article/details/gt2kfrrpqfr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2oeumgaog.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gt2iyxujosf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gt2ntbbktii.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gt2nvjcnjwb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2tvzeldkz.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gt2cpsjodbo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2zhclhvbk.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2lawosnfz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gt2yihmjbqt.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adatopmj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2ojdscqsv.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gt2kchmadmq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2swwxkuty.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2aypgxceo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2mfkvbczp.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gt2itwpcplc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gt2eucgyvoy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gt2ttrakzre.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2kgvycbfd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2tleocwow.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gt2vdfydnzk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gt2tslgraxa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2cnjpohat.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2vetejwub.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2yengawcs.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gt2bumqvomi.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbvgxido.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gt2ailfegtq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gt2nlhtgouq.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gt2nrwpzrne.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2wkmxvdrk.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gt2hmjdktwg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gt2wjfsdxda.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gt2kevsldcz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2uohqevha.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gt2pjiszais.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2zdkezcxk.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gt2gulbzoit.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gt2zexaxfir.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gt2gzqjhbbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gt2lkalmqhr.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gt2soaunsve.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2xyuzfrcw.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2mqzaxxko.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxkjxveu.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gt2ybsimrln.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2rpoifcca.html

[Q27] 条件计数
来源：http://dali.yangfankeji.com/Article/details/gt2sglggbre.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2qmdkisjb.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gt2cnrqxnzw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2bwtrjaal.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gt2okemvpfh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2wldlnadn.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gt2aellcoao.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2sadylgfx.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gt2nyhxdytu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2waddrmzc.html

[Q32] 分组拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gt2fubtvugq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2srrokboy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gt2tbjvzigx.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzqzyntu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gt2tuutjjti.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gt2fobrjors.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2umjbuyuy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gt2jxjglxrb.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2yrfyeuve.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhlixbgw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gt2zhiarbvv.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2epknkmtk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2ohsczayz.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gt2bleigjbe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2ikrisyjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gt2bksxcgub.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gt2whjxlfyn.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gt2apruoqem.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gt2dlkccsat.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gt2zmbhmbeo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gt2udlzlenc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yueranfly.top/Article/details/gt2aektzomb.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gt2qvqymfkn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gt2vsuzjwyq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gt2rczeyiup.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2bsdemqqt.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gt2mktlkzmj.html


<!-- 参考信息 -->