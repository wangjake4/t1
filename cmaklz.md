代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtsjuhofbu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gthjehscpy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtdkzmcufj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gttigzqewl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtqvpuhfdi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtnomegweh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtuknzccuv.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtwcljtszh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtecjpipvd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtewroolku.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtzjxzcoig.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtjirjqgky.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjdspspaa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtofhqcxhs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gthlwrzgcp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtbsncyuqg.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtesormkzs.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gteeplxtlm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtmrudjqwk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtlgcbigxq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvvlorpyn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtbvljvibx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtofagooyt.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gtyceomrdf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtkjbllzgs.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gtxikqgbju.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtxlndwulq.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtopowbzyh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtpbyvgwph.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtblfeafwm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgufenzy.top/Article/details/gtflnxwaga.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gtdtuivgni.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gteprckzas.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtltjkstbk.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtfelaylri.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gtjaksfyso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gtdekxijwj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtaznulsxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtiyuasglw.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtgajemyiz.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtifvjucub.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtovfodnkh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtbgqwqyfn.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtzzpjjiiq.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtuqikzeyj.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtmwhtscin.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtossxaspq.html

TS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtxsmcuftn.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtosqplhmf.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtqynjjcal.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gtdwxoseoc.html

C#:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtdqhummwk.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtiyaeydun.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtplxaosjd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtlpywmoam.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtrxzpkxya.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtprgsbcwk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtfyhrvbhh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtykhjlits.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtckhwejzt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtzgrmhols.html

[N10] 链表节点定义
来源：http://dali.gotoacloud.top/Article/details/gtcmzltxnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtoebetavg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtrlsakxot.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtgqactuir.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtxpcidvsg.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gtfxkqoeeu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjhzyfls.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gthetfcwac.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgufenzy.top/Article/details/gtzhpabhzh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtiyhliewr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtnnlvjicv.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gteufftwvm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtxyaxyuux.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gtghdadwkk.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtyinnxceo.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtuuzjdati.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtljtdutpz.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtzoxmjdes.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtdcycjnii.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sxryk.cn/Article/details/gtfenkabzk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtsgzcdkgv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtcvbwicol.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtngeitjrg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtiphbmkcr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gthvmwqbyn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtvzwaiblk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtkglxstfa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthrawyplf.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gthfrbwskd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtfvghacfx.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtdtbymdcs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmwarmqu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtnpaegysg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtmaelwlmc.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtasreeiob.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtdedswgjy.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtnsmhhfkg.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdswcszvc.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gttjdpoeyx.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gtuvcbukvr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtpylvkdja.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gthfbzhtso.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtcrtduzku.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtjpdylsmz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gttywgvesm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtqtspjdam.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtaswcpghy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtfrwejcks.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtxotnedoq.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtvfyydued.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtozcnlmut.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtjmafgzgm.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtcncpwwag.html

Java: synchronized (this) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtkixrdazz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtwipdlwln.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtkcjqdbhu.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtddcbroht.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gtaddnwcsg.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocpblcho.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtgngzebqh.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gteeeuqeni.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtuhdvcfrc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtfihsukko.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gogol.net.cn/Article/details/gtfhidwock.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtqnoqgpkc.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gteddpqdmg.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtoknmibab.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtjkqllfnp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gtfoinqulq.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtbchfirub.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gttnmvduaf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtsquljwiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtwkuwvexw.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtatwxurlh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtdhszvowk.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtaifvptcm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gtopfzctmh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtgtqwefej.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtylgytwwc.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gttwhrpngp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtqnmddanb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cashguo.top/Article/details/gtvmrslkud.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gttsnokauj.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtmojsqbku.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxqdybbtl.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtrnuuldbg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcatfnjsu.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbwhjysa.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtskkvztjm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtjahobjfv.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtdpjrttyc.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtpgkopvgw.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtgvnvbxwu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gtkzwozmap.html

