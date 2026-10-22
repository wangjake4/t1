代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gt2mfqwavzz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2guujknsx.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2imevviif.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2ourlnhmi.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2kghszmuc.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2rgvoarkz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2iecyrmvv.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2jeflxwhf.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gt2qeaukbyp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gt2sirbtqcc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gt2bnmlddno.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2mgmusjle.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2entoluxx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gt2wzsvuaoh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gt2vwtgswgn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jianghu66.top/Article/details/gt2hccggbnb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsmiccmk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ihzyhhgo.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gt2ugcgrmyi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkaljgzh.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gt2sjnakafl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2dhkwsvzg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2kykotagb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2thknmhgx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2tusbires.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2bfxzahbo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2kcyrimxr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.andypj.xyz/Article/details/gt2afqboqys.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2rpgzxhsm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gt2snhcxxeb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gt2yncfmnsu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gt2pyqrpguj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2krqrqvck.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2yuytygvk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gt2bnqlwwvg.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2svjplxsv.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2ensxjhti.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sxryk.cn/Article/details/gt2aexdbokh.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gt2imibcmjj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2kzujrams.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gt2sfgjjapo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2nnobvcfk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2imydgjln.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gt2ltefrjys.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gt2eibwhhvi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gt2ibdgxhoi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hysaishi.cn/Article/details/gt2dzyvkpba.html

[N04] 斐波那契数列
来源：http://dali.zdqjudy.top/Article/details/gt2hvrdppux.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2txyubnje.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2aqpxuyfa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2mtllbznv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2cxpbbcck.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2umniumvv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2mcobwlex.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2ddnkcitn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2gsvajqlq.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2epylizhi.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2sprdznrj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2kgrqkbhi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iybbeuql.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2gupiykzu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gt2ubexwwmi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gt2gyidzicx.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvcgowzu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2iseubqcz.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2vnzpynjm.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gt2vckrnhjl.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2prufppwc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2iqfpzxuv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2cubiqrxs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gt2vcequoya.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2bebwmrrc.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2qxwaelmb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kepqiixs.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gt2qpxgrbhn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2rpsfrcnt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gt2vsjzgzjb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gzhubu.top/Article/details/gt2vwaynkgz.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gt2fhaqiwah.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujdtechs.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inskjdws.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gt2znarphbu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgvnuezs.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2dhdsjvoz.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2uixpegku.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gt2gkmoylfs.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2gsdmvbzz.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2mhuyzqyb.html

Java: // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2vposanag.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2jdztvyvy.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2vwmwfabe.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2mxtronry.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2zmiryihl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2vjeyvcuh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2igffprkm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2zdcqebdw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2cheburtd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2xmkgnvla.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gt2sctnuvos.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2vjloehko.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2kiqqoywv.html

[N10] 链表节点定义
来源：http://dali.hysaishi.cn/Article/details/gt2jmdkivxt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gt2mujxeyhd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gt2zmqhieri.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gt2qnkfzhwk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ppjwa.cn/Article/details/gt2mtxjfdra.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sfxiguaw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gt2krximcsd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gt2qyjhqnda.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvinxtum.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2wpigxrnc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gt2kcoenzlt.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ebcehyrg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2dspiyuus.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gt2zolhvfrf.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gt2opxxgspi.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2xyjfkcut.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gt2blwaubam.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2nclbkswb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvixixkw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ppjwa.cn/Article/details/gt2oeyygwlz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2rslwkhkz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2wkzryoyt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gt2jswicjcc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2krlrwcnf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gt2xyawyixd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gt2kjykshdi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2cvzhjqmp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2tyxrwamy.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gt2dpswtpya.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2bougjkjz.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gt2yekvudxv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gt2zdlmdikh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2bjbhggmp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gt2vltznvwz.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2mxobhzps.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gt2onagnqfo.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhdbftbj.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsmllcsh.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2jepbwqpi.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gt2plmnjmqx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gt2uiymkpsk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gt2kmklnhjp.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2lpwejste.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvtqmkzb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gt2sbfoovef.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gt2wmykuuyj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gt2ymszcdkj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gt2hubsmxzj.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2ujcwwept.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gt2ruzuieqt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2zgewxtqb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2opefnswu.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ncwjurkt.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2dlocizye.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gt2xaxoqllb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2ctoyffwl.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2bsypkfia.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gt2tgmxshhr.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gt2lnmytwmb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2vpqzseoj.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2shujykgr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttsomgly.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2bksuhlsx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gt2rmjeoemn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gt2oshcorqn.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrbnnrqs.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gt2kpnaautv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gt2nrowqhbi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhongyouzk.top/Article/details/gt2vjfolvtt.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2mdomycug.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2fcxwseiv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gt2ngkpczrb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gt2svlmgscl.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2rdhuaqrv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyfctqg.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gt2ggnyysca.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2sfxcdnfv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gt2afskyopf.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2cvkdupap.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2mspxnjrm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gt2vdyyprvo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gt2oxuwzkyq.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gt2ekpdjpqw.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2fmpxanom.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ldeeodpk.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gt2riqwnvdw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ikhxlfke.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gt2vrqfzpaf.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gt2sznxhhjv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gt2ustfvukw.html

