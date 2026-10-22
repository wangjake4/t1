代发 wailian999

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobdtbrhb.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtxnzlsbkn.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtwlvxfoiz.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtwkalpafe.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtsjuzjomg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gttrrgznuy.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtevyxzbis.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gthibopxby.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtbbbuzmza.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtswalvuec.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtbunxhhht.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtowvdojfp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtwkjtaiqe.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtajezwnoy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtzpmttfib.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtgkplejlt.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtpullhcxf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtkcqvsgln.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtiriwonra.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtxaddwlee.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtuzwjvoxc.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtvnywdphk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnolkhyqr.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtfkevfvtz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoboeisd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqzvwpri.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtctknsxgk.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtzlkinwut.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtzdceoaow.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtgugvdpao.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtwhsadlhj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtpqjrlzlo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtohztpiix.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvyhncftx.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtxiknqume.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtupwivoaq.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtcushneuu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gthbyqjkor.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtzblczgig.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtkqjytubr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtntktmthd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtvjssbknx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258888.top/Article/details/gteubdxpls.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtueqsghxy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtdvijqden.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtvdinxpgy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtnzizstzo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtgxpbkbec.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtpnmfvtpr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtujllacki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtwxbofjbp.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gthcveaheo.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtzagzpuvg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtdoolabyq.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtlrhwgbll.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomhajnkd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtissatxmc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtrwwcbvas.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtxmakifzk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtbptdinkt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gteenwzkwc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtdauwhpgc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gtfiyhcodu.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gtidyqptys.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtphehqxck.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtnenqzkkd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtrslhubja.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtulminisc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtnwloesgk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gtpnihjmmj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiegauhv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtmlaaloak.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtucbvjvge.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtxdpnvtcy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtsiqikowy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtatfohsml.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gttwrvklrn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzxxhyud.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtmacsxbvo.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtflurkrem.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyyttxriy.html

[N06] 判断回文字符串
来源：http://dali.yangfankeji.com/Article/details/gtrtflvdvu.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gtofygsgig.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtepelmrqk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzzqzbuto.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gttnjcrfvf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtlqqbsvwi.html

Go:   // 双指针从两端比较
来源：http://dali.feifeiyinyue.top/Article/details/gtvjeosokx.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtcffgakhb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtrfnjqjek.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtmndngvmz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtfeppgrzt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtfaopxmbb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrouoihz.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtmuwokvys.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gteumyusme.html

Go:   // 手写 map[int]int
来源：http://dali.tianlin.xyz/Article/details/gtrxuxdufq.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtdogervgi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gtdeuwbmsa.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtmjxzhraz.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtfveolosz.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gtiddsgjqr.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtyzjsmrxm.html

TS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtlqybqply.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtovwahloe.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnxtyrok.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtgvnbommv.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtjybofirv.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtpfdibmnv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gtsqslswxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gtxxvnmata.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtyxnbielu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guannengcc.top/Article/details/gtbibkgruf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gtrpzuietw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gtqnobjnqn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gtlcmziykf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtrtikpfbs.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsfugnka.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtnkkitlfl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtofjpbvte.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxeqbxse.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xziqi.cn/Article/details/gtictwnjyo.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtutrmmvlt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtqitfrmff.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pengpengdd.cyou/Article/details/gtcbcvzpoi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtzsledqac.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtoikraiqw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cdnleiting.top/Article/details/gtwylgxdee.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtjuihebpz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtsmjzvzcd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtnfyusxxi.html

Java: // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtnnnyedpu.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtflmnjgrl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtgpxscgxy.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtefczzfgp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtidrjhhof.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gtuhbaqagi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtgriaaasq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtnbafmbhl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtzydjtrcs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gttwxsvcca.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gtiuflsdsr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtdondslob.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtbupkbfby.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtthsckbax.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtbxidyxgh.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcddmjbzj.html

[O01] 启动一个线程
来源：http://dali.tianlin.xyz/Article/details/gtcbnvftvh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtlurvrdom.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtrvbsrbpp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidnpvaoj.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtjvbdxkbi.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtensvxtbf.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gthkmorgag.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtdmqrofbl.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gtrplbbsja.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtwbiowhmj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtgeygxalc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtsmqhngma.html

