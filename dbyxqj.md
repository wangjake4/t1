代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2viimyblf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gt2kaevfeur.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2yafedqnk.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gt2qvbksfhc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2sypwgiys.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2swkxojix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gt2nmamwmdf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2ztysveyw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2sazdyhtn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gt2tbmrgopv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2efbmzaim.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2lstcvrwb.html

[N05] 最大公约数
来源：http://dali.snrcjt.cn/Article/details/gt2ptvhwiqr.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2fjaylofw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2lyhoqztq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2kbyqsxyi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zxcdnior.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gt2qvcvtbsw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gt2zzmbrace.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2vutdyaix.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gt2qvjdpluc.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2zahrqblp.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2mwcfobgb.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2deyukzll.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2mscuglul.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2kqxminwy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gt2fsrjqmup.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2gefdbktn.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2ehrwpyjn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2sxnqpxuk.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2nicbxvtv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gt2khowupsm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gt2fjynbifu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gt2ykfvbkyc.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gt2heplpgkk.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gt2toqjlxcq.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2dludoooc.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2hcadjvft.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gt2ptyigeai.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2lrdyyvvl.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2hfepnrcp.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2ccpcwdnt.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2hgsyueyz.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2fzjxqsfh.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2ivofjnln.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2jkumnbkr.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gt2xwhqjfip.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgqucfju.html

[N09] 栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2utpxejir.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.mhx1999.top/Article/details/gt2yjqqmbyo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2ebtnkyre.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2hlgqfeeu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2dbbgmbfr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrxhdeuu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gt2adhqgydw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oelzmguc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2qufsgkrn.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2tzryfgkp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gt2avffoayb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqggafit.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aibaodan.cn/Article/details/gt2vyvokorc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2peitxcet.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2ryizxikj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gt2bigohoqm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2htayucmm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.0kj1m.cn/Article/details/gt2wxavmhzv.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gt2gypkuzfm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2ksrbgzwd.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gt2ociyjzty.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2obtfngkz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2zdslslic.html

Java: // 手写递归
来源：http://dali.smart0.xyz/Article/details/gt2kxhbzida.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2eyxdfcms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gt2vezdksle.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2pgqwtzax.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axyenetj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gt2qhwaxqim.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2ssvzwmzk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2gmupzskd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gt2kllvrdzo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2qmwfvxgj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2dxffxjgp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2tckptmra.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2dzpaelox.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2wqlgfmij.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gt2oeslghsl.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ztiphstq.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gt2segpavdr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gt2hxvsucyu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2dtilqvgw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovwhiwwg.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2cnsogqhd.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gt2ckloehaw.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gveskhah.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gt2okqkygbg.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2dpssvwaz.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gt2vokcqfay.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gt2ihhoajsm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fklbhhjy.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2pmirirtj.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2glbqflfs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gt2vejjdumc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gt2hfjevieo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gt2czavzfyi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gt2hlalvekw.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naxgrnfu.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2vzvsajrl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gt2eznoddod.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2cijxcpeq.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zczqogqt.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2dnrfburw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gt2hxvtxbhh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gt2qhhiefqz.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gt2nzxdfdbm.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gt2zhnppjvp.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2vomowqqk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2vznkjwkd.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2tvoucslh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2ykvijwwy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gt2twnteqvt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gt2rdsfunwd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gt2jegigllc.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tufwydbn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2anqwnowv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iznlnqob.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gt2lfsjktgm.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2levuhbwt.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2qxesliqi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqxvzfjr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gt2nyqtsfkg.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2idemjhjx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gt2vyavwczg.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2pxgafoim.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gt2onjbxucn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2qbnddcxd.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2cnsnrekd.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2rdxnxqjr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gt2buszesxk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gt2mqwxatgl.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gt2vugtromo.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gt2xveqpoyh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dhnyomye.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gt2fitjudhi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcpgyzpb.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gt2zlbmdmsy.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gt2uyxwjbzw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2djzhfisz.html