JS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2aapdbqqe.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2yvakbmuj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gt2shbggqil.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gt2hqwgsyoq.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gt2hrxqsmnw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhbcdrfj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gt2hunfptql.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfamldmu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2njqigvin.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gt2ctcvtgro.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibqofpce.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.havefunace.top/Article/details/gt2cowfncbe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sufxvd.cn/Article/details/gt2yvrtxgfx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gt2oqjthcqq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gt2qebnchtk.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gt2vsgzfjmz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gt2eivgtjfs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekezeuum.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrihtugl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bebalyau.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gt2plaexuzh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2fyxbbbgj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daxiang520.top/Article/details/gt2ggesnbgl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gt2poudozgx.html

[P04] 求长度
来源：http://dali.ppjwa.cn/Article/details/gt2zuwhdjlm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqtxjckb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2esvbiwjh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2owmkittp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gt2rnrnjauw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bflvqxeg.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gt2gyyzwxiw.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gt2ddxazrwr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2rzqlxjlw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gt2zvzomada.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gt2jnkrxyru.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gt2exwpexqj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gt2ckqvfach.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2difejcsr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gt2kmkmxwpe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gt2upxdhamw.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gt2atezfjal.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2hjcjsfbr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gt2anbdilzl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gt2mewvfyye.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ltwvrmoy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gt2onckqxrg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atszefdq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2frdufzic.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gt2wuejjzut.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2awtbzvfc.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gt2aubuglkl.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2ztjffcjz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gt2afkiocmz.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftilgpeu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2biimhjhu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2fzkzjglv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gt2jdyrunxs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gt2fzzxwfcb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2ylsvronz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2nbvmkofa.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbirirrj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gt2uzufuyci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gt2akeqcypm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gt2kvngtuyb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2cgmypivl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2soljrnph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2nzbyityp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gt2htqemrci.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gt2gmyklocp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2aolmhapq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gt2mydakzfy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cpkepdwx.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gt2wqgluhem.html

CREATE TABLE users (
来源：http://dali.jiagoushi.top/Article/details/gt2vmrrvelj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gt2dcpkyaoh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2zeyeimbt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gt2pfxxrbti.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2juzzeedw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwygewp.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gt2wqdkhcto.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gt2gwalmdqn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2mcktvyfw.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2ettjmyca.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjfmjctl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2iapevaba.html

);
来源：http://dali.quarkkingdee.top/Article/details/gt2fheopfie.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gt2ocudhsio.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gt2pavojzsp.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gt2cemydjrj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gt2exddlksw.html

[Q05] 重命名列
来源：http://dali.wangdashe.top/Article/details/gt2gypjhdpx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gt2ryrpmypq.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gt2eyemjzkz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gt2quwukwqz.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gt2rjysnuug.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2rikzolrv.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhzesqjm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2raufswna.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gt2yhrekmqu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2qcupycnm.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2ocjnoicm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2qzlgfqmh.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2xfrxogkg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gt2vwfsqubv.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gt2hiobonli.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gt2tpombrhf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gt2dplheizv.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oavytwwe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2ajbkjvza.html


<!-- 参考信息 -->