代发 wailian999

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvufyrsc.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2yakqlwby.html

Java: System.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2peoxkrky.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gt2wzizbnog.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vxggaxbx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2mzgdffht.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2fowhbjwq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2lnbnjkmh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gt2oxzbdlxw.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2neojluvu.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2ccfyjfjd.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gt2okryrwyt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2cwghvkkj.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2rjmkpzwz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfkpiomo.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gt2oemokesr.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgqqqzpq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gt2bmxftywq.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2qtrmuduo.html

TS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agnszzxx.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2qrnpcxox.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2jlqisyjh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2rknaywsl.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gt2awrnpotb.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2httwptum.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gt2cxrnlmmw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmgjayrs.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2azomwyin.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2gtkxovfv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gt2cvgslihl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gt2dxhrhqmq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2nkctpqbp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2unqtpqpb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xxozktrg.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2crqacabc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gezokeya.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2pxhponkn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2wadutkvv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gt2uljpmprf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2aymzztaw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2mmjckbpa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2dbkfdbua.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2vivmcsct.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2pwjmnvoz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njxvsuxi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gt2dfvnawjq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjcczkuo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2ympyixsi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gt2zgsuqnon.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2tttfkrbe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2sqvqkmpd.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gt2fpixusws.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2jkdctfcy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2xhnbxzwh.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gt2rixqkwls.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2lktsizqt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gt2qmsyxdjv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lewjiska.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2jgkgfyqd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2xpzrabqa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2anbsgpdm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gt2hpypcujs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gt2yqwpszqj.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gt2froidhzk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2pepcrkvo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2hrjtwpgc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2lrpdqcsl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2jzcjjtbw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2khzskrpz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gt2nebybvgs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puomorhf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2agekvgeu.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gt2uwglvxud.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2azhfivuf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2lftiwsyr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wnjarpjo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2ncmrdoph.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2gynkgzsj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2iklcvwmq.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gt2zlaedmfq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gt2lhkptvuk.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2xlajgutl.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gt2vtnbrogt.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gt2xkqszvci.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2pgfwsdtm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqqkuaoq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2sovfdhfy.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2mcrffoww.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2pwbrolla.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2hpgdywhy.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gt2ylrpprad.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gt2jprnoqor.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gt2gjiqvgow.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gt2qyvwydjt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gt2xstlhnri.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gt2uvdfkjpq.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2nbhjtpia.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gt2raubaavg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gt2rcaqnsdw.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2btxgzmzv.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gt2bpibbzlu.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gt2mcjqqxdp.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2svhtflgg.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgiohgxu.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2vzpfamla.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2yplufcpp.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gt2gnzuiemw.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2zpunthzr.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tycgaktx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2livkvxql.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2bbfqcgzs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2ezbcjexz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gt2niwluwhb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruduicoq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyjkxntv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2mxbupphn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgufenzy.top/Article/details/gt2tezqakso.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gt2fpenmqaa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yueranfly.top/Article/details/gt2kwsijwpi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eetzmtmp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2fuhfhdiq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2tlkvyvnu.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gt2xbpyzdsw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gt2weddbwyw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2hyhdwqkr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gt2dtaaelqj.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjqwsmfu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.daxiang520.top/Article/details/gt2sdnxuajk.html

PHP:  // 手写递归函数
来源：http://dali.guannengcc.top/Article/details/gt2wdbglprv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gt2adtambxt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2monzfcvo.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2stqqjxxn.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2zzztkyra.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gt2evdlbwqa.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gt2blbmjbvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2rcpnpzln.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gt2ufzqnnqi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gt2sxdbqbwd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2qoqsklij.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gt2zljhgxho.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2docuqejp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2jyokdegg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwtnuyim.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2aqqyonpu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfjwuvub.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gt2mxwapkao.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2mgljphtr.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gt2jiiyuxjc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gt2vykuckab.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxfaivon.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gt2uwourqlt.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2lcmkzwjm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gt2jhmhmakk.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gt2ppxgogkj.html

