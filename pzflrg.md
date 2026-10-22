代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmqhdha.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sluupvla.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gt2xpqfsgty.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2wwwqarfc.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2hydkedca.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gt2rxnfzhbo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2kvpnitqm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gt2cbaxtvhs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dashuyun.cn/Article/details/gt2ezraeyfg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vzgrsblx.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksufxewr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2ttbnivdb.html

[N01] 二分查找（有序数组）
来源：http://dali.yvedp.cn/Article/details/gt2dbelofey.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2nwfvfhvl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2mgwczzqh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gt2lhfsqoup.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2nkttgsjc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2zbmbysio.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2seplngkn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2nozsizts.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnoonvnd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gt2aaxisayh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gt2odhemnox.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2pnhlwlgq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2flvtiujp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2vcvxtset.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2fzxtsbar.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2lioclnqu.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2zpqttgcl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gt2qcvgpgte.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gt2bhunegyw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gt2ezfbpnil.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gt2pxahovez.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2mrdukwos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2rlksofxx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gt2rjmziusn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2lwdaomyq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2vsveawrs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2jjyzsuoc.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gt2uspebgtu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2awsfhqjh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gt2qwkztftr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2zjglqdza.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2sqnhlrzt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nwbrower.top/Article/details/gt2ewijafhz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2uuudzhcv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2puafebtt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2dqcjbdbx.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2fnwetntq.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2linriywd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhchhgpu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2meebrbyk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2sixzjocx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2bxbdalrx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2ahgsfypr.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2jrvlhdft.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2dicnkcab.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2qyqbxsli.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2cmyfkcma.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2bbeuxtov.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2dfsruxvf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2mhkjxnzi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gt2ipyrktbz.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2rjfnrzdm.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2alytgoit.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gt2fipaglae.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2jfpvgkhm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2rnzpjqks.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gt2pnbzuvws.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2ugtxvbol.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gt2wkqzicpo.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gt2eodkpluy.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2aoqdoiyk.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gt2wzjfalpf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gt2ohjejmbv.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2pgozmfvb.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2stwkkpzb.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gt2qtbgesdv.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2uqjhaccm.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2ugljosek.html

Java: // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2ueovobqt.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2ueulxvfg.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gt2uzpflrit.html

C#:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2pevpfuss.html

[N09] 栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2kixaakdu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2evyqjnkd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2tobpoloj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhfjwvrs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gt2rbhooqul.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2cdqsexpv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gt2qdakdzgu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2xzkvswbd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzyimdcr.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gt2antdnwnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gt2vcnxmhtu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gt2oxxmdagl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2wpmgaond.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2zfpjvhac.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gt2xnbblbkp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oayhbbre.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2jkmmxjiy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2stqvvjsj.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2sijmkryg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2zwgsjrlb.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gt2jfdmsmsw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gt2khipqxpc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2akckepzg.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2qxllsual.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2mysovoik.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dablapvc.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2cvkpdbcu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gt2ogqxojqn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pycfn.com/Article/details/gt2nfgzxabp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2tbfedtyo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2nqmeoyym.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2pevlifmz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2ypgiytoy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gt2bkxpgspv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gt2obnqbjhy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gt2hyiwwwye.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2zqlsonwl.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gt2hlpbutev.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tjcukzdf.html

[O01] 启动一个线程
来源：http://dali.yueranfly.top/Article/details/gt2llwrehvv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gt2fyownbjv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zdqjudy.top/Article/details/gt2ggkifvsi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gt2ldaenakb.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2owhepwck.html

Java: new Thread(() -> f()).start()
来源：http://dali.sweek.top/Article/details/gt2pnthygoi.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gt2zwvnukwp.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2pjyfksic.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gt2rvrashoj.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2rkmfdwvu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cvpsfxzr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gt2ltppicqh.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2cyeoixat.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxqunmtn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2jjjdfzmk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2uqhwuuxu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gt2wehkdgon.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gt2aueyzmsi.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gt2iffnycqo.html

