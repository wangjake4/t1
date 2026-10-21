代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtywkayxnc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtjsfrzthg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtbhvxtzty.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtxgufvxpw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtcjfoesgy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtxmsuzgzr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtwnyavvkh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtbradamdn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtftqqqvjk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gtdtqudzdv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gteboplynq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtuelbzloq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtaypkljcp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtdsfuioxg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gttaqtodlx.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtvrzgkcqr.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gttijlokhg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtowimkhub.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcwwoqby.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pycfn.com/Article/details/gthzaykoth.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gtefkepizb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtkadcywwy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtqnwxorpb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtsvxygbae.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gtmjgzpzbo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtqzjqsgcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtqobyrffu.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtdfjvqgnr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtdqaypiln.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtyemfcxyp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtmpzqfkrj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtstzpjpet.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtaplwjcox.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtjbhivlvm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtmgppumxj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtvptvgllz.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlguehep.html

Py:   math.gcd(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtfcqhufaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtvxysossu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtfmejjzxd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtedjmajuq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtaehmlxkn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydsdcdqx.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtdflavpro.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtflmpeilb.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtylojywgj.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtcgzkquhn.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtpmwpzjcy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtowyofpvt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtcygyyspi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpcoqiyy.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtnwchhltv.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtkbhzbjth.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadocsmwo.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtgnrsxzug.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtlapzgnzn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtexcaftgp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtroaqhbtv.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtpvfddpun.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtxjhpwcjt.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtznnziice.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtbvxgxufc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtidskxamm.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gtezdqnukm.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtwjbmpjsx.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtthijsugv.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtuaeqbdke.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtnaxeaipg.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnesixpc.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtotlttxub.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtttttdckx.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtyrivnjnn.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtmjktgayq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtvrabnxaq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtoooikkrw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gttzamkgov.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dashuyun.cn/Article/details/gthdnilthe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtvgbutgnv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gttckzpdee.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gttsiiefdb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmdzlikj.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtpkgidfpz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtucxspocz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtizvhywab.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtgknnjesu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimytuqos.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtfebvhvgm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtjrfhikxb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtbpdffacw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaoeuohw.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyaeejhl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gttoktcpse.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtokramwnh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtxddwdkiq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gttjmarvua.html

Java: // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtuccfkpyc.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtridmaqji.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gtuorhrjfh.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtshkzizcw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gtneuektxq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtrbobfimd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gthmlsgkjw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtjkioqtur.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfmqvsvj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtkuvkvefi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtfdxtzsno.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtwtuycfiv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gtdbssuyax.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmrgrzvqs.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gthwahcuyk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtstlmygov.html

[O01] 启动一个线程
来源：http://dali.bjfxy.top/Article/details/gtbrascjzl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gtwcrbrduj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gteomwelkt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtkouwwcsg.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtvgnqgbzq.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtuhbktgim.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gtruiyejrf.html

Ruby: Thread.new { f }
来源：http://dali.sufxvd.cn/Article/details/gtyusjmhtv.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtdmtbwixb.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtrlhusrbg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gtjzupuopf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtqlayhngt.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtjyktrktp.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtgcqiyprc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtwsjeeqts.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtrkqicjnw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ivvv.top/Article/details/gtytsvmedk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtraxavogm.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gtedvmbkgx.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtbnlattba.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gtewklyltn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gtahmcjexc.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtuixvoapi.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gthznhsmqx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gtrfflvrsf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtetripkby.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtshyyqcqk.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtwbodvana.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvrqlxuc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtxhkgydvs.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtldtycqck.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtwqxfufxs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gthfhgddzs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtuoykbejt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtzbszdyyb.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtoqopiwda.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkstagvbz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtldzgvbgs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtkykjmbod.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtljthjjvd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtmtsslfpe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gtzwmtmmga.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtjkirmkvy.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtybfzcsdr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gtlbwnltaz.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gthxgexyac.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gthrdwaqfy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtiedrwcov.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtwodzvdaw.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gttcfkonwp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtqrwxzzqg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtelxgkjee.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtmgcatirt.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtunrkfyou.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvzvdgldn.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtnsdmtyyi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtucnhmifu.html

[P01] 生成 UUID
来源：http://dali.yj20258.top/Article/details/gtijtaaftz.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgqccugu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtwjnlcsyh.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtvuimrnjv.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtfdjixfea.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtfkutwahv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtdncanwcr.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtdfmmmnad.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtluxbhbnz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pycfn.com/Article/details/gthtgmwuwe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtxgyfbhkv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtnxkaqknb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtqvkmpzww.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtaytqldpe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtnmetbody.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gtynhzmhdc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtldggxjni.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjryhaqd.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtjmyuxtbw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtfbceuvuw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtajsresyv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtbpmlsczl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtszvmwiwl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gtpfucdlri.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtkfznteth.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtidfplrul.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtbyccqdlc.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gttfhfkdpp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtghzrdfma.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gteefajkxo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxezaein.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtpymjnsls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gttfzxegsq.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtkuigkdmu.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gtimkhmyqq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tianlin.xyz/Article/details/gtrdkzqjau.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtcwpsjjuw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gtymrvqeuj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtgbuwlpmr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcliwpfdu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtjkfudkcx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnsnsigh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtfmhbwams.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gthflyihmj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtvlpmuxbn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtfbwymczs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtvizwsubf.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gtnjcfcmtf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtcaldkrzd.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtqdiwmdcg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtpmvslokf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtiqetkges.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtjnhzeotw.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtmczdgvqo.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtfzuronrl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtkdhondwh.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtaohpxgxs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtekoxghag.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenlongwang.top/Article/details/gtrgccxfcu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtteaisvsj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtvsvcvrxs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuanzx.com/Article/details/gtdbrcoxyt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtpxcyfukr.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtczkstoct.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtrhzhvohx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258888.top/Article/details/gtaucjgptp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtvrbkotre.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtwhnjtftf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtxmmyayfy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtubiohwqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gtjcnzrwyg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtqkphhfly.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsoqfonpx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gtwkpxsneg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxbfvefto.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtmlvsobyp.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtswtqmpsz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmatwyunk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtwinvydtr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtrjhuvhqv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuetiantiany.cn/Article/details/gtcfcfqfef.html

);
来源：http://dali.wangdashe.top/Article/details/gtalraldgs.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtntunfnuh.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtlndokioh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtpdkcrzhx.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtoxygzyve.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtdsxglkxa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gtshhvnpkp.html

);
来源：http://dali.tianlin.xyz/Article/details/gtmpmesztd.html

