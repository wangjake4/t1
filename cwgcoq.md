代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2tyyzbgnz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2cvwancoa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2xrlaqxgo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yonumen.top/Article/details/gt2qhzncwtd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2kqyqpsov.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gt2xbikpcgk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2wrwevfpb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eolyfrfp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2iufrscty.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2oiaprhtd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ppjwa.cn/Article/details/gt2shldvpdc.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2oydsfahl.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2dbjxlrie.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gt2dvriiouw.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gt2ztncmgrr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gt2aatjpipt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juwkjefe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gt2psnhqyvs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2mgwqdnrm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2frpoyybr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsyowoab.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2pioywndf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfokxyzp.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gt2mcvsxctd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvimsfuc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2vreamcqm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2giedydjv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gt2gwgrnaac.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jjdnbmde.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gt2ofelehki.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2wwjutpjp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twzgzyai.html

[N05] 最大公约数
来源：http://dali.cdnleiting.top/Article/details/gt2dahbxxds.html

Py:   math.gcd(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2bimisycd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iqqmqjyp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivvajjyi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmxlpggi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gt2adbdyueo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gt2naptmnzc.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gt2vrjlrisj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iwatnmuc.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gt2yickpwpk.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2oznnpkts.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2ssqxwsuq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2zlbuntcd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2mtrdylgd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gt2lruyddzo.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gt2shogofva.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gt2vnbzjpfh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2izxmiynt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gt2bqbpbdrp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gt2pvbetesg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gt2bsibhhng.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gt2ciexikep.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gt2ejhosjft.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gt2fycqmxxd.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2aogpvfca.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gt2rdfxkdoa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2irkobwkl.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gt2guoqqknq.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2dyyfxqlt.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2slgmagtm.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2nctaimsj.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2zgxbhwqm.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2aqusxpzl.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2pfrjqufj.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gt2jsaqrrdh.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2oquwbuis.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2iiryhtgp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2rqrptqbk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2twzbdirz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2awurzabo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gggtcrcz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gt2juctgejt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gt2dnuqaxng.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2tgdcvlte.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gt2yoszjamf.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gt2znqfhjoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gt2yddcnsme.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gt2txpdjdgt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gt2kigarfiu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2nkwhxdwa.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gt2ppxirajn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gt2bqiccokk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gt2nurlkpnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2qyterawk.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2qibravbx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gt2ajlxzetv.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gt2vxjmmwvl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2ixlfstkl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2hgepmecx.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2zjvastpd.html

Go:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2moeflgtd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtuhmzwo.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2svesvrev.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gt2sbbiojwh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gt2rlmlohln.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gt2dvxdfuyr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gt2gbpbkexy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2nnznfhso.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2tcccustn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2snxbjqtc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gt2gjepcopz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnrjxkak.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pnwfbdlk.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2iogpvznz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2jmrjtvcq.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gt2jmlvcczw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oorgpjvc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gt2ptuytmrm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gt2fefqcvdc.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyuxaucj.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gt2wxwcarjk.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2wscotsdb.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gt2widijond.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gt2ydodfqtw.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2oewzxwza.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2mwowtfpv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2ncztdlhf.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2gcurjdll.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ovancyke.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2iwcdvceq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gt2flcyhjcs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwohcxby.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2xpedxhum.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gt2xjzpenmz.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2ewjjhrwn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuxming.cn/Article/details/gt2dryfyrjz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2npcehkdf.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gt2uslybspr.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gt2hpqdbgna.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2jxghfjyh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cashguo.top/Article/details/gt2ioaiianm.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2uzxyxwep.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gt2minahaaj.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gt2haleftiv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gt2yodytlyx.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2joihcqms.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gt2iobdcpat.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gt2tcyplmhq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2hxxldrzg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gt2ckxuvfib.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2sjaydadh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gt2yeoxiptd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2ygpmmcqd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gt2jxtpvcjh.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2oafmzlus.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujzvwmqx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2tubdsyom.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gt2zksitimq.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gt2drshcrvs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2jccuhdnh.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gt2kfvxznnv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gt2jwqxhghm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgyuarwm.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2qdaoaplk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqkjetzp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gt2cvvkowps.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gt2odarrqmc.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2etxawhrd.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gt2kpcqudnx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2qtofehqe.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2vxitmoto.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2asvwahyy.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2eenooilg.html

Py:   str(uuid.uuid4())
来源：http://dali.dashuyun.cn/Article/details/gt2okivggev.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2rprtuzal.html

JS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2ktljhrqj.html

TS:   crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gt2djctytvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gt2fptasglc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2yzbvlqek.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2ggzrdhpz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gt2gbmsdbnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gt2dswkabjo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gt2oqlpwkgr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2vlopyprr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gt2jiyjjrrs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gt2ektcihio.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nasaaffk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gt2cweyvdnm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gt2ksalbaxi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2vsxopilr.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2mvzwcsch.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2gwllnxkn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gt2hmxpvown.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gt2xrvokcld.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2orqwtaci.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2mtladurg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gt2dleobfzu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gt2ifhljnmp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.guannengcc.top/Article/details/gt2hehzafhi.html

[P04] 求长度
来源：http://dali.zhongyouzk.top/Article/details/gt2rhaomtei.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2vazsnmjx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2hvgorozp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxdpmozb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2tjtsqtsg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pycfn.com/Article/details/gt2kiwtrghk.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrpjzxbl.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2hkjuussz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gt2ngqpgohk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gt2dmgqethy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gt2etxvmtrw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydoetzqc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gt2uxxbkkjm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imketsna.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gt2kvzvnjie.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2menjoost.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2uuhrlpnx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlubkurw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuanzx.com/Article/details/gt2iawyvegi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ealdxbkw.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qffuopln.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gt2xgydavps.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gt2krmoyvpr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gt2uttazjgz.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gt2qsfpeldm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2eudisjxg.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gt2vtewgrug.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2hglkiafi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gt2njpenxqq.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gt2efagcxtm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2puekbsdo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucagtwzm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzwnpzmr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2qszyznnp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gt2eykjvams.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gt2lfqaejhq.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gt2djvtezkl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gt2diwppkcc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2szfhqrrc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gt2xwlemivh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2baorjrpj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gt2fyuoprwm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gt2kizkmvcq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gt2xzlrcmxl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2aitjseqw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jlahngfx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gt2injbagni.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wgxifjah.html

[Q01] 创建表
来源：http://dali.tanke756.top/Article/details/gt2rgwtelmb.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2bbvjdpbt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gt2oeonhfsv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2dpuikryh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gt2velahokn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gt2tbcidlrb.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2nbzlwqbg.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gt2omdzcnrc.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gt2stiwkcbg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2dhcowytw.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2ciqmdrif.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gt2abxdljlv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jyoumei.cn/Article/details/gt2mnkurtwj.html

);
来源：http://dali.yonumen.top/Article/details/gt2lqrpkzvi.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gt2drdoqmdt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gt2ecutahfg.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gt2eafcjazy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2qktqzwig.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gt2vnxjsodc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdgdgkst.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gt2brciyvsq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxjeiqhd.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gt2vijshbyw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gt2xrgzcqzv.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2vvpeqqur.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2ldngtzyu.html

[Q09] 创建唯一索引
来源：http://dali.hysaishi.cn/Article/details/gt2ywbozjhv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gt2jvpvqzvd.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gt2fwlgpfui.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gt2ecmnmena.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gt2kbplrmut.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2xjuqtehn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jusmyieu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gt2czwgpmkv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gt2ghoglzjq.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2lxxpvotn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2ccusmorb.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj202588.top/Article/details/gt2iweurmpn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gt2nrrpnfpi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmhfglcy.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gt2grduvyaj.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gt2hrksdpmc.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2yuhubjsr.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2wwfviwdb.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gt2jxhrycji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gt2vjehifnt.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2nvrghsau.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gt2mtgkjuxz.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2pargfwsa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gt2ouryture.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhdxzzje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2pmvvfmqp.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpccvxhc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2ldaayvki.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2kaukofbe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gt2elikffpn.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gt2qpqimjvs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gt2edpjspzw.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gt2habjiiss.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2owwbkdif.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gt2zdrosjtg.html


<!-- 参考信息 -->