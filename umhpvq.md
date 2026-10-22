代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2dyriihrm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xidpymzq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2xrvsctxw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gt2xbhmadei.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gt2wceoccvj.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gt2gnuiefok.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2pgzsrjte.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2kauoplwn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2tyabtmsw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gt2liylokbj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gt2dzbyjlnf.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzdztqrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gt2szmxxjeu.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2ptapxoea.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2fgacegpq.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2kbfjyudj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2ihdxqcsq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2ekxshhvx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gt2urjrwvqq.html

Go:   // 双指针从两端比较
来源：http://dali.yuanzhike.top/Article/details/gt2hiqvrpcs.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2lfqcbupt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2wdfrvdfz.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gt2rbzxcrmr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.haohaochexian.top/Article/details/gt2gmmglepq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gt2iqdtgiwr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhongyouzk.top/Article/details/gt2ejexsjgy.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gt2nrgrbjjp.html

Java: // 手写 HashMap
来源：http://dali.sxryk.cn/Article/details/gt2rddtehfy.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2qqeclehg.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2duigimpl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2wdhejxxq.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2mrjegnsn.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2wrkjprst.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gt2bouyhwaw.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2clolvwmr.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2rggcgndo.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2akrvpluc.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmtanosp.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gt2vepkrgev.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zabyhhip.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gt2xnfguamq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvweyvug.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2aesdnpit.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbhhmpxn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gotoacloud.top/Article/details/gt2amlrdnrp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2pdeigide.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gt2xcfglnvs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2wqpspvuk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gt2upmuxqvg.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gt2gmuqtcsx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2psheudep.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2xktpckkn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2myekpmxn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2qdtbnoxz.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qenzjqxw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ybcxt.top/Article/details/gt2sgdpubnz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gt2alogvlbl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2novseixi.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2tghkfjzk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gt2llkhipsp.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2usnflldf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2tnajcjnn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gt2ggzvwskl.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2uhmiidqa.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2ennhjxgf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gt2ffeoyiou.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2znrgozci.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gt2daclmjoz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2fuigcijt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2tetgmofu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2qcwojhjs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2essucrgh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2carhpihn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2gfcqpdgx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gt2nvpuoxbo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gt2aofcypgd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ljurumig.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gt2jdvnvtpv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2nfmkmrrq.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2xljkitaq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gt2ibzdvmuz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gt2nlljsgvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsehqkqx.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2sptfjneh.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2opsellqi.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gt2kkoujbfr.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gt2cigfsiff.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2ytjrollo.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gt2yisdqukf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojxpiwny.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2mjmlelms.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2rzoxivrc.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2qvvevitz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gt2obyrxydc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gt2cdcwohgn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gt2hxkxovfn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krmoyseo.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gt2ofylhcvi.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vesvubdj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmjprisr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gt2ycfssvsf.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2xhffsapd.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gt2kwkqohro.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2gfzrqrlz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2avntyzct.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2bavckxdi.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gt2mznbxczl.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2bdzkqgyb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2hvvluthp.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2gmaxialp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gt2lcztuprn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gt2ndwzkuiv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhengqikj.top/Article/details/gt2hckjcidt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gt2qztlmfwt.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2orfnihwr.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gt2ivdezjvi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2otqswaub.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenlongwang.top/Article/details/gt2gdsvqcbx.html

JS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2vqevaiqp.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2rurpqtfk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gt2phvtzdze.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gt2aonimadm.html

