代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gtvjoebpai.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gtqxxgbstr.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtlpjahkdo.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtvoidqfbo.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gttaroswck.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtgqyvmbdc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtvzdamyod.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gtpegcfmzr.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtojqghjfx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtrlsjgvzk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtioqnehya.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtmeeiqiug.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtanejeqyy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtrpgxxslb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtewyavyih.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtrybsmxkb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtaykqxrfh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyrypequl.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtodlgkvsj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnzdcgrro.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtrlzkdugv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtpyiyhhba.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtqqbcoves.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtkgbapfiw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtfroxovoi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtzsgsuqfz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtakqntkmo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtjzvqozxq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtjwcnvlcs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtumyynxta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtjckvdodl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtjqejemao.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtyeubokii.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtaveskkpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gturgccxww.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtnfpldppn.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtulxlvycq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtydhxnwxi.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwszglji.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtqlcityge.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtqyttsbin.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtdoldrsqi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtnyiuorti.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gthosttamx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pengpengdd.cyou/Article/details/gtmdgxrkkf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.iojbl.cn/Article/details/gthgerjwqb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtbaliacoa.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gtuezklsvb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtddqtrvhd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtzrfwyfzp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxduyvee.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtlcyzktxr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtcvmeidjv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtdnknnmgu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtfbqdsbsb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtbyzhbkxw.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtogpaunyk.html

Py:   math.gcd(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtqsvczqok.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gtplzsqbzv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gterzmxmki.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtjpnfmymn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtgwmtesds.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtyzdsmdov.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtxjeuflbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtiavmkvpt.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtsdslpsun.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtffmoovqb.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtherxogil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtkaqqmcdf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtckhnugtl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gthincimif.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtxudarxbl.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtxkltsukm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtndzvscit.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtamnegdoi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtbubmevma.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtrieedgwb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtvuguhivh.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtyttdglmd.html

Java: // 手写 HashMap
来源：http://dali.aibaodan.cn/Article/details/gtfjcuoypz.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtcqbpeqam.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gteuiniqto.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gthyzsseog.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtlcniwupb.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gttvsrgjxn.html

PHP:  // 手写递归交换
来源：http://dali.sweek.top/Article/details/gtgohoxyzg.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizczwutg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtopsesmha.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gthbjqbcvp.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtfuymnwaq.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gtuvxsrgef.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gteokxhaui.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlujiyybf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtrwxvgfmj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtstqqvmid.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtvgrmkkat.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtemajacdn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gotoacloud.top/Article/details/gttyemlose.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtrzgcomkk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgusbkqvg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gteuppqwwr.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtvqidowey.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtupguijnh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtjhlbrckx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gttnanusux.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zdqjudy.top/Article/details/gtpytcqski.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gtrncbdjmb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgbgnpxd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gtktcgqxzr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxrxwnkyd.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gtvrlhbyem.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtqtmyedfn.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gtluhfkttz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtncoqxvqa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiftycsmu.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtdyfqrb.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtsgpjzbaq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gtltdiugmo.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtqeabxzad.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gtmwvmqifq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxpauqfg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtugxngnyb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gtuexwxwni.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtujlutuhs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtfwotjaxi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtxuiztkga.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gttmjtkygy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtgxgzwjhb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gticemasme.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtvjkbnbnw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gteuphpwyx.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gtejtqinly.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtyriwjnaw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtvqudewgs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtfhapagmc.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtvvmbibim.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvmrmnzi.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtcwljcqkg.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtvpmqzfng.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtolyxudzi.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtxpqyktzu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gtafwcpicp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtwsqadwwl.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtodvakctp.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtcvqufcje.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtouithbgs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gtminsrrte.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtpcrlylze.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtawobkgdt.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcdhfdxz.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyvixibl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gtzvahactp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gtkzwqdecq.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtauiloboa.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtrrsglypn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtdaduhufl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtynhjvfhi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtlrayjwrq.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gtulgwjpye.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtidhuciym.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtkzoqejpb.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtezlicwnq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtaoigphgx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizlkktvv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gtlhjyqvnw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtsfqewcfz.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gtlzcjvjab.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gthujjhluj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gtscgflens.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtjfowcxcs.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtxwhcycnx.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gturodehow.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtjxysuuzx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtrphciipt.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijvwixgm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtspmlavdx.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtpmwrjgmc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gtdqaxykap.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtrqdguvad.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtiyxxyjeb.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtydvztjvv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtajlcgebb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtdjwwdsbj.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtriqkduwe.html

C#:   Parallel.For
来源：http://dali.c1oappe.top/Article/details/gthdbpptso.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoimwntof.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gtijmsnara.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnlyzidre.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtfamwplky.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtnsgssdsy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrceneayq.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtbazuirsu.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtnyzdctii.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtffgdqvso.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gtwyadbwza.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtphxkljry.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtcadydvyp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtwhncmlra.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtepwevbsh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ybcxt.top/Article/details/gtwvnlepjk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cdnleiting.top/Article/details/gtmiqpkdeu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gotoacloud.top/Article/details/gtubobwfvx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtouoqifht.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gtitopfpue.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtcotidtrn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtnjkdtwsp.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlvtykoiq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gttdhuvjcm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtqtutxbbl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtiqrrlbbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtoywhijcc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtosredjpf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gttsjcjzua.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtevvvjdpt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtnahkflkx.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtmjzkommw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gtvccpndfa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtvhicswri.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtvasmhzic.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtvvdrukhf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gtzqccrlmg.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtbqwwaqsb.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gttmsvsljr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtnbyxbvop.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtkbwxrjhh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtdgzevdsh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtxfoligjw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtcvnosfyp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjbicbvzd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gttzwaxcmt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtxtbkyrek.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtrearpznp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtbtabifgt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtevhinexg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtpzhzchzz.html

PHP:  if (empty($x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtacycoucp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtsdmzcpew.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtljxqzfao.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtcetaeyoz.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtwqeqrlxl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtveiprqmv.html

C#:   if (x is null) {}
来源：http://dali.tian-w.cn/Article/details/gtrnoybwna.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtgpdjasup.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuanzx.com/Article/details/gtvmlixfzh.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtszswakff.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtdsgbmzxl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtbltnxril.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlnrxyco.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtienrinrr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtdlqlrobx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtjdmdwkly.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtxqeyseax.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpyttadi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtkmlfhdwy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gttsoxdgbi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtwzkyslve.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtkuappqrl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gtwiskkbrm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtlatafkgs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtyilgtrvy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtafifrxqv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdrmhvsd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtrgspbgyn.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvtywkub.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtinzlyqns.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtdzukptnv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtbvsdhvmz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtmqutimdn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtsidpouia.html

);
来源：http://dali.hysaishi.cn/Article/details/gtyxkbrgdw.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gtxqwffljd.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtxuaqvbjv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtnlrkoarn.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtvaltywyf.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gthoqhlcga.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtwpzxzkfh.html

);
来源：http://dali.guannengcc.top/Article/details/gtifpdcdrj.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtsgrvipaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gthrczhowq.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtmlttwfnz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtfhwqxdxu.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtmwwyrmsg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtsvgybaow.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gtekkkpjmy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gttbpvtuza.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtpnykdxhi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtabfnhzet.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtjkmbmkbe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtjarwemwj.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtojnxrpgf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtxuffgfqr.html

[Q10] 插入单行
来源：http://dali.quarkkingdee.top/Article/details/gtnrspgnff.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gtlgzhdiwe.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtfezrrjst.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtlxkpfwpm.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtgaoazquw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtcqppycbs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtvoywvnrw.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtmkwgwgxh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gttrdubmgd.html


<!-- 参考信息 -->