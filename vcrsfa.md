代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gt2tmvuarak.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2ntyqbpwd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gt2regczepa.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gt2stbafbyv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2sunmhyvc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2ltzxafiq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2igopfzor.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2wdpjfbwf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gt2hkvoebxx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2phgqirbf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2yafarwct.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2cfxtynod.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gt2fbppvaxt.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2npbmcjdh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gt2xqducxbi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2dngmdrvv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivxrxmcc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2krfytevw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkgecopw.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gt2lsxydsig.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gt2jbshuxxm.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gt2oagbzqmn.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2uqrdgjib.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gt2enritede.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2acitfxxk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2webhnqug.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gt2toavzqmm.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2otlumlxt.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhgmaydv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbeqkgtp.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gt2osdcictm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gt2oskrmdot.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2glgloljz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gt2zvkgiwhl.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gt2wyndktxf.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2cnqcpuxp.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2ckbdvpvn.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gt2jlenknfq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gt2vrhvgxgf.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gt2aaxexoaq.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2mqgpvvsp.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2qyxdoejb.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2qpeppkem.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2bsbafnmn.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2zoabocbj.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2rmqfzccn.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2lfyamjlx.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2sygzeqla.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2zkdxrmoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gt2lurfingu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2cloebadg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2crengoyj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hywenlv.cn/Article/details/gt2xtxakets.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2glpwiyzu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gt2pxhgtlts.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2katzhaig.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnqzz.top/Article/details/gt2daztkmpc.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2znqfaoyu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2pcvsllyf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2vievclaa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2pjhhyjbt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gt2tuunbgil.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2npamxpas.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2mzmgfabe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gt2iioldtha.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gt2srscevmn.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2xyrzywnw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2brnfcskh.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmglztnf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmxreand.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2ndmpvwst.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cndvqdyb.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntjzlndt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gt2njgvlnjc.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2dcgsygmb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwewqwgg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gt2mmtecyus.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gt2nqrrzynq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2nuyofjqv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pmjdpobj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2ewrbohww.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cashguo.top/Article/details/gt2aumpgnyc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ggjltkng.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gt2jizfeqtd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2aqlrpjmy.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gt2qsvofllm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jhhryflc.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gt2qqiawarb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nkkreacd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vremtdhd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2qnqsujes.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2wddzbnxp.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gt2woxidhnv.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2khddoqmq.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gt2uqtrzioy.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2zdbmnbby.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2jzwagnpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2svtihdmn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gt2niacnbag.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2hjualajt.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2nfjesrog.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zernidfi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2cmkubune.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gt2wsnyhgpt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2jkusgszj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2juunqvjy.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gt2gzdeyqkf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gt2fedpczrl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2qvdztyqc.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2grpsgqgw.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gt2uawqrtji.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gt2bvyihotl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2ppepwuwu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2gqokgqym.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2cglzagsk.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2cqciotrd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gt2bkamfldo.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2whnoywkd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2oxoskoqa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gt2wfvxjmue.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2svflmtpf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2nqplydyr.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2btdjfpnr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvvovchz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2ufgtkeuv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrexragw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2geuenhba.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2gzoebktc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gt2hmdfedkz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gt2roanktvk.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2gnaxmlmj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gt2ewckcaow.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gt2taigssmw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gt2bmvuhfzr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gt2ktxrzshk.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2qthbinaf.html

TS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gt2ghiamixx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2ukwrbjui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gt2twzeydac.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gt2lrsjxwjm.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2oxdimpdd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2oozncdgz.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gt2ahejqmft.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2uekczkzs.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gt2fpjcrqdn.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gt2vavhteqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2crvjpfsk.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcfuwlnd.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2klfngypw.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2jlbliimn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2vqqynvzo.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2enlypaox.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gt2njaewnux.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2awhqucwr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2bpdvjgws.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gt2lwnognrm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gt2kcnrtlox.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gt2rhtkqmed.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2sxapuzmk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdjksfst.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bljbwzmc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2xmlkhggf.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gt2gyfoevuy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iiuqwbxg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2hwsqcaeg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2uxrigxog.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2rsuhesjz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gt2cuwokylw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2psjhxtfa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gt2ilhslieh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gt2ndnfpzoe.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2lnacnled.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gt2cfhgwyno.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2rclygdre.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2kflqcorq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2gkbmfdum.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2irdmbgln.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2izgozsay.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gt2illwxarw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2oanvzqpw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gt2ixdufgzn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbnedyvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gt2bcfwkkbi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gt2udzbyouy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2gzehgauy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gt2jvvnzcgq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqubxvvq.html

