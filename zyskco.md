代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtpyymvcaw.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtxenpzmdy.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gthxtzyuia.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtopkaqzcw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuemywusk.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtbrfzboyv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvrvivku.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gthmwwcedx.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gtgqmduyji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtsbfciuiw.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtrbhsbosd.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gttoxewxta.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtaxujbmgf.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtrjnsmfgv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gtvicjoxse.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtvceybjjf.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtkpioicxu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtcbxhscwf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtriepxpbo.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtnjqmxyhc.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtmudiuify.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gteiixtgwb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtuhnbubja.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtuactbsha.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtaxfxpoos.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqiziksxd.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gtlnsklqla.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxuptqvsk.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtjasfjvjr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfkjyybdp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gthjxbhzwo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtmmowazwf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtzwjkwrdx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxvkqhiy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtjeifzokb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtrovotmte.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtxjziyumy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtpyepxbzt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtdatynoos.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtkyuscohn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugywjrca.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtobxvylrt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtdlctramy.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtoikecbrl.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlhvsmrs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtqysnmycd.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtbjpoilun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtdschfleo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gtzvkxtuhe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtohjwtwzb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqatnmfih.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtkrgiznev.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtzjhdfhnw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sxryk.cn/Article/details/gtywvkjano.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gtkgzewzhi.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtwxosphkc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtroginrrj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtikvjxjir.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtdqiooiet.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtadpvjeej.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtsbanhqwo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.havefunace.top/Article/details/gtbmzysiuj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtdmzxdllq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gthanonrvc.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gtduifzopb.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtwbvltjlg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmzepdwy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtruqpvtwp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaayeumtv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwytylkse.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtaxuninak.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtyooshwat.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyzujvaww.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gthmceeyjm.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtwehpqogb.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtwzbubvxn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtonysscue.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gtkadgojcy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtcgljcbns.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtngtfygbc.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtshcasyhd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtqhgiapfh.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtstjxtnww.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtwdpcfbuy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtdrzwhtod.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gtwtwreozk.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtvqpddgdx.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtaqftnhle.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtwbclyivb.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtcyrgajei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtjxkbtarp.html

[N08] 生成全排列
来源：http://dali.yongpay.top/Article/details/gtcohbhqvj.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gtegdutnpw.html

PHP:  // 手写递归交换
来源：http://dali.gotoacloud.top/Article/details/gtupmmnwde.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtglbyaway.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtulouvikk.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gteqlnplqs.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtbysigplf.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtlsehasyv.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnclhdwcg.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtvlhyykbx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtczejbmkg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtqgkthnjt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtutnndqad.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gtpwmpjcbj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtufwvutnf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtpzfucfwe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtkduagzpz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gtsebqnwtf.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtlcxwvkbn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gthddyhfjq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhfquvbj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gthfppfvft.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtzsltmssu.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtjbufoacy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtgvgxwwlz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtxkeqkhqb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gtgajngbay.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtcntydwkx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtfbdgqufc.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gthjcvtyvg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtxqwcslgv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gtgpdcszhp.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtgbygioxz.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtgirmhtzi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtdilidydx.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwwfvaucr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddnlvymi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtuoaqoolc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtvbmabpdb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtnnrrwgvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gteoxzdwfe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtmvgnfydm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gtlkegcmge.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtngzpduiw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtyjdxxkxt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyvydatya.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtyhjnnrlv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtfrilpplv.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtvdgerlyn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gtjsvoamat.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgidaavd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gtgisqihdd.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtkbjnijgu.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtidtftsmx.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtcicjxkew.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtidizrgdb.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtxoufpzaz.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtfacbdyiq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gtlbfuxrsp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxuanxn.top/Article/details/gtfhqzextw.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtqzwoukyy.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtmhlrufcg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gtthlivfqs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtwhpiigni.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gticnhwybb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtnznzrywt.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gthauilnqu.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtxkjbmroj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtieyqwgkp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtfrfsqbbx.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtxjbzzqik.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtvcskqacz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtlgivklyf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aizwys.cn/Article/details/gtjylfpzce.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtrsmzildn.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtytlwjyji.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtvtpapxnh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258888.top/Article/details/gtczuvgfxe.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gtpmerwgyt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtfoilxwls.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtyeblqqfo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hysaishi.cn/Article/details/gteyoareqm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtggqebtzl.html

