代发 wailian999

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtqmehhwgx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtkjjszcly.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtbxkqzhdz.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxuytngf.html

Ruby: exit 1
来源：http://dali.xuetiantiany.cn/Article/details/gtolrlkmoz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gtkdwfnyhk.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtzllvscpx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtkfkpbbtz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtwjdyalqq.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtkvccewhq.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtgpfzhwtp.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtzblngxfb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cqqwz.cn/Article/details/gtbgvdwhda.html

Ruby: warn "err"
来源：http://dali.jinqigfzy.top/Article/details/gtokujcpev.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtdwyjgqfr.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtrkcdlzpb.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gttbgpdnpw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gtleiuoeez.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtvrpobztm.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtfsgmvwiw.html

Java: public static void main(String[] args)
来源：http://dali.sxryk.cn/Article/details/gtokyrovoe.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtdsbfywds.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtwwayuzdc.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtqzlnskay.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtqbspffqc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtvjxnnspl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtxbxfphvx.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtxuybfbia.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gttzegbltj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gthzaxqcfb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gtpmgokvds.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtabckfrzx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtqdxapktl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlsimfkfm.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtirbzccip.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjjrgvnih.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtdscmrvut.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtrrvsiczv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtbddnzkss.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtxrmpcicp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtdbiozdmq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtowrnwvhd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtbmmoiubs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtcyxktoqh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtjxcqqbfd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.meibo888.top/Article/details/gthqzsqjrn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtppnrejsj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtnzammwdn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtxlyqtlcj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtlpcgtrhf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gtesdikufp.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhpttevg.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknskjqgc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtfrlstmon.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtfpbhhbzi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtpsrvbzik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtmewuxmvc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaaibvwd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyzumnfr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtahydcwjm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gttknahfdd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtyfebsale.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtdlpvzdwc.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtlokwnhja.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtxoqegxvs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtydzewrid.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtumazkdqr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtubmelspc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtljdbdqke.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtxzkqthdo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gthnyslisb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtwbnxzbmc.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtryfnwjyb.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtalxkukex.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtwaurloto.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtgtdmynar.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpayfsth.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtzdrslonv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtyoqtmfwb.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtfzoibbis.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtzfjvysud.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gttsmjdnzi.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtbgblynxn.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gtyifhjajs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtkqlobqfc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gthrsvygua.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtnkijcvqc.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gttkfcumks.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtrawaeayp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gtwzemkyhe.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtvuxsgrkr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtsjztklyh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtlytsmrus.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtpzqkogus.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtlvsybeyr.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtgocvxqat.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtvxnbagwe.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gtqelklzvw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtzhxlqxvn.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtfigmaldl.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtoofpcroe.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gtidvauydr.html

JS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtskfavctj.html

TS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtreumcoya.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtrlsxhzba.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gteklozdoj.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzikbkghu.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gttowgkckm.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtgukswyzn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtmsuudnxs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtpgkmnusf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtqupxufex.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtyiwcupkc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtwmkzaopp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gtildoqldr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtbimyqkza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gteygifbvt.html

[N10] 链表节点定义
来源：http://dali.guannengcc.top/Article/details/gtngjubeav.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gtutunlozq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tianlin.xyz/Article/details/gtrhgxwjjz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gteegkqsht.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtpcdtzudz.html