Ruby: a == b
来源：http://dali.nwbrower.top/Article/details/gt2gqmqgjrz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjwlfak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gt2usjrhohj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gt2kuojsvgb.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gt2bhnwzujx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gt2oajgriiv.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2dqkdyvwt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qsgattjn.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gt2bmfqranh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gt2lmnlcjmj.html

C#:   if (x is null) {}
来源：http://dali.tanke756.top/Article/details/gt2fbrpdbmq.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnxovlwb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gt2hbfmhffo.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gt2thtcehvs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2jhaukerk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zslgyzab.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gt2ofvpzrxm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gt2rhaqprsp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gt2pbtasraw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gt2tdudhvlp.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gt2chetefuh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gt2nkzeftma.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gt2gkyylkvo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gt2ybilffki.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2lttmagpv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gt2brmodkfg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2nyqvjhke.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gt2rckrygsc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gt2gcfvreom.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhxycfbg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258.top/Article/details/gt2krrtkcgv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2xojcsfup.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gt2bsshuaxh.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkmdzocn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2pwrbfrxg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2mcnqcsfg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmpnejpx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gt2emdhgofq.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2fvpjzhox.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gt2dwcfykad.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gt2vqvskhoi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2ohzxrzwy.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2tqgouyep.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvrkgiey.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.svipenyu.cn/Article/details/gt2wwzfxjra.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2wnjzkscj.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qstlxtok.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gt2llcecjvu.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gt2beaeotvj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gt2ngeghsrf.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gt2ncbsytvj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gt2rbqmbysv.html

[Q06] 删除列
来源：http://dali.yangfankeji.com/Article/details/gt2cgxkbsaa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gt2ulxkyyds.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gt2zquueitu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicekgd.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2mzeskygz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxabhyiz.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2brviwzbe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2mzxxyrkj.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyvffzrc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2wurazvkm.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gt2ywehdnra.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2eiqnktpn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzupsqgs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2gcjxxvdi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gt2mtsiuosh.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gt2rexifkkz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2raxhhpxu.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yekcmfab.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvsersex.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbilztuw.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwilaewy.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2wbdwoqzw.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gt2rcmcmlab.html

SELECT id, name FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2vfxktouz.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gt2qwlwvryh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2qidnidoo.html

[Q18] 模糊匹配
来源：http://dali.zycfv.cn/Article/details/gt2lprcpdby.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gt2ofdsmgze.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gt2hjlznotr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddpdznzc.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gt2wartkdon.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2lbexynoc.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhbtwoqs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2spopjolb.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2vpjemjha.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gt2axsceyot.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gt2rgbcqylw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2otllrzqj.html

[Q24] 去重
来源：http://dali.nanxuanxn.top/Article/details/gt2ctddfloa.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gt2wlqweumk.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2hvpltpwk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qczfwxcd.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gt2byoicxbp.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2mlnmxqoi.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gt2wbizsjiw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2wspgdqdj.html

[Q28] 求和与平均
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrbytcog.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2cunbyreb.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2fuxwzurm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2nnbywcet.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gt2yeyvgsew.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vramserf.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gt2lzxytxfv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2wqnrkvmd.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2olwyuqdp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrirmypm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jiagoushi.top/Article/details/gt2cqedntqa.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2fqgsbhqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2oricwknh.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gt2khkobgqg.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gt2qgbsrwwy.html


<!-- 参考信息 -->