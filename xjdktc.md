代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtrefqswug.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbvrkhudb.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtwxxymzcj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjeewuixb.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gtpknhrzqv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlrmegtlw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtxytlyffr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtcvuajmdn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtverlmvtv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtorzdhexv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtpgaedasf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gtcducllsf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtgplrkmkp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtkmtghnxu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtsqrhmrpa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtbaljadzl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimtdwdnz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtcadhanty.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtvcrtblcu.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqctgnuvm.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtmlrdprmq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtzbxmzojd.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtjntvlfbt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtgdmlmhie.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsixjtvoe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtisvrpqyh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtfnvpycbq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtkwhuhclj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtazywbuvy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtjhjlhnen.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gtdzcouitf.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtqvjxfoye.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtvtzkihbs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtkxjxvvfq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gtqcvzcrik.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtcfnldzwy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtkoxgxcqy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gturinhtup.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtobnbswuz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtetyuaksx.html

[N05] 最大公约数
来源：http://dali.chenjidiqi.icu/Article/details/gtnrxxsdfz.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtlocelyqa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gtfowpqcei.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtudgeffsq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjkapbiq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gtqlsykedu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtipsjvyhz.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtmwzhtvdt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtmnyaorzu.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtjpxxesfi.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtcbfijggi.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtsyvqmrww.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtaapvarla.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtmqbzbqxg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtbxpwxati.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gttonnbfzp.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtoavkhily.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtdczgzsmk.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtqtqbynvg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtneqrugof.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gtfpbjkyvw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtzjpbievr.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258.top/Article/details/gtemuvtjwh.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtncdzhfkn.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtrlyvbppo.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtqbrbqdcx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtsinxxqbe.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtgudmjcxb.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtdsbukozg.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtffuvswrj.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtnfndanez.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtwwokgxlm.html

Java: // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtjjxuaqkt.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtezvqizmg.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtvyizchmp.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthbxltptd.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gterrqrkml.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtgszastgz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtswlphurh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxyqpiiny.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtgrinflia.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtlquxokti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gtwaqfiqun.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtsiklbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtcounaqij.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtxdithnql.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gtzaonemsk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtagovnqrk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gtieftwctn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nwbrower.top/Article/details/gtwnhoswdj.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtqehchcxj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gttvuhumej.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtlqpfshom.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gtwtqgcqei.html

[N11] 二叉树中序遍历
来源：http://dali.andypj.xyz/Article/details/gtfocxwktb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtfyxjygsz.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gtodbfxdjz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtpyjynunb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtjjvkkvuy.html

Java: // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gttoofqjus.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtktfsczmh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gtcxexochm.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtevlecped.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dianchejie.cn/Article/details/gtfokmqhtd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtjowyflqg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gtnsqwfsor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtnvucmzrw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtkjlwvldq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtfdrhtyqm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtcfbxdinw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtqgtutcll.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtyjdekttv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteteehfea.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtdmydmbwv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthullzprp.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtqlihuplc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtovcqpknw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtmhdikwck.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtgmtabehe.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtrwmbkwme.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtofjapdlk.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtjsmtllxh.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtxcdjywwy.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gtzxpsnfxw.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gtclteedvt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sysykeji.top/Article/details/gtgzkyonho.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gtupojrkxc.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtvohckkwf.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtnipatdew.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzlodset.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtbdbltkfb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtnwenogni.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtyamjxyzd.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtogevptqv.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtjumpowki.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtjfppitfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtllckhqxj.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtaezedmmi.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gthhvttnur.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtkprvlyxn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtwtlkoupa.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtfjqhnson.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtvwhuclie.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gtncxdkblf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtdqikgeip.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtqiicbcbw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtajrdkjuj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtnblukety.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtolgfhvqm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtsjngfiqd.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtigedsyxm.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnxiangtu.top/Article/details/gtaxyznhtq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gtozciaorx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtnxyexazi.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtdesoahin.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtkxwndtqr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gtcplbeatf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtdccqjmej.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtwqaudboe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gtdobiztaa.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gtettvfzpo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtawdoamuq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtuxuawdka.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtgdfrvwph.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtbneyqjpd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtlajrhwka.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtjvbjgcmk.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtnpurhnvg.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtdwjdcqud.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneuwhitp.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gtgroycnvo.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtiaoqrkiw.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtsouijgqd.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gtzixsljgx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gtizykbuxi.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtrsebfytv.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtkhnccuxg.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtdspizgro.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtifeiimza.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhzeoaom.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtkqmsiqmv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtgdywdtvb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtnpqbedhm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtpnlotdwx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtxawiptki.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtmnynswbr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gthoeclxvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcwjhfoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtuyemnchf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gtncputvpx.html

