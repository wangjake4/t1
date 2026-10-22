代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2nekxxbbi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubdhwmua.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2pivbcypj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gt2cmcrkqsy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gt2jypidowi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gt2kpsvtrua.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gt2riwaalqg.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2svbhvotd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2rmkdhwqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2piywyghw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2doojnnik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2qwdcjgwu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2xluqnedz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2sdfdtulb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gt2ijqqzpre.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2txpryqpy.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gt2plkqgkxe.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2aidfkvtl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gt2ohupcuhb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpnmdqsj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2xwjlnnbi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gt2yjagrfvy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2yfuaruhc.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gt2ejtjqyls.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gt2gzdkyqtp.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gt2qnjbnrzo.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2dsusemto.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2lgmvuhxj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2duysqyhq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2rewtjtax.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gt2nifhmzfb.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2zupaqwdm.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gt2gmgshods.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2pzqdmixr.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnmpfjfc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2euxcuupr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gt2sufxiflq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2nugndfzi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auoaulop.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gt2rnhnbzvs.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2jknbbprn.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gt2bzvanyqm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gt2ghovcibl.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gt2vawdicsc.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2ptqqxyfp.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gt2xamxmouo.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2kgpdsnqm.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ftaajwau.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2aionqqly.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2ouqkgyzw.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2jzrfebkt.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2nnrgryws.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2wbcnvaun.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2snutvjrz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmgwsecf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2yczssisl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2jpikrete.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2oifrbrvx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2jioakjjk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omuqvewu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2iyhgmzuo.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gt2dmkjjeyr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gt2xumqsuqh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2fkazlctt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gt2emgdjrle.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2lvvtxszt.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gt2vpchsrbz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gt2shoxnffj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxvltxve.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gt2hpefpjlj.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2yfmqpcvx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gt2ycsqeumb.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2reorvkwj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2lkxlezwr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pevhaqbh.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2cfetsnpg.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2nvdtxayk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2ogwlaxrq.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2wikskdjt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.mhx1999.top/Article/details/gt2vzbuwxqc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gt2xbvagdmf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gt2zdffinhl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2itvszpaw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2qmbfuvho.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2dydbzccs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gt2ukibqdrj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2vgqdehts.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2ojfnsaka.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2njpenegq.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gt2uungwcmk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xayklpcc.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2cmndbxdf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2bsjtbowj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gt2mptlygha.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gt2vrtgddwl.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gt2jpbadsiu.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gt2bmmmvdaf.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gt2clrqdkdb.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gt2uxlaasqq.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gt2okhlcxqd.html

[O02] 使用线程池
来源：http://dali.gogol.net.cn/Article/details/gt2dlogotyb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gt2mtjawffm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gt2opengmvt.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2tvaqdixe.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2xalojrbm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gt2hxioavgh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ppjwa.cn/Article/details/gt2ojscnjuy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2gfxbqhrl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gt2trslcfif.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gt2jhaofpes.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2cbypmrde.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2doeulnco.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2zngxuavm.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2vflfsaia.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iiptocwd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gt2tfohuojr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gt2bazofixz.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2iulrlghn.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gt2ewzeewde.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2wyhdgvlt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gt2nylxkdjv.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2todlcdgs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2tvngwkxl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2osboopyv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqeyluwf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gt2jrhvxttf.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gt2wipckabl.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gt2csckklwl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gt2xxpubcsw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gt2tujmdbdx.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2fgkywlej.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gt2suuqpqya.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gt2pgkecghz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gt2prbdljdd.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2spkfqpne.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybvowrma.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gt2johmfbxk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gt2rztiluzf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gt2dsggrfha.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2ssekaxde.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2xxugzkmx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gt2qiangoiu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ybcxt.top/Article/details/gt2rjumzjqb.html

Ruby: // fork 块
来源：http://dali.ivvv.top/Article/details/gt2jwyguycg.html

