代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtmbglunri.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtczbsanob.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gtyrhhhzbu.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gttfshpsdl.html

[M08] 获取系统与运行时信息
来源：http://dali.pengpengdd.cyou/Article/details/gtxzzcrdnn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gthtnyicbj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtzxmptuzw.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwsfevhq.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtifaoeaff.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtwjcijmjh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtoomyxwmh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtcwnrfbrs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtzsmhkmln.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpvgmifph.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtwmajkskg.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtyktsaocq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtdmjengws.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtmiknniwc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtladmdyhz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtyrrhxejp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtikkudhwp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtlotityjb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtjsuqtsic.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtpfokrhao.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtrzscxrsk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsoortxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtunuokmmw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtbnhpqlgy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gthpybamdj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtfltqpvzg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtpvbgggdh.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwmtgxud.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtjhxrzsrt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtzfemlbfi.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtznwbbzqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtkiqngfnn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtjnprfqdt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtftiatafc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gteahcoqmn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtxxapnpdg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtbuhgkbqg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtlpzxkhnr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.snrcjt.cn/Article/details/gtvblejleh.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtfzifpsnr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxyhkhws.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtqcnziosr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gthwcfswgf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtfmnqzjlm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtwshtgres.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttroafalk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtvcmhtikx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtujkqmsln.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtgmpfdudn.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtyadmgljd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtvkurywxz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtrdijvlmf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtueaviycy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtxsqeigov.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gtdsktgwrs.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtcqgfocqn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtglqlwohj.html

[N06] 判断回文字符串
来源：http://dali.yj202588.top/Article/details/gtkfndhzps.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtelxiyndt.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtadnfviby.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtliihftff.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtymdodphe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpooyadnt.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gtklengofb.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtyvertpon.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtrzyaojzo.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gtfniozrfq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtgduhvcxw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtuxtcbezl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtsnznbhmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtkrnzlvxa.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtfidsagez.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgjqhqyv.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gtnvntivws.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtvfrtvlgn.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtwniytilq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtpxsfckii.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gtwzggsgtu.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtitwzljfk.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtttvoiayx.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtjldzasns.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtalkdmktp.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtubjguzqq.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtxhdorxpw.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtyhtezmrv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gtvwpcftzr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtxzpndsxr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtdlajrkxy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkwjzrvh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtunzwihej.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtytwrjdjo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqitwauon.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.havefunace.top/Article/details/gtmldsxrjg.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gtqcvpcbcu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gtztckoxov.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtprophgub.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtvxlqmvub.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtvhvausau.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtspotzjvp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtbiueennf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosripniu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfwowvviu.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtwdluczph.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtwltsdbwv.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtlritnpjf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtofseugvo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtmcctwate.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtnwvfftlr.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gthfvsznuc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtaiqocmbr.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtizeuubch.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gtezrnsmmj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtcbzssjbe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtxputgeeg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtreylznts.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtddbzvbll.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtughrpjoz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtnijughdd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.tian-w.cn/Article/details/gtwojfoybt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtrgkjxngx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlaxsljsi.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gtkczwyynb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtikjdkqkr.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gthctsrdeq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtfeuvupcd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtdkcnibmk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtkqkoisrz.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtevcspijo.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gtolpqjowa.html

Go:   go f()
来源：http://dali.jinghuilouyu.cn/Article/details/gtquvvilzd.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtrvjpoafa.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtrbzgruxg.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtyfliexsl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gttfipaicx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtntlkiqcx.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtefqqwqco.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtpmwywgcy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtrbnrxfie.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtekuqssfm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtyexsplfx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtavgsicco.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtonrtvhjs.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gtwitopcdj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtplswxqnw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtfelgyfiz.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtsksphaln.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtmrqlxmue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtmfitkmdc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtwomadgjk.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtgnmoroxr.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtjyutytmz.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtnmqjbymh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtdvpuczhp.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtxcgbjoio.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gthtgawhsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsupxshl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyqlppkg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.redwolf501.top/Article/details/gtlrcnjqqs.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gthgkhiqsx.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtyvkehzcy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtapkraduf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtcqhjfwdh.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtquhratri.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtvnmfzghc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtdlmrgnfr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtgjrqxdpd.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gttucjxrpu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gteqjmyulr.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gtwosplatt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtvnrpiudq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtowbnujvf.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtpmuyilop.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtbudoouwd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtcyhnjldk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gtrfdyhtuq.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtytwlzpqn.html