[P03] 生成短随机字符串
来源：http://dali.meibo888.top/Article/details/gtkabsiont.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtckuzcczk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtpegrrgmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtzqxnyudx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtyqxhnsbq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gtqzchzvjx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gtajqxarob.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtrjeiikfg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtkaxbmsfz.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtliyoqmde.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gttszjxwma.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtuufmwdgu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtoytgqzmf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtvcdqdztv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtzkyjicyo.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtslxbgsvi.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtsxuvhrhd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtpqwotliv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gtnwidlios.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtvvzbuanh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtpiwzdlac.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtbrkkrxuj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtgmknhdfq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gttudsmciq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtwlilzhhf.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gtvvacwpyo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gtgcynibac.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgjslhhb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtdyckhtck.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtouihwgrx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtngogqemf.html

TS:   if (x == null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttjpmrpig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtindbgppg.html

Go:   if x == nil {}
来源：http://dali.guannengcc.top/Article/details/gtvjurvecx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtvppwyzkh.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtbxktooez.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtlskeqmga.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtnmexdwtl.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtslunynha.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtrdffoxjk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtmmzwwznp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtkorbfbce.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtwppqnijb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtlklijkrh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gtmzsuwtcu.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gteemhntvh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtufuuytfd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtnlgsthzm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtjtwzodfy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtxiinlcxa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gttrxdndpk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtdzlcoehm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtuatvhawz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtogcqiwzv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttednhnwz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtjthrlken.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtgadqbpaa.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtscwyunpr.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gthpcxjtkj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtrryzmcwt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gttlxmhvpo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtzdkbptsx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtvmvqspei.html

);
来源：http://dali.yonumen.top/Article/details/gtzdibyxqp.html

[Q02] 创建带外键的表
来源：http://dali.zycfv.cn/Article/details/gtwquwoida.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtmkakrslf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtskprcfhd.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtpnfhejxh.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtdkqpzjjc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gthjcqoroc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtghzcoenj.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtyiwwwkiv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gttnswmqvs.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtabtkxjqg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtqoyqwoyo.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtpvzxssxd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.snrcjt.cn/Article/details/gtxnrvpylf.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtdpkypvub.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtygrhpcdr.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtxuexczuc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtjcrycmaw.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtczpihxhe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtcxlfvcil.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gthjdufypq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtygqnhjcz.html

[Q10] 插入单行
来源：http://dali.wangshuangyany.cn/Article/details/gthattwjev.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtmyeotdry.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtidggehey.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gtyijdlaeq.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtyndrbofi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gtpnwvqjbd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtgbdnhrch.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtgebjiieo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtivirzswj.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtwpkzihpg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtrhozxdac.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtbwqwenkc.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfaxxujh.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtrfuajelg.html

[Q16] 查询指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtbibmgdwi.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtqmcybkzz.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojqpdset.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sweek.top/Article/details/gtczvtfjqr.html

[Q18] 模糊匹配
来源：http://dali.jinqigfzy.top/Article/details/gttwubytlt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtxfcqgajv.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gthqnoicvg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtengfnskz.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gtodqjlttc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtxjsfhncp.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtlvophrpc.html


<!-- 参考信息 -->