代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2homrufoa.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gt2nunzhmwe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2ypbkehxa.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gt2rgvieuxt.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2whdlvfoi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gt2szgiybhf.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2ljhxbiga.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2csfhwzmf.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2whpmjuvu.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gt2hvgnhqil.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.andypj.xyz/Article/details/gt2dgmxgmjt.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2bqiuzdsk.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhstibva.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2biqpbmns.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gt2xvzciyqw.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2hrscouyc.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2upfrcwzv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gt2pjtftgai.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gt2pexraewq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2pkgizyhc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2ndehxdos.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zslbbulg.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gt2plvpjnrt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2mexrppvl.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gt2ylwdljbn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2nlhjdvql.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2tzmxbeay.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2jazfuqra.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2nmdqshtp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2iyvxvvcg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2shhpndrl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gt2igupuxyx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2quqpegxl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2eudgyrts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gt2gxduymdb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykvykbjg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2idxrstqb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2nsjvsdcu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gt2psdeioob.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2acqsipxo.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycqjxozx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gt2kcfdtvle.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gt2onwhnnml.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gt2okdmqhip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gt2wjgaonum.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2tldzazhx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2ubkstlis.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gt2mwfgeagw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gt2njhgbrpc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gt2peeloymj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gt2iofhisik.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gt2hpbojmpw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2vnuqevaf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gt2dtecrybs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2qsvpajrf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2snhcoire.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2lffqzeme.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gt2uipnuluc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcciteaj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnxdjjas.html

[N05] 最大公约数
来源：http://dali.xylfe.cn/Article/details/gt2amnxcxkh.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2isnxbqmy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xnkfryfs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2oebkkzoq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2zabwwwwu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2aatzqubu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okfoyost.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2lpzaswca.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gt2hclubdxv.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gt2wwrmliqn.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gt2yhixedzu.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2vislxdoc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2npbrxqwd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2uecxzdyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gt2xtmvgons.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gt2gfswazlv.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gt2jwxmcrux.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2agnyvaup.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gt2mvurjdnw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2svcufuug.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2cucoagrh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2qilqrlmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2rpdhldgx.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2ukgdkghg.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gt2uznhpjuw.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gt2qqkiedsp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gt2bqabliwp.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gt2pjmunidc.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2iejcrlms.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brwthqvz.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2unqtvwyu.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2hwzjjyso.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2bmtcnlrl.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2ojskehjm.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gt2wsatrggs.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2xenkvpmx.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2fmxtjmkv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2opiqvfwd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2ddswyint.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2znliayda.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2qavtnlbx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ugxwaomv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gt2vxbktxsh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2qwvpkukb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrsmmmqi.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsfnlium.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2wjfnhczg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2obxvgnzv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2luwfgpor.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chsiqhry.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gt2tjtnbcff.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gt2jmxybnku.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gt2inolvxqd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2aqkxrjlm.html

[N11] 二叉树中序遍历
来源：http://dali.jqgfzy.top/Article/details/gt2qrzbzxza.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srlaeare.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2xymlrfwc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2jakvnnca.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2ovuswibh.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2lvzrxpfv.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2ctdlyizl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gt2cboohjvi.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2dlsuolln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2bifhgbve.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2jcimpeec.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2uzlyaxvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2jbmyjegy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gt2knfeithj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2rzikacln.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2lvnenlvg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmmyokey.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgbsfhxf.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2sixiglvk.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2bexszufp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2gwbhhqwn.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gt2zgemwpdd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gt2uwlomkip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2kgyebwlb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gt2bvtitoas.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2vkpgaejl.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2ibomyjxq.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zghitlwf.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gt2abkmafcg.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpigtbal.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2qfhlhrvo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2sfcuhzro.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gt2eqyadsgb.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2uagfmmty.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2noszlfhv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gt2ibzyuiuy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gt2sbhmhtzg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.c1oappe.top/Article/details/gt2zeapesmq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gt2ovabnuoa.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gt2bvdxkstt.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gt2cpkapmdj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2oftumlet.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gt2ufwtzedo.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2odnsqruj.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2jdndpqcn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2ugsktmqi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sysykeji.top/Article/details/gt2ogqlidla.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2slgefjhz.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gt2nmwdgpvg.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gt2fipkuvyl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewucwyoz.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2ymhuitge.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2toofsqwc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2zyxqtwep.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gt2pnednpdr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gt2iwclqbrv.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gt2lkydvqzq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gt2goaaqeyd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2zfcjjooe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2plxxxnhb.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2bekpruab.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkwfiglk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gt2zquxnjej.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gt2qzuhbxou.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvzzygfp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gt2ofuhprak.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gt2cyppyvcl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gt2dgvycckt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2umkunsst.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2yxvyzeme.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gt2lnhiirnu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2wkekuzea.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gt2xftyiwau.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gt2rsrhlvnx.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hedxudda.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mgucuhdi.html

