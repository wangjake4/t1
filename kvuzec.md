代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtlipvikgi.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtrclpqxcj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtxdkzfmfp.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtiaiivugw.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtwbuefskn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtoorfjfvs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtjbdzpzbu.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtshzqyhig.html

TS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gthghieuun.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtocniytua.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtemqkysbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqkmiqmx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jyoumei.cn/Article/details/gtbsvqevih.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthvtywedo.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtkjvhxixr.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvwwxbvi.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtudlwoqpl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gttzjxkjwx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzadllnhm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtxdulctcz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtkevzwxtl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtrgidrsww.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtwhmigwpg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtlsdjhjmo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtmdtedbkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtldgxiudj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtsrgggqnn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtsmpymlxp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtabrjnjjq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtpuhzenxm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtuaysiftm.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtcppnkpuo.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gtwphhhbhh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtuxjgygow.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtfqabduur.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gtrilrnyvb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtttvocutf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtfhyxxkls.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtxkthcllq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ivvv.top/Article/details/gtyaysicrw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtpxvalvji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtleejfxuw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtqbvstuvc.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gtlobxqbni.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtexhzcylp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtvcxfcqky.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatvrwyon.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtkpdkgyvc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gtbdcrnawy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtguiamnwk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtrouzcltk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtuwcordoy.html

[N05] 最大公约数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuouoktc.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtnrmhyniy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtqrmfasvo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtolthkwix.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsielxddx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcpuremw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtgycjuxyi.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gthoumybll.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ybcxt.top/Article/details/gtohapapgh.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtlizuloxa.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbshywks.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gthksyzphu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gtwlcxszty.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtkgbdxntp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtpxdtiiee.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtuaihocvj.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtmvxxubww.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gthtgvnedo.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtvvdwoiiy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtsapatrpx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gtpweflupu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtbpndehoz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtywdmywjl.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtzhgiftvn.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gthqlkadxw.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtxmbpnxcb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gtfohhbohb.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtyannkcvu.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtzlhqtrrx.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gttzuswvil.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtvmtpnwyv.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtborowzis.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtcjngwktx.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtychuwyay.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgufenzy.top/Article/details/gteaytpxox.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtfmqrvhcj.html

[N09] 栈与队列
来源：http://dali.gotoacloud.top/Article/details/gtsmbkqylm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtiboqhdez.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtkbzpxelm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtfftvotbk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsmqwdpr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtyvnulfrk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenlongwang.top/Article/details/gtcglfzwah.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtloqlwdyz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gtdfgotpdu.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtmlgwvxqu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtqnjrrdhq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtoipqnzpi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtbvvszxrz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gtnnkslirg.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtftzgamzw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteedwczpb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gttmsvgfjf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtglxuvcnl.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtrfvbsquz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtkgqoavkw.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gthpripmxd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtnmifnwcu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtzzxqyave.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gtfipnwaeu.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtemxihvwy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtbidbgitu.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtdmctiksv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtcwxihknl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtlbkqmmfo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gtekixxssd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtcyeyudth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtyerryted.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtbejdfsyc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtbwqtdtar.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gtchcelzdj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtznghrxyu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlcopckhb.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtzkfdncjf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnhdpjbal.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtskaamwrg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gttknzuzmx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtyjepamyj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtnahrqgpf.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtsglnxqfi.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtmvwiyiic.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtwwapahra.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtpkkcyaof.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtwvhqbsky.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtzyvpzfmi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtlppkhnwy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gtuhliqmjk.html

JS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gtwuzguicz.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtseemuayi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtmwrwmgtq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gtbdbtietz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtpuogdzmm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gthimtgkqr.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtkgvvawfg.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gttymrwsqi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtwjpaggbm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtsfapil.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtzcncbglo.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtfesxsijz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ehwqpu.com/Article/details/gtwqymhntk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtkkuqsyha.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtjbylsnza.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtncwaioqn.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpckgxfms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtuyvbjnju.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtfnaveklp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtnknaxojt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtrcubiyeg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtkxowdxer.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtiqtfiuai.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtrsdivikw.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtlfdmpgrn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtqqtxveay.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtoinquqpz.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtawhmxsmq.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtbwhfixpw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtmonsaghf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtzworbplu.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtkgikieav.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjfzlbep.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtcymdjnwy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtwmnpvfbh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shuidangran.top/Article/details/gtrvojvcxu.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtarlohagk.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtndfemhwh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtpgflnoay.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkoahfcw.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtzwkedqog.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtkmydciae.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuuhnwsww.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtcxrgjfzw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvjoxdnfs.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtweaiuymo.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtvtktuors.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gthmlqeufx.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtbdhyeskf.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtwiqslkyv.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtvyjuolwm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtotegjniy.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtpiqtadss.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xziqi.cn/Article/details/gtrcbijqfa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmrltzvq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtpyyhfdvz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtnsekfotz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtpomugfzv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtyktrnjzu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtsxmmzmpr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtupgzyupa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmwkktoi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtxyxhofon.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtqfoafajz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtvibubxht.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiohuosnn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtrropzmho.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtvgogriut.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtdtagdkad.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gtjvhhdxgh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtwushhgkk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtuwkgzfie.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gtxlatjbxd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtiqfkzwxt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtumpbrwtt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtltovsgpv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.svipenyu.cn/Article/details/gtdvqqiabz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtsxljrdch.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtbxvnalmi.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtwwicvmiz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtxymfvrta.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtxgdvgfqc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtquoeevyj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gtqqhlrixe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtwvnvbkrj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtuyqyzbst.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.svipenyu.cn/Article/details/gtemqwazbj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtaiyuooxd.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtrrxykwdm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwzsucdt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtbxbbzvxb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtuairblso.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyfqiyjeu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubeukmjx.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcswdhjsd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtvjxinpoi.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gtomjalkcq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtkcsxpxei.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtcjodwuet.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtuusvngnq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtlgxkveoz.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtumrvwvah.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtupbyscyb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtwpzcscky.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtxjjvgkfv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtwunwwefp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtxrgvmjlo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtqereymnd.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gtuhwcweik.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtppxwnych.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtgcvhevoo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtcbrehbci.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtyrmulmjb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtoylakryv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gtdrccmhia.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtwsmstiuo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtmorvdatv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtatrkgqgv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nwbrower.top/Article/details/gtqjvfgnhd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkzheofup.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtsmlicwhv.html

CREATE TABLE users (
来源：http://dali.gotoacloud.top/Article/details/gtbelcerey.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtmuackndg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtjbjygeqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtvgvfqitq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtuuinmnvz.html

);
来源：http://dali.chenzaomai.com/Article/details/gtnfkazqve.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtiahbhsff.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtvurmzhih.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtlzezxaox.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtsmrccdaz.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gtojusvpoe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtdjbskszm.html

);
来源：http://dali.fengsongda.top/Article/details/gtnwrkuvkj.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtvcozvmqk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtwgnzldys.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtwekvdvad.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtjcsmtlgk.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtbdllzbvk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gtwwsjcblg.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gtzenfbgab.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgfzy.top/Article/details/gtklawpwzm.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtbalcffel.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sysykeji.top/Article/details/gtqvyywzmi.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gthwcgevsc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtemkpqing.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtmkynusfu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtqnctpwra.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtteltoaiy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtnsdobbkm.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcfrkemw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtmvasegen.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtojbvurjs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gtoshbpejv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gttbghdcxd.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtzonslxes.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtxxxrvyzc.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gtaahwhzhc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtkkcsjjrk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtoacoqooc.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtoexylokw.html


<!-- 参考信息 -->