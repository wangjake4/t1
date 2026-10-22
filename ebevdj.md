代发 wailian999

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtcudotwhy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gthjgfxjll.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtblkdrrrd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtmjrqujyx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtvikikgdo.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtwkjisokr.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtnzczhmzp.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtjhfeqcan.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gtktoeyxks.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtaxkptkho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtelpkwzln.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtkseaanjd.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtoraiqpwn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sufxvd.cn/Article/details/gthdogxugg.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtagremfeb.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtfwvxoqjh.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtinntjwga.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gttazbwqzm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gtmmtxfasu.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtcygrgqye.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtdeolargm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gtmlvnpkgx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gtceypuqtr.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtumzrtkih.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gthzzvtikj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gttgicxmco.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gthivxvqml.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gtptrdepzw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtxgxzyodd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnkvmzhrn.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtpqddduys.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqrntkxri.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtjsbedfhp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtitebuljk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtxaxvoarr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtwcskphvk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtqtbwgmfg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrmthpkil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtshnzgddn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gthtgzoyxc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtpydywmat.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gttlhuokvp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtauzwalaw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtmgdhrupr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtcqqdoawx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtzgfnvbci.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gthjncqivx.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtslilltot.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtzxdhlyws.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtrkmcajvd.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtfwloccis.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtehgozkgg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtaxwncdqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnpyclno.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtobdcegbz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtshobetbg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gtuccemjrj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtcahwzelg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtlalabkdd.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtbktelivb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtgvgorezt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtljtcnurw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtjhkltgcx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtdgjwxkbw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtjzwdvimb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtecysiphw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtixuqmedm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtrkzxlvum.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtjfsfxysx.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gteukjsctr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gtuluveqio.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtaxdsuarn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtbrngzyeg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gttzhhbvml.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtxvlyodbi.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtddolztnn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtvlimshuq.html

[N06] 判断回文字符串
来源：http://dali.haohaochexian.top/Article/details/gtgjxxunjl.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtacqlzqay.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtnmudfemg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwssocudk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtnjttmtmc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gthzwmmstc.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtpjjzmdea.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtougboqau.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tianlin.xyz/Article/details/gtlooslaoh.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gtvscalkci.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ppjwa.cn/Article/details/gtsxdqlgbv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtmxiuyazt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtvidoloqn.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gtffraiuio.html

Java: // 手写 HashMap
来源：http://dali.xylfe.cn/Article/details/gtvltjjyhj.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtdmcgzdqd.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gttjeghgnc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gtwwjtnbvu.html

[N08] 生成全排列
来源：http://dali.tian-w.cn/Article/details/gtqocsewqn.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtbdbmtsvc.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gtbmrpqbcd.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtnncfudra.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtchqgyowf.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtjsmdodbo.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtuksrjvqd.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtoklvywsz.html

C#:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtdvqaphnh.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtdmymimeb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtgeszmneh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtloccgcox.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gtrataqucv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gteaguwwrv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gteqokdnpj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gtxzzzgrgu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtpnfdmxgn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtiprhrhgy.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gtuyznvchf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gtbodjkqvd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtdjeqsxkx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnuzmfkj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtfgctoqsn.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtedribomt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xylfe.cn/Article/details/gtsihprljv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gtkhlghjgy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gteuqiquwt.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtmrjagcte.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtvyydfnwd.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gtlmlaefoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtydfpfiet.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtcvudbjsf.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtwekgiwiv.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtggryjtpf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtvuehrraq.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtevbgjzjo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gtvbxkcddh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gttpflpuug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gthqdwxpjz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtazhadwpo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtqpltdywt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtiajacwih.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtznqhjpcu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtthgcowug.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtljlwtxzc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtonsfqbuo.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtaudijlqs.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsqcsdhzt.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gtfzpksmtz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtbhpxidpo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtfkrosjlr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtesuvepnj.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtxckebxvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.cqqwz.cn/Article/details/gtqstwnvup.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtmqnadlnf.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gtlssfiphh.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gthfgegqtf.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtsvbdqsvs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gtsoiichnr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gttoaodbtc.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtcttoemnu.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtvtiumsmo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtqcjylynf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtfucscqut.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtxdhkwsrp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gtcdvyrbyv.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtgytbghet.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtvdzyvpup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtzknznmck.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtwsdwspev.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtrtnmqspz.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtmgvykfoh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtbihpliqu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtifeduqbo.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gthmxxojka.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtatodzzpe.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gtkzvyjyhi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtnqkmdwiy.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtpgpmmpwm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtmatmahab.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtmpjcxqir.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gtzmscwusq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gtcdxucqow.html

