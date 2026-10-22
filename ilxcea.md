代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2tsvciqac.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2lvgrxmut.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2lukvofbn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2tbnfaatl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2tgqfhmka.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2yjaaxfqb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2oppsooog.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2pufgcica.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2uwjypsvn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xldunmlh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gt2bwbyygux.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gt2xuiggyat.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2lmjtsjgy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjzwyqrq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gt2dpdnezjo.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2cnowkfuq.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2xbspdhic.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gt2iyxjgwta.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2mmrdzpry.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2qvkergaf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gt2nkjfwotw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2yamkdhtm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2ewnlwlhc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2gszuipli.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkezygud.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2lbpwpfal.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2vapxzlor.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssvwawwf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2knluchzd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2butdzesa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2vbfxcmmz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2nbdpflgw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bxseyqoj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gt2kjlqamqq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wjlnejdf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2tzjauzti.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gt2iremqpsd.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2vllkpchx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2imjmylcl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cdjhfhxp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2soemtbmi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2iaidoeby.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gt2lhgmolea.html

Ruby: a.gcd(b)
来源：http://dali.tianlin.xyz/Article/details/gt2ifcqiksh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gt2pypqdepe.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2txleojqg.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2knbngefc.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2ldfswtfd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2omlibngt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzxmssao.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2zmkxfvfk.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnpmqxdg.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gt2vkxrepcv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gt2kfwlvwso.html

[N07] 两数之和（返回下标）
来源：http://dali.tianlin.xyz/Article/details/gt2knhskjnj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gt2hplkpoyd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gt2qodefgxa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2bshuzrcc.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhongyouzk.top/Article/details/gt2aawoykqx.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2dzarxmjj.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2viahdaoo.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gt2dzetoryi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gt2ztudrjys.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2ikxcksvf.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2uzlilerh.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2vxxdzcyk.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2zxdcsjbj.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2loeaqdpk.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2hrdweaam.html

Go:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2ybfvwysz.html

Ruby: arr.permutation.to_a
来源：http://dali.ehwqpu.com/Article/details/gt2zvpvgjjt.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2bqsvalvh.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gt2hmbuyajs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2ldpttdgm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2iykgvjom.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2acnfrvfh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umdyavzb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2gcxledib.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gt2ielifosd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gt2gcusksnf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2kxidznut.html

[N10] 链表节点定义
来源：http://dali.bjfxy.top/Article/details/gt2rynxarjg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gt2cdjgqjgw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gt2oxqozhue.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gt2sffbeyjm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2jyoipkck.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gt2jveobsnm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wplaoopr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gt2chzhyjou.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhoauile.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2gfkjynox.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gt2hewemvzn.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gt2zlvhfnwq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eemxtgew.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbxvsrvu.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2yuydxrmy.html

Go:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2lcjulyec.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gt2fyjeavqn.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2bfrszari.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfylvnwo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gt2tkogjgmy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2gqhzpzma.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2zzmjyfgs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2iwrxhhqa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2hyaqmatx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gt2rcvlsure.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gt2dcqgvdgs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2zwoukbxy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vfzcwjis.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gt2fgfhqtwf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2jfdkijsl.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gt2xybqgqtc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yonumen.top/Article/details/gt2mkyfzfra.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gt2eixapnad.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhiwuduotai.top/Article/details/gt2ursqtgvo.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2dkdlueoy.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2osmvqjbl.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gt2falonvoz.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gt2cbidhdbx.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gt2dtpswkmz.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2zajsvups.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2nkayavmp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pycfn.com/Article/details/gt2gztelrut.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2dwhvvobu.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2fwphkung.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gt2thgylami.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gt2uhftprmx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gt2czbjxano.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gt2orzhlbnu.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2orrdcjso.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2uyzpcrqz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2jafyygoj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gt2jigqbavj.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2shzbprxp.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2emmsgslf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2qnnqfxkv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2kkomthpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2tevrrvog.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gt2dpufnvbg.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2demtcnky.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gt2kjabdwrf.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2brprgpig.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2kkgksvnr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2npkhpnqe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2boeyybgy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gt2shoutboi.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gt2zvkzvsfx.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gt2jrbwsyqw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2grihytnv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gt2oyfuqlov.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2tathbtwl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aetkyojw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.quarkkingdee.top/Article/details/gt2zxduhbxi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2rtzvrnyp.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeajburt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnzhlsl.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gt2bkzxrncf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gt2tgwamots.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfrvuufq.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2ikycipcu.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2trokxvyp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmbrvvsx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xinyue.icu/Article/details/gt2zxinznoq.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gt2ghnqlnxt.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gt2sobztfly.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2erszbzko.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulobimaj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2cldafowt.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gt2czehwqqp.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gt2evrfghir.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuxming.cn/Article/details/gt2raspvmbs.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2lffyolzj.html

