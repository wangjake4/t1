代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2bobkhjwg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gt2iducnjcl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gt2symsnoyq.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2gjcqzqls.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2uwlmrmby.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2ptdfmbyt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2hkxcbugs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2ddsqkstg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2sumszati.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2nmetvwoq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2eqxbtorq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lsvrwdcv.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gt2mqqaxrnz.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfrlcsdd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2lceahyae.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahkuekjj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2xdlayovv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gt2pyxafqay.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2nrcaceiq.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gt2hnbrxzex.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gt2pjwtsjtw.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gt2prlaeblh.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2hcgujwel.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2kewpgyge.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxscbluy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2hnqtrnqz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2cxlmekfi.html

Go:   // 双指针从两端比较
来源：http://dali.zdqjudy.top/Article/details/gt2godrxzym.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2xnkcbtwh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.meibo888.top/Article/details/gt2gevfzewv.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gt2fvomqzqx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2qoytgonr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gt2quvubpld.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2reyybuzi.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gt2xygpzwzf.html

Java: // 手写 HashMap
来源：http://dali.hysaishi.cn/Article/details/gt2jkgipcji.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzqsbtnc.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gt2kqowbrtu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gt2vpxtohwg.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gt2snrdzlru.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2kejgtlqr.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2kvfyqwpy.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2dvetxvkk.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kojtlaxz.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvmmhvae.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2dvrgfbll.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gt2lgzpevju.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2qpjzaqyb.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2bgfmmrar.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gt2hpinrpkh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2dxilkrak.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylkxrzwz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuxming.cn/Article/details/gt2dpyeqomt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2jzkjzloc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oubamims.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cebczaww.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2bvphsdrw.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2sjzmbues.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gt2yeuczxbh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tagdkksa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gt2vbdrtnin.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gixlydyd.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2orcxljgw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2onzcclnk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gt2rffsrmvf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2kgvrrfoe.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2gueermbc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gt2sujpjzhx.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2vncczkxw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqetwjfy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2preqoqzs.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2rdysziqf.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2fpqxxgnj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gt2cnjiozij.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2bkmktpcw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gt2ynmgnppb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2wpcfrgrm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gt2abmtwgaw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2urquhcdl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vshkrgdl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gt2ipdiyodc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gt2tqfriuol.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2xertomol.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gt2oudqkjsh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2kfstcxmp.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lluxrsyy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2skfhondu.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gt2mmhrbfrb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2lxakiptb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gt2dhwjgwuj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gt2rldqszts.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2myfqmbdq.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gt2dssfxtpb.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlleotsy.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gt2iejkonil.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2gazlbyay.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2kaoeoxfq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2lktltchi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gt2umvacrpi.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2lagaknxk.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2abbrbzlx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zxhygxmq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gt2iwnbenre.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gt2qkliosaq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxrfbgle.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gt2gdstwlqc.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gt2rtwayihz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gt2srbqblqm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2cqqgfram.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kckkqefp.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2bbyhebsa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guannengcc.top/Article/details/gt2ybkmcpjm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2zhjkzpxz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gt2rzvorhnu.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gt2jgmruirx.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gt2pngxuywl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwlrgplj.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2txovfnda.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2wlhgmdfz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2lackmcik.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gt2sejluhml.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gt2sxgzrccc.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gt2fjwiudbi.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2eqgggvic.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2kzhupygt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2nwskiduk.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkurhykp.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2qrwbhani.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gt2ylvooles.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gt2msjgrjvi.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2begippsx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cdnleiting.top/Article/details/gt2fjapjjtj.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gt2mptdajll.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gt2vohrpico.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2jgpkyvni.html

JS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gt2xxfodhrc.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2bubnvowd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aizwys.cn/Article/details/gt2zzmsigmz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ntbkwslw.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2faencmge.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gt2ekntsskj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wnlodbau.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gt2pmndvzgq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mdxdsqba.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2zpvjmfqn.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gt2trgcryuq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2jezgpomt.html

