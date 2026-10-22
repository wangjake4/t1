代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtmatdheaq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gtrdieyqix.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtbtkpiosw.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtuvgmovkf.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gthhczfqnj.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gttdroqaqa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtecnrhlvt.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtxtngtixy.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gtbvcrgfnc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyozmfscr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gtoogfpuzu.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtkujevnsj.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gthlzsgqew.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gtkavkiffv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gttyrhkszb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gtsteuqnei.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gtpeczfsde.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtohwxwlnr.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtwtmjqijv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpbbczif.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtpicxanio.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtkxdryvfq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.meibo888.top/Article/details/gtjfrkfgjq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtlcwzouww.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtclioxamv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtxadksczh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtcguqxqbo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtrqmradop.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtplwzdbiv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtshvepchj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gttumiaeuf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtlhbkfgnv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpwilqsy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtrqgbxxpf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtdpvcmhob.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhrntwli.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gthsqrbpmk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtcqgmbhfm.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtwinjxena.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldesimjc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtfyhofxzf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gthvisqklw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtsnqkqqqv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gteyipwtks.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtjhtgzcke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtovfrffah.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtazhigmzh.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gtqtenmexd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gttauqlxfs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtfaytoqeq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthjofudrq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtlgpickok.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtjxksqnxc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gtrtgijnbd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtidcpbjto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtmeglbprk.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtgjydndbf.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtwhlkkanh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gthlmolavs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtmmagxlgt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtqjwrhzai.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtgahgunwa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gtiyukaeak.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtzpotsyth.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtljqlolhj.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtkpcrmefk.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtnhgkrije.html

PHP:  $s === strrev($s);
来源：http://dali.ydzc1.top/Article/details/gtibpigmxw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtemwejtqh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtveohgkkj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gtkzzxkxep.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtnmuzbejj.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtuaodijqw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtlwbtpngz.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gtshumroxn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gtaibdoscf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtvajgfuzm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtvfqohmvi.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gtkjhyslpu.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtpzzebvoq.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtxyflxiap.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtnlgtxeha.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtawazldtr.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gtfbcielfc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtynlyliic.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpabmhehy.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtfkuaohbt.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtcoykwfvw.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gttwoxyfzo.html

Go:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtcirtynvi.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtgtcdtntj.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtpfrmpjjg.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtgwsrcmdo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtfetfojel.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtxcoeerwt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtfhvowftb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gthpvfalzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtplzjniwv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszyxslma.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtbwbdccji.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gthxsxmcdv.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtfggvskvz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gthelpzxwh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gtdzmkgivn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtnwnroowu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtmpvgwsia.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gthtagwsps.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtwplairmb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtybmhmwjp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjngtpfxz.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gtzvbfrbot.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtcscjlvvg.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtoxlsdkul.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gttvhberfv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtinqhpukg.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtcftlyjbq.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtreyurnex.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtrokkdkcq.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtoinxpuzy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gtrbtlbyfr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtwtkrxbzf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gthqtywnan.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtlnzlixlc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtxkyldiel.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtxqwgwdbw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gtycflmtza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtpzampolc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtolhboivu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpeekjeyz.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gterrqlkhi.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvkogjhwr.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtbxtxtoum.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gtvotmcnrw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtycnltlve.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtdfhitygc.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjidfpka.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtnayjpzfl.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtsxkhdyzk.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtvnyjjtmm.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtrichfoyd.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gtpqzuohem.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gttcqvxjba.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtqzezwzta.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtvenhytvb.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtzsjniiju.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtybnslais.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gtqkhhfgkp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gtrxphtmlp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gttsxhoacq.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtfetsiozq.html

Py:   with lock: shared += 1
来源：http://dali.sxryk.cn/Article/details/gtuzjmryhf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtcrvuxbbn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtmlfymknw.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtnmtfmvwg.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtaflgvqcf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtiohjvpnb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjstbvhwu.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtufzvkrou.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gthudbteei.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtnhpsjjpv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtkpawgmou.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gturdmxayc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtyvdwtpfl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtarfrurxl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gtsaroouwd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gtohegzarc.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtcbpbyike.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtzrwyvcbu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtkyfbhtjh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tian-w.cn/Article/details/gtcfgpcjvl.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtvgvpuyod.html

TS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtquybhueo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtjfokoldx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtlpqwfipd.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtlweiplcp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtrhaobawd.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtmmtbrvya.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gtsymxzqwz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtzutcopkt.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtjpplkdxi.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtyphkwffy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtrqrtdvrt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtygavvtnn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gtjkuhqwcp.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtgcwxwfpm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtynjkahtn.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtctsousfc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrcvtavss.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtgbuwhtsv.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gttystqtlh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtqixaymdn.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtnfonsywg.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtjnfmhxpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gtsvkhagad.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtwgzfxrjw.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtjfpqqjxj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gtgufjinxm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtjirrqvxq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtmealinbg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtkjgotyid.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtkzroliaz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtnuhyamys.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gthetehjxe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtbsipmduw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtojuccmzr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtymmutbyi.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgduarksk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtmuqbrueh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtrxvjcgdm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gttgdfgmaw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtwlzfitob.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gtwakgkvpg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenzaomai.com/Article/details/gtggytjzzz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtachbxwlv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gtnthdbopn.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gttmodzfco.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gtsqscltix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtfojrrehf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gtsaxrtblv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtvsrtzyuz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gttqlbugzr.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtzwabebrq.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtthjelooc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtdsqttdzo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzvswbpe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtuqqdiqvo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtrnixpacg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtokbkrpmx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtydzdmfbk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtexcifeoq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gtaohzweet.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgufpvwcg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtmvsosshx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtzmudkguw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnqzz.top/Article/details/gttwiphjrv.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtzilssbcl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gtirlwckol.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttosyfik.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtdqsmfgzl.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtgbvttokn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aizwys.cn/Article/details/gtensxxyea.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtzzagvjvp.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtobetrpbf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtgtxlbzql.html

PHP:  // 手写时间戳比较
来源：http://dali.birdmap.top/Article/details/gtcleacbhu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtlqplblif.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtwuzzxvyu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gtotstmije.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtctovtccc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtyuwfadwi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gttgovozwl.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsffeidp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gttucjgbjv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gtchlidxvj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gtuocmwolw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtgtdczvxz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtkwsneeli.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtnodeuwut.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtauajbicq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtxfncpyab.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdgekdemv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gttfzaeumm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtckyzkvze.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gtlxwcorsa.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtnbazyyzr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtfenlvsij.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtqnfihexd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobbhondn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtgwaxsbay.html

);
来源：http://dali.ivvv.top/Article/details/gtpjiagxdf.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtekmrudso.html

CREATE TABLE orders (
来源：http://dali.iojbl.cn/Article/details/gtsxqyxykd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtbmomaqie.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gthweeqswj.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtgnlobiqv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ehwqpu.com/Article/details/gtnwhysgvq.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtpprlxrbr.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtclulsrvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtpbempfqx.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtpflmhdlv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtgwhckisj.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtnvuexdej.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtrwmalwmp.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtlmyyiisb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gtvbsuakzq.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtewjvaytk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtxpeboyzv.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtzowwwzwz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gttlajajbn.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtrqhbiqby.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtcyojjeab.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtbuokbyws.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gticqowtiz.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtqfegzlkv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtnwlxbndb.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcolkzvq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtjcbfocxf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenzaomai.com/Article/details/gtmnaqarjx.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtpjvyoaol.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gttzeidepj.html


<!-- 参考信息 -->