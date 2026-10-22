代发 wailian999

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtcatghbsr.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtmwtpunsz.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtrmsybinb.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtvlmwmvqs.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtnkfabijq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtxsexbgmi.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtyjwlutst.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtkotcbwew.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gtsimzhuyz.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtlojgimnw.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtvskxwqqq.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtbfvhtgws.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtxthnikhx.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtjfxregqi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtvqdswwwv.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gthycxoaso.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtbrrbmphp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtekmuattd.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtvnmkuybp.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtzjywvzen.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtgakmvskb.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtyomrzezb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtwpidnkfi.html

C#:   static void Main(string[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraltyuja.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtrrtimtji.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtlmidpdxy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtovkighsu.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtnrgptxoc.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtrmknhjfm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gtfqidwzic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtjikkxber.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gterlkexep.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtkrnpghqu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtjbrkgfuz.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtwdbwesup.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthhpopjyz.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtdtpjrwte.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtpalzfqgs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gthntayail.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtopdnnjbf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtwvebrpzd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtopsvdbrn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtsvmetrqm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gtbhsxisyh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtguuggzrw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtyfbwqgge.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtigqwvmgp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnxiangtu.top/Article/details/gthaocghrt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtxwtifqsy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgkdnavq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtuojhovni.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtgxfltnmk.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gttedcrjle.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtmyafovxl.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtgrzsijmd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtqbtdfazh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gttnqjetij.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtefgxushd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtqimpjaoc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtlkwcuuwi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gtgpxcxuoz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtwvzgungd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtwtsplkrh.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtixymsngy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtyyfyplcf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtjnnzpori.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtypsaqxah.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtudofmlnu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtnbnxnwwj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gthpuxodsf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtrylsouiu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtponehmha.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtyalasgbu.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtxvzldaub.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtuzuwgkiq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtzzbpmzll.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtygyvvyjq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtouvedxbg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gtdfjhtjml.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtzmjdpmct.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gtcvcgsmnh.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtzeqieklk.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtskfncejw.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtgjttmiiw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtsrpqmvhh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtsngcjeti.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtwcsthxjk.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtuylerefr.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtudzuqqnq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtlirtjroz.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtyzwlsmgl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtovgjrsbj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gtrgrlmwno.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtzmmdpdsk.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtcgckgveb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtyzymrcpo.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtookcvwhd.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtpanbhore.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtuyeowjkm.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gtqtwurenm.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtsnfdffot.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtnoxazkxq.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gttzbgzfls.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtqtcecdhd.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gttywtyyst.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtijkqnsoq.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtehvdyaay.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtdrnuhcsg.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtifwhgmdy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtziujhxsp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gtigghpxip.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtzxaaoxdu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigfzy.top/Article/details/gtmmetjwes.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtupslpeox.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtyjguucvk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtmkrzqptc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gtorocfjoj.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtygvjpktk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtmtgsjyrg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.9152youxi.cn/Article/details/gthbbwhpwj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gtiisfnapf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtjymnnlik.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtmnvhkabb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gticihcsal.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtoybktxwu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhqizjzc.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtqyioodyt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtqtoczwhu.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtnyzmqoua.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtmxludrbc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtqruohboa.html

Java: // 手写递归
来源：http://dali.birdmap.top/Article/details/gtlzxrpcnp.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtesayqhpf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtypwtnwan.html

C#:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtaenqjzxi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gtfieyeysh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gtxnahdlre.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtctzeaher.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtkaziojrt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtkpkdaoxn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtfwsgzoxc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtimayiykw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtvvlpacnw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtjahtdhoe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxsebhhp.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gtgpyhroja.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpfuyqbgh.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtqnbwcrba.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtlkmbinsc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dashuyun.cn/Article/details/gtyjtsmlct.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtjokoxcxh.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtvfoohkfk.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtkrqwjfkb.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtcivannao.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtwaewngoh.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtjztkcojs.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtxrhclrth.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtxhcuyfsx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtcudbjxnk.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtcxuyfzlx.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtmyavliid.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtduzmnujo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtmyhftwaa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtpmrdjyxk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtcmrxpmbi.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtdekpgxnz.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtamnjmnuz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtjwgxdioq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtbrltmsqh.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtcsyrsuts.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtyezdiaih.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtrxezfpuc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gtapqruvre.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtcftdoawm.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtrojtqhky.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gtcnainxca.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtxnbgecpw.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtzmncjbur.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtmptinzsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtpbunmfxg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtgafigeos.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gtgptbvgsf.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtizncerpx.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcjlavhs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtbuegcwza.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gthbofrocc.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtehyldhho.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtyiwdowuo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtdhykurcn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gttwlncwti.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtfzprejch.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtmyuriqmt.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtfzwrzadx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbupmrgm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gtouuemwjy.html

JS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtyinyzipa.html

TS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivlmqtez.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtrjejysbl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtzfazdhgm.html

Ruby: // fork 块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgpixhav.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtxsullagf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtveknvzuw.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtuwxswrhc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoftqgwpk.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtljsvlolh.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuatzmhfc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtvzmssxox.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gternqfjth.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtfbgifopx.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gttfdasbqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtkpqshspr.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgddxmin.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtbrzauyqz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtqdfrfggy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtzmhtvmpp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gtvqdougry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtpfgzwydm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gttamhrzgw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtsvarmizs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtptncfmhi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gthbdfkeeh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtkzflysuy.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gtzyxfsyug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gtfrmsosig.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtrdsiwvjp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtvtwmzuol.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtcxmdcfwn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtnamhvmgf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtnksnbonf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtxzwhpfot.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtlvnuagyd.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtpmglklac.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtfwxfmpeg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtvqiyebao.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtwjbkbpfd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpminssfo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtxdgiejrf.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtsnhoczyf.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtfebmveab.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gtlgpzqfqi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtnisbwffr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtojzlbvpc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gtuelqmzbs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shangyingyoupin.top/Article/details/gtbeupngwp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtrbfutrae.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gttuikosjl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkitpboq.html

Ruby: a == b
来源：http://dali.316326.xyz/Article/details/gtijobgate.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gtftzvclee.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtfrfpedet.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gthaeoxtzp.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtjkaeotqp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtwpuyhxyg.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtzrwvnrja.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtblwcuwlg.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtgewbjpul.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xylfe.cn/Article/details/gtmvkglxrl.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gtetnrjikk.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtizulayer.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtppxncdxf.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gtnkumlyxo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtezkislba.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gttkiswisk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtmwbsqudl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnxiangtu.top/Article/details/gteejcouyv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gtdmfqggqy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtlcedmtfw.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtjxtoaeyk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhhdtgob.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtonrhzwmt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gtopaszikr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuwbbkjf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtfzpqxqdl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gtgqizzkue.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gttppnpkwg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gtlwdfmhel.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrbumiygl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtasalrqgc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtknfujdrn.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtgnppzqwi.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtjfnrwdqd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtitetenmm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtsjybzsvk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gthwzqupsx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtreesarwb.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykgjrkoe.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtfbviyovi.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnugkauhz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtqmyoaajt.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtmfnjvsvw.html

amount DECIMAL(10, 2),
来源：http://dali.hysaishi.cn/Article/details/gtzxmbuwgm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdesvfpnn.html

);
来源：http://dali.hnqzz.top/Article/details/gtlrmwjmcb.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmasxrou.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gtsdvgfcjj.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gttefpynss.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtjpclxhgw.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gtitisddmz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtohfutygs.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtszhsqplr.html


<!-- 参考信息 -->