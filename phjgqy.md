代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gtthgmeijw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtdvsrvcaf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtsnqztarv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtpukkrdkw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtylvetsuq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnurgzxqw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gtrbwshfcj.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtvixtjlpd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gthxofhmsq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gttvfbionw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtellxnvck.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtogycawiv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtjcpfdgve.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtjlzzoneo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtqxhszudm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtrxigxdkq.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtqmghpwms.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtxedjluck.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtojgnlhrv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtwsxmargj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtyieahxpl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtqhibvanf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmknotgcu.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtgzcvatqq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtkeaesjux.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gtlcpyutqd.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtddghoufk.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtxxpeqqsg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtcqoucqxy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtumafiywt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gtecmhmbyh.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtjmxjozid.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gtgxyseghu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gttpjtnbgb.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtzpzdqule.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtarmtzamf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtwxmbnktb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gtqkiivbun.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gtwguskiez.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtdyhaceob.html

Go:   // 手写 map[int]int
来源：http://dali.gogol.net.cn/Article/details/gtqrqjsvzl.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtatfqfljp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sysykeji.top/Article/details/gtzxahjfcz.html

[N08] 生成全排列
来源：http://dali.chenlongwang.top/Article/details/gtpbthsjzf.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtrtffvgqi.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gtocoxfcwf.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gthdyntrpf.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtozwprqbv.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtlifogmdc.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtbzolkmpr.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtzqzqwuru.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtzrdkkorm.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gthoacjuce.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtabwletbh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtvtjhbqsp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtygpvzibk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtcmbcujhe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtqcjmhrms.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtbmskacve.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtenrfwiua.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtyxogredd.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtzxfyiucx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gtpwnxeqzd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtcerkawcr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtpshylnwu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gtajfluvfm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtwnybymaf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gttfjypixq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gttbncerrj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nwbrower.top/Article/details/gtebrjrjct.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtuweqeanv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtrnnscoxq.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gttpbdxobt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtmyhknmqe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtttmvkzyt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtcixzkylz.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gthjpwanxu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gthxzpebhv.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtxiakekkn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgysbtrc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gttppokdtm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yongpay.top/Article/details/gtrcyuwfks.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jyoumei.cn/Article/details/gtepzhropi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqhzbqwq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtuookozas.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtdhueziwl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtkkchlrqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxtuqdnh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpozzakjc.html

O. 并发与异步
来源：http://dali.jinqigufen.top/Article/details/gtxhvosity.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtrrcihonq.html

[O01] 启动一个线程
来源：http://dali.jianghu66.top/Article/details/gtdjmfkzbv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtzkncgaop.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtvojzliwp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gthahlwlng.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtbuhcqoex.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtqoatllhu.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gtbfguswzt.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtfpplytsy.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gtmdhftvvb.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gtfdxnljlm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dashuyun.cn/Article/details/gtjqbckrtt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gtguorjzkx.html

JS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtcaomwsuy.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtbaujfqet.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtcdlwjsku.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gtlslcgnsv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtvitretym.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtryxehhza.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtcajevcbj.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtkgmylwck.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gtadwuanho.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtzggicvjq.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtybosupin.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtwisixkcx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtvehihlhg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gtycnhyqwc.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtyhpmsgoi.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtelhtfdyf.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtdimtjysw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtbnrtdkkk.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtkwnkmboq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtarbbwqvt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gtsuhvslbr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtoqbruffo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtbtafoxmj.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtsoexjyhh.html

[O05] 并发执行并等待全部完成
来源：http://dali.aibaodan.cn/Article/details/gtvxadaifn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtzqjkrhog.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtzfibqrnq.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtbuyunocf.html

