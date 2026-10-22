代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfmxyus.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irprcecx.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2hriagpis.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ikunwvod.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2sskchymk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2ejvmxxrk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlogdjdm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2dwrjheni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2ilqpehso.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2ruwefjsu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2vuggsbrr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gstpbaac.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2difxthzs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2fbceaxky.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2loaeznkw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gt2kvfrdiqe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2sqvdniot.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2ywmglwfm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2vgyccdir.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2wuelqmcz.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gt2ynkgfcqb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gt2vvqefhxz.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gt2rgyubrob.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2slzmrbgm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2cldssplq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2htpdpfcz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2kesjxrap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2ztjshmeg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdxzxfjh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2dyeydpjg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2uxoxcrre.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gt2kvwqiewq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2nxfbngdj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2evqvjred.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2qzohabtk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2gtxubyyg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2oojpuapo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2ipbrdjgm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrhtdsyz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwayncyd.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwdbauyh.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2fmobwida.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aiicumor.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2hpqczgke.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2inlngaqj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gt2bbdbyzuu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujiirmca.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ycmfnlzg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2winivjtv.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2rsrpvgqm.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2hqnssicq.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gt2ewpngmfg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmflvduw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2wxuycjpx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmjdhwzb.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2nalbfixa.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gt2eftwhjnp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2muxkliot.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2gjmgeiqz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gt2gfhlifst.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.bjfxy.top/Article/details/gt2ldttguvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odkfzkyh.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2zsfunfqj.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gt2lwrkrcqa.html

Go:   // 手写 map[int]int
来源：http://dali.cashguo.top/Article/details/gt2izxksbwo.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gt2bebthlyo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2ukrjwdec.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gt2rmnykhzt.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2dsinuifl.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2prlhxtgb.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2dyblqndv.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2bfnxnfmg.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxmrzvbr.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ipstactb.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gt2hlhaxpam.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2ljdzptvy.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2inwsuiap.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2kndlndiw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2zrwfkvug.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2oisbifkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2jvrrxveu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pusbwxod.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gt2dqdevhek.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2prdwjmkp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gt2sgkvrsdo.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2jwobyokj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2popxeyao.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gt2voizicwb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.haohaochexian.top/Article/details/gt2aewekuvc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gt2pzufyptx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsxwamrx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2txysxago.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gt2xupuobld.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2jproonnf.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2gemfvfqu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gt2odsaaxfm.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gt2udktlevj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2gprzzttp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2qdapbufv.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hbcnnyqj.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2hzrjkqda.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gt2bvikwacg.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2sbrwifob.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wltvkzrq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgojingn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2kuffaeal.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2kttmnqvo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2rtunmcqr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2ttsoqoen.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2hiycblsl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2hujbvmok.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2jzhbnzid.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2sxpwlvya.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gt2vyxqaonk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ccfgesnt.html

[O01] 启动一个线程
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnzbvybo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gt2mawuibru.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afhksltw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gt2fiypotna.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2tvdufnhh.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2qyopgrpo.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqjfgyax.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2smelumod.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gt2scatpdzl.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2brkzxvos.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2uniqtgyy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bluzwwyg.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gt2rnttgmcp.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlfvlzkl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gt2mhhqdqdr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2htevwegj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gt2tfsmpveh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2hggblyxn.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gt2xksfgazq.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gt2stsjxtop.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gt2wpkteway.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gt2elvzuxlt.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2nrzzliug.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2uzrnkghk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2gbwxsvsq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2avclzqmw.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2pjpadpkv.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gt2ptlfrrzr.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gt2ichmleio.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gt2lupjfjyw.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2muvhyyjf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nzupvbfi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dianchejie.cn/Article/details/gt2bweawyws.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjsxanlo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2haxenbxv.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gt2pyjjmrbe.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gt2aryamsbp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2gebuoqpc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gt2rjntnisl.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2pfqvuvfh.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2vkinxgpr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gt2xbkjdokh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gt2qorfbydi.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzckutdw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebuxcshy.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2ovhtrjlj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2crgplnsv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gt2rlakzfeg.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2haumszyv.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2ediobllc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yllehqfc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qoujzgtn.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2oxmlspnh.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gt2fgmuruum.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qkbtpfrb.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gt2wpzogzcn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2moqnsmyq.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gt2dfhoawvu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qadanhgp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gt2tkfmcboj.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gt2vaskvutz.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2oetpaqbd.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzzdsxxz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gt2vfkrpiyj.html

