代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2ysrqquyg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2axyhhpfi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gt2sgtmnhsg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wawcghlz.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmstbzjw.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2awianadw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nspphtdh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gt2elmqltow.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2evmxckea.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gt2sphbgizj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2spdrwkjg.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2cutluogi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2orenchyq.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2miwlxorq.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2pkyorpff.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2avstukeg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2sllvhxig.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2flqhcfjz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zycfv.cn/Article/details/gt2oyypfiqx.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2txkmtsxn.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2mdilbvws.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2eqnkodgu.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gt2phbmwuaf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gt2kbbruqix.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gt2iyqaupvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gt2wavhloou.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2cvzsikjm.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfcngdak.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2bviyyryx.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gt2kytnuyfi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cdnleiting.top/Article/details/gt2dhyzxssg.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gt2ctigstzq.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxrxrdfj.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgmwwbzi.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2lhqrerqh.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqwvdvlj.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2jjoejmzj.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2emriebfa.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qoyafrfk.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2zaafqkij.html

[N09] 栈与队列
来源：http://dali.birdmap.top/Article/details/gt2yjhugkhu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2bgwtvbza.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gt2wyuvaxho.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2brtnkude.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gt2rzvyniai.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2fefmrwla.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2qozuknwn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2btbpgtnt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gt2znrfcysa.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2wlsdnuiw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gt2nvskcfis.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2arvhzamf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2bcwtwbud.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gt2lnzccwrr.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gt2iicgygyd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2tpmypyuu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gotoacloud.top/Article/details/gt2zbvuinow.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wghgpqto.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gt2lkhpatex.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gt2yjpxlazi.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2hunewdil.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2ireqfvcp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2sgaamihe.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2ppggdyig.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2tpwkjnmx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2quusqiri.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2vudjjqdg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gt2obfdibqj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gt2ovakpvjw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2xhzipacd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gt2nulvsyds.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2qmhnjvqe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2hpkoiofw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gt2hfxzasrr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2gaxrmucy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2xiuetfdl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wdmsaeio.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gt2gwpsfigr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2dfpxpqjt.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2xqmnedjh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2sihqupga.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gt2djmbjcal.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyvdgmgp.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2sqzajott.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gt2jkwbbhnt.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gt2ezjeccsg.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2ldxntunc.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2cvescelm.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2ycgsyltw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2yuaalbcy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gt2uofdhtzd.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2yrpzxgyt.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2ecpxdvzb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gt2iraugvfl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gt2adooctst.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gt2xqrbxpoy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpqdmqml.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gt2rkotogwa.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2thcddggh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gt2vyuyejfd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gt2nzossrbu.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2aphwazdw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2utrsggys.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gt2iqkubqun.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2mginnvtc.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2oryjgxku.html

[O04] 定义异步函数并等待
来源：http://dali.zdqjudy.top/Article/details/gt2ebljyzty.html

Py:   async def f():⏎    await g()
来源：http://dali.hammf.cn/Article/details/gt2mpzazrhz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvzxthqh.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2yqbneqnl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2xpzexkao.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2uuiwcoub.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gt2mvbovath.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2iltnkufm.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcgnzcqy.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gt2fyajggjs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2ceqrlzrn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gt2actxskja.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2yxbfcmhk.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2dlcafhbg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gt2zycbdwwb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sufxvd.cn/Article/details/gt2veulxqct.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2pupvgtbz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2cvateuox.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gt2efzfwraq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmphaiap.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2tgkkjlus.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2uldzpgbw.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2lsodvlph.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gt2rfkpvjaw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2olxbffji.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gt2ibxlzxnv.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gt2ltqeaxen.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfwxyszy.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gt2pplksnyh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gqrpsvoj.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptdrfhch.html

Py:   str(uuid.uuid4())
来源：http://dali.c1oappe.top/Article/details/gt2zitbldyt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2crmknaqa.html

JS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2xauhtssx.html

