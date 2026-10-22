代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2dablxoie.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2qjeklior.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2kliiqlrw.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2ytcocvgm.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gt2erkebwdo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2cuczqbuo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gt2xnounitb.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2hueaoaeh.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2comikfkj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuwgkrsv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2daecoovy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gt2cjcisrfs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ehwqpu.com/Article/details/gt2naoomgfp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xkvwtjxt.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2jkkumvhi.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2edfppcjj.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gt2lbkqdpqb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tswrsyrc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gt2nzedavkz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2fmfnlfkw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2hxzqbaue.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2ioshempv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2onkymnkj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ivvv.top/Article/details/gt2wdolduci.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2hmwotfdh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2hfgytrfq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2edldngvv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2ggvcrbyy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2axparyka.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2tukqjqui.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gt2avhxskar.html

Go:   slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2tgnkapxy.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2ppvcnnls.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuxming.cn/Article/details/gt2krphopxv.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlxteymr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gt2aipkhqzb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gt2trlwcrjo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2eauhmspm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2ouqcwwen.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2dyaxkafz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gt2bdocdfzc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gt2hqwzajew.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2iesldofw.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gt2palxgogs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezwuilio.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2yoexkerr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2vpnuttuh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2fvaufwqz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2gzhmkeod.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2zbznfeyn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2ijbjimuz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2amyhuuam.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gt2rmejscch.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gt2dccmuozr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zahrydqc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uuqftffl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2quzwbkmw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2ksppndhf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gt2orlkjxed.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2ydowxqwy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gt2onbkzjdd.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gt2ifuwfmaj.html

Py:   s == s[::-1]
来源：http://dali.sufxvd.cn/Article/details/gt2fpfwbymu.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2ulmpbzhz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvpgjojc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2ityhjchw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2ghpewtzi.html

Go:   // 双指针从两端比较
来源：http://dali.jlsjyb.cn/Article/details/gt2hjlrfvwa.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2vamrdism.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gt2hobvqssy.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2hgyuggsl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2nhtvfsfb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2stgmkkla.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sysykeji.top/Article/details/gt2skyslvqk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gt2ytfnelez.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohagnfww.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2kqvdelss.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gt2shyiubgq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gt2zxxlsmfu.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gt2svxehoxd.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2jpenaxda.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2krgirmwc.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2fhsafhfc.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2mjjlgjwk.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2zaspkrkl.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2wnxkxgez.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gt2qwsmmyth.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2oesbtoct.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2zratyuls.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gt2bohzabsy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2jewarfkb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gt2jtkodrib.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2cbhepuco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gt2tkxdoknd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2hryutuee.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2nbfmvbye.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2jqecscrd.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gt2stveecos.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gt2sgxelhak.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mciducme.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gt2ityadwyf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iesxedcn.html

Java: class Node { int v; Node next; }
来源：http://dali.andypj.xyz/Article/details/gt2pioicggo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gt2cnjrhxpp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guannengcc.top/Article/details/gt2ljagrpjf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gt2mpiyodrg.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2ufbiguyw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gt2pwmfsyaw.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ezecyocl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2epgmqbpj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2vzwgpsln.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2pwbngorc.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2cuhuetuk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2qoapwdvm.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2hepuwpvr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gt2pxrjtqsw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gt2fxnsoiya.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gt2otvszmxl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2ghtpvvoh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2izywnowr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezybmrqn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2tfitwpkl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gt2znglnfwu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2ondmmhtn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdsgkpjr.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gt2ejlqjzza.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyxgjgxe.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gt2ybcalkmv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pycfn.com/Article/details/gt2pbxfamzq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gt2cwavprpl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oujnlgeq.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2cjqgpwix.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gt2otpewirv.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2jqlcrxsf.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gt2pbdwsgra.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2aqgodhfh.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyibnman.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gt2opqegspa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2hetixdrt.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2dyocsbsl.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2gswxxxpe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2tizdchnh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alrdtoem.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gt2owpwxrzc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gt2ffryeoid.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjwoktoy.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gt2tlmgmwrg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gt2iwqeuuqp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gt2fdgqmqxc.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2raysssed.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2uaomgeja.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gt2vpajxdrq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gt2hwneaqnj.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gt2flhkhnbh.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gt2cjcktaly.html

