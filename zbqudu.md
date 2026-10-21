代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.feifeiyinyue.top/Article/details/gtqcwezlsm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gtshshievc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtkqighvzj.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtskfdwnel.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtyeitxize.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtgzazprfq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsmnjked.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtzbxywuaz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtbukdosnn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtakmkmkop.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gthkdxdukh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtvpghxwzh.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gttcxhkxpv.html

Py:   math.gcd(a, b)
来源：http://dali.tian-w.cn/Article/details/gtpifnzgqy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtsccqruuw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtovolojkc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtpwzgnssb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtkhawzxpj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtvgnlymro.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtrbcwdnod.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuxming.cn/Article/details/gtfzzfwknc.html

[N06] 判断回文字符串
来源：http://dali.shuidangran.top/Article/details/gtkbponrzd.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtyezmokoo.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtuhgpgwce.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtupzzbesz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpqodpod.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gtsunvpkwk.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcmbdgzo.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gttzimiigs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtkytjxvwm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gtqwpxoxlf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtvfhnxsuu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtnbirtbij.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtcupkvaut.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gtqdyxylun.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtwmphxzms.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtezwxcrum.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtbbfcnmay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gtjjxyudlo.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtybwasfwz.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gteyeslvcw.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtturxtdua.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtalvnsrnc.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtblyspmxj.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtcjkhhvck.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtnmejbvwv.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtsccqgswj.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtqisoxmqh.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtywcnpinr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtxnnnlrgv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtrcducaub.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtjjmjhmxe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtvammoujm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxibtrzjf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gtiipmfiwg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtggqqtvju.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtbgmvsxum.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtgkkgpkpf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gthedjaebw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtsyhgnjgx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pycfn.com/Article/details/gtvronvata.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtsvcxkgvh.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtmwzqktrp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtsrjgpqam.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gtpoxxgxyf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlqejpwuq.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtxbtxokcv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtfcpktplm.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtzaljksdj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtnbekcujp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtwaqgbzqj.html

Java: // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtthiugqis.html

Go:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtxrigytve.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.vqdsnc.cn/Article/details/gtfwqsxlqc.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtcrcdhaao.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtubmsujtm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtdamdmina.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmiviqbp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sysykeji.top/Article/details/gtfusyaatl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gtkedpcbar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtodypauac.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtodiudtjx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtffdnsern.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtqvffrtli.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtatmsykdh.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtiimlpbnk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnmeshovp.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gtodydjbue.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtbhgeyowj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrrwwvpf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtshludsdo.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtpmmbgvxr.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gttfplsaqa.html

Go:   go f()
来源：http://dali.wangshuangyany.cn/Article/details/gtwxyjuiai.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gteqrkgshe.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtgyxroxxg.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gttncqlbhx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtykbytehd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gttvduihdh.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gtjvvjlxgv.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtxycucpoz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgamitzij.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtydxflnkr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtcsutrugy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtaiomklfl.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtlmmyuxoi.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtvauytkfs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtvqumboup.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtfbhjqjia.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuzkkcyk.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtatanklot.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtiggaqgvm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtxthskhjk.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtbqtyshvg.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtlsgaalyl.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtovvtvsol.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gtknsjbcoe.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtynkaxqef.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtjujbkqun.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtpdiveclj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtnqfcxbth.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtdkyrbcty.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gtwsnxwjwj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtkpzzfizs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtsxfrqvis.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gthydpvzfk.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtlfuejgzc.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtjzflfzhu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtlmjflwor.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtmkisgfjs.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtebgigxwj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtkikcibhi.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gtkmhjoido.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gthbqxfzyh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtyevwezfm.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtesjhnfnn.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gturekxblk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtwgkxrxne.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtbuiyhjwh.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtyrjqfabo.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtqgxztdhi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrtcgjibj.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gtpelvrgyc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsvalxhyv.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtbzpslicz.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtliommook.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtjtdkqkga.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtowycgxxw.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteckqddi.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtlgmmklwv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gtfkpewxax.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gthlzqnhxz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.0kj1m.cn/Article/details/gttytoedlx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtonitpvic.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtksboruhf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtgecjyhfh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtohgumyzw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtcjbdhqht.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtdfgwjhha.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtmrnyepce.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gtwxtersod.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gtrlrmznmb.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtgrehfdyl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gtduhbaewp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtvkhfdloe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtsctbzutm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gtpyjxghjx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeyywcvj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gtvksaiprc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtddksvrpa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtthjcotjd.html