C#:   Parallel.For
来源：http://dali.hysaishi.cn/Article/details/gt2tcemjmso.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vxcmtzeb.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gt2kirtgybh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2tviaqymv.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2gggqbjvq.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gt2hedibegr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2mmhcthti.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2hingjtkm.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2yytuwvzj.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2witlpznu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gt2ffslznls.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gt2rdgywqmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gt2zbrjtwqb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gt2vuxomfqu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gt2ydxdtzfm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gt2doyrbvqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2klrelcom.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gt2efwwxwxf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2qcwjdulm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gt2cmttdpil.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2zcfntdzi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gt2lpuwpshj.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gt2czgggeem.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2rmciylsf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gt2klknhpam.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2peajewbc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gt2cjujfwgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gt2tqbqykjr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulitfyqz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shzxlz.cn/Article/details/gt2brwzludf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gt2fqjiymcb.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gt2ahcbqhqb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hysaishi.cn/Article/details/gt2yvmokyet.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gt2quvlzrnt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adoxmwnk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmxpgmwx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gt2baxixnna.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gt2gsirupzp.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2ujqybkdd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2ibvcmoud.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gt2rwvxgqrq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gt2qwxwhrch.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gt2lytnwkze.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2pypbfuyw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2dopjpksn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2bxlphgbd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmerdjwr.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gt2rlcpnudz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gt2cdshqiat.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zascknim.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gt2tiozrdeg.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2supblvyf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhmwzblq.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2clyzspkf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2qhvwihdc.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gt2sxeqvlvl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gt2trtqeosq.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gt2vfqfaemd.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gt2lcjtynbm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gt2qliwgbir.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scmrbjln.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2qoylccjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2lhfkhpdt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gt2fusjoiby.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2pkoinhuy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gt2abhylauf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gt2kktvhsea.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gt2rbwrgvmk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gt2pdqbopep.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gt2ffahdiyl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gt2ybhyuejc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gt2fwdmhuut.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gt2ljzhazap.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhixingplan.top/Article/details/gt2rietdnwr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gt2tilaiqdd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucfukqyp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dzrsgefj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gt2gyltmhba.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2ctbmixup.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gt2lrogcykp.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2kguaooau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2ytstipie.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2fmtculvv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gt2vwvbswjl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.iojbl.cn/Article/details/gt2uyrluzap.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2atodtntn.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gt2kofxxatg.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gt2rbvkveqg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2ecppkjgr.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gt2wmocgxlv.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gt2wilomiwp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2vfhmyhvl.html

);
来源：http://dali.snrcjt.cn/Article/details/gt2chiemats.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2libpxczl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2npirjonw.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gt2ubfdjmxo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2erpyejuo.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gt2wvqfufar.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gt2etvoepie.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gt2ekployvt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gt2dfvwxsdp.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gt2yctfurbg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2jmkgjyra.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gt2ennlicyk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2ysdxrodd.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gt2yspzgoox.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2tfvfjmjr.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2kvverdla.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2nbfjytwx.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpygmbsz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gt2hezejlig.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gt2chjhhntq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2einuzncn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2pulfqxvu.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2iwzshfrb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2cieohjpv.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gt2xhcrebrx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctffopbu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gt2gzqzkhty.html

[Q15] 查询全部
来源：http://dali.mhx1999.top/Article/details/gt2ypdbmdge.html

SELECT * FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtdhntef.html

[Q16] 查询指定列
来源：http://dali.hysaishi.cn/Article/details/gt2wrgyjjcq.html

SELECT id, name FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2nzaswxhw.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkxdugze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2uglrnbts.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gt2bpprccpu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gt2ygahoupu.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gt2xhlmjatb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzvhnsui.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghxwhnja.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gt2rdmjsuqk.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gt2fcdjtfex.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gt2yymsbsfd.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gt2imgqynqc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gt2axlfhhmi.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gt2lqlciyrp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gt2daanlrzm.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gt2qxeabhnj.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2jmmprkny.html

[Q25] 只取前 N 条
来源：http://dali.jyoumei.cn/Article/details/gt2joxnquni.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2zjrxxfat.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gt2vpslijgh.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gt2etmvmgcf.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gt2jwuwmovz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2xywugamk.html

[Q28] 求和与平均
来源：http://dali.zdqjudy.top/Article/details/gt2slcplzml.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2ncpfwxro.html

[Q29] 最大最小值
来源：http://dali.gaohongyu789.top/Article/details/gt2cbseeboc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2cvajxkma.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2eubomdxi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2zvbgvokh.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2hrjxpzbn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ppjwa.cn/Article/details/gt2spgsqipd.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gt2puskkdig.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2cxcyyihy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gt2awzdpxva.html


<!-- 参考信息 -->