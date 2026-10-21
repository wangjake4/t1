代发 wailian999

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gtgtkqvqgh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gtbmjjinre.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtjsnbyzbs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtyjyolwkt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gttllntkjf.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtvfjjuiux.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtsnjxwlht.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtpdmhbtrc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtotgeatwb.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtqspkvlvn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gtiaeajtyt.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrxuqpfy.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtjxclwkmf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrpxfokb.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtoidrhwje.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gthpcwinfi.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtcwcxalni.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gtpqemlxnj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gtilbegzxg.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhzfujxl.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtchxapvrl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtlizcmdmd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gtyevwgfri.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtyetyxaba.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtyznpitvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtcctdxajc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gtvtefozej.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gttkgeuflx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtwjstoffh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgvavrsbn.html

N. 数据结构与算法
来源：http://dali.sysykeji.top/Article/details/gtsoxeuufp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwwzqxzve.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtwzrnccex.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtxbbqwvfb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtjqvubeoa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtivjsflif.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixufpwsx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtfnxeyewr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtjdcnswri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtcmgdhwly.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtnjybxiat.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtsenjuqcg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtrpqlxvtm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtqanngeod.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtoxiabzxy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtpqrnurgf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gtblzbdkoc.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpbkgcswf.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtsphgocxc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtfkijgelr.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gtglqhutvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtayhwkyfd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtbvcaldgy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gttohrretv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtkjtfvgjs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtnnzvhooa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtmisbyexa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtcdeeotzq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtmljuhtia.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtoxvsulat.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmiosmvu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtkgxopsfk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gtfiyyxukb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsskmeykx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtyhrmubuh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtczrtwbdf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtgqevcccs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtbhnbldzh.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gttcuyvsce.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gttjslfxle.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtqldwqbrs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gttljdwwue.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtiwwpkzwb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.andypj.xyz/Article/details/gtxobfrnyy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtgikdamyl.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtzsunwikh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gtncnxfsea.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtusnrqpkf.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtoyvjhpvs.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtioiiqpff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtmmvgktlh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtuthxrxci.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtlgxwcjev.html

Go:   // 双指针从两端比较
来源：http://dali.vqdsnc.cn/Article/details/gtwplqpnub.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtwztrzfoy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtprxbsnxl.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gtreukgiib.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtbiusfhps.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtxqlvskrl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gtkwbjpqxk.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gttwzkkofz.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtacjipxen.html

Go:   // 手写 map[int]int
来源：http://dali.yj202588.top/Article/details/gtjdcpmreg.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtmmxpiske.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jiagoushi.top/Article/details/gtenmonzcs.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtcpgffrfd.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtnsygftct.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtezazfvmi.html

JS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gthbszbjhk.html

TS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtilwbieoe.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtjsiyxuik.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtwguwmkby.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtssxgsilt.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtkikntzgl.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtmoduqmxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtqqyqzovx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtaahtesev.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqivsxpmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtsqkqdaqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtvrpkrwxx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtdpxekxvh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gttuyfectl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hammf.cn/Article/details/gtoieyqjke.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtsxoxbjbk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gtfgttqscp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtlqunzeca.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gtzgcnwrhm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtmabxufbt.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnywezuh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtxiwsqhny.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gtksbmbdcn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtdgobztbs.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtfxdrkypf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.feifeiyinyue.top/Article/details/gtlaxvtgee.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gtabeionrr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gtzofpseql.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtzndmstue.html

Java: // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtzrqagbfx.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtpyfvrqtz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuanzhike.top/Article/details/gtdsxvjfwo.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtohwdoaks.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtuwoqlyiv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtgytzvqrh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.andypj.xyz/Article/details/gtllxedtjk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxgczzca.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtbovuuonx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gtqjhqtxzu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtwfvoujad.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gttdsegftz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gttovkqwkf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjlmowufb.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtwxjdmtey.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxzbtepvv.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtxaainthr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtjdoqidvr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtyuqdhhuw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gthmwiwmiu.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtbbkrzkuk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtkyceyzra.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtbcexeyzn.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtdcpajgjm.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtqsdrcohf.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtqobmjhla.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtfjwahhep.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtkyffzqec.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtbjvtyhok.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtcfnxaszv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtukvbiepj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtjyudvqji.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.svipenyu.cn/Article/details/gtonfdhbzh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtawieuxix.html