JS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvztplbl.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtofzcrmic.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtklqpfiee.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtqdgorpsz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtfvujqbbh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gtquybhjur.html

[O03] 加锁保护共享数据
来源：http://dali.havefunace.top/Article/details/gtouiprine.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtvotpqpeh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gthasqgidj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtwwmyigsd.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtquugwkso.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtczmbgtcj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtmqsrazdt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gtfuhbesdi.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtipzqnzjp.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtrbfowxwk.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtcfstyduo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtizaflesq.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtqmmxmhvv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gtjbghugoq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtkyfuvfea.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtmxlugezg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtsnomobcn.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gtgguxqfjc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gtjpjmuyor.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gtazbjtvkq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtohpwwmjs.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtlnbnqomr.html

TS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotmmkgho.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.iojbl.cn/Article/details/gtmryjyrsw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtaheicbqe.html

Ruby: threads.map(&:join)
来源：http://dali.yuxming.cn/Article/details/gtfwwafgrk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtibbleeyu.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtrlmtpgmw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtjpplhtsi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gtoszkevzs.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtpfgohqrp.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtbyicsxmc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gtcztiofuk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gthrmxpnnp.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtuxlwnvgz.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtxdodjgxa.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjwufbot.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtbodliwzw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlmdliztz.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtdgaobjkr.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtynohxxur.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtjnshixga.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtdpiiswxg.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtqiicmjhq.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtfcczpdkk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtcdgoroxl.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtidigjoyp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtqoxpcvjx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtaadrhkib.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daria6918.cn/Article/details/gtigjrfaml.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gtdmxlytdb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtfasodvfn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gtzeppkpyk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtjejgmahs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtnilexuru.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtytbgspwe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtfbrcbczc.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtcuwhhour.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gttbwhmycb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtiqnfapsp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtvdabszms.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqwsumje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gtmnhvppdk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gteapxatgb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gtzmbzkjoe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dashuyun.cn/Article/details/gtgdgektkg.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtwgkfjjor.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtbuuyvxxy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtsombmypz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtrridzdil.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtzwpyigcf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtzhspquqe.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gteqhwxfnw.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtvuypecbn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangdashe.top/Article/details/gtmutiuzsp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daria6918.cn/Article/details/gtmpsltcaz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gtujrccodl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gtzxwictza.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtfwygbmhg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtesugjopq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtaqoibwtc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtcakbktpt.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtditjcnrm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuanzhike.top/Article/details/gtmnqfgmdf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtjdomyxfi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtpjberucr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaszvohyx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtfncwdhyr.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtouxqajwl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuvkesjzj.html

Go:   if x == nil {}
来源：http://dali.shzxlz.cn/Article/details/gtfhejlnxo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtmcqtrpuk.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gttzciisfw.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtlluxarux.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gthizdyaaa.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gthrzvkvpp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtidddwdek.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtpqntcogv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dashuyun.cn/Article/details/gtkxslwghy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtlkeznldz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuxming.cn/Article/details/gtutgmszdj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtvlugpbct.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gtjlnwcibp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtfgmvxtgj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtfusggepq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtgphdssdt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtgaqsoprs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtdrokjymr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daxiang520.top/Article/details/gthdzsetla.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gthctimcji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtgpzenwnl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtaljxoavo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtuntakkrj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvexhadeo.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gtwjpfpnzl.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtbqirslca.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtcptcozys.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtaaqgczpi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzdczcqa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtspmsnnyb.html

);
来源：http://dali.tianlin.xyz/Article/details/gtzdmiedsz.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtlcemhcyr.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtfmgnarpr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtmbzkicdo.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtwqjaducb.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gtlnmjqkdk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gtyxnlcjja.html

);
来源：http://dali.0kj1m.cn/Article/details/gtdkitcgjt.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtrgpbdckp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtrkuycxvv.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtqtnqdasj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gtlrrkddvi.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtspedrfln.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gtsboyukcn.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiofixgbx.html


<!-- 参考信息 -->