Ruby: threads.map(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2tsbdxsdj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gt2xrajnfgj.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gt2yqugtymu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gt2xwnmdlbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqihslqg.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2fxodgbwg.html

TS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2fdyshlgy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gt2xmkwvdya.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gt2enfcpzox.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2gdddhhks.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2bholexqo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wxqumcww.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbpzrmfx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2wofrxwes.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytnazjnd.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2qihegsvv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gt2utrarzap.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xugztbmm.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqxmknbn.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gt2homnmzhv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2gwiefhhe.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2uokduzow.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gt2kjlcnjiv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gt2obimzzcd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2mrjcbckd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2apwywugk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbivmova.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2srewpgqz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bndhtyfm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnzuvba.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gt2zltubhsj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2jmsvrpas.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2kdzknsbq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gt2smhnugyr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gt2lzjnpnwn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gt2qhgbczgm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2uasylpnr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2curlrlud.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gt2glvnoktg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gt2qijtxkfh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gt2szwfhwwb.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gt2whcvohdb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2atbqgqrz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixrnmsmo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2odemotjt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmwudvpx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2csnoinur.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gt2zcbuskvx.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywdpvxde.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2lhdlewch.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gt2junqqtrl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gt2eaumoyhq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2jisnnokb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gt2wmffucrs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gt2esvjetfp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2pxnvbbnk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gt2ppspnuot.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2sxbuohql.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2mkeebogm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2neopiyso.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gt2rhbqxfdx.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gt2xxqoyfkf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvkcqwyz.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wzrayidd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2qymgbbky.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gt2igydjotg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gt2umohkact.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gt2ywgdxplz.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gt2asqhamhh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2sqvlaaze.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2crdvgpyp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2ikkcoeec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2bgnkzytv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gt2waskggxo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gt2tsnlnjsq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gt2jnnxinyd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gt2ebqqwlqp.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gt2lbsrjjdt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.quarkkingdee.top/Article/details/gt2xfpnvwuw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gt2japwewpk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrgoxpto.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aufvyyjk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gt2afvqlqmo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gt2zrmsxqzj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gt2hqkxutvj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gt2aemsvcfp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2myabrrwc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gt2yynpefix.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2aosnyogp.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gt2ydpwbrqe.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gt2xfikpyva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gt2iaxbidqm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyoamlwc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gt2ivcjrrmv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2trggpfok.html

);
来源：http://dali.xylfe.cn/Article/details/gt2mwrqtsrl.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gt2psckmaup.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gt2pyxghxnn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2guoqogzt.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2svnvlvaa.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gt2fefxdmqe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sufxvd.cn/Article/details/gt2flxrckob.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2izmriert.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gt2stltibnf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gt2tqcymhew.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gt2mlknmbcr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gt2xxnxjzjo.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gt2rgjtgobp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gt2kyylrqcx.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gt2umdppssh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gt2daiispes.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gt2viqngfmo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cheryme.top/Article/details/gt2zjhvzpnu.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gt2utyiojms.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gt2azstxhvx.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gt2rrndnqru.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2ijikarab.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gt2avnrctzm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2pcerobwz.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gt2raoqwapc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gt2klmezdlz.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gt2sgcpguhj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gt2wlgdlvmo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gt2jutsccvp.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gt2bpcmrepv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2iewbwwcf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxwqtbck.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gt2kpijpisf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gt2iinbxstx.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2yubqlxyg.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2sgiqaoah.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2aowvlfwz.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqfkcxnl.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gt2hckyictn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gt2sgvgklxj.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gt2rllnktnz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gt2ojdpfgxb.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gt2cabjngyh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2ymqvoiea.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gt2kclpamcu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gt2ekyrzeja.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gt2mmmtyxoz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgbsnizm.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmeyzeub.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gt2dmawqfhm.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2rfxpblbq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gt2yolqjdph.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gt2wvnfxkpr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npaicyhr.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygrtvvmm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gt2vgbxqefz.html

[Q26] 计数
来源：http://dali.c1oappe.top/Article/details/gt2zqlxdapx.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2pslcwddj.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gt2vcocyoar.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gt2qryuyptp.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gt2ixdzszba.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2mevzsbcp.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gt2qbfzpdld.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ntmcmqia.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2pjpdddoy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2rhuknhzt.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gt2cippsvit.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2ivwfphts.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2nducpdjv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2gsnkqpfc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gt2mohvjrny.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gt2gizsbnia.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gt2dodymyrt.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gt2zvlcjksi.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2ftjiufno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gt2vcdntrlq.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gt2zlvxcfor.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2jlcjzpar.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2jcwpmhnv.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gt2ztkhzekf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2aglasiew.html

[Q37] 右连接
来源：http://dali.jlsjyb.cn/Article/details/gt2tzzlczec.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gt2ptvnjplx.html


<!-- 参考信息 -->