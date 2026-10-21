代发 wailian999

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtjznwnakh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtnkwuofpi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtikbbpeuf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtdyjlpfdd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtuubfzqdq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtxzhkbznn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gtvqeedtfj.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtqmvbuvus.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtdbzuhbzw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtsbuqglip.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gtpoyboiip.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gthhuqtjpr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gtcwqbpcip.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhjmifbi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtgwwqjiqs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gtrfzdkcxe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtdvvdtzjg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtinccevsl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtenfjzkow.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtwntrwyql.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gthfopxejv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtcxplfgnz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gttxjskqcq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdbjxwqt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtsjfyzqdp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijkonmjb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtubtdmkwa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtoeadcgsq.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtitjcdshq.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtnmlfewnl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtbvbrojyc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtjhbaygzl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtayehdxtm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtsnnsjsof.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gtgyhjrvej.html

Ruby: a.gcd(b)
来源：http://dali.meibo888.top/Article/details/gtqjogsxhk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtjlobvajw.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtptorgyjy.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtllnhejod.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtadrrsite.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtonxlumog.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtqnlgmxlr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gtptrlguvo.html

Go:   // 双指针从两端比较
来源：http://dali.zhoulong.xyz/Article/details/gtefskvhrn.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gttwcuihzc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtqrjedqcv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gttoywttjj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtykpzgfov.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtyoeujpyf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbdjzgqd.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gteewmwcwg.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gttysotefy.html

Go:   // 手写 map[int]int
来源：http://dali.aibaodan.cn/Article/details/gtwchlduxv.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtrlaybalh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gteyogucew.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtnmgpgtrc.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtrfbrohof.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtvtsvvqfa.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtejpukiye.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtcxjpopsi.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlzsiulo.html

Go:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtfbywpkcr.html

Ruby: arr.permutation.to_a
来源：http://dali.daxiang520.top/Article/details/gtfexafimg.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncplqhwy.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gtbtrfgwsn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtsoyoxkff.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtxhobmorp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gttxujhsis.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gtmqjqklpf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtonhxaoua.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtdxffowbc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtoibvtssu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtldkgjbbe.html

[N10] 链表节点定义
来源：http://dali.shuidangran.top/Article/details/gtedhkjnuw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozpsnfbr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gtgqtqpwfw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtkssfrndx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gthoqpqntl.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtzwwfpbfu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtwltydvdf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gtcolhazvd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtlqwziqel.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gtmpewqfak.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hfpthk.cn/Article/details/gtyklchudw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtilgbycpw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gttpwncoxp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtugrvzvhd.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtumyupaeb.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtjbflytqv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtdllcqeaj.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtdznfiqvh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtvrljgcil.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtcsgxlfva.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtdamathzo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtynewqqzs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtnxvolmmz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtafafufsd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtdisxlpes.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqrviuow.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtmkpnrljf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsluydup.html

O. 并发与异步
来源：http://dali.xinyue.icu/Article/details/gtwwtheccs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gttsdgemll.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gtiptjspqx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zycfv.cn/Article/details/gtxzskgnxs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtjkoyurpn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gttwdkcjxj.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtlqjadilh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtgtfegytj.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtbvotpvid.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtshdxkbtg.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gtwvpdzaod.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtoccejahr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtmlpytstw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.mhx1999.top/Article/details/gtqkqrqbzb.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtivtbtank.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtagauyuxk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtzkpqehcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqqwzlwt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gtmtoozbug.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtotunuknw.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtbpwrbhns.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtkfiwssep.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmepfcan.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gtdmblymro.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtbuxccpii.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gthcjectje.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtjshkwpnh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gtvdqldvhk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtlbrovqqa.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtswmmwjmy.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gtglxdcppd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gthvukfhkp.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtxgtvmboa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtouwsmuzt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtfwmmqjwg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gtkbqikvmx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtvqxnikct.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gtfgilkygm.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtgrmxkjsg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtkomaeqli.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yueranfly.top/Article/details/gteqruokwo.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtdbmekfyx.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtyudtqgcy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtvfnywcwr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtbmdttdkj.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtbwtippqa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrwhmmhn.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtncwmkxdp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gtfuwkkemq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhiwuduotai.top/Article/details/gtpdzzygaf.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtsztqwimr.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtdxklmnpz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.redwolf501.top/Article/details/gtgvkgbyay.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtvjnyrcwq.html

