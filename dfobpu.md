代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtqiwrvjqq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtulojplvs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gtmvgvpeyn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gtpkvoaxzy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtgmqbbssl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtphiuxusf.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtjwskrwpu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtiterskpq.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtweuwovue.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtobyltmno.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtnnrcsedx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtkakizxdp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtbytjbvrc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtkibhbkjv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtbvggzcng.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gtybpebgiz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtwtoccdrb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gtireygqhc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtcvtjbgyg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtqzoxiiue.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gttpvcnwyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtrctdvuyf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gthzxhhpte.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtpbpftebd.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtiyvxtoal.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtueylwmbc.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtctwufqrl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtqzjuopqc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtgdmrdomm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypsvwrzm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtugjxdcxi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtazaguqcr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gtrwpjomeq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtlaibcoay.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gticwfquot.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtjbmbmskb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtgukxitcu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtgdsyyboc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtrryoxqrx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtdaprnxed.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtcjilqfrr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtwryzbkat.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtuzyntyyh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gthuhsjdrf.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtdqymzmde.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtrhjaatzz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtzpqtplkd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtkjrfbwyt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkcasski.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gttwmkisoa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gtnvrxqmjt.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtlcjfrgyw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtbrbbuvvx.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtgiflutcd.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtsbistncx.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtioyjuqhv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtepdckgvd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtbsgovzyi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtzfbuuviw.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtwlwfkefj.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtsuqdozvx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtunxnbbvd.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtcdptdhfh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtoxqkyrvt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtjzzurdrm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtvgduhxpe.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gteycrmgca.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmooerra.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtipcourig.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gtyzjsdosn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gtpcjfzdkh.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvaxjxlv.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtehpvcsve.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gthukzphrj.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gthlggzyju.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gthcaovaae.html

Java: // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtxjzbcgjt.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtmqbcffdh.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtxwjcbqjk.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtosrqqnno.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtiajcgqgr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtvmcypaco.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtccwdppnp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtudqnzlke.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtijhlcwpy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqarlzuui.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtlydhpjcd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtntgwrfaw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zycfv.cn/Article/details/gtkinojzqd.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gthgfmgymk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtqoqfptfr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtmffbgoaj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtwqoxrfww.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gtwshqjfkp.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtwveulrep.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtcgkxpebu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtsxkdjdfi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtaffghjfu.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtcxjogegg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtrrbpdzoz.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtbrzpasrf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtqfmyzoxs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtagoxhpbx.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtsesumeqa.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtfqlankcd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpmgikiv.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtbbptzolr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gtnjfasqae.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtrzoemgch.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtkvtbhmxl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtjbhgdbye.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gtijolzbne.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtknkvjwej.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gthbdiqxnz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtgbnthztf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtivnwcoay.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbrstwdl.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtssowckhy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoqgivjjy.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gtooeeuhzm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtsjouspbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.snrcjt.cn/Article/details/gtbjidxnqw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtuerhotju.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtkgwqczlj.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtdoigijvs.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtynskanyg.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtlgoruryt.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtiwmscimh.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtvivigwxg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrigsbtu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtsjrehxna.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtuvmuhqfj.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtpaogsqqh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtjdnngpsp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtllfzuabu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gthjgdxsra.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtuuszlhft.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gtxsjbumxe.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtmpfhxrce.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtlapnbvch.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtmimniztw.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtwvxqarmy.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtykalkhxv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gtlihnmavp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtysfzmutg.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtkynqfgyp.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtxthsniru.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtwoibbvzg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtikukteoc.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtfxzhzxac.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtqsxqfjnw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdglfilft.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gttfeifuqw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtesbhlwyr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtgusgtfhf.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtwqghtjgj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtvidmacdk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gtloippbae.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtsfpitfzb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtfqxwprts.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtlokfgepn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlgvjied.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtzsygkngw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxdqxmkgf.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtdphrbwmn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gtdbjnjcpi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtoydcxcfp.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtjqmkqtcq.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtikmtzzjm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtqkxlebln.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gtugnwtfdh.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtayyzuolq.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtqpiazigo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkwtxpmcc.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gtgyeereub.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxammfyak.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtkrjqonvh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtefleawtj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtrcwfgmyr.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtmjrolkyi.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gtxgpqawvf.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gtofaxqwcr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtbvsqturz.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtzyxqtbdp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtygicshui.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hnxiangtu.top/Article/details/gtmjwphmnc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gttejagpid.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtiwwzibnw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtzrteqmzq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtgquyawui.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtjepmtbfw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtmpeuxhko.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtutirbxmb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelpjqxok.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtksvzfzzb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtupjxnvbm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gotoacloud.top/Article/details/gtystxtdhy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtazcjyyey.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtjoctjldd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gtfaypetlc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtseamvyju.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gtaxtufwte.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffqvoiag.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtwkbmsxps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtgalopazc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtoxxgnrtc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtrlepwvki.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gtgtfipqao.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtvzxednil.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtdwdhgrec.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtmjbatajn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtruzruhsv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtzpvjszwi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yongpay.top/Article/details/gttozamlvm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtawmhhdcn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtwydswibx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtrbyjwtor.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sufxvd.cn/Article/details/gtyalnggmd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gteryllxcq.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtjylaurhh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gttsmycgkb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobwlibbr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sufxvd.cn/Article/details/gtfmjvzobo.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdawnjtuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtnqirklgr.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtxstlrdar.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtawzkhsub.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtvmjndwuk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gtyvwrcpkt.html

C#:   if (x is null) {}
来源：http://dali.yj20258888.top/Article/details/gtbmkpfesy.html

[P07] 防抖与节流
来源：http://dali.gogol.net.cn/Article/details/gttvtonrku.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gtkfakecws.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtgpcvzjie.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtdpmyavgl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtkcymmmcs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gteonmejyy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtbzejwecy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtkywbjvza.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtjmxvswnp.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gtnpuulfbl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtrefttwfg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtabndjycz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtkufjypry.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtliygcjuy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gthlguckjr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gttqboznvx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtgyxcqies.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtfbllwkaj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthvepbcrs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtqblrybjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtszyrehhu.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtueefjili.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtshjlnqvt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtykzqemug.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtttjkxvel.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtvznjanqr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtxrmwwqba.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtjtxoooci.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtajfounsi.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtshglbzht.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtujvakklr.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtmdfhhjnm.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtkrqrimnc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtmnerlvie.html

);
来源：http://dali.jqgfzy.top/Article/details/gtzscmqjez.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtuqfcmjex.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gttqvkghrn.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtayszlhon.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pycfn.com/Article/details/gtwbjydfse.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbsklevz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gtagpjqmsu.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtgswlbgra.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gttqpkegot.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxujwqwee.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtkiddqais.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtyzmuodyw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfemrokrd.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtlighkiss.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtjsjxcitz.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtlkliwcio.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtelpnuiuj.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtbvzdmgkt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtgjvcycng.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtbuirrzxa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258.top/Article/details/gtltwfggdk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtgqyprnry.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtqzbqfpqi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtabthcszc.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gtjsuixduz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtorpddrgj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gtrcmhzzps.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gtmupkhnxm.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtaujcnhyy.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtmihhoemf.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtibxtonof.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtswrkkgxb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gtpkzvvdwv.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtvyiscjrn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtnovlnycc.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtwqenmrpv.html


<!-- 参考信息 -->