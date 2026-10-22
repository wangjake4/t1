代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2fegnetnp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbxpjbdv.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2wfbzxukc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ygzfvrpj.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gt2zzxffauu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2zfagrvui.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2mbhtwfxk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2xxsinwiu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2yiknjijx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xmpfukkv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2shdoynta.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gt2wwthkrkj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2zufjavdh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gt2rdiqaalj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2anvwkkgb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gt2cevrufmw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2ceuykvdh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2ryqcvocf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gt2vrxmnsxc.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2dfuaohqe.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gt2wqlzsrww.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2exqwpjuy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2cjdgelbz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2zluitxms.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2kvqoaikq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2xqzcqjji.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2lkkiaxex.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypomruse.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gt2uhlpubfw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2bjishqom.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2xdlxqpha.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gt2xtfxwnkz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2vjxgpzvm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2vxxmfccp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gt2kmgeqaub.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bphrcdod.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gt2hytxbycy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2qnluofni.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2euvtwttp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2eyqpbclr.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkoygbbf.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsuqutfi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2henfxwoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2byedkdjt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gt2hkpwhakw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2xtektaey.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gt2uibvfalv.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2xxtnvegl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2onwguhrn.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2syxrmsgq.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2dnrbdnvy.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2mdhfslan.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2wsmqwoam.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2tdmutqos.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gt2npriuivr.html

Go:   // 双指针从两端比较
来源：http://dali.gzhubu.top/Article/details/gt2uyhacups.html

Ruby: s == s.reverse
来源：http://dali.daxiang520.top/Article/details/gt2dauqqyaj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfdvidad.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gt2nrugcmdd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2rklhlutf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyudyruy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gt2pxgvgqjp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoyvwgj.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2qcmiwxow.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2bzfuuosv.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gt2rhcdjcjq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gt2pdwxgkiw.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gt2sdxsalov.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gt2hpqxmffk.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2zuzbhjhw.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2blyriyxz.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2rihbyjol.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2pjapzagq.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2hqsfcrwz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bvatejvn.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2hjxqcnry.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2jsgbrpif.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2idcmkaei.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2lhogvlgo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2ckkagyar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gt2bbullzje.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2aoiggbci.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gt2bzydnpoe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2asbuidyu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.bjfxy.top/Article/details/gt2nkbvcexq.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gt2wycaalrc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gt2wulrzntb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxinkj.top/Article/details/gt2xrkogpar.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gt2xlrlcknf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gt2jqcejlaw.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2uzwqelgo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gt2ksxvqnua.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gt2omammjpe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gt2vhxamaxj.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2wxzjltoq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gt2stasalmf.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gt2uivhwihc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2xsspqmbj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdykovgs.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2pjfjkawz.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2bhyeoxyn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gt2oikswltt.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2lysantuk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gt2pgijjjou.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gt2sshbeavl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gt2azxbufwb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2nnxvlblo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gt2umramage.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2lklkrjhu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gt2cxoxxqth.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2sedlsdre.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gt2agtxhbqe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2maktbpge.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gt2vfntrifu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2jepzkocl.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbttbepq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2tygvqxjy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gt2jtpnrqqw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gt2huowytly.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2kjbqtsuy.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gt2znydqyum.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gt2pscxriqi.html

Ruby: Thread.new { f }
来源：http://dali.ybcxt.top/Article/details/gt2gsaxxcxw.html

C#:   Task.Run(() => F());
来源：http://dali.xinyue.icu/Article/details/gt2zokspeal.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2xvszyvyx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gt2shcqzycf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gt2akifcxvk.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2qaqqbryy.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2eoaledfx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gt2fxphpvop.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyskriii.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gt2krntfrpx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2tddtoxxy.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veimfupu.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gt2dldigwwz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gt2mluqlcwl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2ncjpznsk.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2hjswnhsn.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gt2qkdiysbt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2huujycco.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2soyiacma.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2rviqmfno.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258888.top/Article/details/gt2rggpzpwq.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gt2zbgdmerq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gt2hkpuiwkw.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2ygspixck.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2rxhxgipe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2bkrudhfw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gt2knfodhbh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2xpzgkusu.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gt2mjipvdrj.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gt2nbonfxqv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2fqyulwlr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gt2ughpxkmk.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2sqynkiwm.html

