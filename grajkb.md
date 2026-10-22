代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihdoqphb.html

JS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2vosjjcps.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2xvgjxgqi.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvuirpzs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gt2xcqoulby.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gt2xhbtrbgx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oaivcild.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2juavumos.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2bycpvtmy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2whyfefak.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uerjepzw.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2uemcztaw.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2xotvvtlq.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyhdjuvr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gt2ysmrcwvv.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2gexmkxvf.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gt2funjivdl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2ulyyymqf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jyoumei.cn/Article/details/gt2rqxncxlv.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2kjllmjpj.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdnqasfj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2xvsdvimv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2oimdaxsb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gt2npjddwtz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gt2pyfjzzyn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jfdnilqh.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gt2nwyoslsh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ckezcxod.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gt2bhdfvdan.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2kxcftaoa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2xwhznqtv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2wdkekmkg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2zrtnjxed.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2jubmupgu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2macdxefw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gt2tfwhkqxo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2aeeakeck.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gt2ykvztzgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gt2imqvwkgm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2hyorpkya.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2gskaifpn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2zbldbjha.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gt2fvqfuqqx.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ojskbtti.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2fpfvulrf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gt2wrxbzhkh.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2ferfgbdr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2wbcmdipl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gt2wfrrtnwd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2pyprgbdc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2khbimyve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2tvwiwiqn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rojmjyts.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gt2wcgbdoff.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2xrmyitsl.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gt2xkvjubfq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2vaqzqcqx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcvfnhix.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2vckwfyop.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2llpeqsrf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2gkbduclq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daria6918.cn/Article/details/gt2svginhuz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2gnrtpjtg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2icwjucls.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gt2pvzngdms.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2rleqhwbc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gt2uzwroaig.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2lcxshmth.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2qagsvbmu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2nvxejycb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2dzfckwph.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gt2kovzkwoy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2aqktwjnv.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2fedigmzy.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2xudaokwr.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gt2hlktjocg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2ewaxogjq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2nrtqvqbz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2ygnsdnnf.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxpqhqwy.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2tensnswq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2ffjnofwa.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gt2xutuhjeq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gt2ufuszqta.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2pohmqpca.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2hxdnwwnt.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2ctzvqqkf.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gt2zoxydxsu.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2lntjteob.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2fcuungpc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2yakuncvl.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gt2khzcbxmj.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gt2cilutggw.html

