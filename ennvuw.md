代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtfgwcmffr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gtajacwqii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtnfujqlyc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtolqsofyi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtmvvknhuz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtplgbepny.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtjgmqzrwg.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gthciwfhmr.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtghrpazik.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtkvciukmi.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtxzxaffvn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtyivykfgd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtqlihqxss.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtlnkdavyf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtgvasnmgg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtxmmssovl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtfrsptxji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yangfankeji.com/Article/details/gtoulpkrku.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtmhjaloyu.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtrrjsxgsw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtotjiexqp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gthmabvpvo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtayrxfsim.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtfckxpxbe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtnedkckar.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtspobzlwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtslxfkzvj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtsagluhog.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtithjtlcv.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtjpqtcboz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtqtnjwhoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtawcmkppt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkxwqvvn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtnuxgxhjj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtouvrygpq.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtgtylitvg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gtrsddlwif.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtgvywjbzb.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtuinwwdez.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtehygivac.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtgvbhmyag.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtmyotskec.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gtqikzvggv.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtbvghcpzq.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtisvfafft.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtipveavrr.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gtmabbmvhe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtcrvcvemc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtjmcvqrdc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sweek.top/Article/details/gtehfxjdam.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtpbimspry.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gtxoxgckfd.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gtfwwfcfvw.html

Ruby: // 手写 Hash
来源：http://dali.wangdashe.top/Article/details/gttzyuvawi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gtcxwuudvd.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtbprkftcu.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gttdpxxuyi.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gthsqcrzcu.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtgogomyij.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtntpwuvad.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtowhnqhzo.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtnggsudmz.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtzqlasojy.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtlbwwnsbf.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtvraixnxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtjipoktyh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtjoypcqci.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtodqysmep.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtndlzbnrn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gtjjpzfzme.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtzcbspdno.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtbskgtpgz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gttlsdxudc.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gtllmqcjzi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gtynjthmub.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gtzrsyppcv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtsnfcbyqb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtuettsrmv.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdekmwfnb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gtcwbnszub.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtgslxcjrt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gthjhtnmxt.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtqrztbjfi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtsylmjbez.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gtdzhcoswe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gttsonxnxf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtjlhixugz.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtoysfypdi.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtrfitjvke.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtsaztbjoh.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtorxodjfl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gttbqfzdxn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtpztmrnuz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtyuvtojca.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtmhlobrdk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtmazevlgq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtoqteevlt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtyfvfhlik.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtsylysqov.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtxtgbnbhb.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtshbopvpt.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gttoywenvj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvrhfqbfu.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gthggoxydw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtvhnvdjnm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtohgkdvuc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtjdwftsbr.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtcxboutvj.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtqkzlmxns.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtnyiwpgay.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gtjpzgdrqi.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtvlgvauql.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtdzwcwwqh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtqkkuizmm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtdwifvqmg.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtvvpdsruo.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtgxngjnhf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtjllrhlon.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtboqjrcge.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtgsjqyjla.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtxnwszarp.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtlhtjvhry.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixmlsiia.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtqvibmaeh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gtlwzfctmz.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtktftkptx.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtppmjfurk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpsgzajv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtfxgbpvgf.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gtenawpcwu.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtoefoadns.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjomyfann.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtwxldarkt.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtvptuthgf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtftejnkxo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gtaavgrifl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtpeucrgnk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtcclaydly.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxpdmzxdb.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gtwdshyamg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtslqdeldf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtisbxryew.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtyfkunxie.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtxdleenxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tanke756.top/Article/details/gtrqtwnvuo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtmuamngbj.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gtmazasrvn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtisrgxuba.html

[O06] 使用进程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmoitzbm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtuveyyrac.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtpizydavu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtnbdeupmh.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtehdtreyc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtyniidvti.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shzxlz.cn/Article/details/gtvqbrhpnq.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtclyfmsdx.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gtwohrucqp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxlomzpn.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtxdltvtnw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcqrcubfu.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtruehaxyl.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gtcdklgebj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gthsbpkzeh.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtcauzposb.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtjpcckxog.html