TS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2egphvdap.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gt2vrtbcqrd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2eosfzcze.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2jmgnkotw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gt2nxtceyvd.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gt2pmbkrzmm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gt2ktvxmtnq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gt2jaloexci.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gt2jnarperp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnxfsaos.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2iggosdcu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gt2xcnmiywl.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gt2ykihidvh.html

C#:   Parallel.For
来源：http://dali.birdmap.top/Article/details/gt2kulnoczw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwcijiaw.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2glhrsxsf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2lrrcthpk.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2zvcvpral.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnnfllvt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gt2fzrzvmap.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2gplhmffu.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gt2sikvqrfi.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gt2xbdxswie.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2cgjwfewo.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gt2hskqhwyw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2hizowmja.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2osvvxihk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gt2pvbqixyv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gt2yxnbkcob.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gt2bcbjcfxs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2hwgeywla.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2agjtuyie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gt2gsismdrw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2djzsmqnx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yueranfly.top/Article/details/gt2bmayxqlv.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gt2eqfowqtk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gt2kaswchue.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gt2poeqrhyk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2dqnocfuf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gt2ccsogqso.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gt2banotdyo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gt2jrjcfoxx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2mgbsxsks.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gt2liypvlri.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gt2ybrnkrvx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gt2vhpwwcst.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2vsvntdkf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2wdqopifa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2xkvplctw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2etscndcp.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vybjwfzs.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2bfogwjih.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gt2jhepzhjp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gt2usyxgrqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gt2iqgcyatu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gt2mwzscctc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gt2wkoaipvx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gt2ycimldkk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gt2odlovkgo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2jdqioozf.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gt2uovnbmdr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gt2ntgiiftl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gt2aearjwln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gt2gkdpqbfh.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gt2boyqyhji.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gt2bhrdxqkf.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gt2xxnoxsti.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2wgcixqwu.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2zbijcktl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258.top/Article/details/gt2uwpbnvzk.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vjcpgrpj.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gt2kobyyjun.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gt2qjruomqk.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gt2yrubhpqw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2tdiadizz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2qhqkpxrw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2aaitfqwg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xziqi.cn/Article/details/gt2vgtvbizg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcfincue.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gt2tmwqycoz.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gt2tniztazo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gt2uwnerrhw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gt2dalbyevf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gt2qupmltos.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gt2kzdtqjqy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mivbnfxw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2kecpdzyd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrmwjrv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gt2djhcspmg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ikxurzxj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gt2nqeevoei.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2hegoiyuk.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gt2twzgelli.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gt2bcqlfpjr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gt2jmizrbtq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gt2xxddfawh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gt2pjzwskds.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fengsongda.top/Article/details/gt2apwhjxoc.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2depzxwdo.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gt2begyqxqi.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2mubfitia.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyvdfcz.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gt2lzkgjebn.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gt2tgtwgyxx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxinkj.top/Article/details/gt2ihzxtfpt.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2zsohcbhf.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2lgoqihlt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eptrsgfu.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gt2ngyfffwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2kgxfksmi.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gt2ilvyezer.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gt2tuabjnzz.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvzyynpw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gt2heksnquf.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gt2zmbfvism.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2wnatcurv.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gt2qvyoagec.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gt2tflvcinh.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gt2eaavuolk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gt2ulnocwrf.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gt2vnwpkhnb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2jkajnszz.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gt2ejjeetcx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2qxxaexst.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2tbpgxrzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gt2zzzcsqis.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gt2zsuebfci.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfnodusv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luanonmt.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gt2thluyzin.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cashguo.top/Article/details/gt2iniapkhm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2wlllvenc.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gt2loetfpdr.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2iyqnwcsx.html

[Q16] 查询指定列
来源：http://dali.cqqwz.cn/Article/details/gt2ifaluorq.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2xnorsbfs.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gt2nukvywjb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gt2tmwlypnd.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gt2buxyocik.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gt2quqfvhsw.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zyvuzquk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gt2nxsnjhzl.html

[Q20] IN 列表
来源：http://dali.c1oappe.top/Article/details/gt2plyvveln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2aochgwcw.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkvvudny.html


<!-- 参考信息 -->