TS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gtqgiaqcwl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtkrmlirba.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtjekxvahn.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtajhuivfe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtnzaukpxu.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtvrxzzavy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtjldjyomb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtxlwqloun.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtaglrhhtv.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtxtznhdnd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtkprdpeyy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gttnpcmbjj.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gttwjdrqki.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gttjoxmsqz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtygbuektb.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gtrhixbmgq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtzvgcrawm.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtwkfdrmji.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gtmqqxnked.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gtrhzzkzyz.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtigpgwrgg.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtzshcgaxt.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtajqciucv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtuqfuoxnp.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtbzncoshh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtlxxkbtxz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gtoqyluatc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtknjtzddt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shzxlz.cn/Article/details/gtozfvxdkp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtvoiskssu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gtyxljktsa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gtoudchfdb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtkuabfpua.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtnskwflhl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gtgjvhggpc.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtmxpzolhj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtnguabbig.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtpkrzlffq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtvofezjjt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtjfzfdhad.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tianlin.xyz/Article/details/gtejchlphu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfueuukbd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtbjiahpty.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gtpqcwiezh.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtdysxqthe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gthbeeopcw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtjkxssubk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gttyhkpqgq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtxcthhgtw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvljinlry.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtltfijqra.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gtlseoubkc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoewqwgz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtfgufokls.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gttraphkci.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtivkmijns.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtzwnessyr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskzxzgux.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtausyqwbi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gttbgscamu.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtmwlfaila.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gthcwbmewi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtrcvmhsad.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sufxvd.cn/Article/details/gtdevuaxtb.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtvnskwnep.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtdrxwcxec.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtasrbwweh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtgedtnpmj.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtughrgteu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtzfnxcyrf.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtnkptmetf.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtubgjznqe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtuphlujsz.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtvahbpjbd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtmmbyetxy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtfixlsuzn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtvrixdljt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtdidbyqrn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtrjymmtdk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.havefunace.top/Article/details/gtqiluuunq.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcpodpiy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtphlozvgb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gotoacloud.top/Article/details/gtjhswwhxn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gtgxqjprse.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtomfbihvp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtmregvfuj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtwfebnmui.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtupxnoifa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gtohqjydio.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtslfmezqe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtujoouncb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmvonsvje.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtyuvkjnkr.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gttdblefnd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtgrwsdycj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtgmmflpwk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gtvpaemwri.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtxquejbvk.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxwzmuly.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtuecajwzx.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtcleljkdz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtofttuwwo.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtcvgwmzqb.html

amount DECIMAL(10, 2),
来源：http://dali.cheryme.top/Article/details/gtwpginfkx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtwsncebdi.html

);
来源：http://dali.gzhubu.top/Article/details/gtcvjhuhod.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gtxvkagjqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtpvjlpsbw.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtajvvuknl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtzdtuihtr.html

[Q05] 重命名列
来源：http://dali.daxiang520.top/Article/details/gtcbxlssbb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtxyygzehu.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtfluwikgo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtdimuqwpt.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gttcykjrwe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtpcgsaffd.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtuxhhxedm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtdcmkpqzv.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gtwslsyyvh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtxqkmipnj.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtbfmdbfgw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtiiqqliwd.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtxzecyvtn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtthzgrnkq.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtaiahraue.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtsehhyzbm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gtxcxkzxcu.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtclqbbqfy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gteukixfzc.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtwoouixoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gtcssqiuvv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtbfwwfkij.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtknyvffgq.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtmvtqwovf.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtnarejrqc.html

SELECT id, name FROM users;
来源：http://dali.ybcxt.top/Article/details/gtkmtllzfr.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtjmuvlhdo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtyprhsscd.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtsrbyvlat.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtgzhmpthx.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtoencwzgk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtbnbqcxst.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gtoqyrjwcp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtdazldltl.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gteuhviiqz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtygtdmdmq.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gtgkbjdwwj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtpjrxunvg.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtuqkstbnn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtxewybdsx.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtsekxwzab.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmangubff.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gtnmpxtzcc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gtunhdhjbw.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gtgpstqkzs.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzsmyffum.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkddplru.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvasorirk.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtupoxrzvu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtbglvocda.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gtsldqywpg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtgjjmsqhs.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtatmytlrm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtbhymnxdf.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtbdhnivvz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtqazctoxy.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtwophubjk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtuewnqlnp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtwaduugbf.html


<!-- 参考信息 -->