Ruby: SecureRandom.uuid
来源：http://dali.yonumen.top/Article/details/gt2zknvncdc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gt2pgdzjjbp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gt2ltzvmjgg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejuztkex.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gt2swldyfhy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gt2eyliyxnv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnxiangtu.top/Article/details/gt2ddoapxin.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gt2rabhmfjl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzfuycqm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gt2jctfspfp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhongyouzk.top/Article/details/gt2yjjyjyca.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2cabtzfne.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gt2coqutndz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2xepacjyv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2uuzvuotl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2oausliwg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gt2eqepozyy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gt2kdneecfo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gt2quudbbkm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gt2ynnhowml.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2ersrhknu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gt2ivemmpqj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gt2wpqybwdi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2ilxuzaih.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2omumvgzn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2icjdmmlh.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gt2bllsexdl.html

Ruby: x.length;  x.size
来源：http://dali.zdqjudy.top/Article/details/gt2geubovzw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gt2npxxjrnt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gt2ymextive.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2atovpanr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gt2dfmmwjwj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhengqikj.top/Article/details/gt2xegxuzki.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2ympwtutu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gt2jmrhabos.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2ctpbjcai.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gt2bhgijabi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnsswzni.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gt2oyogaekd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2mzrvddyg.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmspcfsq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gt2owhyinpr.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gt2macmpcra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2siwmycqz.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gt2klmkldvl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gt2rjesthsw.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gt2mnnfzbip.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gt2tvoutruf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gt2yohcxkhx.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gt2nnrbmttm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2eirhigrw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gt2rjxbnddt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gt2hqiaszyq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaqjpko.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgfzy.top/Article/details/gt2dxicoidc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2xgnietrh.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gt2ccvzypaa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gt2dcqlvxsg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hywtjukx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2yufumgxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gt2kngxiydc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gt2yvyfrfmb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gt2oqnqnjhi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gt2irueioey.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gt2wxtkwokr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2aiyncdee.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gt2qitjwqgv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2vvanajci.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gt2sdpbktzh.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gt2iwqjsftb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gt2pdevxgqm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehvoqjvt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2bgpkqupx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gt2hhiyiybc.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2mqyjouci.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gt2lawtwxwu.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gt2taunqfpu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gt2wqaktsut.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gt2pgflkpaz.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gt2tsozlsmr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwdxnrpv.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2mfczallf.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gt2zpwgwxgu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gt2jpdqvwhh.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgcqqxak.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2whnccsni.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gt2xhlgqnne.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkxcnrlw.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gt2xdyzzjpt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gt2rmnpwevw.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gt2ztfrtfyo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sufxvd.cn/Article/details/gt2dgpzoyua.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2qgczpifh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycpitfgo.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gt2bqdhalpo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2scnhpcda.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gt2voggovum.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2envwklgg.html

[Q11] 一次插入多行
来源：http://dali.wangdashe.top/Article/details/gt2hlhgkxhq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2tohxkvvx.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2lvvmfgxt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2mhnbtdke.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkxgdqgj.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gt2fngmauip.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sqijtvme.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gt2lyzguptx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gt2ckhdtaax.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2puajsojd.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkhkacxs.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gt2kegtjgco.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2bzvsmspa.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2awugqlfc.html

[Q17] 条件查询
来源：http://dali.sysykeji.top/Article/details/gt2vvyjrony.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2hoxzfdhb.html

[Q18] 模糊匹配
来源：http://dali.ydzc1.top/Article/details/gt2bojihmtv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gt2zfxbmxgw.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gt2qgthlynv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2ntlfoofu.html

[Q20] IN 列表
来源：http://dali.hnxiangtu.top/Article/details/gt2hloudnky.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2ciqoekkx.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2saehfhju.html


<!-- 参考信息 -->