TS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gt2oynfeslt.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2abqphgss.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gt2qfbetgtt.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2fjzjdlhh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2swjlnxry.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2xokitlkj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gt2jquptnox.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gt2iviqpjiq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hammf.cn/Article/details/gt2jnocdcdf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gt2epcstixs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gt2fckytufi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gt2bjqbebgn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2nkrirrqe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shcxhwem.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2svorkajy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gt2amzfvpoq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gt2uivrjewl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gt2yyvfxoro.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gt2ysyfrsfi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2axnsmnoq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gt2drpklacd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gt2gyzkjinm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2mvippxiu.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwmxlche.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gt2cbaiusbp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2hdyqvcbg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gt2tgtllxve.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhecylsi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2wtlfhxgz.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gt2yueookve.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gt2kjfisdla.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2vjvawoha.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gt2cthtrtpn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gt2phsdxgdx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gt2mwktcrdl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gt2unazwywk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2oaznytkv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gt2fzpgokuv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2qmzjivqg.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2gxqlzgle.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkwezgcr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2vrgourtp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gt2dujmdqsj.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2lqjesnsm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gt2ovkmnevq.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gt2eppjjdgy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyvbkdfx.html

Go:   if x == nil {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zcakyglj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2xvhonnxz.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2hgejattj.html

[P07] 防抖与节流
来源：http://dali.shzxlz.cn/Article/details/gt2dmqlzwlc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gt2eyliiaxq.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gt2zupcruag.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2mfdqlqwg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2pebephht.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pycfn.com/Article/details/gt2ipjastik.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2gkrrpafj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gt2spuracyx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gt2ddnixigh.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gt2esyvndbo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2jjawokdc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gt2mfbjdgdd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2xvrmrdan.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2zueecdhz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gt2geklsxqp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gt2chqdtphz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gt2kbhrszpq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gt2pucxfjqz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2dlxlqsxx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gt2dnxvundb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2tubdquof.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gt2tfcpcmvt.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gt2hxbuwxeh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2jxwhjrzd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2xioiormo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gt2wznixndk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2jsrulvnr.html

);
来源：http://dali.redwolf501.top/Article/details/gt2fpqwhzya.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gt2eeagmziw.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2glbpepdr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gt2ybugpqsp.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmpivvac.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2xteavfkh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gt2sswonfyv.html

);
来源：http://dali.yj202588.top/Article/details/gt2wpfrkdle.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gt2zxrrqzpv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2ekulubqy.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2ececmdkk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2gkvyyhkb.html

[Q05] 重命名列
来源：http://dali.zdqjudy.top/Article/details/gt2nwdprkim.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gt2bidkxlna.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gt2ziegazvb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbfrqgw.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gt2oothqfzc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2hfhutzdn.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gt2sduanoyk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2myjeaouq.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gt2qgaqaten.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gt2jusoxovt.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gt2fneimugv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2sgtavuln.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gt2htqrutgo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2aygvysac.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gt2mcjdqvfk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gt2vqdipqyd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gt2uxyngnoy.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gt2ethawmrt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2ynitidjb.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gt2jqwyrpqi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gt2gqwtvwur.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrqnhcwd.html

[Q15] 查询全部
来源：http://dali.vqdsnc.cn/Article/details/gt2nbcrjryx.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2xeuiuyzg.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2jxdgeahg.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2eksnoxzf.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2fvgfcmkd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gt2xbdrwfnf.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gt2gocxsohb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gt2oxbqcyuk.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gt2yujbrnjn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gt2yotxegvk.html

[Q20] IN 列表
来源：http://dali.chenzaomai.com/Article/details/gt2aaheeihk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2cdiclcoq.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gt2tjvgdclz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2fslsogxp.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gt2yhuavayv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gt2pdbgjhkq.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfywnkdo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gt2umcvbext.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2knidfuvf.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2ifofoqba.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gt2mirerpzu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gt2tjnsuntn.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gt2rywasgux.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2rsgmddac.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gt2uqhrpvvh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yonumen.top/Article/details/gt2eervgysf.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gt2xeduvdld.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2izcyxhuv.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2yechzlfe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2nsdvejbi.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gt2aeksxkkl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2mbzqodkv.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2wzthsdxh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gt2bpcprspt.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2yfjwromq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2iwpokxnl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gt2tywbhdeq.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gt2wevuotot.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gt2wgktsavq.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gt2dmphbpdn.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gt2jpjbcapb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gt2tfciqaaz.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2eoofxbse.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gt2mnkyfeay.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2lrjydntp.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2lpmwplxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2ohkdsblx.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gt2ouiocdfy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gt2opydrbbh.html


<!-- 参考信息 -->