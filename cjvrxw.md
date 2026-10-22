代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gt2uliwygrk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2bdlkvcth.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2drhxvdpp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gt2uojymuud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmhfntuh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gt2quvevobq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.birdmap.top/Article/details/gt2wrlixgnv.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gt2napgqkri.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kssxlvux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqszztgl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2fqtnluej.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2xxfmltau.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjdfqzql.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2mvrtvgha.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtbixflv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2blljuwtg.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2aniwosja.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2wkpevuuw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sjowkfya.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2ajwuxmvx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gt2phjwdqlq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2pjdjjgds.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejsiwsje.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gt2tijnnhem.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2djxilevy.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gt2yaixlgvl.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmkemoqu.html

PHP:  $s === strrev($s);
来源：http://dali.mhx1999.top/Article/details/gt2acfolnth.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2polelkab.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2roenguiu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2gjssqnba.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gt2nxbqtazm.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2nxgcpdzj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2smvecxlf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssymkqwg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gt2pqcxomfa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2hxadgect.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gt2gorfavzb.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gt2kqguuncc.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gt2zdssbnih.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gt2fdwownkh.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2llumqpit.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gt2rxwgdcfq.html

[N08] 生成全排列
来源：http://dali.tanke756.top/Article/details/gt2lzagggnq.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2qepdkjqz.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2olicazlq.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2txxybwgq.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2wkxdfllz.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2wzfixsed.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2pwyzjevn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2hxdtzjyf.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2qhkicldw.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2rwslmzgo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2bcuedvlr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2acmgfvvy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2ldpladmk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gt2flgjdorp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2texbjxwd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gt2kqvtjkiu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2uzvdiccp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gt2lhhsetwn.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2bccsoujs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gt2dwzpvdcd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gt2vdywpxvd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2rmavbjtk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gt2psnosaqe.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gt2tflpisyt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gt2jygafgfz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gt2djnvylcl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcwithzw.html

[N11] 二叉树中序遍历
来源：http://dali.cashguo.top/Article/details/gt2jmeajpke.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2nantrqml.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gt2vefxdgna.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2nktzennv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2juliezhv.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2tmjqdrab.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2xqmoxshp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2cyqrlvps.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2xvgfzqxl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2bmghwemy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gt2vazclych.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gt2zsmoacak.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2xptktekx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2wcealetm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2sxkaucty.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2tainywem.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2hsuummxl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2bfjuvhvf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2gqwiunxs.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2cwqrzqre.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ygyecdio.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2rvufrbpz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jianghu66.top/Article/details/gt2jusgwtxo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gt2lsdkqony.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258.top/Article/details/gt2ypavwjlc.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2sztgdcst.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2hsnhkhru.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpqgpftg.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2fmepfyug.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gt2dmraguxh.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gt2cuwxdkkm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gt2qavtqpfr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gt2wytdrunb.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2ckkbxzlv.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2gnczihfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2mguiwman.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gt2kqfiabjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gt2yooffwwj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gt2lyoyaeso.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gt2hjqhbxxm.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gt2wlzlfcmt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gt2uazbrbol.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gt2dxmqrhea.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgdgiurh.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gt2iwmefxyp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gt2fomrejdp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2ewzwnhsi.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quxfjazg.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gt2qkhewzri.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gt2netntafm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2iuxfsntk.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2emhaxrcq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2qruukdct.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2gfllsabb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gt2qluwtdhm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gt2dgrqjzqr.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gt2mnappjib.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gt2uzcvyrqx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzjxqnap.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gt2ycsdmfpl.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smknlbvh.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2ldljmele.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gt2ydzgemzl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gt2qcaislfs.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2rebgqdyn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2snhzpitk.html

[O06] 使用进程池
来源：http://dali.yuanzhike.top/Article/details/gt2kficzgks.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2ncxcyrsu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2wvztynki.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2knuvuegc.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2byzshttp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2brzgrqfb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gt2cvfsesnt.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2zwimpiog.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gt2tyludlvi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2yrwjjnre.html

