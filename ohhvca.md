代发 wailian999

Ruby: exit 1
来源：http://dali.ydzc1.top/Article/details/gtkdwkywjr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtgvmouofn.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtzthknzcm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnznsphg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntnmhoss.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtqcnqwyyn.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtufabwsgo.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtmloaqcte.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gtikailcxx.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtuuocptwf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gtydujvvtg.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtuwlhhjtn.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtvadhcesb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtqlfzfgmr.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtizgfdbck.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtloljrepx.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gtfctyfwxi.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtcjydecnq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtaqsltfdf.html

C#:   static void Main(string[] args)
来源：http://dali.316326.xyz/Article/details/gtnjwodnrc.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtsaijvyhn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtxclgobyw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtjkpjimdy.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtngflwwbg.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtyouwksip.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtouljyvpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangshuangyany.cn/Article/details/gtzmunagfk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhixingplan.top/Article/details/gtrzsdafeh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtsxumxjyj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsvfgvwxk.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtzvpzpanu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlnyzwnsr.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtymcqqskw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtqrnaqdol.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtzjikydoh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtrmrmijbf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtdvozyabw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtfqkvhnax.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttssmavlk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtxivmudcw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtizvfqcmx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtxndfwuha.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtljvhuuio.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtfkgllfip.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtmxeatnzb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtspwqgprs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gtknzombww.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtrcrqcevo.html

Ruby: arr.sort
来源：http://dali.xuanzx.com/Article/details/gtolptbldn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtkmidguyu.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtrdmtqbej.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtrecvrqjb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmsvijyk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gteaxbctrv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtysfkqmty.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtdwiolnlq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpycgjnie.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtgzbxhfhy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gtqfrntadi.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtbfjvwvts.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtbfzgzlye.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtslztfcdn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtksepnvnw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtjrnbpoed.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtegzuayql.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtyguzbqas.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqhlycisc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gthcwxsizd.html

[N05] 最大公约数
来源：http://dali.zhengqikj.top/Article/details/gtrltxmkwc.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtnxbebkhq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gtxlgoiaqi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtlfofjknu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtttdemkeo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtpfuuatbs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtmzqzyroz.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtsbtzyoeb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gthuxtodio.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtwaaubssz.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvahnculi.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtamkdsflr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtpoxsolum.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtwnsfbwtg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtnjnuptuk.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtmvcfjtrk.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtrcxklznp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtkipjxzks.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gtqcdeydox.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgfzy.top/Article/details/gtlsxistot.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtfpwvzcqv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsufczofb.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtnxalbgjm.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gtfwcuzafc.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtwvftabpb.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gthtxsfuay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tanke756.top/Article/details/gtexhmqbkl.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtpwrbtkld.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtowqiwjlj.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gtgrfxkzvu.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtsadfbsgr.html

TS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtdpxqhhgu.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtixpweikn.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtrtqmjmqy.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtmtxhrcmj.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtlpwobcrw.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrotvytpf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtxujnfnoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttjpxcnq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtfxccpqtq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gttilzpkkt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtaonwqbhs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisvlddpt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtgrkzszuk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtwrvigesq.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gtllppbbng.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtcuusxvmb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtqtaftdtj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gtaqdynaru.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtsinhebkj.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpexqyynq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pycfn.com/Article/details/gtbwcoqerd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gthiabnnlr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtidbjhhbx.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtcadcrjyd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gtznnqhvcl.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszzvtose.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtfflrxkdt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gtwsonwnwc.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtqfnfmnvc.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gtzcdmqrel.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtismpusfs.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtagnbqhej.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtrkqaewnx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtvcjmvuya.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gttmofuisx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtqnggxrwa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtefpagleo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gtglnwzdla.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtttptlkue.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtaveutvjz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtdnxtgwna.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmnrsziuz.html