JS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpqrcmap.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2oacasyap.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gt2uwvwgrqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2bzzozdkd.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gt2dhtgsqvo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2lkcsvfib.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gt2exjabnjj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gt2rykutjzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gt2xjxblikx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gt2xvfuxcrp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfkildr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gt2ayuwjdkz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gt2mjnkilqk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2awnkrmsi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2dydesjdx.html

[P03] 生成短随机字符串
来源：http://dali.dianchejie.cn/Article/details/gt2anoywirk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gt2sqqegkkc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gt2eckgbslv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2gmgzngiy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ssexhtrr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2fmadgkfx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gt2rkgmqctg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gt2wivxjexv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cucudq.cn/Article/details/gt2aumdepud.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gt2sjzjsxjp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gt2jozdqgdj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2jufypleo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2enkucoyn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gt2gozpyjmq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gt2ycbqqbai.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rktrgtur.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvxegowv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gt2aulawmyg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuanzx.com/Article/details/gt2hxeaaxst.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvekldsm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekxngpbg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gt2mytckmwr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2oynrhtfx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gt2lrxzwlqy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gt2cvpwmkck.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gt2cunbimbp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gt2smolfprl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gt2difbqhsi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gt2kwqegmnl.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2shyawghl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gt2xgivffyg.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2polbdclh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2vppfgvgx.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwzyssoj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2tuzmfopj.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gt2novwmsqj.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gt2iswdcdtv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gt2rfxcegso.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gt2ufaxevqp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zeqqckht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2elkowkwz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gt2xlxkawjr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cgosqrio.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2suiwlthk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gt2iwwqnild.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gt2liiiserq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gt2hgyizmxh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gt2jkiwrmre.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gt2btvildrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ofitxibe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2gubhdtxa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gt2mtwxgfhb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gt2gotyxssl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gt2vzrirpfh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2iklquiea.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yvedp.cn/Article/details/gt2bttrvxna.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2cikaliif.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gt2vztiicvx.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gt2putyepun.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2hbirxxkl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2lgvurqew.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzkmwyxe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gt2tbwfilfn.html

);
来源：http://dali.cheryme.top/Article/details/gt2jlqtgcqy.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyitdbkq.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gt2hqlpxomk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2ipyhklhw.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2uamxhpya.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2iayhxtbx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gt2xmvlhdvi.html

);
来源：http://dali.nanxuanxn.top/Article/details/gt2kpssroad.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2cxdszfvp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2zezxvgrd.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2ozftfzkj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gt2erfszxqu.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gt2mckehbtp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gt2fdxcioyu.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gt2ikwpyayy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gt2qujnnocp.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gt2rtjvefaq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gt2xwfayckh.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gt2gksfkhbv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2bfoczobb.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gt2ayrwxmzl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gt2oabwssng.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2wdsevyws.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2pampfwgj.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gt2srxgpopd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2cmnthrgi.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gt2zlsuhkgr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gt2mfcarinr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangdashe.top/Article/details/gt2dcswkdtv.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gt2gkustvxu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gt2msdcslle.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2msdneipa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2prvvbdtc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gt2lqygtrod.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gt2rumhuvuw.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2xeykjfoh.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gt2leiiegsq.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2xzzyoviq.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gt2znbqwgmy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znqlohay.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2dpurhhcq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gt2pafmxets.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gt2kaczmung.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2acbtjfuw.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gt2odtgxsta.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2iavyuzoo.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gt2pmszvkgu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2nmkhcoud.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2mhpnvnos.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2deoootxm.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2tibjbhhh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjnjtvxs.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gt2ymsbsqpr.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2kpgaggjb.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gt2gmlcczul.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gt2rxrmznep.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2gtcmzcfj.html

SELECT COUNT(*) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2pmgaaxxu.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gt2uktkckzm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zerxuazf.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2ayauokka.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2xpfvkcrd.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gt2chmfbput.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gt2koebhxge.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gt2mdpljdni.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2kkdcbjgu.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gt2bhzmhrlz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gt2zelijttk.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gt2yytmmkyb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gt2rtyrxfln.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2rlczykwc.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2xrvlkuwl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gt2uqwqkwhv.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2mtnekxrc.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gt2wvkbuonu.html


<!-- 参考信息 -->