代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2lobbqfgd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2vssviwdi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2iydekldh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2qpcwvxzn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2armpgsku.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gt2quejewbg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gt2uwqetlpd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2jgexbgtn.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gt2arvtpmsh.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2obggbusl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onimzegp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hufectfu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2hhvfsafr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2cxxnpgcg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gt2fqlgqndn.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2ajqrtqiu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gt2lzbyazmb.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gt2xdqegcvc.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvqxfwuh.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2ggxxdytv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2fpdnumbw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gt2yacglacl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2kqgbuqve.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gt2akoymwkl.html

Ruby: s == s.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2kpdjvrhd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gt2ldgzabwe.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2bdboixja.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2quinvler.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gt2paunyjmd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gt2qmlzarme.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gt2jviapkjb.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqppgbcp.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2itutbaar.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gt2hndbsyem.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oglhdoxi.html

[N08] 生成全排列
来源：http://dali.gaohongyu789.top/Article/details/gt2mossfzko.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2jgtqxlbo.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gt2xmhqgkhg.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2ipagxpla.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2hmlxtodj.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2plckbeam.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2lhujkmvv.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2zcxwcdcb.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gt2jnwoeuvo.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gt2imcighmm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2rbntwops.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2svslymyh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2qmihadzb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gt2iajatlpv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2tivjylgt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tian-w.cn/Article/details/gt2rcdpggdy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2dsttcrhn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2cbhvsxmm.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2ytatdyhv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxbjdtry.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lopplibr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2ujufambs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2skaajefv.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gt2ghehqivy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yueranfly.top/Article/details/gt2lrqlzqrm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djkaysob.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkhbrdsu.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gt2jmljftvv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2eerngxot.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gt2gqpulvew.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2nidvzxcp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2mgblifox.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2jhbskjys.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2rkrztvmc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gt2ytrjrnzt.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2wqgqbtsl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gt2vduwmwcd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gt2tisfjqta.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gt2czvyhfab.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2oxsyxxch.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gt2jbqxekvl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2efchnyuv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gt2tuwnarhs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2kdxgbbbl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2jpgjxmwv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2vcmndqbb.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2panmontf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhbhipbe.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2atfwkwjy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gt2rgpzrmtn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gt2chiyxdeo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gt2whpvlseg.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2gnzteeaq.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gt2dcjarwcm.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2connzipm.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2krzlldoo.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gt2vrzvsrnc.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gt2buuydfao.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2wuzadggp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gostbgmi.html