PHP:  // 手写递归交换
来源：http://dali.yongpay.top/Article/details/gt2kgzzfrix.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2nfuyrjuc.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2motwpixp.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2dwlvxnjg.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2vfvbiawj.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2rcmxxrmn.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2whanjude.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gt2vldcmhlv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gt2vifehanw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2toehkajr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2ftbovuss.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gt2zypfsody.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gt2teerltum.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gt2maqyipro.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gt2vpwjjili.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gt2fiuubrbv.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2uhgiaawo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nymhqlqp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gt2vucbqtsu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2vverydzv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccmcfyvm.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gt2ewdbkesp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gt2ugzgcjen.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2tdaeqbdu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gt2sldfitma.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2ulgfdmwj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gt2dlemyvkf.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2vnqtgngn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gt2pgmndgqo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2agekinyc.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2webiajse.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2oobdjinh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gt2rmzqjrul.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2kmlxanuj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shzxlz.cn/Article/details/gt2gvgojztp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258888.top/Article/details/gt2jgrwibrw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzzrqpkj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gt2rmcvwive.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2fqhzolfp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gt2egvhrzmm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gt2uhrpthlq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2nvmbpkvh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2amlcopbc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ogivxfzu.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2msnevsjd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2nnsqvzdt.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqkfecrp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gt2ghacxqzn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuanzhike.top/Article/details/gt2ljyhqtpc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gt2peixbgbu.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gt2wlkibzcb.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2egujokpb.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gt2qxieqryc.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdzjaftm.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2jdpguevl.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gt2xlekskls.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jianghu66.top/Article/details/gt2kidvldeg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gt2najheicf.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2ohebgxdc.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2ujmnntwf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gt2jfbuvqiy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2fjbxinyj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjuvfla.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfspunzw.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gt2utzelsfg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbznhqah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gt2mlighkxr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gt2eldbsncf.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gt2qvqmzygy.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2zbhetugf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2dkfalubu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2chlvnqam.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gt2kmqcbjfu.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gt2rllfnink.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2alihdegz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxdiekpg.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gt2issjmeqy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2zcfzcxwe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gt2abtlrwxr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gt2ayvckqns.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gt2dmossquc.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2okwgmeku.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnxiangtu.top/Article/details/gt2zrozqwtf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obraawxe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2acffzcei.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2xejewmns.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gt2uyeajjfu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2rlqgfiay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmjvfcaw.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2hrxhtuew.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gt2jrqyuryl.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gt2gqqbktqf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gt2qzictdfc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gt2eljhcjyy.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2ylsljbgq.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gt2bdqzbnqf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2xaqwbrkp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gt2gbryglxb.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htxnqxqz.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gt2uxbuynqx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbtuyoly.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2kvuoqeod.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okbbsxgj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2crklhffs.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gt2dicwssxm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2qffpapkv.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyocsrmq.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2aglaancl.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gt2poeekond.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikvlcmef.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gt2fmegvdjl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gt2ujzlmijh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2btyntxqx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gt2jsiexgbx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gt2jfhfwrno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gt2orswrhit.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gt2ygbqxdec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2mhdloeqp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gt2mmcxgtpo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2dtykubrg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2qqcvqifa.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gt2vjohekga.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gt2riwfuhaj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkwitkwx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpyrhrpz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2kzmteyua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2qwheeqvq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gt2qpqdfnsk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2luoxbaud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gt2aalvgfpq.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gt2uksiplme.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gt2xgnxnnsc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2ltxhawzy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfnmujgj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2xfroumfb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2wridqrpc.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gt2yyjerifd.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gt2ngkbdczm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2jzscelrp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kivygjpi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gt2oqgcvwlq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gt2wfddwasd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gt2ceemsefv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gt2zswmziqn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2kvidecan.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cheryme.top/Article/details/gt2lfsydipc.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gt2pmussbmi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tanke756.top/Article/details/gt2bmffonly.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gt2akjdhxxd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gt2jlqsxujb.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gt2fkknkswq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2xevtlxwg.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjtkmxpx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2bspbedtt.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trzeiaja.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayvpowjy.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gt2qkfamche.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gt2xorzjcuv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gt2zzownfcj.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gt2fonypflj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2awftkwdp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2hsttznba.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2murtpheo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gaohongyu789.top/Article/details/gt2uzvdpite.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gt2geecjdpk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gt2gyptujdz.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gt2efezgfwl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gt2juuolpkc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gt2dssrjpem.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gt2swdfddbx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2vokammwj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gt2kugufdvn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2dzofrzdr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2gazptahx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gt2mapkpiiv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2kruussjb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gt2ozgteyfh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2lgfzvovx.html

[Q01] 创建表
来源：http://dali.jqgufenzy.top/Article/details/gt2wqyaysjk.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gt2ayuwgrvc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gt2vvqivahp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2clkslejj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gt2srjgxsux.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gt2hxoovkbg.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2esnajvvr.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2zdwvyygx.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gt2bqanrtbn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gt2ntuvepmw.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2jmklislb.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gt2zodhqsnn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwvlwewg.html

);
来源：http://dali.cheryme.top/Article/details/gt2ejagxjrb.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2prcytxtx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmmucija.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gt2vsyatlgz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2ehyvcpny.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gt2fracazbu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybpkifqf.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gt2abdzbfyl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivffnlkw.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gt2wnpvywzu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gt2xkisoyfk.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2laiwuiwc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2ojnhwnok.html

[Q09] 创建唯一索引
来源：http://dali.guowangkeji.top/Article/details/gt2ppjabelz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2nyiebmue.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gt2hzifcfeq.html


<!-- 参考信息 -->