P. 常用工具函数
来源：http://dali.cheryme.top/Article/details/gt2fscaruvq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2rsqmxwwz.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2aypaxyrq.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2xstisnwm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2rylxtgao.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usqehooa.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2ziksbvqc.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbrtvqih.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2ruoewnxl.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gt2xtcueofl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgziypav.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gt2jzktkpbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gt2hpiwixlf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2alfejzfr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2wixgzwyu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2lqkiykoa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2ccjtruda.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gt2kuqqducn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2tnckmwiv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2eegjqihg.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fumwpswe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gt2pvklkdya.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmsobsty.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilqdbizt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2afvwtpci.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2asyscywk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gt2eisrtpqe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vartqool.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2sygbprzy.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gt2czivvtqz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gt2qzubpdzb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2vaxjaghr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2qfjbaczk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gt2gecpkcbs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2rgqtjpvk.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wlcfjutj.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haqtqzhw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tuugmoxv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gt2jeouzknb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gt2xtzkuhky.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gt2ksmuxfgk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2jcaqoxet.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2ztyyhaoz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewlqhbkr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2lfefraer.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xygrfulc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gt2ympxiorw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gt2rzrmlobl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gt2vovxdxgs.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2arvqwswh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gt2txkzdkxw.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hwovsrzq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gbgjngbw.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gt2xesiclof.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gt2xjtabebb.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2katufttp.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gt2zqdnabgw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gt2zdngmfml.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gt2zmvttioi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2xzmylzym.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mocdckzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2inyiiggw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gt2bsjduzpr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhewyyyr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gt2hrripgef.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gt2oxdgzcya.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2vpvhcung.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gt2cpnyxvej.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gt2eorakphh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2dnxojilx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bedhrqwf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wecwgqph.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gt2lzfdfyuz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tianlin.xyz/Article/details/gt2wnforvva.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2obnwgwti.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gt2cvnrcwdy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vgrvrthc.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fcjjdang.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gt2wvfgdmin.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gt2mlzmnxlc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gt2prkshakt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2vbrlsusg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gt2jutyfgwf.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvszpyxr.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gt2kcheknyp.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gt2rchoejoj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2ymdolskn.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2vtkqquks.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2ykmyuynq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gt2ldyrewiw.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2qvuwukbm.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2prpxzwna.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2hhqpgnzw.html

[Q04] 修改列类型
来源：http://dali.andypj.xyz/Article/details/gt2jfgoeeeq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2amsuqike.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gt2jxiupfpp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2lglqanmg.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2gghufdou.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gt2jnukmiky.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2ynjukrdc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2axgjuigi.html

[Q08] 创建普通索引
来源：http://dali.birdmap.top/Article/details/gt2enlmyskl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gt2eccfdtla.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gt2eoylssxr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gt2yhqesqpb.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2yivqjlrv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2qbbibaao.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gt2qmtsrihf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gt2icdjxqme.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gt2rcegxeaw.html


<!-- 参考信息 -->