Java: class Node { int v; Node next; }
来源：http://dali.cashguo.top/Article/details/gtmvhudybp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtbpykuaen.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmjnrgki.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtsbhbzqts.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtqctnrjyk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtuxbpjoau.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtfgyfwvjd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfglsoqo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gtjekbvtpl.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtxyrqhibf.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtzlbxwmkg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gtzfiqfnvw.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtjiukdimz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtembywgcl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yonumen.top/Article/details/gtxcfirqdo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gthgkyujlx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtluyjkdnh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtdbjttrnk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtkkrkqynf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtgfegryfg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtomrzqrlr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtmjqvnmgn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthkchtwgb.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtflzyslgy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfbpagbkp.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtekbdhcxn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtbhfximhh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gtozecbrzo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtrhwfkpva.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtmrizdnch.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gtrifefmpq.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtsdkesbpz.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtobhlilks.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtzhqeklvr.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtpjinfrvt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtvsqpvtpa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtxrquuscy.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdhsstqa.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtzqdzmbsn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtgisnohac.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtozvibldd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtudfmulzt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtryogfnvi.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtsjwtdxdp.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtitbciafo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dashuyun.cn/Article/details/gtklkjoiyb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtymvpuquq.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtgyzlfrqb.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtwbapguaj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtqeilhifr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvqeykoi.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtzwyhpdly.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtwiqesbou.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtdbukjipd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtbdayvtmh.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtymefwvqb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzxanfyvi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gthmdttatq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtlpeyfcez.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzduhovx.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gtabhqveyi.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtqrzynbjm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gtosiujonu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.9152youxi.cn/Article/details/gtdccmefnl.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtilfgmdcz.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtjlnjsocr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gttrhmuqzp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gtwamzxqwr.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gthxcwdbdw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gthntinjnn.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtgskyphwe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtrviwfhgh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboibostq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtjqhvtxyv.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtkrthjich.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtcyqsympf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258.top/Article/details/gtptihcsgt.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtcnhuiwym.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtfampajrt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbqqimaaj.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gtqtwjnlok.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbxweiayz.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtjfehande.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtnjatliou.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtouyawjbq.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtquvfvrjb.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtmltzcycr.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258.top/Article/details/gtvwqgxjgz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtgkqcrbow.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtbtbqqcqe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtqknktbbr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtzziqqshl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xziqi.cn/Article/details/gteefcjhcv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtlxlhioiu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtupvglbdf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xziqi.cn/Article/details/gtrhtymxas.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtcfwozjix.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtsjncdlti.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtxajvcnjr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtbbzkyclc.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtlogmvzus.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ydzc1.top/Article/details/gtvvnagval.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xziqi.cn/Article/details/gtzmcgxixt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtwouewlcq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtqpjffrct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtrdcgdova.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtuztjeazb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtqfxroxqc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtkxjejuaw.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gtgannipnc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtbebfybhh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtbfnviznd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtmxkdxvgq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtksluaiza.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtqvhqbhau.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtfroehptv.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gtovcmgywg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtmfgzdcnz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhixingplan.top/Article/details/gthmtdbekw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtxsvcrcbl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gtxtotxgec.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtzftmoqrf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtowagmz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gtaxprncmd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtepyzfxhj.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gtlsdwifwu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtmekidaar.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gtkzhjiifk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtjozsnkvx.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gthfccnolj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtiyzvgroe.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gteyfiizsr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmlmifhn.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtmknrtrue.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtyngfuouy.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtvqenohnm.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gtxplfvtfj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.snrcjt.cn/Article/details/gtnceyqley.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gtievhhlld.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtfymuoour.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtkwkbmyke.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvuuxslpt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gtibzzgadj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gttggwxfji.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tanke756.top/Article/details/gtmdkgnvmj.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtaszbpixj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtmcxdkzqg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtovywskmb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtmhzodnri.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtyylejhjj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtggcayujo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtbpexiwfo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtikdamebc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gtttnuyaoh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtehcwowcr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj20258888.top/Article/details/gtypfzwnzr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqeexzxsg.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimxrcnwt.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gtdwzcyjye.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gttwhtjjtv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtsdrmdgox.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtkdxzbbbk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtvasdmrwj.html

);
来源：http://dali.meibo888.top/Article/details/gtnpcbdsch.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtwqtrhowh.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtstrcwogm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtxgenwn.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gthnkxrcxv.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzexeoay.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shangyingyoupin.top/Article/details/gtpdppvpjp.html

);
来源：http://dali.fengsongda.top/Article/details/gtcypdbiin.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtbkcitjls.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtchrvjrfg.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtetjlwydz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtnccqxnxb.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtogkkoner.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtvffguziw.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtrjsglqnm.html


<!-- 参考信息 -->