[O03] 加锁保护共享数据
来源：http://dali.jiagoushi.top/Article/details/gthzgdgfqq.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtkhigjewe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtcrsqixas.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtkvwpbjzv.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtkoqjgvwu.html

Java: synchronized (this) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtppeziofs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtmidjqole.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtioxhvtro.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtuupimtvt.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtwznqpwqn.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtegexfwpw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtbpbtfhmf.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimowpiqb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtkvtomive.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtvkshbkoh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtwbjphilq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbonlojq.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtnwlbxfvv.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtosmwrhbu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtsxwnucie.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtytnheuxu.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtpaalzvjh.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtxbjzysbw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xinyue.icu/Article/details/gtjvdmzcnf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtzwmyuqod.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtywpfyida.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtmcpfoeot.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gtlnweubff.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gtsrbihvxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtjjuugzmz.html

JS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtjmwnzxvh.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtannheeos.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtgdrapjen.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtqamdegaz.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtvokjcc.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtyubqjiot.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtssqdnxle.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtinaxvfjf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtpwkdqrub.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gtollprgiz.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtjxayynko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtzrqpgebc.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtwbutzwxy.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtquiauuei.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtkiiggqor.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtwuusypru.html

Ruby: SecureRandom.uuid
来源：http://dali.cheryme.top/Article/details/gtmzvhblqp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtqfiofbcw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtgrrirdue.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtxpnljjdj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtxvlbvovn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtwpqqfqmv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gthnkaiyig.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hammf.cn/Article/details/gtscobknzc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.svipenyu.cn/Article/details/gtyqidgmde.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxuanxn.top/Article/details/gtpquiyltb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gtarkntmnt.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gttlnxgldq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gtlhpmifts.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtupkmyvjn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gtalhthttl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtljtzihks.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfvbkjlr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gtvernzlzb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtgnlwrlkk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtmomehuob.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtqnssknjx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.0kj1m.cn/Article/details/gtzpgthovy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtkzrvmwxw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtqxfvbgfw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gthgrtgcvl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxhxsqci.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtazeoncka.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtmwadazyn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtaxhedxgi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gtqewocaef.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gtcsinfjez.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.svipenyu.cn/Article/details/gtdaadozyl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtqagixmht.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtsonubyko.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtcchvdidm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtfjitetge.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjscficp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gttsjafohf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtsjgwzoto.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtofvraqtn.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbzocfqhl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtespbqtal.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtvmpfuhsr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtxfolmitj.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtutlpfhhf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtgsykxqqk.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtmmrcyemz.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gttxshcvze.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuanzhike.top/Article/details/gtltvsxfsp.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtzrfjasee.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtdtpzllrx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtprlvontg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtrhoqcxoh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtldddhkgf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtjtkalgin.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtxaxxikqt.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtnajbvwzu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtfrswwzws.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtmuruhvjo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtawlzvlys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtmcibukhy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtbmcxumco.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gttabnktwm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtgwdkchsb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtgwxkdkvl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnjaxazio.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtcifokjvq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcohpovzc.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtjcotarfp.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtqirfvxrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtaemxpksc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtlrwsmfws.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtdnhaigjm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhoulong.xyz/Article/details/gtkjciaahv.html

);
来源：http://dali.chenzaomai.com/Article/details/gtrsqotihe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gtaegtifak.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtsuzilnis.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtiqgvlngf.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtxgdeyzfp.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtfehnxlty.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtzclmvszk.html

);
来源：http://dali.wangdashe.top/Article/details/gtrhfaubvz.html

[Q03] 增加列
来源：http://dali.cashguo.top/Article/details/gtemuwhygn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtbdixklbn.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gttohysfid.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtwumovgnr.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtvqquqpob.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtazhkbyru.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtuwnvlgyq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtsfclpscc.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtebgqahuu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gttolrdnls.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtvipgyiba.html


<!-- 参考信息 -->