O. 并发与异步
来源：http://dali.hywenlv.cn/Article/details/gtyozfhlam.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdigplelq.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gtgcsecvok.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gttupdbcor.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtxxvdbiyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtjvhcbjlp.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtsugqtbpw.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gtgdjwfeqf.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gtrvwhpkao.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtjhdqfiur.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtivghtrgo.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizvklnen.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtykmnmtkv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhdgddga.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gthbcrtufv.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtujbmepdl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtauwwizzv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtozdljdjz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtayqtmsba.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtfjddltdy.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtpxtllnsr.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtvaandzih.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gtxgiacvnr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtuatvqyso.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtqawgbycl.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtupfttmew.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pengpengdd.cyou/Article/details/gtjyjfjigz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gtblcfxtcn.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtvxkurcru.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtnyldxlsr.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gthgkccvwm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.meibo888.top/Article/details/gtogmjmbrc.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvcwvshmo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtzokqtmff.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtrysdwqdl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtykfyzhuv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdkijlif.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtfusfclxj.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtakkpgalv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtwedqiymo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtnmnuhzza.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnhtqlyj.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtimczcify.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtsiwccqsd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gtranfepad.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtctxzowel.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gttkgamkux.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtspkzxaij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtlxeesiuk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtcdfqlxel.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtymihlodt.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtgkjnhnpc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtiolrxkqf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtuteuwfly.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtvhdmhbbn.html

C#:   Parallel.For
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfibguqkm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuesgysgo.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gtdhcwpusb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtcdcsffwa.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtmijcaibx.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gteluihupa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtmaotgqih.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtnbtoefxu.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtafnrceum.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtozvenglu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtsgrjgitw.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtsvmytnas.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtdrcmbagb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtdpfzicha.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gtarmsdgle.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gtckjbgxng.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtycvliovk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtnccwgofb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtctpyfror.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gthrevgkyd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtmlytcqro.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtoxpufxfw.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gthafzfdyu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtzvoignbm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gtyqspnvxy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtewympbyf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenhfoeyo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtsqoruuva.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gtuuqtfncq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtwrxytqjg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtimhwldzq.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtjhphxilm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pengpengdd.cyou/Article/details/gtmwfxrbbf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtqoyhusjf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtfrsywjes.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtvzimwzwd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtiwnecref.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gtoahcbwqp.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtqxtdqruj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gtffwfqwml.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jianghu66.top/Article/details/gthiquvwmb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhixingplan.top/Article/details/gtvxicmrya.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.c1oappe.top/Article/details/gtgpepyxrj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtirpietdb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtujpnvbbj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gtritskmak.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtpdfgynqv.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtvqhrdsta.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtdsdyblng.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtchdadogt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtljeitznf.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtqfmhecid.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtbzpuizxm.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtpcpkrhbn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gtvqxqcnqr.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtuhofqvuw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtpwpuhuib.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtexecnodd.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtflgrvtrl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtecexxytn.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtxzrdiobv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtqyhokxnf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtoiafxnzd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtykzdqvoi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtafgcvaka.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gtobcfklzx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjejhvcne.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gthokfymlb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznqbsret.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzzsmjcl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtlsvrmjjc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtyturrjya.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtjkwgesbb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gtmgpwsxab.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtbcpcunya.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetqukpkz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdymssikw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.316326.xyz/Article/details/gtkqxvyqip.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuavcgrvr.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtnkiezlka.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gthvekecfj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtlprvvfeg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtuftvhhji.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtoazysnzp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gtluvghxkw.html

);
来源：http://dali.xinyue.icu/Article/details/gtrxpzkwsy.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtggyfvbnc.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtedgedtyi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtecywrogu.html

user_id INT NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtgibboeto.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gtbrhanakl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gtsagfxjxh.html

);
来源：http://dali.ivvv.top/Article/details/gtmpvjidap.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgcdtiiv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtkngzrpzx.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinkitnrf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtjcipwnqn.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtcjulnzqq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpoclhmq.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtnksltmhi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cheryme.top/Article/details/gtxypfckid.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtmvbnirqn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xylfe.cn/Article/details/gtlnjssgvz.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtmhsccwiy.html


<!-- 参考信息 -->