TS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viuhnvdh.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2gkipxfbu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvbgsjpn.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2veezfkap.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gt2ujihstta.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gt2aggejwyo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gt2ioiacvfr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2phwwdymo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2bnxgxiyz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gt2odvjchaz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2rszjwrwq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tian-w.cn/Article/details/gt2czjwltqp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ufdqtixz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gt2rqangzvx.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gt2jmsnnxwa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gt2kwxbniwz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gt2dwynzpeo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbuvcnhv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gt2rkwttsqi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gt2zydntjlq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2srmhctxt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gt2zmvahmom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwqsjpqk.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gt2dtkzuzwj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gt2bnvhpwdx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2ayftvrfr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2czoiurbb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2qecnnqxo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2bwunlrto.html

Go:   len(arr);  len(m)
来源：http://dali.gaohongyu789.top/Article/details/gt2addgnvjz.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gt2zzzspwdp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2thacxzfe.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gotoacloud.top/Article/details/gt2spaielob.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gt2oiqikujn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gt2gsfifckh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gt2oglzcnwt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urqxhvmy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2gunuodda.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2ibgxxoly.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gt2bhwufysu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzrjgunw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gt2sagflsxw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gt2ulzqyfxk.html

PHP:  if (empty($x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkfkysrc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gt2nsjqtjdq.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2eggvpzeh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.snrcjt.cn/Article/details/gt2giqvjilf.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2zkkjuobm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2onlhiapc.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jkgtqhdz.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2hbipzhua.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gt2rqrkfdiw.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gt2zgicohxc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2ztkbgudq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2ruppyrqe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djumvflv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gt2ycrqislf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2trggcslx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2trcgbaje.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gt2ngneopdp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gt2vfhjjieg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2whaudufz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gt2ymcjywaw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gt2jqqgxczi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2fllnwbdc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2qitmpvdv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yueranfly.top/Article/details/gt2qbgimpsx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gt2otwwvmgb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2sjmvawyc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gt2whfgdnvc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2mjfmkhog.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwkroizg.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gt2wnmcsdop.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2natokchb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gt2ayycsaac.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfssfyoe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymmfbitd.html

);
来源：http://dali.tianlin.xyz/Article/details/gt2czypibtq.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gt2nskrodqh.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gt2goiioptk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gt2lgwuwpys.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gt2hjeldrpa.html

amount DECIMAL(10, 2),
来源：http://dali.shuidangran.top/Article/details/gt2hcoddrkq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2sckqediv.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2kzpypyro.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gt2jxtkxxdz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gt2hyyittru.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gt2dxuehzjf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gt2xctbikmw.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2larvbvwr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gt2qpxtcxim.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gt2pebhdnyl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gt2tuqhuxpg.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svjiavjk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2efhocyok.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2shovxsuc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2gxhdczcy.html

[Q09] 创建唯一索引
来源：http://dali.mhx1999.top/Article/details/gt2lhjcknux.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2cdhinbwx.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2gtteeutt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2orknhcya.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gt2rwtosvgr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2riywjyta.html

[Q12] 插入后取自增 ID
来源：http://dali.hfpthk.cn/Article/details/gt2cszcndbp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gt2rarhsnlk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2mhuserpq.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gt2mnvjivac.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2rmahdlgg.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gt2rwgftmvy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gt2zvidifux.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2bikhmnhx.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gt2jzwyymjw.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gt2xrarcmqf.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gt2fwmmjdtr.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nygzbqgr.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gt2qyawegcx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2iksrxpan.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2pdwuzuaq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gt2zdauvlce.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gt2eluronmn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gt2srtceadx.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gt2jwwdvhkw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gt2lxpewgqp.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gt2vzqutqod.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2imykbiff.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gt2yificltw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gt2enzwprlm.html

[Q23] 分页
来源：http://dali.chenlongwang.top/Article/details/gt2thqfrtxk.html


<!-- 参考信息 -->