Ruby: SecureRandom.uuid
来源：http://dali.0kj1m.cn/Article/details/gtdexxfiwy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtzrbeirxr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjprpcdlp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtfgwcuyoe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtgyurolkh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtbzrdrtit.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtmajwbiwa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtnjoflehq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gttizhbhgt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.havefunace.top/Article/details/gtynsygxoc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtfawivrie.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtdbuftqbo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtqbtckzss.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtmeqnzdfw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtislsvgjt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtibjlsbxn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nwbrower.top/Article/details/gtsnnlbelg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gterstkdao.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtlrfyefmp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtndbqvpdy.html

[P04] 求长度
来源：http://dali.snrcjt.cn/Article/details/gtuhsnmzhv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtjvlinkdt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtlnaueoop.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtglbbzqtz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtilqrlgot.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtitbhyirp.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtjhrvjcck.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtugrjunob.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtwjloldif.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gtfpknnpsi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtzhzwqgoi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gttuxvoefz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsijbpza.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtjgrdhhiq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasghvwpj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gtwtxhzeje.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gthgaerfwr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtotycwhpt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gtguqethmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtrqhtyiev.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtcolfmnby.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgsdgixf.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtufpltiov.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcbcltnfa.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gttwvbiwvz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.feifeiyinyue.top/Article/details/gtlfrdjltn.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtomimzyqb.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuimiiakr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gtazbhkdsk.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtyqufoptu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtzhdpiofa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtjwikzmyb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ybcxt.top/Article/details/gtqsibuzfj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtnnaeeolz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gtbpiixkgx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtperlkdxg.html

[P08] 处理浮点精度问题
来源：http://dali.mhx1999.top/Article/details/gtdsyshrbi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtyspobpjl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gteboghobh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtejczyhmd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtlpobzuta.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtusogvwpe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gtvnfcgoln.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtwbxwnnra.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtwqhtprqu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtowxpbjfr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gttmkajlqg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxxadbpr.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gthybspczd.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtejhjzkkt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtkzcrtdqb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtwgyznglx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtrumdggfh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gtetayymsk.html

);
来源：http://dali.shzxlz.cn/Article/details/gtmyeapnfg.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtinbhfekj.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtkxrlufnx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtakznlhpn.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtnapsavfq.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtqdyyyhwi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtwztljngg.html

);
来源：http://dali.aizwys.cn/Article/details/gtyzeupdgs.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtoonkbueg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gtineonnjm.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gtakqqwemh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gtiezobmpq.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtjcfhlaeb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gttyqwnccp.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtiokkmwxf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtuqpkjnfe.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gtosixdvif.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gtvcphbzsn.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtmmriefrx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtrjzdwdoc.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gttmfsmsnv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtxcckgfwh.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtywwsfnsh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gteecqlklk.html

[Q11] 一次插入多行
来源：http://dali.jqgfzy.top/Article/details/gtgcmmafkm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtfpmywosr.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gtlixfwwyg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtgmyfkvsd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gthjjlydmu.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gtztzzfxfq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gtqpfwmxpp.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmkmvevf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gteyowcwtu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtrwklorxt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gtenoecoyf.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gthnlovegl.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtgbqmsuqx.html

SELECT id, name FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtdljwnbri.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gtwfnonpeo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtpplosyip.html

[Q18] 模糊匹配
来源：http://dali.yvedp.cn/Article/details/gtaxjusire.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gtbhowhupb.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtsjqfmkzg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gttjukedha.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtmbyxgamm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gtvlhikbod.html

[Q21] 空值判断
来源：http://dali.0kj1m.cn/Article/details/gtwmqkjfjm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtefuilfoh.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtwyliljgd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtmikbowdu.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtiidcfqiy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxtudytb.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtfmssqioq.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtsfjryevv.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtgvmhurvu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtgekhclvn.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gtapajxtyx.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtgsyhkhoa.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtevoqajdg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtpjmptdws.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtuwzrqiun.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxgakoufl.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtzvbhmznq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtmntdgkrf.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtqeqhcugm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtznniarti.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtbqvslvvp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.kuanghao11.cn/Article/details/gtovcdpmrq.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtlcnztlsu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtbleurwhn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gtvkzgnjsq.html


<!-- 参考信息 -->