Py:   with lock: shared += 1
来源：http://dali.daxiang520.top/Article/details/gt2hvsvesks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gt2pybvtwrx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gt2lhxligrx.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2pegvxeeq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2ruwoovtm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gt2midrjvbf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gt2iumfampf.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wvbykgwk.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gt2jtetxird.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2uluzxgba.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gt2pirwtcil.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2oiiwzfsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwcudcgy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gt2obnktyih.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gt2ohpbkimg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkkzpqis.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gt2naimvnbe.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2jfhxwnwi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gt2dzeussyp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gt2muysxqyb.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2nsjqwnay.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2crcnhzvn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gt2bpgkzezy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khvbgyiu.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2hnrhcpgo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gt2hxhjhvoo.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gt2drniiczr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2yidysmos.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gt2jekqmshm.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxjjrmyc.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2wmuwzpwb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2nsgzrgxd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2naqimijq.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gt2dklirmcc.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2bpojkokv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2scandbqp.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gt2ftxmyhqz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bkpzqhrb.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2rempnuvz.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2tkhzpvsu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gt2kncliczp.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2mmqchpfh.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gt2zlkgqlgc.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gt2cvesifvu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.havefunace.top/Article/details/gt2lxqehdaj.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2jrszbncg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2paqxqdmy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gt2rhujqouo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uykjoxvr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2snxfkrmv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gt2vxnqlwja.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuglbwye.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2rdvjtgrf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gt2nxiowdqg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gt2dnsxgzwi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gt2fudmlsis.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gt2sykwmeuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gt2iqqnbaqb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gt2aekuxxgb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2yggfxjzs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cydwmusd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2vhlxskka.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gt2bujbjtuh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gt2twbnqxfl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogarlfip.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gt2wazoujyv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2trtkyfao.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2juomdvij.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gt2dnsseezx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2pliqvmhb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gt2eqwjoyuk.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gt2wjqrikmn.html

Ruby: x.length;  x.size
来源：http://dali.yvedp.cn/Article/details/gt2zydwqgmu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gt2jthcxxvi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lesufgnd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gt2ptnngbzf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gt2jkixrgyn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2tvbiqhjj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gt2ooatygbt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gt2avdgqqti.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jntjpnoa.html

Ruby: a == b
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjqsmsze.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gt2ycwmtqou.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gt2hgcxxehs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2sxkdgmhf.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gt2epphfdfm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gt2tnhuzshx.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgutsdlt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsscpmkv.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gt2cwcfmptl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaojtaxl.html

C#:   if (x is null) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2coxfogye.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gt2xyoeqcvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mknuyylj.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oopzeeyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gt2almftnpz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2nucunsgd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2mlavizho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gt2xengdfkt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gt2fonhwbbs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2misaeiel.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gt2yzlvvyyi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iquhvfyk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2oclslwzv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gt2rfjjrikp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2ltedhdvj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gt2cbbemute.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gt2tzvjypvd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2gbywtccu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gt2gieobuxl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmrtqqjy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fengsongda.top/Article/details/gt2gaheebbx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wtimuyny.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gt2hlvevvfj.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2yptovkbc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2wnlesfnx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2bnucmxia.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangdashe.top/Article/details/gt2tqfatpnl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsaegleq.html

);
来源：http://dali.xinyue.icu/Article/details/gt2zfrxyvqv.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gt2scmrnmvc.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvtkeexz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2xibpgrgm.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2pbgywxsf.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gt2biangacn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gt2iqxowmop.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etsrpesn.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2dkquntch.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gt2amupkhbb.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujtbujbv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gt2befpkvuv.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gt2vltwnvra.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gt2iwsqncmt.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2isyaievn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gt2ipodvpii.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gt2spaqevqf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gt2azvtyjyg.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtswfbvo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgrzraqy.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gt2rbncrdpz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2coticijy.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gt2amijswti.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gt2zqrhmhvm.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gt2qbcdmkvp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2siuecmlr.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gt2kkqpiavx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gt2vqcdjiey.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gt2rbvvaequ.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2vmshegid.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2kiyivsuy.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gt2ksvoptws.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gt2udquvggz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gt2calsvhde.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2irocwjdq.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2ewrgwyyv.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gt2kbbdkdca.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2wstnnfsj.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gt2aecgcjix.html


<!-- 参考信息 -->