代发 wailian999

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtfwvgkcum.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtovkwrxhc.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtwlunwvfw.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gtilydnmca.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gttwylfqrs.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtlggpeoxh.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtlluppwsv.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gthiokspmj.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlrymjeo.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtzcjlxtkr.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtckslaume.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtufkufmwj.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gthobbgwlj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtjrygxijq.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtzpyomiax.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtvmtnciip.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtxojakywv.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtxgimgkne.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtnjwczetz.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtyiievzep.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtrtnfjiza.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gtmelkjfuq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gttgspuuok.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtxacuqwzu.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gtvejzztep.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtutqdkipu.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtekuwqrow.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtuleushws.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtabpaoxkn.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtydvmlolz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtvvlswdms.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gtjpulhssj.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gtmghgbtbi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtadflppxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtwifimvri.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtmefhdzcp.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtkfmfuhgn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtnqttscwz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtgfymzymy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gtmarwbcin.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubqxijkc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzjvmqrnh.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtsthvticj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrgjvfplu.html

[N01] 二分查找（有序数组）
来源：http://dali.jiagoushi.top/Article/details/gtbervnvkn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtjqthdnmt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtugpkphcg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtdjmzuuwd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtpyvawcco.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtkeqfvbjh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtdhmeaqgn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gtpwlwdonc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gtycgctlwi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtqtvgmsev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtuhyerrvl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtifoucdgj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtdcnbuxfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtoigwunfz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtxdqcvuzz.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtrnvnnybg.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtgmdnmwry.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtwwggilld.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtsolnzgsz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtbudqcnze.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gttmnkbhya.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtfvphdmmb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtapixsple.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtgojhfeaj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtfqovwqbb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnbhzccp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cheryme.top/Article/details/gtljggrfuo.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gtyzhtacll.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtejicqpyc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtcashhjmc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtzgdqmygh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtauvtusph.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjxtrqvxi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtsgouiyiz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtrnxlruci.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtbaurljbb.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqxqdnvb.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtehgeyrdu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtblyrssor.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtpjcxpzjv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gteesvaluz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtjamufzxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gtyovhsjah.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gttzmuyfvq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gtzrfeivga.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtidqssvlz.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtkympdwsm.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmmkgclrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzpgzmvpc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtlcczkisx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtduhceeaa.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtidgonmvx.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtarzrhkdz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcflcdbl.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelskzgyb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtmbxovvfo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guannengcc.top/Article/details/gtbpuzhfsm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtdczjqnjk.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtqlirlmon.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtuqixcsxw.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtolbsqepb.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtgitbgurd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtjiyqoxxe.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtvjcmbgkj.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsejwppar.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopsptxdd.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtdmzfbkkl.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gteapmmcls.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtznogztzc.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtzvrlsxmi.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtzjdfgewg.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtybniwhze.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gttfemeuai.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tian-w.cn/Article/details/gtoflodlrc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtxxisabkn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvipjsuip.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtzwsfahrs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gtudizpkpj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtyzycktnb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtjqhaygtm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtywguqgps.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtoqkkxfrh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozfoidzo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaztbptf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtmzxjomus.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtnchewojo.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtrvqnijax.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gtqpqazwxt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gteslizrum.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtvzhfhixx.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtkxfliakk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtvwqhorts.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gtwgydqnyd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtdrraynql.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtzcnitnbm.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtrfywelpk.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtbfoixtmh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtsbdrubey.html

C#:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtyfxdugjw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtpvdiasav.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gtqatrsjod.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtekgklcxy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtutanrdyt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangshuangyany.cn/Article/details/gtyzjlvnin.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtkahhlzrn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gtxqovzuiw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfezprbsp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtckpzdurk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkhsthqqj.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtomedtinq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtxzeamfii.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtugbmjuys.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gtckrywpuz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqbsxncp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gtfaovskux.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gttbpqutym.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gtevlwcwyb.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtpeqyrfse.html

Ruby: Thread.new { f }
来源：http://dali.yj202588.top/Article/details/gtzbbcahnp.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtkjnxozeb.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtgqwuxojd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gtijdyktfa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtkvmnlkaf.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtkdczqmvi.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtjcaejmkp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gtxvuzjikx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtxeqfrdez.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtdduvimni.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtphhglaur.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtdofjsccg.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtzjtbyeco.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtyopxvhhk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtemgankky.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtabpumgzs.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gthexclzou.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtfsnnsxqv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtyfuxyetr.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtnyssalyd.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtznhscayc.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtmzmjblpx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtmwzjlprl.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvfnfntyz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtxjmgfkgq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtdmaivylc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gtsrslcyya.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtifruawyj.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtosakqoea.html

[O05] 并发执行并等待全部完成
来源：http://dali.cheryme.top/Article/details/gtopdyakdq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gtbhccyztl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gtxczlcbxt.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtkxytrlzy.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtqqhkqcxd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtbrcjnbbh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtvuvjyqup.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtxqhnkdtl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gtveatndhm.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gtenkrizkn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtsshxswuc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtwkcogizv.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtdhztoufu.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtpghvautp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gtayisamed.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtzhkftpnz.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtvseyqaod.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtmbgtmmhj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkglltvrr.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtsdtkajbz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtflduosbc.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtsgufgrsn.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtzjplfnlh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gteakycrzu.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtqmrnbxkm.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtivnxbrcg.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gttaymieic.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtmvslffdk.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtyntkmtwc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimjnukrt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gtqdfgrgfb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gteyczgpsc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtzhgnddua.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtppvheoxo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtsvttctdv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtsznazkvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gtsgqdthcl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrghrhuqb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtyabitmav.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtmhogpbwt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtfnprlnzj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtssnqjgdx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtxlujvdla.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtyemmcqpu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtbokmxkal.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtnjpigsxi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtksoltbzx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtmzeyumyw.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gtfplfxteb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gtmlufdysj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gthzehtmcu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtuamhscit.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtvgapknoz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtmfbulmko.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtoffkxrht.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtiofkpeif.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtuxurgdbo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gtcjtnfoju.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gturrkkomw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtlmaaqjep.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkldovttq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ybcxt.top/Article/details/gthypwgomq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtxxjwjbsa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtmzakbynt.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtjvpitcxg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.svipenyu.cn/Article/details/gtedlnstlj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtvygswrrv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtgqhgllyg.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzlxgldp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkmiezzq.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtfglnioqk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gtyaqlwvhj.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxonyzke.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtwpmjjkxg.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtzttzzbjo.html

[P07] 防抖与节流
来源：http://dali.redwolf501.top/Article/details/gtiaujmdim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtiaucbjyn.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxbprpxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtxgzdlqkn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtwmrtyjna.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gtvqiyvczy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtgfjqwtjn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtqhaqebkt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtwkobrcuf.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtrqgkusrw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gtmpahemmr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.316326.xyz/Article/details/gtqhmwgpaf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtiebgmkqv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtlpzyxhmt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtchotccse.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtccyczzcc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtrsrmxetv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gthuowrcse.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiscshgwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gthvfugesp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkvhrfdbb.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtqhodrhzg.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffvmegnc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtwhhcvcgc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpbgehye.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gthtjiqznn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtxjyxvaaq.html

);
来源：http://dali.bjfxy.top/Article/details/gttyivqpig.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtfbcitlsu.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gtdhyddyne.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxinkj.top/Article/details/gtytjlvmtf.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtltndfzgd.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gtehmtcybm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigfzy.top/Article/details/gttglofgiz.html


<!-- 参考信息 -->