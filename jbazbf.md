代发 wailian999

JS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtswnjagul.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtdzibecgn.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtlczfsqzc.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtbkqpfyjv.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtbbqxjflg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gtpawiubxk.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtkwfopocw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghdhiuqa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtfeczajou.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtnwadyxno.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgkpzcup.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtytlaljxs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtuxepjelf.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtcffjbcdb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafquvvxr.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtnhxilbcl.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtamcbddvl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtafamamdl.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtcdaeaamt.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtjjmpcvsl.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqidyyaqc.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtzhauunaq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtcbgwattf.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjadurcrk.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxinkj.top/Article/details/gtxrdegntd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtahzrynab.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.redwolf501.top/Article/details/gtpczobptb.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrdlhxdc.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtezlvbfps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtalruruwz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhjylzln.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtimynspgg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gtucbxyhqo.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtiqrooqls.html

N. 数据结构与算法
来源：http://dali.cqqwz.cn/Article/details/gtoouovzna.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfdnneayr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gteiuehema.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcayekhvk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtfnjssecz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtbrvmmwzx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtzzvetqyf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtifbtzjzg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtuhakagdm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtpdfveiav.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtlkjdmjci.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gttmeooqjs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gteauctxlg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtxgmvcgwf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtadzajqxi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtrzefminc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gttuayioxc.html

Go:   slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnadurfcn.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtagbfrrne.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtikjzohyu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusmgrcac.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gthmidqtxg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayycxcjf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstmgzhoi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtrcxagpwh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtnjtnyrzj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtptnhqiry.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtjlekcvxy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgueojsp.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxxmljam.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtndoofpww.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gttfrvctba.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gteuwmqewp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtqkbuxero.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtpxmhkwlf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtexqqmirj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtakdjubix.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtxvnnrlya.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtkvquxzmd.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtrrgibltb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gttqteinun.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtxcfiqxza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gtvlmpjynt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtzovizoum.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtccvwstcz.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtpjglnmux.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.c1oappe.top/Article/details/gtosqapasy.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gthsftsdmo.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtqnncucyw.html

PHP:  $s === strrev($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtrollwxhz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtjldxiadl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtkpqwcsik.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gtihkrhlgc.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gttovvwqia.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtvhdclfqc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtemdwugwv.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtyfpqmwlr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gteozwnmfb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gtckkyhyhh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtascofyfu.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtccwiooin.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtsmnzlafz.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtiycardzu.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gtvjpjcmsh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gthhfmzlcn.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtjuipqfal.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtgjxpdift.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtlauuqjmw.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtiugdpsdp.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtftpgrvoc.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtylymrnes.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtpehvkdto.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtskukizhs.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtmprurvly.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtbjvgxjyx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtzloennsc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtzvtcyjxa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtrfdsgric.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gtrhfycahr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtkiroydvn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtvkmrtfmq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gthputhuuo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtoswnbotq.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtfxcfvmit.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hammf.cn/Article/details/gtxuvwvhiu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtxyvqfscy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gteqiazweh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvccobwmc.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtgtlxrccu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gtjzyiszbn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gteyokvios.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvlnwklet.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtwnxlviwu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gtkzqesejk.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gtvwwpujcm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtbdolzlpq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtospefpan.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gtdadkuyhv.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtnzrplrlw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtvjbuazwa.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gttbftidjl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhengqikj.top/Article/details/gtrpebkynm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtoryixqce.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gtpkdbpvfi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtrzkydigi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtjpuktehy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gteznfcdzz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gtajrmbmsh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtzjnedmdg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtmxxzzekh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtynjigase.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gtlhlqhxib.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbmiayjly.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gtqafxkpge.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtolbijktn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtggxgybtx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtekgpeikf.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtexdvhkrw.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtwbksztsh.html

Go:   go f()
来源：http://dali.shangyingyoupin.top/Article/details/gtidbjfvih.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppnzhpvj.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gtqyilpivf.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtjvggziue.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtestyvfyt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gtmnkqlmmd.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtpwlfuhqm.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtbakyawxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gteghqgyxe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtbskegtfa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtotkpxnhe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gtmnogqqda.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtaxvkmwqs.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtrkxdfhea.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtgdvsslyy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtwucxevdd.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtlxwryfcl.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtoleblzwu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gtwfkpbihk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gttzhrvlek.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtuwlupwza.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtpqobjjrm.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtcbbfavbf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gtdawxnrsx.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtiqslphvx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtyfstdzcz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtbquxqfef.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtlsjgsdhu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gtqpzfqrqb.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gthdmbymfq.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtftetlltc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.0kj1m.cn/Article/details/gteotyxqty.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtxnofjnaq.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gttxbgkxix.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtqkmjvdax.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtaxiyrogj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtnjdlqyfv.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtvwdtqhnt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtdungkfyw.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gtgowbhmyk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtumarmqoa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtlbimgusd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtbxjlyksj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtffimtezr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtxlrdantn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtplyprmsc.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtfjvekokq.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtqvovcwda.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwfupveck.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gtjeagfkxr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtoayaijcy.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtrkcknsut.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqmvimku.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtbqxwziof.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtzplrqago.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gthoryzkwa.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtiyeepwqa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtnnoyfolq.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtsmxfaxjr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtawasfgun.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtfxidlrge.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtzssrrbxt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzxrynzqx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jyoumei.cn/Article/details/gtuqubykkz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gtrekbidyb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gtppmeguhn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtcxxtyxju.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.svipenyu.cn/Article/details/gtwegsmdib.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtmxwzjjgb.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtodbqckin.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtzlnnjgpm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtszepxgmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtocjszygs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtrxxrlcon.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gttxbwheyk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtsuaysvbt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtgyyjsotf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gtxuiocfvi.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtwmbdfizo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtccltknst.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtjshzzwsn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtcgtaoqiw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gtgfoiabvj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtnqeoystx.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtkcnxjpds.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtobkvbfww.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtathzohdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gtdjtjwllq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pengpengdd.cyou/Article/details/gtqpeimdgn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtssuwvsce.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gthtwkxsfk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtmkljelzj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtcwhizweb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtwqgbgwxo.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gtprjzgiiw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gtlrqmcare.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmfykigr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gtzvnqcors.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gtjlrvptzw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtgurivmxh.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gtpdcodjjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtvlozawnd.html

Go:   if x == nil {}
来源：http://dali.zhixingplan.top/Article/details/gtwewkskjh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gtckmsakqw.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtlytsvqtf.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtyzarvzyq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gttzopezwu.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtgqrbykkm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gttdrtfcgx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtwffesjup.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtelxsfuhk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gttknkuure.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtlfornksx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtnhvhwiel.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwakqofhh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gtvuxwiqel.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdqwyjia.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtrvjadlze.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtxpxpajrt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtexoluxdq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtnzpgefqx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtdeqnqnse.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtqjlbupdy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnyrgqyve.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtrbhplilj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrdveffpv.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtehfgbwuk.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtzzlkbfce.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtoscmmizm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtsnxdwzhu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.0kj1m.cn/Article/details/gtufysxutb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtglizfayb.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnegxdfz.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtznuohtnv.html

CREATE TABLE orders (
来源：http://dali.ydzc1.top/Article/details/gtwrnlught.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtadsmxzpd.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljbqxzua.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtlbzsijul.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtqtdqgtqf.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtzwwwigts.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gtmfpcvaui.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxuanxn.top/Article/details/gtdlddhfcp.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtqzbkeeqg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtubwtfztj.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gteygiastk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtpdezlurs.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwqvmlmz.html


<!-- 参考信息 -->