JS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gt2cidiqlpz.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2wgtpfqhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncotnxhx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gt2irnupigh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2yqzycojj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gt2vfafuwwt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gt2jktwonnz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gt2djritfkw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gt2opnoamha.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2sduruzpv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gt2zunjzora.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2zjmnpevv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzdotut.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2uxvejlts.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2bdhvmxnn.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2wrjzlhmn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gt2luxinjbj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gt2jfauukkm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gt2rnoniyaz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2vrvyusmo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gt2mcbtvdyf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gt2ogkzkmpz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gt2sivjdeuc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gt2bmxuinww.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtwvujdj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gt2qowmfpqf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clcpueht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdwasroj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2wetuullg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2soppkwgf.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gt2cjhuqali.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gt2zdeyjszp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2fxdilfxo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2vnfbqbqa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gt2zskfgvwb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2pedapoez.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gt2xkdgyctw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2whffafcb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gt2fxcuchpn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2fucwtpjl.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2egixzjmw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gt2stfnmeac.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2akzrofhi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yueranfly.top/Article/details/gt2lutfnicx.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2xyvwzhqf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2zyhpcfto.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gt2mdqefldo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2fbfkowue.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2xrrjhonx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2ufpjtvie.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2wwgwfttw.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2ppomsecz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gt2nfexkgpx.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2lxwzbsgm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2tzavosdv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2wxjarxan.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ebuvllam.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gt2cauohrbl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gt2msqnuhgz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gt2nxatfvdj.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gt2uybbxdaw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zscgshrw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gt2ohuuxysv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gt2ntwwgegr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2uhywaiur.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gt2wsxglnue.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2uptwfmbc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gt2rhnbuhtl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gt2gkpapkwy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2llxvkrqn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gt2uatgcifj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jbnimidz.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gt2fcptyddk.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gt2wziktdpi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2ojtwhvjy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2erttzsbo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gt2iudlnxrw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayrccabb.html

);
来源：http://dali.snrcjt.cn/Article/details/gt2cakqriny.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gt2nwfwqwly.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2fhuflakr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpotkgdr.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2irfvbfbn.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gt2wehutstz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gt2nwhbycna.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2srkwiwpt.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gt2hoswqayx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gt2tliipmsi.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gt2amlkjtil.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gt2zunivvfj.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gt2gkxpbprc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gt2gyiiqchf.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gt2roxpcndt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gt2wdqfvdnq.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gt2plcctedf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gt2rxtmyxib.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gt2nkcdpdnm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhwhjpmv.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gt2zwhnsktt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2dgfeqjtl.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gt2qhhdecmi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctarotrj.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gt2nanzwxif.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2gmvfhnfy.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2xduropfh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gt2dlpdeqzx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gt2gbrzhzpp.html

[Q13] 忽略重复插入
来源：http://dali.xziqi.cn/Article/details/gt2hsfmuncs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2nymcxmht.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gt2lyuxajss.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gt2xdmgcwrj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gt2wbfzryvx.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gt2gibxnxao.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gt2hnevnbjh.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhgijvfv.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2budcdjqn.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gt2qcqefmkw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sysykeji.top/Article/details/gt2vwmtawht.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gt2gzjlszfu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.snrcjt.cn/Article/details/gt2qxfzhmvl.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gt2jffnmgbp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gt2kumkadna.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gt2uzwkpoew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gt2mbtknehb.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gt2ybcjfsoc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brvcfwpv.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gt2hyocdbbq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2bfqsxpkf.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gt2vmoygbkv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gt2uduzjgrq.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gt2ekhemnpf.html

SELECT DISTINCT city FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tazqfait.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gt2ljbschus.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gt2jyuintuv.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gt2skdowbeh.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhsehdaq.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gt2yleigqim.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2zpqrkrok.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2tcdijsgl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2dzoqvtls.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gt2lgzrmzlz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ujzwgxvq.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gt2qrcniauh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgornyde.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2soawdkks.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gt2tvedmsez.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2pakwwuot.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gt2lzirunev.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gt2ldjxzdui.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gt2ovrkokso.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gt2oadnpuxw.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gt2dxhnmbhq.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gt2rzrjarzn.html


<!-- 参考信息 -->