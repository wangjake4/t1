代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbtzlemn.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gt2ryripcqw.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2krsnwwkp.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gt2eovenhrl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gt2jrllazpi.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2auzwmpaw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gt2unlxztvq.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2hsbnjlte.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2ypngzcnu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gt2wcxhubqw.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2dljoniay.html

TS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gt2ytacxjke.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2gbwozrvp.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2uziopnlt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gt2pmyslpgl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvzliat.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gt2owitjyer.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gt2pwkrexfa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpszouyf.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2jjqiqwns.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2wfibhots.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2jgpjzuhl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2ozzduvsu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2eljjrikv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2soicndvf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2plzubpsx.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krerrpwd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qnvmbxmu.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2nvlevnsb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2dgcyciso.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzzdmvvh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjfzaidl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2eygpzfeu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2kophvdnt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjudozsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2qdwwwzte.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gt2hedfwdqp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gt2cctymjiy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxdsbxon.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cashguo.top/Article/details/gt2qlfmdzlc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2kfhddiev.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2eouelgyg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2csbeecij.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2gcspvhpk.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2looljmfp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gt2ntdczreq.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcalrgqz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gt2mbheixtr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gt2jmfnrdsr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2nlpmueum.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2ggigcuff.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwcveucc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gt2bidpezcq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2nttqzgjr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sweek.top/Article/details/gt2yelguyih.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gt2lpcnyhxr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2wnutuhqx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.andypj.xyz/Article/details/gt2eooruttt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2ocgzlyvg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2dcctlyid.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2gsnuvfrd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigfzy.top/Article/details/gt2ecxavwkc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2gbfiutdc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gt2orgyfawq.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gt2voqiuqea.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2ncycmsio.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2ltfywfat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2dibkroqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2xfuzyooq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gt2jtizybwr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2rqdsmfbn.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gt2zukzuqyi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gt2anktiluu.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gt2qarzycsa.html

Py:   s == s[::-1]
来源：http://dali.guowangkeji.top/Article/details/gt2woswquvi.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gt2yunhzaiu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2xntebtzp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2lputxvke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gt2tsqejyys.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gt2golifftz.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2zwuxyzfa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gt2zptzxcsi.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gt2rvvgjpbp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gt2vfhcwcli.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2etjuovms.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gt2oixufymt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gt2yrmmrpmv.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdpfbqxy.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2hcegidjl.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2rsrqgvgx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gt2nfoustyo.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ncyljdod.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258.top/Article/details/gt2snjtzjkt.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gt2oeewmwjq.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2atwdqhyr.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2erdglnhm.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2pjlkoaqe.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2fzshosuj.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gt2pjtzzcaw.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2zzlboxce.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikkrxvzm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gt2rregpkfi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2xjukllkl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2lzzzdmvp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gt2dqirfblb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2lagippkw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gt2uessmdpt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gt2dyvketuk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2ryqefyoo.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gt2umgnbvnc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2tjvvckva.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gt2ywkuucxw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gt2hivhmyls.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugheawjj.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2lucjexge.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axbvpikc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gt2rvzrmgcg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gt2zwqbrfzv.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2lruucxjn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2dhdfxcng.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2abigdsjg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gt2oxsusrem.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2oohjgayw.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gt2kjctjrbf.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2tzwjgncz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gt2zzgkxazg.html