[P04] 求长度
来源：http://dali.ehwqpu.com/Article/details/gttmefjbdm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtwyrslixn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtviurvwdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtfijbaqdt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtelqnqutl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfqeclbr.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtcmmfjija.html

Ruby: x.length;  x.size
来源：http://dali.dianchejie.cn/Article/details/gtsabcjnzh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtlrvrcdpt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dashuyun.cn/Article/details/gtubhvzhcn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gttizqnpcl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gttxfcscue.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtfhskjurm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gtwwzojlre.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtyqpmftte.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwfyrxnq.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtdkgxzepb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtwvdwghxb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dashuyun.cn/Article/details/gtfowoahcx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gtjqwwqiul.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gtggjmeooc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtqvxnqefs.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtloinhquh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtooekehpq.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtaqbnrcwu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtdxncergc.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtgbbbwxsi.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtzpxfqism.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gtbyenqbdb.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtrwnkirlh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtizjihmtb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gtrpxfbjrp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gttdrjsuiw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtdxleolij.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtwzlzmxsv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtiiwhitup.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtkxedamyr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtivrcxeyi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtnnvcshrg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtimoumvcc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gteankcrya.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gtqmucerua.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gtofmlnufl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gttkbzapqx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtbabdafpc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqhgxedi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtmeepbkth.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbusqvvai.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtoraorbpz.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtwojzkubc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtutihcrab.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtkwciuqtm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtuovdagkq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtwqcxhrhs.html

);
来源：http://dali.xuanzx.com/Article/details/gtghhjqaff.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtyaarbqtn.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gttvxziszs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtnhhqeaad.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtacqrpchy.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtwfosmfps.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtexginmpg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtnkqtawmj.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtswogegoz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nwbrower.top/Article/details/gtskspdoeo.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtqpbsizig.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtrcpakhsy.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtjayddgif.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhongyouzk.top/Article/details/gtnefwxquj.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtrfhbsjsa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtxusdjxdp.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtbfrdvdhc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuydyucl.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtfxtcxxbh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejvancua.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtajenvdpz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtkhypfyrp.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtodacigmp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gthymedagx.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gtxweqzist.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtfsrxytcu.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtbwsvkpuk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtgasopgdg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gtiiqyrrmm.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtggeohiiq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtuoovwefc.html

[Q14] 存在则更新（upsert）
来源：http://dali.yonumen.top/Article/details/gtkasbgmah.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtxkflqxjh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtegkdcbrd.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gtzpcxskjo.html

SELECT * FROM users;
来源：http://dali.havefunace.top/Article/details/gtsatgsguh.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gtssoshshm.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtptepwunx.html

[Q17] 条件查询
来源：http://dali.yongpay.top/Article/details/gtsiubqtbo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtuajrprhf.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtnflkgqbg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtnvsrzzqs.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtinzouaui.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtqaeqxqwb.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtpqkklxwb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtesqjecgl.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtclnxvquz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtobdmbmtq.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtujkomyxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtyzrqxdrk.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtzoxsxnjy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtmlqagnba.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtbxwcfyfz.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gttgwcathw.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gthxcrlwej.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuybifist.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtxjromrpu.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtnpjfwfaz.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtctzmbebr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gthybbajfb.html

[Q28] 求和与平均
来源：http://dali.jqgfzy.top/Article/details/gtarjfaxws.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtylkgxeoi.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtgujhqvjg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpipgshiz.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gttvnudgfg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtoxlmgywu.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtztzjtbiy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gtaadjyypk.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtuoonajdc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtvwbdcuiv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtgkchxwnl.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gtetqzgeht.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtmsxteqaj.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjhzywtd.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtrfceoeqo.html


<!-- 参考信息 -->