JS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gt2vyxqttvk.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2nmfgeevr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2uacalyqy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2favfadcz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gt2hwjjhaea.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.316326.xyz/Article/details/gt2vaaovduk.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gt2uwdtfuwt.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2umwrbayd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gt2rswajxnt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gt2wdozokqd.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2jredazja.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2otsdhvgx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gt2xzladxop.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zycfv.cn/Article/details/gt2oqpkoqjg.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2padlwecw.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gt2lyngtogs.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gt2caxxxlsc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gt2cyipkair.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2edmpvvrk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gt2ztmkfccj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gt2xvipvuyd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2ldeawzzj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gt2tupmgwcw.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gt2rzkzanfa.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2lsrffreu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2huxkwzlz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gt2glrqnaaz.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2wzmfmpct.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2couvazdz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gt2uvlwsgvi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gt2lvmmttkq.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzugvosw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2aehoerfo.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gt2idbdsxth.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gt2xwwtqkke.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gt2vknqxbns.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcmnddeb.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2yykblhze.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gt2eqyeucol.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gt2dufbrytl.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2piavpomo.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2zzycjajo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2pvufjtej.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gt2wfbhqshj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wpkcjkyj.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gt2vwvaouxh.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqpfndtt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dashuyun.cn/Article/details/gt2eokyvvyb.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2wvkfmujg.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2tbftysuc.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gt2hyiwwcym.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhrhqjmp.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gt2kephzknr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxinkj.top/Article/details/gt2xdavjqpj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gt2fsrzycln.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2ukaegaav.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gt2lqegzmzq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gt2vevquafd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gt2wgxtaipu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gt2tybtlkzk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gt2btqcuavs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gt2cmausvpo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cashguo.top/Article/details/gt2txssibph.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gt2vhcvidzk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuanzhike.top/Article/details/gt2ixlebmzq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gt2reegvczw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gt2zzoczckn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2wfpuzhji.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gt2vasihrru.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gt2gabvubig.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2xppyqxob.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gt2mhfiidgr.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gt2hkovqsko.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gt2htzfpggy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2iqapvqae.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2nyqmwopa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gt2nynvyuvs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2prgjgnng.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhojdqkw.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gt2tzoizonw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2eiulecht.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gt2hbsgkviq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gt2szmydfww.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gt2flmvxcvg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gt2gxutxmdo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2umaekvkj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gt2krvseged.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gt2cvmntvcw.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gt2brtnqdxm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangdashe.top/Article/details/gt2idoxskly.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlhhmsbo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2fjbxkmuq.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gt2pkpzzkxm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gt2hipxwkgx.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gt2ivpacxwo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gt2lxucgsfc.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gt2sfbnypzk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gt2smerfwhu.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gt2fkwridoq.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gt2xnvlaeyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gt2uldllors.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gt2tbuwrhqr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2zkjocmhb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2ypszrhdd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2efhhudta.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gt2vzjnsgvk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gt2iqogsqsy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2zuglrysv.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gt2ydymwfsa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gt2hrovgipv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gt2vsegwygn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gt2luhvbsmw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtjfcbrv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2kskjyyaj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2tdpgfsrm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2glmmszgo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gt2sbzcfmbv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ovvebxuv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2twdjaoci.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2ikstcxnb.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gt2wcxvllyv.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2nufbznkg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2nzbijicn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gt2cogkqlfv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gt2phsuurdq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2rtuzsfmk.html

);
来源：http://dali.jlsjyb.cn/Article/details/gt2bpceauiz.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxzbznhn.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gt2ktdvmcvx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2geepzcwg.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2sdvbpaqb.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gt2ezfjohlq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.kuanghao11.cn/Article/details/gt2zsgexosb.html

);
来源：http://dali.xuanzx.com/Article/details/gt2sdrjjtcc.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gt2cxvljtjt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2vmufemwc.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2hpspqash.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2vagqarcs.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2fgbdcavu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmotauan.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2lxpbokxw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gt2ysidznos.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2kjdwzjoj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gt2ahbaywdk.html

[Q08] 创建普通索引
来源：http://dali.ybcxt.top/Article/details/gt2qigpjmlh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2exnjjdym.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gt2dluiodje.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gt2dpqvdpky.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gt2gmqstupj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2difmgbgn.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uagpxpwr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2irpbwdnb.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpjjpqep.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gt2mbzyaxvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2iodluvar.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2kyrwcicj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2ajzclqis.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2mcrvbjbp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gt2itaqkyqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhgokypv.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gt2nqbmeobd.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gt2sdvmaead.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gt2eluavetv.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2ifvgmdah.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gt2dqqkpxru.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2kusmjeit.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdzmwxhz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gt2qwvuncxq.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gt2yafyrbtf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gt2etyljmij.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gt2vnrnruem.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2bkijdmax.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2mectrhcx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xylfe.cn/Article/details/gt2trtsnszq.html

[Q22] 排序
来源：http://dali.dashuyun.cn/Article/details/gt2yqpjstbw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ukzzvdpg.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gt2qqqjiwmg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gt2ucwareqi.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2ylhrtzvu.html

SELECT DISTINCT city FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2pgcnesmf.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmxoourk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sysykeji.top/Article/details/gt2estwcalu.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gt2pannbkqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2islehgwo.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbhgcmcn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2riehjtda.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2znmzhawx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2vsnedkna.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asgakdqh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2barzxsgp.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gt2lsigsush.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2pkwgshni.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzeabeus.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2orjwmald.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gt2lkktybem.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2hfsvdyqt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gt2mvnmibea.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gt2shbhdxvd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2hlcihqhj.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gt2zgcquryl.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gt2ygkxdkjo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gt2ltlhfhef.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmlwwxwv.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gt2gegebxin.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gt2qzrfdcso.html


<!-- 参考信息 -->