C#:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2etdxaqof.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2oerxuvyp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2bkuaplec.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wobkgnlh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2nvdnsilw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2bnzrnklt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryjqrvsn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2ubqdrzdn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gt2dhjqpxnl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2zmkmytng.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2tbunswfi.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gt2rnrgfscg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2rmcrzdhq.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gt2zsigldvh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gt2znqnwdyk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gt2zzqsvjvw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2laljhyyy.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2npgqxcur.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gt2wplpyevc.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2gpfxpfco.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2innolqbn.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gt2lzkympav.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcznxtba.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2eyaqlgkn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gt2gvwyhxqo.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2dqjtgnti.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2ucdzuzhd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2onsudwqu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gt2bmnolsvk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gt2pptlozkh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gt2yutonhev.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2ifgkbmon.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2dahxszyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gt2hizqtrmk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbknrquh.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2kukgmret.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2hexhwysc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2ngfecolg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2sgdqhbpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2owewsswm.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gt2vkajjfvt.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gt2nttowygp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2qugmjbvb.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2huqpysfh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2ybkrlzrf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gt2ocnjiidn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjoidbou.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gt2cvegunbj.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gt2reeirjod.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gt2izedbiot.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gt2sqmcwdxz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gt2tydrdtxi.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2kamfaslb.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2zqltuhem.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jianghu66.top/Article/details/gt2effcetwx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2bltyhmes.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2etaibvcu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2dmspcpba.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2eahnevmf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2bwzzhfnh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2athkseex.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2tawcfcxx.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2eosofkaz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2wacvbspk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.haohaochexian.top/Article/details/gt2aekxplya.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2xrrjhutm.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gt2fjuvmubd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2gdsizsnj.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2vnmjmqke.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2viftfymh.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2fdbpdhza.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gt2ymxbehnz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2fgsaapgl.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2nkuytcgc.html

TS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2cpdowqjf.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gt2dnyneosw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gt2cnakievo.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gt2imioburx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2fzdvrssa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gt2jewacbzq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gt2qjxvgstg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2ybsblrte.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gt2btpkffge.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gt2skitkoxe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gt2mactkhlg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvaqrtsi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2iseptvzy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gt2ermnmyoo.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckmqvrvx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigufen.top/Article/details/gt2caiyocua.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2zpngyujn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2ygutverc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2yordztch.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2txqwvslj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daxiang520.top/Article/details/gt2ybsdvcng.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2xliwrtic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2ubdvtfoz.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gt2yybjvuoh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gt2udahpdes.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2uquwsztk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2gdjkoxiv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gt2muwnjtfy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhrzqhwa.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gt2wzstarge.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gt2fyyaqsim.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2hbxmeshq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gt2vsjrmngs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2nvkgpyte.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gt2ivmblrht.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gt2vhhwzhmn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gt2kcbrjfhb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2eoznfxkz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2cblknjdn.html

Ruby: a == b
来源：http://dali.kuanghao11.cn/Article/details/gt2spqcjuji.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cfryoper.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gt2czvtqawv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gt2hfxahcrp.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gt2jhaqofhu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gt2oqpfwqeg.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xqftamch.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2wqqentpg.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gt2npvgibgt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gt2ngevqzju.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ejnhylvr.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gt2hpcyotic.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzbppqwo.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gt2ytlxpazp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2xjjujxnf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxcwcsjw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2dskfdnmi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2frgdesmw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2xfuoymfi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gt2trkmpmly.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gt2ihpzvyid.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gt2pnqgfvxl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2gzwjebnt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gt2jenrnbch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2hglksgss.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwvuuayw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gt2lhfsodav.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gt2uteckjsl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gt2gzwvrhsj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2djdllwvj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2whfpcvda.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdracayj.html

[Q01] 创建表
来源：http://dali.jqgfzy.top/Article/details/gt2cluxvoli.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gt2wbfefrii.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2ovwhlbto.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2jabvzpgq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gt2brwvqzsw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gt2zfaqissf.html

);
来源：http://dali.ydzc1.top/Article/details/gt2wnyzegfw.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gt2olwvaidq.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2dugjklxs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpfjyzsa.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2wojyacco.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gt2utublkhv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiahribd.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2dztvvkbe.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gt2cmzhdtzw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2luemhuiy.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryvwieel.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gt2apfgejwk.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2vliwvcwc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gt2vaisomul.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blpikbak.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gt2ogqqnryu.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gt2prnbthpr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2pgcbfvgm.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2cfkcehkc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2gusfgdsx.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2drsumoct.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbegckyd.html

[Q10] 插入单行
来源：http://dali.daxiang520.top/Article/details/gt2rueukrfw.html


<!-- 参考信息 -->