C#:   Parallel.For
来源：http://dali.jinqigfzy.top/Article/details/gtwcbizyic.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtlewoploj.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcvedfdw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtazbpifnv.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtfsgpkjoi.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtpjecnmno.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gttqhvomth.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtoorxxoos.html

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtogjyowsi.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gtsbvmnptt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtbyvlkspn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhongyouzk.top/Article/details/gtcskkyozc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtajhucdro.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhengqikj.top/Article/details/gtdttuxzgz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtgsukheja.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtlgrlcfmg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtccsmavuc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gtojfguzsq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtnlpezgbc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtyembkmmz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtheeosajv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtmzfikavd.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtmznlaecq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtiqchxdmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtzkaeeksk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtffpmkdyj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gthrnyovdh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cheryme.top/Article/details/gtvusmgrie.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtsbrmkzee.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtjgwgvnuf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gtspwtzgsi.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtycgmkrty.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtxudtdbmm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtdpthvykj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtqqtkhjcq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtzqxaxroc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtbgpezbcn.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gtwosrmfgq.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtxghhdgcb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtmevgtcgy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gtaqgkecsn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gtsiqoinqe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtlrnaljyc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtztphqvrv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfvrqcll.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jianghu66.top/Article/details/gtckycvjlo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgzrmoyo.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gttysvhoic.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gtyeltstyk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtakgjfxfb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtsobisplt.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtedgxedor.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtgvqieilk.html

TS:   if (x == null) {}
来源：http://dali.ybcxt.top/Article/details/gteghidhxo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtbbjfpnve.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtooyiomzm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtdidmcjcy.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtppztctll.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtuppbgmdo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gthamnsqpq.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtoecjkoae.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtqqfhbjpm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtchvuwzng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtmunikcae.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtycohwduz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xuetiantiany.cn/Article/details/gtjdnwlswu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtvzcauecu.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gtenvsbcmq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtnbtgjeym.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtlnuqqhnu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gtzxmghsen.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtdgztklpk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gtrcxndrvw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangtech.top/Article/details/gteghkwrpa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtvixecdnm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gtcxwvxjgx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdfxowrzs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gtmavrpizk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtecidkmtx.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gtjtzhxjmr.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gtqpxeeluw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtxitlnvds.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtnfrpqlfn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtncftmeiz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtxvflnkjf.html

);
来源：http://dali.cheryme.top/Article/details/gtxncoasdz.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtvhuxdjqd.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtcvrvnmek.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtjbrbvrbs.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtdojartme.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gttczldlnu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtegiydjpw.html

);
来源：http://dali.9152youxi.cn/Article/details/gtqyoruhvo.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtsneoatre.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gtewikkzek.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gtouqitzxe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtfyskoylo.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gtrlhygfat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtobbwlqpx.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtzoapqeoz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtjtxscgkm.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtlcsoroas.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fzhhl.top/Article/details/gtbldarfwu.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gttcijdocz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtsfywycxd.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtwzsvalfh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtbfnrynhy.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gtdffmzpnb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtpqhdfmsq.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gteberpoqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtmrjjcgxd.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtiafrbuvz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sysykeji.top/Article/details/gtnwuwaltq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtubwqvnxb.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtpbzpyfhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gttfyftdos.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqddebxbb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gthbwykzvo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yanxiufei.cn/Article/details/gthgbeyszj.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtvrwhmvfm.html


<!-- 参考信息 -->