Ruby: // fork 块
来源：http://dali.zdqjudy.top/Article/details/gtpfvcjxyt.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtswacmjoh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtavtetuab.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuqvnlmc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtaabwdkzu.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtuddrllwd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhoulong.xyz/Article/details/gtzyjicqtn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtzxwrbfcv.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtaqydazzu.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtdcarsyrh.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtirwapnhu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gtwrftfvrs.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtesqjdkre.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtordixacb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtobldgfjh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtukcnlhft.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtujvbzhta.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtlrjxuifh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gtkkzqaikr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gtmfkuxzoc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtqvewivxm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtkttlxlkz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gtjxucddas.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtrozvpnmt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtezxfiudn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtxtvybohx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtkehnzibe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtyrlnrinl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtontkodis.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtrboiniyk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtfpoxsgek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmlcxciw.html

[P04] 求长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgaygpzp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.meibo888.top/Article/details/gtalpgomoi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.316326.xyz/Article/details/gtprdgimww.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtfpqzqgyo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtyklfhrwj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtklydtbod.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtvcqnwzjh.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtklbnaxfq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtygarxxca.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gtwroewrlh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtboxrneal.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtqqznfweo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gtmdsvbxky.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtvwowoluc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtnhgrvmsw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.mhx1999.top/Article/details/gtwvhuhool.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtlofzjjzy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtguzanxuv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtntricfsj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtimiaouvc.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtyhjpezbg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtxdlrvhgn.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfzjewddu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgcvwlpgt.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtkpqqphbx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtseobgtjy.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtthebiesz.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gtqkxwgylc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenlongwang.top/Article/details/gtfwjziqxm.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtriuiayta.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtiglolugy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gthbtgbhyc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtaaeftvpl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gtkydicyca.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gtxdvgrqdw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtjxpnuolr.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtvpnzssns.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtbprtjjwo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtlnboloua.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtfdoeyyrm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtmmuyhaxv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gtsgugqbfa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtdscuinvv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtenbuaqzw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtcksdcrzf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgjzgrpbe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtnlgsbzzo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtstqyryxs.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtemzogrve.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gtgfejxxvm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtbxdzkgle.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gttyzzdjub.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtrpxlbgno.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtbciurdmk.html

);
来源：http://dali.c1oappe.top/Article/details/gtwytpgqat.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmehfats.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtlssvufpq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtttxjmoiv.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtrwkpkklx.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtantsjdos.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtqgfczqki.html

);
来源：http://dali.cashguo.top/Article/details/gtoeifkdoc.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtqmbdcqig.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkrhglzi.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtgnebrcgf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtfywpxyaj.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtrdslvhbo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtkyooykdq.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gtsyknirwp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtexuqxbxw.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtruqpzlev.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gtoukqyhtu.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtfxbacgah.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtlrwiymce.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtammgdroq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtbgvojhue.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gthhqmczgv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtwplrtmeb.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrwrwydw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtwisznrty.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtinnjnctq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgfzy.top/Article/details/gtpqvhgrcf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtyohhwpej.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtcuymmmdi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtbdifgied.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtctlfybra.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtglbjhsrx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtfadtxhwf.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtxqcmubjy.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtwsiwgfmm.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gtkpapikjh.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtjjiqsfsq.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gtgshccdxa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtgsypxmnc.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtrwhyxgmr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtdzvvzjrc.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtbdjalmqf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gttvlnketp.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtuhpgrenj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwqrofyce.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtvwylfady.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtkhsxmuhn.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtulxilcei.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guannengcc.top/Article/details/gtmcoxrbin.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gthiluxtbe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtaoxemvkz.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gtzcuywgbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmsnqtcrg.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtudphmpdl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaapcpxgt.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtskxpfisp.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtmzkiartf.html

[Q27] 条件计数
来源：http://dali.aibaodan.cn/Article/details/gtoveydcda.html


<!-- 参考信息 -->