P. 常用工具函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozhdmnsm.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2pidqzhze.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2vlvjgoxm.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gt2ynswskdk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2lxrpllmi.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2ttvgjagn.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2badlsadd.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2blvoufdg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gt2nxxgfluw.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gt2ekejlxpk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gt2ccmrvrca.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gt2eelsydyc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozpofyeh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2ykobcvle.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gt2ogxwmhxr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gt2hgncotlf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gt2nawdmvty.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gt2tifiewvn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gt2rjwvvitm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gt2awnzbwnh.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2rfmocfio.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gt2mjebnyco.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2yqlsnhwx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxhksrpy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2qaneheyk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gt2abwccrop.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2hwvgomhc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gt2wdjgabbw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2gpyjbgsa.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gt2xagxyyea.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gt2lqzobokx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gt2ssfcfaou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2szufbrqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gt2wlvuffxl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdgijdqj.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2iqikwlcg.html

Ruby: x.length;  x.size
来源：http://dali.ppjwa.cn/Article/details/gt2ujncwvbz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2pvwvhisb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gt2rtybcogj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gt2xpgxifjs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gt2yaczugxu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gt2swyudcck.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gt2qopipvwo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajfrjnzp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sadqeuju.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gt2kbhcemqu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gt2qwdurgnk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gt2thsmnezu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2resdnovh.html

PHP:  if (empty($x)) {}
来源：http://dali.zycfv.cn/Article/details/gt2widpfyxw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2ubiuirus.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gt2kjplveio.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2aeqsftfv.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gt2dqjxzbpa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnqzz.top/Article/details/gt2tekgzows.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gt2ipqbtpmc.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gt2stgmetta.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsnpuggl.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gt2ksocatiw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2jtsfweqk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2jexrvrck.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gt2qkihodml.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.kuanghao11.cn/Article/details/gt2okagtgrw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkekhbyj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2krkwmtnn.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2guvrntxq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrsaubrn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gt2ogzywgaw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2cbhjlxxi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2yeejdgwr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gt2roouwlgo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qdahdfpf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2alxtbggb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gt2mssqfihz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2vrodvtdt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gt2tbwnhlbx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xtonmjpj.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gt2nbphqucd.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gt2qjjprxml.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gt2grrdehzn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2opplmakk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gt2wqevkylo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gt2gpzmtysv.html

);
来源：http://dali.jianghu66.top/Article/details/gt2zdshtzyi.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gt2schmhdio.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gt2kvpiljzt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gt2rqeqhxus.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gt2sjcprbza.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gt2ymjpnzci.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gogol.net.cn/Article/details/gt2zsqdveyp.html

);
来源：http://dali.yonumen.top/Article/details/gt2adqpjcjw.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gt2xtmtwiph.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ybcxt.top/Article/details/gt2jssjagdh.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gt2kwtqybtu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gt2lwvetidc.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2hesqzrjk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2blhygcpd.html

[Q06] 删除列
来源：http://dali.zhixingplan.top/Article/details/gt2tntqbsop.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gt2qjpzighu.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2qvojyxch.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gt2rustsvlz.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gt2dnownrht.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2gnpfvwpc.html

[Q09] 创建唯一索引
来源：http://dali.tian-w.cn/Article/details/gt2ludqappl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2nnpfqgqq.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gt2aeikotpj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2jisynxhd.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gt2svkwzfvx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2niccwpni.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlisldqk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gt2fumfbsfl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gt2svbnaarm.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gt2qzeoxwzi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2ogdovack.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2ubccxgbq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifkreilb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gt2qoqjaeva.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gt2gomxnczk.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2tbmqjzhd.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gt2ttvudckr.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2iilhxiuw.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2fwxbsoau.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shuidangran.top/Article/details/gt2cnadzsuf.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2lezmxizq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2jrzgvhzn.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjjcdnzt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.snrcjt.cn/Article/details/gt2bffsqukj.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gt2phyokcsi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2kkdsiefb.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxmrxcqn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gt2ztnwwras.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gt2taukygfh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2vvmmrnqi.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gt2lirdyzjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gt2xegyhkjl.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2boscblkf.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2ybhcjnbo.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2bwawxyhg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gt2qribujmn.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gt2ujkqrwkz.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2ndeqyasi.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gt2dbcarnie.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2ftgcoqgm.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gt2hepxwdko.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2mgmhljsz.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2enjkvfxo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2dwkzccey.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gt2cigzewbl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2ncujzrhk.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gt2inoqdmtn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2foquiqbw.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2ziimsqgq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfcndrfd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gt2xizuhmop.html


<!-- 参考信息 -->