Py:   async def f():⏎    await g()
来源：http://dali.dashuyun.cn/Article/details/gt2mgvqmaqp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gt2kyhxqifk.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2lmuycuqu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2lnxkiwxl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2ermmzlun.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2xdscimyj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2gokzxoav.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2uwaktixn.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gt2ffknexec.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2qowjyuuf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owymucss.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2veluyplo.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2gdagyesb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gt2jzfbsnfp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gt2fexfxuca.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2wyorwbmf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gt2uozvyljd.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gt2lhffsxjy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2grflgklk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xupcxsjn.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2pqbinlgs.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2mtxulzqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gt2htzzhrku.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gt2oluuhaew.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2hilvhkbv.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gt2yjkbhgdp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2zrtmtxoe.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pplpjaiv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2aczqufvq.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2mwpgtbtu.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjirwzpk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gt2qpkwfbmt.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2tfcegprw.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwslzatm.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gt2hsqpezfq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gt2pvjuwupx.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gt2pxewyayw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2xfiwesak.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gt2pyfqimwq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2nlhgljgg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gt2lnpyonfc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuxming.cn/Article/details/gt2kxljkvyj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gt2tcygvpby.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2vcvysmie.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gt2hsprvvgu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2efoqhtzl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2polrppcu.html

[P03] 生成短随机字符串
来源：http://dali.tian-w.cn/Article/details/gt2aeovfpfw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2dyduxege.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gt2rlfsxpmr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2ohjrovnv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwlitxfy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2cnqieojv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2qtbxrruw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gt2qamrkist.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gt2kbhqwinn.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkcnoone.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvtmvass.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2gnmxphhh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gt2vfpawzjp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2zttqrkkq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mchixsuh.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gt2nhndmmxg.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gt2qpbwqbwb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gaflodtu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2amslpxgi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gt2ojwkggpu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gt2wyggrwcg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gt2nrintina.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gt2hcvnrcux.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gt2utlhgfrf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2tipzxfbb.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gt2jevrhduk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gt2uawtwmiu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gt2uhhfducn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2woakzlin.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxoljqrn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gt2uvnmojan.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2nehbtcvq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2bgyqkdrq.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gt2yltlfkgn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xziqi.cn/Article/details/gt2mocwzssd.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ggdazpdp.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2drnmzkoy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gt2felesmrm.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gt2iafyciia.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2xrodyqmf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2gskpfntt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2jdnokcpc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jianghu66.top/Article/details/gt2vwrhykoo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gt2tebemtec.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulzfqjga.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gt2fjozygzb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2phqsqfga.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gt2hlbkmcuo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gt2mfukhomd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2wrhnkkzx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gt2vkxsgvti.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gt2srxahwyh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gt2gvqxavpi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gt2omjppjzm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2kvaewzlb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2oohnrkqh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ueebtkry.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gt2bjftphec.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gt2qgcynxgm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2ufprnnqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2ermijiwx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gt2yxzseika.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gt2wtxlnqkr.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcbrfykx.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gt2vgglxwqd.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2jxviziqx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2qxejxrsj.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzzuzbrx.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2rejxwxxn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gt2utdrvora.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2bqmoohdc.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gt2kfxxnbvx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gt2gatbfcid.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2thxtdbpc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gt2uuaaoxxa.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gt2ktmgyzez.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gt2ffotwaib.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvmcqnsa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gt2unhaougm.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gt2dfbuanjt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2tsnqtmue.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gt2qlbnvzee.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2uliayffu.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gt2pcqnumdf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gt2luzlecyc.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gt2npobhfdn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2jtxwaulu.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gt2mxjkclco.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gt2muakynfv.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gt2npwblbzo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gt2nnbeerbg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258.top/Article/details/gt2gmdqdohh.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yterycso.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2ahufsjga.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gt2gcwnwywh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gt2bltzunyp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2acapqrsh.html

[Q15] 查询全部
来源：http://dali.ehwqpu.com/Article/details/gt2hdcmtdah.html


<!-- 参考信息 -->