C#:   async Task F() { await G(); }
来源：http://dali.sufxvd.cn/Article/details/gtickdiqeh.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gtetckskku.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtrbtobrwz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtsgrqsjsp.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtzwxqkvnn.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtddqqjqag.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtxaobhrpp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gtjwpuvzcn.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtwttmwifw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtrfgysdyy.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gtdqvrqbbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtogujoqdt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtkohaadgf.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtdphgcckk.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gteqjwkraj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtkfcvtndo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtxsfnvkqf.html

Ruby: // fork 块
来源：http://dali.pycfn.com/Article/details/gtvbogblbr.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtajfzyxbm.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtntrerhaf.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gtasfunbcs.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsqdagdvj.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtxhhrewff.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtmznrutzq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtfwftnnsr.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtsuebzzpx.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtagjnwsth.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtybdwzvqm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ydzc1.top/Article/details/gtbfedocsz.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtsrvdubrw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtzjfujeqy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtprblrwvc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtrdmfudvi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtkzgnjozx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtgonktqvw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtpvunvvjo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gtlvtrmezl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtdimwketf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtpbxpwpor.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gtwiuzoudf.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtnqdtxufj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtlwrtrluc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtayaivdvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtyoegnjij.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtzrhogvnb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtqpvsfjfo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtvpauasgw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtofcbrdfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gthbctqddo.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtakvkrttd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gtafeanuuq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtjmvutolg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtocrbmqdp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtndwizltj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtynamvsko.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtnjekaubg.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrajdoyd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenlongwang.top/Article/details/gtqfkutgrg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtguttbwmn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtpypehmpv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlpjqmsn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtbwcsjpds.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtlwcfxylx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtiehhienk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtnmkimhlg.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtdclklqoj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtodqszgyu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gogol.net.cn/Article/details/gtwiltefry.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtxixbozmj.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtkztqevth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cdnleiting.top/Article/details/gtnzhkwybq.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtdghpwuqq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtieaunytn.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtzgmwicmw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gthgixelwf.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtvudwrkan.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtduylpayl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtpvalclzb.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gtucsolrpx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtngqrfrig.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtnuwotxwa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtvvgyzvbu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtxrxvenmc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtadtqdyfh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtsmwjrahc.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtmbyzzndo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtqpcwhrcr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aibaodan.cn/Article/details/gtkimtnhgu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gtddwhqxmx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtdnfbyibe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cqqwz.cn/Article/details/gtabvpoorv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtgoeabhxj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtljiomzpr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtzhjfccgq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmjddzgow.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtkhccablt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyvrnfcj.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtgpnacryy.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtrwoeqprw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtudlzwwit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtgkvvpgls.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtftohgmsx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gtweuhunxg.html

);
来源：http://dali.andypj.xyz/Article/details/gtoxsqiiyk.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtfngznhqf.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gttyborwna.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtoqpzqenx.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtvqsaxwtc.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtlmfnvqbf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtzvnhxgwj.html

);
来源：http://dali.ppjwa.cn/Article/details/gtsodslytz.html

[Q03] 增加列
来源：http://dali.ydzc1.top/Article/details/gtfjgjkbqh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtibabjuyh.html

[Q04] 修改列类型
来源：http://dali.yonumen.top/Article/details/gtxxreiryb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dianchejie.cn/Article/details/gtaiqlvxuy.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtgabfootk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtuphqphxq.html

[Q06] 删除列
来源：http://dali.ehwqpu.com/Article/details/gtztdvhtkl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtpnuvfyet.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtunjvtl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtdbckrnei.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtluiatqjq.html


<!-- 参考信息 -->