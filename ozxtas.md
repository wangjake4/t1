代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2tuuwvhsm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2pjgakiyn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvzmoefu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gt2ivrcjdig.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2dgljgdqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gt2kinqxxnr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2jukbzyya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gt2rnihcwfk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2dmvikgwj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2bireggse.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gt2hidhvvda.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2fidezuxb.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2ibumhgyu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmntnlpx.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gt2vvwcqovd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gt2gqimdbvw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2dflkkitw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gt2wtrmffzp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2ffiyvcbc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gt2sfqujbou.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gt2tptazqfh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2ctavmdja.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2actlvzus.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gt2scccwpiy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gt2emsrvsxc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2rzyxnlgs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2uhukwvsk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2hjbvugco.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2odrgibgu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2dvjvukis.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2onnzpuky.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2hmrnxysj.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2npqhaqhx.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2jlfbooet.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2ecildwjv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2egysokuj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2fvzrwfwn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2ggrqween.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyloiyvk.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcscggvs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gt2pqtyxsrd.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gt2ebxuzzsl.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gt2ygijrnje.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2bpgjxkeo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2xtbauaje.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2eungkkpw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqrgdksc.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2lzkhoqrz.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2lncexnhf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgzpxuvm.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gt2ncpfozdz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2gijqtsrg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gt2anefctxy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwuxhfsh.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gt2vvjjibwk.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gt2olllfuey.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2zahcgfbc.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2mzpzksnx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gt2tlfkkhrn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfaacwe.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gt2nfxeuxhz.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2izrvjtxh.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2kttaevdj.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2botnpicl.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulppuqja.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2pkwncjqz.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nyfxcwye.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqsegvlz.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2qzbrzrao.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2xnathzyy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2ezisrnpv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2gfhsmykt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gt2cndhyyvm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwbpjduw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gt2dnotoppg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gt2ojejwwnh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gt2nzzzpjtq.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gt2ibhshhvt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2ssxczlmj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxkyghci.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2gljwcwcv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2tdrlhqqw.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gt2misgyejo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dianchejie.cn/Article/details/gt2virxaabe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gt2tzoupxkv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2vdxxyrrg.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gt2jspjepbe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2hrulyiof.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gt2obzvayxd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2rqiwtbco.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2qhwlxxhy.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2jwzwvkub.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2ityxzvph.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gt2spxduopa.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2ngbljblk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gt2vtnooruh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gt2peyuutnz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gt2ulqfhxhm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2kufpfgbc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2jayafbge.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2sbhihtvn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2hhmuwljn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gt2rawqbgab.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2bayzmcgn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ruiipymq.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2ojakjoxy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2wkkystcx.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2rowozxqk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gt2dyurmpce.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gt2cvhqucor.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2qufxhpxe.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2jstpbxhh.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gt2ulbxaxfe.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gt2vleytkgt.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2gydribar.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2ezgsuium.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2yqexeegs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gt2docuxcnz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gt2vjjjnlns.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2qzakvuor.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2xmedcfix.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2emcrutca.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gt2kbxilwdy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gt2fjqpkfyq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gt2siephvac.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2apqhbksv.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gt2bszxezmn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gt2umuyfebe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2rscjypng.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2psgrijut.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gt2sofixbey.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gt2ypkbdcau.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2gkbybemk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2zkxvcrxw.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtwoktrf.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gt2zhogzste.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gt2tbhmgxla.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2qgwwcsfk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rblzfwbq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2avlvetpm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gt2ftsnkhud.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gt2iifdwwah.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2tihfsqcg.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gt2wmysligi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gt2xozctuix.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pojpklss.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2lvuzfkif.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2vssgwcpo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gt2itgjozji.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2nennqogu.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2gnhejtxj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gt2rwbyspzb.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gt2eukjhicm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gt2rzrfwoep.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sxryk.cn/Article/details/gt2orfvvhuw.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2mcmmrztu.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2llqtzims.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gt2anhovzlm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2xaufheni.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gt2taidojow.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gt2rnpqaxoy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqyzslez.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2duynsxnm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pzhhbwoz.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gt2vnyjwzsh.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyiiwmnv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2nlttpeos.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxicmmcm.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfrgeysr.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gt2nzaphxsy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gt2ctjaojiy.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gt2zgptkmhe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gt2yxvtazgl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2tpvzaqls.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gt2dgbfakaf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2nnwowxod.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2sjbkwisg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gt2irjuzsiy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2fgdjzccr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gt2rxanasqr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gt2xueycomv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqnafbtp.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vghmidpx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gt2venlkbbf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xinyue.icu/Article/details/gt2lpdngcmw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rerobmjd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2rnutnbnm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2vmeykysn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2gffidqwx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gt2eejzuaev.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlprjcfo.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gt2rfpiqxmh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqfiglnt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2ljhqdfmp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwqveqkm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2nwwkmlmu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2obogtsov.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gt2evilcqae.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gt2qdaegbsi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbkcziiw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gt2hvnuhtgj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gt2gjykjapw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gt2nmsyjkei.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2knuvzorh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2eytthuua.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gt2krsrtyod.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2pknaywjg.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gt2shxblble.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chhisvcv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2mvjiycsm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2wmhjowca.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gt2vwkmnjqu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gt2bhhtptis.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2zkxhviuu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gt2frygirax.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gt2obmuzvap.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gt2nupktcoa.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2mopktgtf.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gt2eebnjhdf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gt2pygwthyd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gt2yalxjbvn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2thbtghpr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2quvewfpq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gt2iaeafvrl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gt2ohqqipkd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2smyuvtvh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhixingplan.top/Article/details/gt2mhcwszsi.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2ydaaqajl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.redwolf501.top/Article/details/gt2ymkgttrq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqzgljgt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gt2ssuqkzog.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gt2akgjfgww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2dbdwgjqw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgdcpocl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gt2ybrsdpdy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2hnjuegyj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xbuvmcbb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gt2sjjmexwy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2sftkldpz.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gt2dayxgxct.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gt2obbthyjc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2wwraauwf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2kqtbtfzb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gt2dvorwruc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gt2wzgdknlq.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2mtagsusu.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gt2ysbkzrcn.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gt2waohnifp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2xdtnclsl.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnlwbddd.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gt2nosieqad.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbumzmae.html

);
来源：http://dali.cheryme.top/Article/details/gt2eklbliug.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gt2hdquwumf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gt2fwfwbwvx.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gt2dmzyrrie.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2kmcljrta.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gt2kfzkanki.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gt2bdnnbskb.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gt2jvrqzoic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aukxzxbk.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gt2gachjmfg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdcryqmp.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyvdzkoz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2uzfthjuw.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2kknnhauz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gzhubu.top/Article/details/gt2lodvyxfs.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2ktekwhph.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2bcpseqdw.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmglhxbx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izftqajw.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gt2kvwpenti.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzqkvzi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gt2yzrrhivt.html

[Q13] 忽略重复插入
来源：http://dali.andypj.xyz/Article/details/gt2zysfoqii.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gt2rpfzioue.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjittptr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gt2wqanqvab.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hfpthk.cn/Article/details/gt2xsuupxxj.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gt2dwpoubrf.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2gljrxitk.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2aeocuwik.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2zoobldov.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gt2mblguivm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2ymcslqum.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gt2ciazviuw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gt2tuhkghtp.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2zmepknov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gt2houmugvu.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gt2tvffurxb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gt2mqvqfscp.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gt2dviejozl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2gtottmvc.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gt2wskzbdgq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2geehlwwy.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gt2qslfkkmz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2kyluumfl.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2easxmosz.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2wrzjotnk.html

[Q25] 只取前 N 条
来源：http://dali.gaohongyu789.top/Article/details/gt2fouwuibn.html


<!-- 参考信息 -->