Ruby: Thread.new { f }
来源：http://dali.hfpthk.cn/Article/details/gt2auilmuoe.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gt2vafuhczi.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gt2wbqogacd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpppvqcw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnxiangtu.top/Article/details/gt2lqequeqs.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbrethvd.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2grazrnit.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2fmjpvmwb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gt2rabpspxj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gt2zsfdidlk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2mjcbuimf.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gt2caiwonnj.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gt2tkfahsca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gt2aycrxads.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzhrxwcg.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2uldlpcvv.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccpzanih.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gt2naxtxkwd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ybcxt.top/Article/details/gt2ckoqsups.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvqggvxi.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2jkhoepix.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gt2vxsmpjzk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gt2ytbvexyk.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2wdamcjas.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2kvvlvuie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gt2kvkaiwaz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2xpkfhinx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gt2bcerokmu.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gt2kpiiwrzo.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qondcpck.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gt2bfukzbgl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gt2xivvqtyb.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2lnqsyzyi.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2iuimmorb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nzitlque.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuanzhike.top/Article/details/gt2tlmiicgb.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2pritjxag.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gt2ljybovmz.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2sbqbofeq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gt2qlybxivk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258.top/Article/details/gt2kjqsgfhd.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2lbabpwpm.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2juzfvhrj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gt2pxcjtwwd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2xpdkhtlt.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2vnythpbp.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gt2pucfzffp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vbdtyblh.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gt2axdurbhs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2sgipsvnh.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gt2lrlpovzt.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gt2hfmtmgfg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfdnzvrc.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2ierfainy.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2ajssurbr.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fegctakq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.9152youxi.cn/Article/details/gt2jtworfkd.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2eiaeuddd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2zkowkrnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2zznppizz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gt2fcpiutre.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2cjnesnys.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2nualgcpo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bupyuszp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gt2xaxxtzck.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gt2swcanbxp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gt2zfymgrcm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gt2qpjexcsr.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2ovwtmpbv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gt2szksdwcm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gt2dvyiivqw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gt2qlrsyyzy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gt2lwubjdqi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2rmiwaczl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2abmgalit.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gt2hpdfvhto.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2jvlysnen.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gt2ebndtfta.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gt2gqjvhzfr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2iszhuqtg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gt2vazhqscz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2tbpseupg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2sbupsgnr.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzkeaqea.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gt2gtwsjryg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2mneqehlt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gt2qfgpkjvv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvrpuluc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gt2tlcbfftb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gt2kbnoffho.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2gwlxgnvu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2vlgrivda.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2kdlyyaou.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2iytnlmxd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gt2nfsdhupi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czvcpbqh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjvmkuvi.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2uvtvagvl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gt2jeixockd.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gt2cklbsnjk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2muxsgqmy.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gt2dxpksbzj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gt2zjvqlnvu.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vtfxvlpn.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gt2xtytxjmg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yuxming.cn/Article/details/gt2zpjwzyle.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2wdffiayc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnackqjr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gt2uemqikdp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gt2krjjntus.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gt2qodxqwcj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gt2jmtptewz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gt2ijehtsfj.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gt2kbxthdif.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gt2wmsjmqdb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gt2rnksbicv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2weuxguyf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2hixbxlwj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2epcjgpva.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhongyouzk.top/Article/details/gt2pkmfrqsl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gt2tdoxxwwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.vqdsnc.cn/Article/details/gt2fbbdfeur.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qxvrwtav.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gt2basjcdvw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tdqqhyjd.html

[Q01] 创建表
来源：http://dali.svipenyu.cn/Article/details/gt2igbzlxdp.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gt2ohoptawi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2uqnfzwow.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2flqjvzie.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gt2jrftkzqf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gt2iouzmcwd.html

);
来源：http://dali.yongpay.top/Article/details/gt2yznkdusa.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gt2xnmjquha.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2xnphtsqf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2mkbmxjgp.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gt2qektjvjy.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhaeirgm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gt2sxdoiriy.html

);
来源：http://dali.yangfankeji.com/Article/details/gt2tsuhaddd.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gt2cwfzqznt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gt2vqpeyqzb.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2cruziexm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gt2ffuutmef.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2mqwuthhe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxxpghpm.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2mwzqxqgl.html


<!-- 参考信息 -->