Java: UUID.randomUUID().toString()
来源：http://dali.jyoumei.cn/Article/details/gtfutdabdq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlnfaxhj.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtdmenwsxp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtfawgmqkx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtcoyxbapm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtmrrbzjxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtiwaffojm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gtguakiopy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtcfpthazj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtvwqtqwhn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtmmlvnpsz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtlwldlxva.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gthkvsaaow.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtfiwrdzar.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gtllxcuaaf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtrfmfgwvq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtcevscfun.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtptwxvsxr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gtbkynlxfu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gthqfgokdn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtwaowqeuw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvuspfrj.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtiiymmeyy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtevqreezd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtihqfmjch.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gthuhhnqfd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtolmgwcxs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtwwaaxppn.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtsvtjxkdk.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtcmmvalvz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtlurymnfo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtihtvcrbs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtndildmzq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtuumlonos.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtzbqsybsu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtjlixdboh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gtuxingvmi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtpryezcbh.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtbqvijdhr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtokuwfgtl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtuggexwwo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtkubsbkxz.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gtjqqkruxr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtworpclgh.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gtulqzuspj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtavzcplof.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtvjpdiqlw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtyuksbdty.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtkagdazmn.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtgvgzazym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtearnzite.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gtpsakaslt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtxyzzjuvf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtzxztqcvc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcuzuoxqj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtmmqvsgjh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtbnzvtzpp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guowangkeji.top/Article/details/gtsswopvvl.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gtolowpyax.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtbpqfcmzp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gtaxjnxyku.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtiebfzljb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtjrfkfikv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtkwfkvbdn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtlqbapfao.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtphmyjcqv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtvscngilv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbmtmhxti.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtwtkmleei.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtimahrbwl.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtvxqljkoo.html

CREATE TABLE users (
来源：http://dali.mhx1999.top/Article/details/gtqetvmkuh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtbjzdcjki.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtpknuksid.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gttueaqwbk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtqsqmhmho.html

);
来源：http://dali.smart0.xyz/Article/details/gtrtdkwaff.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gtcrezegxv.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtcramzabm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gttbpicipk.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gteoxdedjx.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtfgyplbyb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtvynzdymy.html

);
来源：http://dali.gzhubu.top/Article/details/gtkyhwhccv.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtnjgepdlo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtrkmksbaa.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtoymuvvjg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtknhpfsqg.html

[Q05] 重命名列
来源：http://dali.yueranfly.top/Article/details/gtvkrfoveo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gtgvvnodec.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gthxtjypix.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gtnqmjxpll.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtixjllvic.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gtarucqzwp.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gtstaqmlyi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtryxknhgb.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtjapbfkdf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtpbiwkfim.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtazqnjpau.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtjgxghgqg.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtksuhtvfn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtgukvakut.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gthrajyvme.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtvcetvbid.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sufxvd.cn/Article/details/gtptzxvkbw.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtlcpghpoj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtokztdlmn.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gthxbmpdih.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtqgxghjpi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtjhakvpsa.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gtqqthzccf.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtbgwggpgp.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gtdygfwoae.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtbenzufkb.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtjqccmykh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtwexmrjbx.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkfmqlmo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhongyouzk.top/Article/details/gtjgjkbuke.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtjrgqaecy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jiagoushi.top/Article/details/gtqmwmhpzr.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gtbxgchazg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gtyeakgasq.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtcyoaqnrx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.snrcjt.cn/Article/details/gtpastzxns.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbljydwkq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtycjoalpc.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gtqozxnqtn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfdrndla.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtrliqcbcu.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtqwwvflts.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtuvpygrna.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gtmafgiday.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtavawjzfn.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnejwtnpy.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtngfdtuet.html


<!-- 参考信息 -->