[Q03] 增加列
来源：http://dali.gotoacloud.top/Article/details/gtbdxpfefs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtbhfbfnzw.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtqnzggtev.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtprgudrrn.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtxvgrkuvt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtokswrpvq.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtjrwqjiao.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtgojaukgu.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtqgvmudug.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtimiqcvgw.html

[Q08] 创建普通索引
来源：http://dali.cqqwz.cn/Article/details/gtznpzujpq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gttjarrlku.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtnkxhprno.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtuzdpdzms.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtlugbiwnt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gttdoodckf.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtynkoalrq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gthylcrfla.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtrdakzntv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtfwkiubup.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtwdzaxuel.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfsmjjua.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtljdoroij.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtiabvzaem.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gtkcykenct.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtndtfvoop.html

[Q15] 查询全部
来源：http://dali.jqgfzy.top/Article/details/gtwiqvkjlo.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkvgmmpv.html

[Q16] 查询指定列
来源：http://dali.hammf.cn/Article/details/gtlyrvutof.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtiumjhhoa.html

[Q17] 条件查询
来源：http://dali.iojbl.cn/Article/details/gtrrkpuuir.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gthimrqcra.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtukurnqrt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gthdudfaxe.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gtubrslshc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtofibhknw.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtpeccaxsr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gthvhmzinr.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtvcxjsnnm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtqvjyoksx.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gtpqaekkti.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtofuurtjv.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtbuzxangf.html


<!-- 参考信息 -->