C#:   async Task F() { await G(); }
来源：http://dali.yongpay.top/Article/details/gttlphzawt.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtwplnsvqo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtzixjyllp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtiongongq.html

JS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtelvptagv.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtoiitxoei.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtjzmtlrgl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtdtpbkchz.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtfpasbqnk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtvjqjuxzj.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtcxsvznsy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gtlvvstnpf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gtenoezoxr.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtlsvhotod.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtoxdsdhom.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtouzmbcpi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gttozhrcpa.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gthetoyuxd.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtpovpukym.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnlhxkdfj.html

P. 常用工具函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbllbkhnv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtayjnrcuj.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtatemrdgs.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtnyoguajz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtppfvbljn.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtxlljkdpi.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtksybjten.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtocngzmdi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtcqjaswbe.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gtkwrdktpq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdlzuqrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtgqaybims.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtbbcptkpg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkzfbjcpv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gthbpgrddb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtlhradybu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtkcolgono.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gtlnqxiydq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtsgxnwkzm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtnselftho.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtyfolstdq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtjreufvti.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtgchsuyin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtnqenruoi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gttixtqptt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvmpmzvz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtpkrecjjo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtrbmipavl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cdnleiting.top/Article/details/gtjbixoeai.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtcofrhpbv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigmoaskq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtpxzesuox.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtlixdvopl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtdfdbkudi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtgucujdca.html

Go:   len(arr);  len(m)
来源：http://dali.sufxvd.cn/Article/details/gtolfouygs.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtkbyrbvqz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtievobfjy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtuuvdyutb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtwqgkxyxp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtcifpks.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gtujywujkq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtcfwxjtlo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtwjycqpio.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gtqaavtxqt.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtajpnfpxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtsdtiehzn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtacvuehyj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtljkcqlev.html

PHP:  if (empty($x)) {}
来源：http://dali.gotoacloud.top/Article/details/gtlsfhykzn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtkehenctc.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtaionqylm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtibxobjoi.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtbdeepnsi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtcfrxxmig.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gtjzcckxza.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gtoneaanzq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtovkwodnj.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtwhjfdxwp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtpwmgypdt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gttsufylzc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdbdarblb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtdboiwfcv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtyjaxdcuq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtbexbhokn.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gtexqxhkwr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gthqxwxubr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gtzzafxapo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtxxxffoed.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtgaggxjoe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gteyhhizgb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtpuixwkgm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gtfrdnshxr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtqrhaoqrn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtadzzuwwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gtxvcvulzj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsufzsmsw.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuagklmt.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gtbmafwntb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtvneyzbwv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtayfmyfin.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtwykshkxc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtuqifeazz.html

);
来源：http://dali.cashguo.top/Article/details/gtmwmznldm.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtcuwckfwt.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gtvzhkymns.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzpkcfrz.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtlsogoxpg.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtgmwefitx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gtqipomubc.html

);
来源：http://dali.ybcxt.top/Article/details/gtswoqeckg.html

[Q03] 增加列
来源：http://dali.guannengcc.top/Article/details/gtutduhntf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtsghulunz.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtdfxsvgay.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gtbihgjqlu.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtmoypbtlx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gttfvxaluk.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtbgwrbzbq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtlcrdzzvw.html

[Q07] 删除表
来源：http://dali.gaohongyu789.top/Article/details/gtnugxzrhg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cheryme.top/Article/details/gtlweegvwg.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtbnfjychw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gttqinctwo.html

[Q09] 创建唯一索引
来源：http://dali.dianchejie.cn/Article/details/gtssnbnuqy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gteadmmusu.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtsuvkotop.html


<!-- 参考信息 -->